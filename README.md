# News Snack - WebView News Viewer

## Overview
News Snack is a Flutter-based application that allows users to view news articles in a WebView. The app ensures that all links use HTTPS for security and provides a seamless browsing experience.

## Features
- Loads news articles in a WebView
- Automatically converts HTTP URLs to HTTPS for security
- Full JavaScript support within the WebView
- Simple and minimal UI for distraction-free reading

## Installation

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/Aman-1199/news_app.git
   ```
2. **Navigate to the Project Directory:**
   ```sh
   cd news_app
   ```
3. **Install Dependencies:**
   ```sh
   flutter pub get
   ```
4. **Run the App:**
   ```sh
   flutter run
   ```

## Usage
1. Open the app.
2. Tap on a news article link (handled externally in the app logic).
3. The article loads in the WebView.
4. Enjoy reading in a secure and smooth WebView experience.

## Dependencies
This project uses the following Flutter package:
- [`webview_flutter`](https://pub.dev/packages/webview_flutter) - to integrate a WebView inside the Flutter app.

## Code Explanation
- `DetailViewScreen` takes a `newsUrl` as a parameter and displays it inside a WebView.
- The `initState` method checks if the URL contains `http:` and replaces it with `https:`.
- A `WebViewController` is used to control the WebView instance.
- The WebView is created and initialized with JavaScript enabled.

## Contributing
Feel free to contribute to the project by submitting a pull request or opening an issue.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
Made with ❤️ using Flutter.

