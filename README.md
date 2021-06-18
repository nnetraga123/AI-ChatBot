# My App

A Java chatbox application where the bot is powered by AI. The AI uses AIML files to generate the appropriate response. The Bot is coded in as a Bean as well as the ExecutorService. This smiplifies the App from previos verison of AIML implementation.

The Front-end is based on the Vaadin Framework which make UI development in java easy to use. 

Instructions below on how to run it! As it is a Maven project, Java and Maven are pre-requisites for the project.

## Running the application
The project is a standard Maven project. To run it from the command line, type `mvn` and open http://localhost:8080 in your browser.

You can also import the project to your IDE of choice as you would with any
Maven project. 

## Deploying to Production
To create a production build, call `mvn clean package -Pproduction`.
This will build a JAR file with all the dependencies and front-end resources,
ready to be deployed. The file can be found in the `target` folder after the build completes.

Once the JAR file is built, you can run it using
`java -jar target/myapp-1.0-SNAPSHOT.jar` (NOTE, replace 
`myapp-1.0-SNAPSHOT.jar` with the name of your jar).

## Project structure

- `MainView.java` in `src/main/java` contains the navigation setup (i.e., the 
  side/top bar and the main menu).
- `views` package in `src/main/java` contains the server-side Java views of the application.
- `views` folder in `frontend/` contains the client-side JavaScript views of the application.

Please feel free to make any changes and let me know!
