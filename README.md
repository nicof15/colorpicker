# Color Picker App

The Color Picker App is a mobile application built using Flutter and Dart. It allows users to select a color from a predefined set of colors, and the selected color is displayed as the background color of the app. The app utilizes the SharedPreferences package to store and retrieve the selected color, ensuring that the selected color persists across app restarts.

## Features

- Select a color from a predefined set of colors.
- Display the selected color as the background color of the app.
- Store and retrieve the selected color using SharedPreferences.

## Compatibility

The Color Picker App is compatible with Android devices. It has been tested and verified to work on various Android devices.

## Usage

1. Launch the Color Picker App on your Android device.
2. The app will display a set of color buttons.
3. Tap on a color button to select a color.
4. The background color of the app will change to the selected color.
5. The selected color will be stored using SharedPreferences, ensuring it persists across app restarts.

## Implementation Details

The Color Picker App is implemented using the Flutter framework and the Dart programming language. Here are the key components and their functionalities:

- `main.dart`: The entry point of the app. It initializes and runs the `MyApp` widget.
- `MyApp`: The root widget of the app. It sets up the app's title and theme, and defines the `MyHomePage` widget as the home page.
- `MyHomePage`: The main page of the app. It extends the `StatefulWidget` class and manages the app's state. It includes a predefined set of colors as a map, tracks the selected color, and provides methods to retrieve and set the selected color using SharedPreferences. The page displays the app's title in the app bar and a column of color buttons. The background color of the app changes dynamically based on the selected color.

The Color Picker App offers a simple and intuitive interface for selecting and displaying colors, providing an enjoyable user experience.

**Note:** The Color Picker App has been specifically designed and tested for Android devices. It may not be compatible with other platforms such as iOS or web browsers.
