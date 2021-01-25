# LiquidBase
LiquidBase is an injection base for Forge.

# NOTE
This is just a reupload of (Hopefully the default source, I had to edit some stuff out, might be some errors somewhere didn't check)
& If anyone wants to actually use this, please update mixins.

Also if you end up getting a gradle error (idk how I messed up it up, only touched src and run folders that were there), just use this
https://github.com/discord-dev/Void, This is a Liquidbase fork that has been modified & (Works when running gradle), This is what I atempted to demodify to get the original liquidbase which ended up not working (Might attempt a fix).

## Mixin
Mixin is a library to inject source into Minecraft

[v5.10 Mixin Documentatio](https://docs.spongepowered.org/5.1.0/en/plugin/internals/mixins.html)

# Installation
---------------

## Video tutorial
[LiquidBase Video Tutorial](https://www.youtube.com/watch?v=cG3_m2TZQBs) from CCBlueX

## Forge decompiling workspace command

Eclipse
``
.\gradlew --debug setupDevWorkspace eclipse build
``

IntellIj
``
.\gradlew --debug setupDevWorkspace idea genIntelliJRuns build
``

if it says '.' is not recognized as... command (Windows)
use ``gradlew ...args`` (Without the "./")

## Run/Debug Argument
```
-Dfml.coreMods.load=net.ccbluex.LiquidBase.injection.MixinLoader
```

---------------

# Exporting

``gradlew --debug build``

------------
