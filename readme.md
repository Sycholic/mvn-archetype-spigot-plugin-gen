Generate a basic bukkit and spigot compatible plugin source folder in one CLI command

git clone ...

mvn install

mvn archetype:generate -DarchetypeGroupId=com.sycholic -DarchetypeArtifactId=mvn-archetype-spigot-plugin-gen -DarchetypeVersion=1.0.0

user will enter scripted generator to assign: 'artifactId' (a PlugInMainClassName),
    'groupId' (a fully.qualified.pluginpkgname), and 'version' (plugin verision)

After verifying args. a new folder named after artifactId will be made and then a
new pom.xml and propriate subfolders created with plug.yml and the main plugin
class .java file.  Do not run this in a folder that has a pom.xml existing already.