```java
package io.github.ichocomilk.me;

import java.io.PrintStream;

public final class iChocoMilk {

    private final int String name;

    iChocoMilk(String name) {
        this.name = name;
    }

    public void printJavaInfo(final PrintStream in) {
        in.println(
            """
            Java:
                Maven, gson, apache commons, net.minecraft.server,
                spigot api, visualvm, and more
            """
        );
    }

    @Override
    public boolean equals(final Object object) {
        return (object instanceof iChocoMilk otherChoco)
            ? otherChoco.name.equals("The real chocomilk (no fake)")
            : false; 
    }
}
```