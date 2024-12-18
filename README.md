
# Android Battery Saver

This project is an undergrad dissertation aimed at assisting Android devices in saving battery life by intelligently managing app configurations. By saving and restoring specific app states, such as brightness levels and CPU core frequencies, the system reduces unnecessary power consumption.

## Key Features
- **Dynamic State Management**: Automatically save and load configurations for foreground apps.
- **Energy Efficiency**: Optimize brightness levels and CPU core frequencies for each app.
- **Local Storage**: All configurations are stored locally in a database for fast retrieval.

## How It Works
1. **Foreground App Detection**: The system detects the currently active app.
2. **Configuration Management**:
   - If a configuration exists for the app, it is loaded and applied.
   - If no configuration exists, a new one is created and stored in the local database.
3. **Battery Optimization**: Brightness levels and CPU core frequencies are adjusted based on the saved configuration.

## Data Stored for Each App
- **Brightness Level**: The screen brightness level specific to the app.
- **CPU Core Frequencies**: The frequency of each CPU core used by the app.

## Technical Overview
- **Platform**: Android
- **Development Environment**: Android Studio
- **Database**: Local SQLite database for storing app configurations
- **Languages**: Java/Kotlin

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/SyuzannE/AndroidBatterySaver.git
   ```
2. Open the project in Android Studio.
3. Build and run the app on your Android device or emulator.

## Future Enhancements
- Implement machine learning models to predict optimal configurations based on app usage patterns.
- Add user-friendly interfaces for manually managing configurations.
- Extend support for monitoring and optimizing background apps.

## Contributing
Contributions are welcome! Please fork the repository, create a new branch for your feature or bug fix, and submit a pull request.

## Acknowledgments
- Special thanks to the academic mentors and peers who provided guidance and support during the development of this project.
