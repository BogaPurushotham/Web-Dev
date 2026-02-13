# Web Development Project
Version 2.0 - Maven Project

## Project Structure
This is a standard Maven project with the following structure:
```
Web-Dev/
├── pom.xml                     # Maven configuration file
├── src/
│   ├── main/
│   │   ├── java/              # Java source files
│   │   │   └── TestJava.java
│   │   ├── resources/         # Application resources
│   │   └── webapp/            # Web resources (JS, HTML, CSS)
│   │       └── test.js
│   └── test/
│       ├── java/              # Test source files
│       └── resources/         # Test resources
└── target/                    # Compiled output (generated)
```

## Prerequisites
- Java Development Kit (JDK) 11 or higher
- Maven 3.6.0 or higher

## Maven Commands

### Build the project
```bash
mvn clean install
```

### Compile the project
```bash
mvn compile
```

### Run tests
```bash
mvn test
```

### Package the application
```bash
mvn package
```

### Run the main class
```bash
mvn exec:java -Dexec.mainClass="TestJava"
```

Or after packaging:
```bash
java -jar target/web-dev-2.0.jar
```

### Clean build artifacts
```bash
mvn clean
```

## Project Information
- **Group ID**: com.bits.mtech.fsad
- **Artifact ID**: web-dev
- **Version**: 2.0
- **Packaging**: JAR

## Dependencies
- JUnit 5.9.3 (Testing)

## Notes
- Old files (TestJava.java, test.js) in the root directory can be deleted as they have been moved to the appropriate Maven directories
- The `target/` directory is created during build and contains compiled classes and packaged artifacts


