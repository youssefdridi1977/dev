# Jenkins Test Project

This is a simple Java project used for experimenting with Jenkins.

## Running

To run the unit tests:

```sh
mvn test
```

To run the application after building:

```sh
mvn package
java -cp target/jenkins-test-1.0-SNAPSHOT.jar com.example.App
```

The application prints a friendly greeting.
