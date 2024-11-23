# Minimal Flutter Chat App

This repository contains the source code for a minimal chat application built with Flutter, following the [tutorial by Code With Andrea](https://www.youtube.com/watch?v=5xU5WH2kEc0).

## Overview

This simple chat app demonstrates how to build a basic messaging interface using Flutter. It includes features such as:

- Sending and receiving messages
- Displaying messages in a chat bubble format
- Basic UI design resembling popular messaging apps

## Demo

![App Demo](screenshots/demo.gif)

*Note: Include a GIF or screenshot of your app in the `screenshots` directory.*

## Getting Started

### Prerequisites

- **Flutter SDK**: Version 3.0 or higher. [Install Flutter](https://flutter.dev/docs/get-started/install)
- **Dart SDK**: Comes bundled with Flutter.
- **IDE**: [Visual Studio Code](https://code.visualstudio.com/) with Flutter extension or [Android Studio](https://developer.android.com/studio).

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/minimal-flutter-chat-app.git
   cd minimal-flutter-chat-app
   ```

2. **Fetch dependencies**

   ```bash
   flutter pub get
   ```

3. **Run the app**

   - **Using an emulator or connected device**

     ```bash
     flutter run
     ```

   - **For web**

     ```bash
     flutter run -d chrome
     ```

## Project Structure

```
lib/
├── main.dart        # Entry point of the application
├── models/          # Data models
├── screens/         # UI screens
└── widgets/         # Reusable widgets
```

## Built With

- [Flutter](https://flutter.dev/) - UI toolkit for building natively compiled applications.
- [Dart](https://dart.dev/) - Programming language optimized for building UI.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **[Code With Andrea](https://codewithandrea.com/)** - For the comprehensive [tutorial](https://www.youtube.com/watch?v=5xU5WH2kEc0) that guided this project.
