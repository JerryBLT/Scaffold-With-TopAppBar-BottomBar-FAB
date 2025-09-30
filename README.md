# Scaffold-With-TopAppBar-BottomBar-FAB
Scaffold with a prominent top bar for the app title and a bottom navigation bar featuring Home, Settings, and Profile. Add a Floating Action Button (FAB) that shows a Snackbar message when pressed. Ensure appropriate inner padding throughout the Scaffold to maintain a clean layout.

## Features
- **TopAppBar** with app title
- **Bottom NavigationBar** with 3 items: Home, Settings, Profile
- **Floating Action Button (FAB)** that triggers a **Snackbar**
- Proper **innerPadding** applied to avoid overlap with bars
- Uses **Material 3 Scaffold** structure

## Getting Started
### Prerequisites
- Android Studio (latest version recommended)

### How to Run
1. Clone the repository:
2. Open the project in Android Studio.

## Project Structure
- `MainActivity.kt`: Contains main Compose UI and state code.
- `ui.theme`: Contains app theme and styling.

## Usage
- Build and run the app to see a screen layout with a TopAppBar, Bottom Navigation Bar, and Floating Action Button (FAB).
- The TopAppBar displays the app title; the BottomBar lets you switch between "Home," "Settings," and "Profile" tabs.
- Tap the FAB to trigger a Snackbar message at the bottom of the screen.
- Padding is automatically applied to ensure content does not overlap with the bars or FAB, using innerPadding from the Scaffold.
- The BottomBar supports dynamic selection—tapping each item highlights it and updates the selected state.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
Jerry Teixeria  
BU Email: jerrybt@bu.edu
