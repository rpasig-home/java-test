# java-test


Dependencies:
    
- install java (java 17)
- If using VS Code, install Java Extension Pack
- Install Maven for project management



Note: 

1) maven project has been created as:

```mvn archetype:generate -DgroupId=com.example -DartifactId=SeleniumDemo -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false```

2) Selenium Dependency has been added into pom.xml
```<dependency>
    <groupId>org.seleniumhq.selenium</groupId>
    <artifactId>selenium-java</artifactId>
    <version>5.10.0</version>
</dependency>
```

To Run the test:
```
mvn compile exec:java -Dexec.mainClass="com.example.SimpleTest"
```
