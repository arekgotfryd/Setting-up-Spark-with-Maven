# Setting-up-Spark-with-Maven

1. Clone repository and cd to main my-app directory to execute maven.  
`mvn compile assembly:single`    

2. After that new jar file will pop up in the target directory.  

3. Execute program with below command:  
`java -cp target\my-app-1.0-jar-with-dependencies.jar Main`

We can check if server runs by pasting below url to the browser  
`http://localhost:4567/hello`


