# server-client

###1. Download or clone this project.

###2. Go to the root file of the project, where is pom.xml file. Build projet in bash with command:

```bash
mvn package
```
 
3. Run the Server.java program with command:

java -cp target/server-project-1.0-SNAPSHOT.jar com.project.server.Server

(use sudo if you want to connect to port below 1024)

The program asks you which port you want to connect on. Type the port number and press enter.

4. Run the Clien.java program with command:

java -cp target/server-project-1.0-SNAPSHOT.jar com.project.server.Client

(again use sudo if you want to connect to port below 1024)

Type the same port number you gave to the Server.java program and press enter.

Server will respond to the client "Connected".


