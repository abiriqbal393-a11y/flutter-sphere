# SPHERE - Flutter Social Media App

A modern Flutter social media application featuring real-time chat, social feed, and user profiles.

## Features

✨ **Core Features:**
- 🔐 Authentication (Google & Phone Sign-in)
- 📱 Social Feed with Posts
- 💬 Real-time Messaging
- 👤 User Profiles
- 🎬 Clips & Moments Support
- 🎨 Dark Theme UI
- 🇧🇩 Bengali Language Support

## Project Structure

```
lib/
├── main.dart          # Main app entry point with all screens
└── screens/           # All UI screens (Home, Chats, Profile, etc.)
```

## Screens

### 1. **Splash Screen**
   - 3-second splash with animated SPHERE logo
   - Auto-navigates to login

### 2. **Login Screen**
   - Google Sign-in
   - Phone Sign-in
   - Modern card-based UI

### 3. **Home Feed Screen**
   - Social feed with posts
   - Clips & Moments navigation
   - Post creation interface
   - Post cards with engagement actions

### 4. **Chats Screen**
   - Horizontal scroll for active users
   - Search functionality
   - Chat conversation list
   - Online status indicators

### 5. **Profile Screen**
   - User profile header
   - Profile picture with edit option
   - User details section
   - Add Friend & Chat buttons

## Getting Started

### Prerequisites
- Flutter SDK (3.0 or higher)
- Dart SDK
- Android Studio / Xcode

### Installation

1. Clone the repository:
```bash
git clone https://github.com/abiriqbal393-a11y/flutter-sphere.git
cd flutter-sphere
```

2. Install dependencies:
```bash
flutter pub get
```

3. Run the app:
```bash
flutter run
```

## Dependencies

- `flutter` - UI framework
- `cupertino_icons` - iOS style icons
- `intl` - Internationalization

## Architecture

- **Stateless Widgets**: For static screens (LoginScreen, HomeScreen)
- **Stateful Widgets**: For interactive navigation (MainLayout, SplashScreen)
- **Reusable Components**: PostCard, DetailRow for code reusability

## UI/UX Design

- **Color Scheme**: Dark theme with blue accents
- **Typography**: Bold headlines, readable body text
- **Icons**: Material Design icons throughout
- **Responsiveness**: Adapts to different screen sizes

## Future Enhancements

- [ ] Firebase Integration for authentication
- [ ] Real-time database (Firestore) for posts and chats
- [ ] Image upload functionality
- [ ] Video support for Clips
- [ ] Notification system
- [ ] State management (Provider/Riverpod)
- [ ] Search functionality
- [ ] User recommendations
- [ ] Comment system
- [ ] Like/Unlike features

## Contributing

Contributions are welcome! Please follow the Flutter style guide and create pull requests for any improvements.

## License

MIT License - feel free to use this project for learning or as a template.

## Author

Created with ❤️ by Abiriqbal393-a11y

---

**Happy Coding! 🚀**
