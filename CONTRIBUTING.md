# Prerequirements

[Gradle][1] is used as a build tool for this project, so you have to install it. Of course, JDK is also required.

## How to build the plug-in?

Execute: `./gradlew buildPlugin`. The first run takes a long time as Gradle needs to download the whole IntelliJ SDK. 

After the command executed successfully, a .zip file with the plug-in will be available in the `build/distributions` directory. 

## How to run tests?

Execute: `./gradlew test`.

## How to run a testing IntelliJ instance with the plug-in installed?

Execute: `./gradlew runIdea`. During the first run you will get an error, something like 'PHP plugin is required...' Install the required plug-in manually and execute the command again.

[1]: http://gradle.org/gradle-download/
