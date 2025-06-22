# 🤖 Gemini ChatBot App
A modern and interactive ChatBot application built using Jetpack Compose and Google's Gemini AI. This app showcases real-time chat functionality with AI-powered responses, featuring a beautiful Material Design 3 interface and efficient message handling using the latest Android architecture components.

# ✨ Features
- 💬 **Real-time Chat** – Seamless conversation experience with Gemini AI
- 🤖 **AI Integration** – Powered by Google's advanced Gemini model
- 🎨 **Modern UI** – Built with Jetpack Compose and Material 3
- 📱 **Responsive Design** – Adapts perfectly to different screen sizes
- 🌈 **Dynamic Theming** – Supports Material You dynamic colors
- 🔄 **State Management** – Efficient handling using ViewModel
- 🎯 **Clean Architecture** – Following MVVM design pattern
- 💾 **Message History** – Local storage of chat conversations
- 🌐 **API Integration** – Secure handling of Gemini API calls

# 📸 Screenshots
![chat interface](path_to_screenshot1)
![dark theme](path_to_screenshot2)
![settings screen](path_to_screenshot3)

# ⚙️ Tech Stack
- **UI Framework**: Jetpack Compose
- **Language**: Kotlin
- **AI Model**: Google Gemini
- **Architecture**: MVVM
- **State Management**: StateFlow
- **Dependency Injection**: Hilt
- **Async Operations**: Coroutines
- **HTTP Client**: Retrofit
- **Local Storage**: Room Database

# 📂 Project Structure
- **app/src/main/**
  - **java/np/com/bimalkafle/easybot/**
    - **ChatPage.kt**: Main chat interface implementation
    - **ChatViewModel.kt**: ViewModel for chat functionality
    - **Constants.kt**: App-wide constant values
    - **MainActivity.kt**: Main activity of the application
    - **MessageModel.kt**: Data model for chat messages
    - **ui/**: UI components and theme
  - **res/**: Resources (layouts, values, drawables)
  - **AndroidManifest.xml**: App manifest file

# 🚀 Getting Started
Follow these steps to run the project locally:
1. Clone the repository
2. Open the project in Android Studio
3. Obtain a Gemini API key from Google AI Studio
4. Add the API key to local.properties:
   ```
   GEMINI_API_KEY=your_api_key_here
   ```
5. Sync the project with Gradle files
6. Run the app on an emulator or physical device

# 🔧 Requirements
- Android Studio Hedgehog or later
- Minimum SDK: 24
- Target SDK: 34
- Gemini API key
- Kotlin version: 1.9.0 or higher
- Compose version: 1.5.0 or higher

# 🤝 Contributing
Contributions are welcome! If you'd like to fix a bug or add a feature:
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

# 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
