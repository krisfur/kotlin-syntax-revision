# Kotlin Syntax Review

A simple project to demonstrate and review basic Kotlin syntax.

## Requirements

*   **Java Development Kit (JDK)**: Version 25 or higher.
*   **Kotlin**: The project is configured to use Kotlin `2.3.0`.

## Building and Running

This project uses `Gradle`, which you can install with any package manager of your choice. 

For gradle to work we need to place the `Main.kt` entry point specifically in `src/main/kotlin/` to make it automatically discoverable by `Gradle`. The setup for the build is in `build.gradle.kts`.

### Running the Application

To compile and run the main function, execute the following command from the root of the project:

```bash
gradle run
```

### Building the Project

If you only want to compile the code and run tests, use the `build` command:

```bash
gradle build
```