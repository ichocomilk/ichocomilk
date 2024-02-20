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

Java developer
<a href="https://www.azul.com/downloads/#prime">
  <img alt="Java logo" src="logos/javalogo-64x64.png"></img>
</a>

Apassionate for minecraft
<a href="https://minecraft.net/">
  <img alt="Minecraft logo" src="logos/minecraftlogo-64x64.png"></img>
</a>