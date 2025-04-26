# iD Solutions Flutter Test Project

This is a simple Flutter application built for testing purposes at iD Solutions.

## Description

This project is a **test project** for iD Solutions. The app consists of:

- **Login Screen**: A simple login form with validation (username cannot be empty, password must be at least 6 characters).
- **Dashboard Screen**: After successful login, it fetches user data from a dummy API (JSONPlaceholder) and displays the data in a list.
- **Pull-to-refresh**: Added functionality to refresh the data by pulling down the screen.

### Features:
1. **Login Page**: Validates form inputs (username, password).
2. **Dashboard Page**: Fetches and displays a list of data (such as products or users) from a dummy API.
3. **Pull-to-refresh**: Allows refreshing the dashboard to fetch updated data.

## Project Setup

1. Clone this repository:
git clone https://github.com/andreirawan313/idsolutions_fluttertest.git

2. Navigate to the project directory:
cd idsolutions_fluttertest


3. Install dependencies:
flutter pub get

4. Run the app:
flutter run


## Technologies Used

- **Flutter**: Framework used to build the application.
- **Provider**: State management solution.
- **JSONPlaceholder API**: Dummy API used to fetch user data for the dashboard.
- **Flutter's `pull-to-refresh`**: For refreshing the data on the dashboard.

## Technical Details

This app demonstrates basic Flutter functionality including:

- **State Management**: We used `Provider` for managing application state, allowing us to easily fetch and display data from the API.
- **UI Design**: The design follows a simple and responsive layout using Flutter's Material UI components. The UI is mobile-friendly and adapts well to various screen sizes.
- **Error Handling**: In case of API errors, an error message is shown with an option to try again.

## Test Environment

- **Flutter version**: 3.x.x
- **Dart version**: 2.x.x
- **Android Studio/VS Code**: IDEs used for development.

## License

This project is open-source and available under the [MIT License](LICENSE).

