# Lab01 - Android Application

A foundational Android application project demonstrating core Android development practices and setup.

## Project Overview

Lab01 is an Android Studio project built with modern Android development tools and best practices. It serves as a starter template for Android application development with proper Gradle configuration and dependency management.

## Technology Stack

- **Language:** Java
- **Android SDK:** Target API 36, Minimum API 24
- **Build System:** Gradle (with Kotlin DSL)
- **Compile SDK:** 36
- **Java Version:** Java 11

## Project Structure

```
andoird-lab01/
├── app/                    # Main application module
├── gradle/                 # Gradle wrapper files
├── build.gradle.kts        # Root build configuration
├── settings.gradle.kts     # Project settings
├── gradle.properties       # Gradle properties
├── gradlew                 # Gradle wrapper (Linux/Mac)
└── gradlew.bat            # Gradle wrapper (Windows)
```

## Key Features

- **Modern Android Development:** Built with current Android SDK and best practices
- **Gradle Configuration:** Using Kotlin DSL for build scripts
- **Dependency Management:** Organized through gradle.properties and dependency catalogs
- **Testing Support:** Configured with JUnit and Espresso for unit and UI testing
- **Material Design:** Material components included for modern UI development

## Prerequisites

- Android Studio (latest version recommended)
- JDK 11 or higher
- Android SDK (API level 24 or higher)

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/00zkr/andoird-lab01.git
cd andoird-lab01
```

### 2. Open in Android Studio

- Open Android Studio
- Select "Open an existing Android Studio project"
- Navigate to the project directory and click "Open"

### 3. Build the Project

```bash
./gradlew build
```

Or use the Build menu in Android Studio (Build → Make Project)

### 4. Run the Application

```bash
./gradlew installDebug
./gradlew runDebug
```

Or click the Run button (▶) in Android Studio

## Dependencies

The project includes the following main dependencies:

- **androidx.appcompat:appcompat** - AppCompat library for backward compatibility
- **com.google.android.material:material** - Material Design components
- **androidx.activity:activity** - Activity framework components
- **androidx.constraintlayout:constraintlayout** - Constraint layout for flexible UI design
- **junit** - Unit testing framework
- **androidx.test.ext:junit** - Android JUnit extensions
- **androidx.test.espresso:espresso-core** - UI testing framework

## Build Configuration

### Compilation Settings

- **Source Compatibility:** Java 11
- **Target Compatibility:** Java 11
- **Min SDK:** 24
- **Target SDK:** 36
- **Compile SDK:** 36

### Build Types

- **Debug:** Development builds with debugging enabled
- **Release:** Production builds with ProGuard optimization enabled

## Testing

### Unit Tests

Run unit tests with:

```bash
./gradlew test
```

### Instrumented Tests

Run instrumented tests on an Android device or emulator:

```bash
./gradlew connectedAndroidTest
```

## Gradle Wrapper

This project uses Gradle Wrapper to ensure consistent builds across different environments:

```bash
# Linux/Mac
./gradlew build

# Windows
gradlew.bat build
```

## Configuration Files

- **build.gradle.kts** - Root-level build configuration
- **app/build.gradle.kts** - Application module build configuration
- **settings.gradle.kts** - Project structure and repository settings
- **gradle.properties** - Gradle system properties
- **.gitignore** - Git ignore rules

## Features

- ✅ Modern Android SDK configuration
- ✅ Material Design support
- ✅ JUnit and Espresso testing frameworks
- ✅ Constraint layout for responsive UI
- ✅ AppCompat for backward compatibility

## License

This project is currently unlicensed. For license information, see the repository settings.

## Contributing

Contributions are welcome! Feel free to submit pull requests or open issues for suggestions and improvements.

## Author

- **GitHub:** [@00zkr](https://github.com/00zkr)

## Resources

- [Android Developer Documentation](https://developer.android.com/)
- [Android Studio Documentation](https://developer.android.com/studio)
- [Gradle Documentation](https://docs.gradle.org/)
- [Material Design](https://material.io/design/)

---

**Last Updated:** May 5, 2026
