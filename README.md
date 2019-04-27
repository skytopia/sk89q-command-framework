sk89q-command-framework [![](https://jitpack.io/v/OvercastNetwork/sk89q-command-framework.svg)](https://jitpack.io/#OvercastNetwork/sk89q-command-framework)
=======================

**NOTE**: This repository is no longer maintained, but a [second iteration](https://github.com/Electroid/intake) of this framework is still active.

sk89q-command-framework is the command framework from sk89q's WorldEdit. It has been factored out so it may be used in other projects without having to include WorldEdit as a dependency.

Compiling
---------

You need to have Maven installed (http://maven.apache.org). Once installed, simply run:

    mvn clean install

Maven will automatically download dependencies for you. Note: For that to work, be sure to add Maven to your "PATH".

Distribution
------------

```xml
<repository>
  <id>jitpack.io</id>
  <url>https://jitpack.io</url>
</repository>
```

```xml
<dependency>
    <groupId>com.github.OvercastNetwork.sk89q-command-framework</groupId>
    <artifactId>command-framework-bukkit</artifactId>
    <version>master-SNAPSHOT</version>
</dependency>
```

Contributing
------------

Your submissions have to be licensed under the GNU General Public License v3.
