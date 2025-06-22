# 🤖 Gemini ChatBot App
A minimal yet powerful AI Chat Bot app built using Kotlin, Jetpack Compose, and MVVM architecture. This application allows users to interact with Google's Gemini API to get instant, intelligent responses. It features a clean, single-screen chat interface, making it easy to ask questions and get answers in real-time.

# ✨ Features
- 💬 **AI-Powered Conversations** – Ask questions and get intelligent responses using Gemini API.
- 💬 **Real-time Chat** – Smooth and quick interaction between user and bot.
- 🧠 **AI Integration** – Powered by Google's advanced Gemini model
- 🎨 **Modern UI** – Built with Jetpack Compose and Material 3
- 📱 **Responsive Design** – Adapts perfectly to different screen sizes
- 🔄 **State Management** – Efficient handling using ViewModel
- 🎯 **Clean Architecture** – Following MVVM design pattern
- 🌐 **API Integration** – Secure handling of Gemini API calls
- 🚫 **No Ads, No Clutter** – Focused and minimal experience with no distractions.

# 📸 Screenshots
![home](https://github.com/user-attachments/assets/92105cbd-33a4-42d7-b902-da949eadc9d9)
![home 2](https://github.com/user-attachments/assets/ee1fe992-06ca-41f0-a3cf-28c4b8847a78)

# ⚙️ Tech Stack
- **UI Framework**: Jetpack Compose
- **Language**: Kotlin
- **AI Model**: Google Gemini
- **Architecture**: MVVM
- **State Management**: StateFlow
- **Async Operations**: Coroutines

# 📂 Project Structure
- **app/src/main/**
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
