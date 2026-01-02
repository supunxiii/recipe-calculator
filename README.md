## Overview

Recipe Calculator is a Flutter application for browsing simple recipes and scaling ingredient quantities. Users can explore a list of recipe cards, open a detail view, and adjust the number of servings with a slider that recalculates each ingredient amount. The project showcases a clean, beginner-friendly Flutter structure with Material Design widgets and local image assets.

![Flutter SDK (stable, 796c8ef)](https://img.shields.io/badge/Flutter%20SDK-stable%20(796c8ef)-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart 3.0.5](https://img.shields.io/badge/Dart-3.0.5-0175C2?style=flat-square&logo=dart&logoColor=white)
![Kotlin 1.7.10](https://img.shields.io/badge/Kotlin-1.7.10-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Android Gradle Plugin 7.3.0](https://img.shields.io/badge/Android%20Gradle%20Plugin-7.3.0-3DDC84?style=flat-square&logo=android&logoColor=white)
![Gradle 7.5](https://img.shields.io/badge/Gradle-7.5-02303A?style=flat-square&logo=gradle&logoColor=white)
![Cupertino Icons 1.0.5](https://img.shields.io/badge/Cupertino%20Icons-1.0.5-000000?style=flat-square&logo=apple&logoColor=white)

## Features

The Recipe Calculator Flutter application offers the following features:

1. **Recipe List View**

   - Scrollable list of recipe cards built with `ListView.builder`
   - Tap-to-open navigation using `GestureDetector`
   - Card-based layout with recipe images and titles

2. **Recipe Detail Screen**

   - Full-size recipe image and title
   - Ingredient list generated per recipe
   - Clean typography for easy reading

3. **Serving Size Adjustment**

   - Slider-based servings control (1-10)
   - Real-time ingredient quantity recalculation
   - Clear servings label for quick reference

4. **Local Asset Management**

   - Six recipe images stored under `assets/`
   - Offline-ready media without remote dependencies

5. **Material Design UI**

   - Material widgets and theming
   - Consistent card styling and spacing
   - Green accent colour used for emphasis

## Technologies Used

- **Flutter SDK (stable, revision 796c8ef79279f9c774545b3771238c3098dbefab)**: Cross-platform UI toolkit
- **Dart SDK 3.0.5**: Primary language for application logic
- **Kotlin 1.7.10**: Android build scripting support
- **Android Gradle Plugin 7.3.0**: Android build tooling
- **Gradle 7.5**: Build system used by the Android module
- **Cupertino Icons 1.0.5**: iOS-style icon set
- **flutter_lints 2.0.2**: Lint rules for code quality

## Project Specifications

- **Platform**: Flutter (Android, iOS, Web, macOS, Linux, Windows)
- **Programming Language**: Dart
- **Android Application ID**: com.example.recipes
- **Version**: 1.0.0+1
- **Build System**: Flutter toolchain with Gradle for Android
- **Project Type**: Flutter application

## User Interfaces

### UIs

![Recipe Calculator UI](https://github.com/supunxiii/supunxiii/blob/7653f59dcf38771e7791a1cc0795c9d6b4cdcd3c/user-interfaces/recipe-calculator/recipe-calculator-ui-1.png)

## Getting Started

To run the Recipe Calculator application locally, follow these steps:

1. **Prerequisites**:

   - Install [Flutter SDK](https://docs.flutter.dev/get-started/install) (stable channel, revision 796c8ef79279f9c774545b3771238c3098dbefab)
   - Ensure Dart SDK 3.0.5 is available via Flutter
   - Set up an emulator or connect a physical device

2. Clone the repository:

   ```shell
   git clone https://github.com/supunxiii/recipe-calculator.git
   ```

3. Navigate to the project directory:

   ```shell
   cd recipe-calculator
   ```

4. Install dependencies:

   ```shell
   flutter pub get
   ```

5. Run the application:

   ```shell
   flutter run
   ```

## Project Structure

```
recipe-calculator/
|-- android/                     # Android platform files (Gradle, manifests)
|-- assets/                      # Recipe images
|-- ios/                         # iOS platform files
|-- lib/                         # Dart source
|   |-- main.dart                # App entry point and recipe list UI
|   |-- recipe.dart              # Recipe and ingredient data models
|   `-- recipe_detail.dart       # Recipe detail screen with slider
|-- linux/                       # Linux desktop files
|-- macos/                       # macOS desktop files
|-- web/                         # Web platform files
|-- windows/                     # Windows desktop files
|-- pubspec.yaml                 # Dependencies and metadata
|-- pubspec.lock                 # Locked package versions
`-- test/                        # Flutter test scaffolding
```

## Development Guidelines

### Building the Application

```shell
# Android (debug)
flutter build apk

# Android (release)
flutter build apk --release

# Web
flutter build web
```

### Running Tests

```shell
# Unit and widget tests
flutter test
```

## Contributors

This project was developed by:

- **Supun Wijesooriya** - Developer

## Contributing

Contributions to the Recipe Calculator application are welcome! If you would like to contribute, please follow these steps:

1. Fork the repository.

2. Create a new branch:

   ```shell
   git checkout -b feature/your-feature-name
   ```

3. Make your changes and commit them:

   ```shell
   git commit -m "Add your commit message"
   ```

4. Push your changes to your forked repository:

   ```shell
   git push origin feature/your-feature-name
   ```

5. Open a pull request to the main repository, describing your changes and the purpose of the pull request.

## Important Notes

- The app uses local asset images and runs fully offline once dependencies are installed
- Ingredient quantities are recalculated via a servings slider for quick scaling
- The UI is optimised for mobile layouts with simple, readable cards
- Recipes and ingredients are stored in Dart model classes for easy extension

## Future Enhancements

Potential improvements for future versions:

- Ingredient unit conversion (metric and imperial)
- User-defined recipes with persistent storage
- Shopping list export
- Recipe search and filtering
- Nutrition and calorie information
- Theming options and colour customisation

## Contact

For any inquiries or feedback, please contact the developer:

- **Supun Wijesooriya**: [GitHub Profile](https://github.com/supunxiii)
- **Project Repository**: [recipe-calculator](https://github.com/supunxiii/recipe-calculator)

---

**Note:** This is a beginner-friendly Flutter project that demonstrates core concepts such as list views, navigation, state management with `StatefulWidget`, local asset usage, and simple data modelling. It is a practical example of building a small mobile experience with responsive UI and interactive controls.
