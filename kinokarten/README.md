# Kinokarten - Cinema Ticket Booking System

A Java-based cinema ticket booking application developed with Java 21 and Maven.

## Prerequisites

- Java 21 (Zulu, Temurin, or any OpenJDK 21 distribution)
- Maven 3.6+
- IntelliJ IDEA Ultimate (recommended)

## IntelliJ IDEA Setup

This project is configured for IntelliJ IDEA Ultimate with the following features:

### Opening the Project

1. Open IntelliJ IDEA Ultimate
2. Click **File → Open**
3. Navigate to the `kinokarten` directory and select it
4. Click **OK**
5. IntelliJ will automatically detect the Maven project and import it
6. Wait for Maven to download dependencies and index the project

### Project Configuration

The project includes pre-configured IntelliJ IDEA settings:
- **JDK 21** language level and bytecode target
- **UTF-8** encoding for source files
- **Git** integration
- **Run Configuration** for the main App class

### Running the Application

1. Open the **Run** menu or use the run configuration dropdown
2. Select **App** from the list of configurations
3. Click the **Run** button (▶️) or press `Shift+F10`

Alternatively, you can right-click on `src/main/java/com/kinokarten/App.java` and select **Run 'App.main()'**

## Building with Maven

```bash
# Compile the project
mvn clean compile

# Run tests
mvn test

# Package as JAR
mvn package

# The JAR will be created in: target/kinokarten-1.0.jar
```

## Project Structure

```
kinokarten/
├── src/
│   ├── main/
│   │   └── java/
│   │       └── com/
│   │           └── kinokarten/
│   │               ├── App.java (Main entry point)
│   │               ├── Counter.java
│   │               ├── Factories/
│   │               ├── Helpers/
│   │               ├── Interfaces/
│   │               ├── Managers/
│   │               └── Objects/
│   └── test/
│       └── java/
│           └── com/
│               └── kinokarten/
│                   └── AppTest.java
└── pom.xml
```

## Features

- Cinema management (Kino)
- Movie management (Film) with FSK ratings
- Hall management (Saal) with seat layouts
- Screening schedule management (Termin)
- Customer management (Kunde)
- Seat reservation system (Reservierung)
- Interactive console interface

## Development

### Code Style

The project follows standard Java conventions. IntelliJ IDEA's default code style is recommended.

### Testing

Unit tests are located in `src/test/java`. Run them using:
- IntelliJ: Right-click on the test directory → **Run 'All Tests'**
- Maven: `mvn test`

## License

Educational project - Rhine-Waal University of Applied Sciences (RFH)
