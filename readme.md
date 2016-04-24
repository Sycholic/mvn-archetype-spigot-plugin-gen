Generate a basic bukkit and spigot compatible plugin source folder in one CLI command

git clone <repo>
mvn install

mvn -o archetype:generate -DarchetypeGroupId=org.apache.maven.archetypes //
                          -DarchetypeArtifactId=maven-archetype-simple

    ## it will be in the list runs offline mode this totally beta still till find correct CLI @params 
    ## no batch mode... yet

user will enter scripted generator to assign: 'artifactId' (a PlugInMainClassName),
    'groupId' (a fully.qualified.pluginpkgname), and 'version' (1.0-SNAPSHOT)

after verifying args a new folder named after artifactId will be made and then a
new pom.xml and propriate subfolders created with plug.yml and the main plugin
class .java file