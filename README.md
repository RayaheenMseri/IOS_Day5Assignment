# SwiftUI App with Name Update and Dark Mode Toggle

This is a simple SwiftUI app that allows the user to:
1. Enter a name into a `TextField`.
2. Update a displayed label with the entered name.
3. Toggle between dark and light modes for the background and UI elements.

## Features

- **TextField**: Users can input a new name.
- **Button**: Click the button to update the displayed name.
- **Dark Mode Toggle**: A toggle switch to change between dark and light modes.
- **Dynamic UI**: The UI elements (like text color and background color) update based on the dark mode state.

## Usage

1. **Enter your name** in the `TextField` at the top of the screen.
2. **Click the "Update Name!" button** to update the displayed name.
3. **Toggle dark mode** using the switch at the bottom of the screen to switch between dark and light backgrounds.

### UI Elements

- **Name Display**: Shows a greeting message with the user’s name.
- **TextField**: Lets users enter a new name.
- **Button**: Updates the name displayed when clicked.
- **Toggle**: Switches between dark and light mode for the app background and UI elements.

## Project Structure

- **ContentView.swift**: Main view of the app with the name display, input field, button, and dark mode toggle.
- **DarkModeToggle.swift**: A separate view component that handles the dark mode toggle functionality.
- **ContentView_Previews**: Previews for both the `ContentView` and `DarkModeToggle` for testing.
