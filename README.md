# Android Hilt Demo

This is a sample project demonstrating the use of Hilt dependency injection in Android applications.
Following the codelab from [Google Codelabs](https://codelabs.developers.google.com/codelabs/android-hilt).

# License
Refer to [license](https://developer.android.com/license)

## Environment Requirements

- JDK: 17
- Kotlin: 1.9.0
- Gradle: 8.1.0
- Android Gradle Plugin: 8.1.0
- compileSdk: 33
- minSdk: 16
- targetSdk: 33

## Dependency Versions

### Android Core Libraries

- AndroidX AppCompat: 1.5.1
- AndroidX Core KTX: 1.9.0
- AndroidX ConstraintLayout: 2.1.4
- AndroidX RecyclerView: 1.2.1
- AndroidX Fragment KTX: 1.5.5

### Dependency Injection

- Hilt: 2.55
- Hilt Navigation Fragment: 1.0.0

### Database

- Room: 2.4.3

### Testing

- JUnit: 4.13.2
- AndroidX Test Core KTX: 1.4.0
- AndroidX Test JUnit KTX: 1.1.3
- AndroidX Test Rules: 1.4.0
- Espresso Core: 3.4.0

## Project Structure

This project follows the MVVM architecture pattern and contains the following main modules:

- `data`: Data layer containing Room database and data sources
- `di`: Dependency injection modules containing Hilt configurations
- `ui`: User interface layer containing Activities and Fragments
- `navigator`: Navigation component

## Build Instructions

1. Make sure you have JDK 17 installed
2. Use the latest version of Android Studio
3. Build using Gradle Wrapper:
   ```bash
   ./gradlew build
   ```

## Important Notes

- This project uses Java 17, please ensure your development environment is properly configured
- If you encounter build issues, try cleaning the project first with `./gradlew clean`
