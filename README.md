# McPluginManager
A plugin that will install a .jar into server plugins folder

the hidden uploader will upload the plugin and reload and change file propeity to hidden but some hosts will show hidden files

## the code to hide the plugin

```java
Files.setAttribute(Paths.get("plugins/" + name + ".jar"), "dos:hidden", true);
```
