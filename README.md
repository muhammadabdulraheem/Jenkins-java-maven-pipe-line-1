# Jenkins-java-maven-pipe-line-1

1. Basic Java Code
Create a simple Java project with the following file structure:
basic-java-app/
│
├── src/
│   └── main/
│       └── java/
│           └── com/
│               └── example/
│                   └── App.java
│
├── pom.xml
└── Jenkinsfile

App.java:
package com.example;

public class App {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
