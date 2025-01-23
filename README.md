GitHub User List App - Jetpack Compose 

This project is a modern Android application built with Jetpack Compose and other cutting-edge tools. The app retrieves a list of GitHub users, handles offline and online states, caches data locally, and provides a clean, user-friendly interface. The following features demonstrate best practices and advanced Android development concepts.

Features

1. Modern UI Design with Jetpack Compose

Fully declarative UI designed with Jetpack Compose.

Offers a responsive and elegant interface for both Light and Dark Mode.

Dynamic theme switching based on the system preferences.

2. Retrieve Data from GitHub

Fetches a list of GitHub users using Retrofit for network operations.

Displays user data in a well-structured and visually appealing format.

3. Offline and Online State Management

Detects network connectivity in real-time.

Ensures users can access the cached data even when offline.

4. Caching with Room Database

Uses Room for efficient local data storage and retrieval.

Stores GitHub user data locally to improve offline access and performance.

5. Dependency Injection with HILT

Simplifies dependency management with HILT.

Injects dependencies such as ViewModels, repositories, and network services, ensuring a clean and modular architecture.

6. Light and Dark Mode Support

Automatically adapts to the device's theme settings.

Enhances user experience by providing consistent and accessible UI across themes.

Technical Stack

Jetpack Compose: For modern and declarative UI development.

Retrofit: For network requests to the GitHub API.

Room Database: For local caching of data.

HILT: For dependency injection.

Coroutines: For efficient asynchronous operations.

ViewModel: To manage UI-related data and lifecycle-aware components.

How to Run the App

Clone the repository:

git clone <repository_url>

Open the project in Android Studio.

Sync the Gradle files.

Run the app on an emulator or a physical device.

Setup and Configuration

GitHub API: The app uses the GitHub public API. No authentication is required.

Dependencies: All required dependencies are listed in the build.gradle file.

Screenshots

Include screenshots of the app showcasing both Light and Dark Mode, online and offline states, and other features.

Future Enhancements

Add pagination for GitHub user lists.

Implement search functionality to filter users.

Add user detail screens for more comprehensive information.

License

This project is licensed under the MIT License. Feel free to use and modify it as needed.
