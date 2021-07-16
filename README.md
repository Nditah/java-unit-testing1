# MyApp

1. Generate the project


``
mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false
``


2. Change into project directory & Build the project

``cd my-app && mvn package
``

3. Test and compile the project

``java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App
``

``mvn install
``
``mvn clean jacoco:prepare-agent install jacoco:report
``


 - sdk list java

 - sdk default java 8.0.292.j9-adpt 

 - sdk install java 11.0.11.j9-adpt

 ## Read

 https://www.freecodecamp.org/news/cjn-junit-test-with-maven-in-vscode/
 