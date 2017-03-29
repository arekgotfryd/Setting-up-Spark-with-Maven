# Setting-up-Spark-with-Maven
First Spark tutorial solution with explanation

After cloning the repository you have cd to main my-app directory to execute maven build tool.
Execution below:
"mvn compile assembly:single"

After that in target directory new jar file will pop up.
This jar file contains compiled and builded source code with all dependencies.

Now you just have to execute the program with below instruction:
java -cp target\my-app-1.0-jar-with-dependencies.jar Main

Server starts and we can make request thorugh opening chrome browser
and pasting --> "localhost:4567/hello"
to address bar

