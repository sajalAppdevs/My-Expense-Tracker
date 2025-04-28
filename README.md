# My Expense Tracker

A modern and intuitive Flutter application for tracking personal expenses with a clean user interface and powerful features.

## Features

- 📱 Cross-platform support (iOS, Android, Web, Desktop)
- 🌓 Dynamic theme switching (Light/Dark mode)
- 💰 Track and manage expenses
- 📊 Database integration with SQLite
- 📸 Image attachment support
- 📅 Date-based expense tracking
- 📱 Responsive design with ScreenUtil
- 🎨 Modern UI with Material Design

## Tech Stack

- Flutter SDK (>=2.17.1 <3.0.0)
- GetX for state management
- SQLite for local database
- GetStorage for local storage
- Flutter ScreenUtil for responsive design

## Dependencies

- get: ^4.6.5 - State management and routing
- get_storage: ^2.0.3 - Local storage solution
- flutter_screenutil: ^5.5.4 - Responsive UI adaptation
- sqflite: ^2.0.3+1 - SQLite database integration
- image_picker: ^0.8.5+3 - Image selection functionality
- date_picker_timeline: ^1.2.3 - Date selection interface
- google_fonts: ^3.0.1 - Custom font integration
- dropdown_button2: 1.7.2 - Enhanced dropdown widgets

## Getting Started

### Prerequisites

- Flutter SDK (>=2.17.1)
- Dart SDK
- Android Studio / VS Code with Flutter extensions

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/my-expense-tracker.git
```

2. Navigate to the project directory:
```bash
cd my-expense-tracker
```

3. Install dependencies:
```bash
flutter pub get
```

4. Run the app:
```bash
flutter run
```

## Project Structure

- `lib/` - Contains the main source code
  - `backend/` - Backend logic and database operations
  - `controllers/` - GetX controllers for state management
  - `data/` - Data models and theme configuration

## Features in Detail

### Theme Switching
The app supports dynamic theme switching between light and dark modes using GetX state management.

### Database Integration
Uses SQLite for local storage of expense data with proper CRUD operations.

### Responsive Design
Implements ScreenUtil for ensuring consistent UI across different screen sizes.

### Image Attachment
Supports attaching images to expense entries using the image_picker package.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
