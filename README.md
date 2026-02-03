# SwitchAccessibleApp 🎮

**Switch Accessible Tablet App (SATA)**

An accessible adaptive game library designed for individuals using switch access technology. Built with Expo/React Native, this app provides educational games and activities specifically designed for users with motor disabilities, controlled via external switches or tap interactions.

---

## 🏆 Award Recognition

**🥈 2nd Place at 2025 RESNA Student Design Challenge**

Our project, *Switcharoo: Switch Accessible Tablet App*, was awarded 2nd place at the [2025 RESNA Student Design Challenge](https://www.resna.org/Events/2025-RESNA-Conference/2025-Student-Design-Challenge-Winners).

<p align="center">
  <img src="assets/switchgrouppic.png" alt="Switcharoo team receiving RESNA award" width="500"/>
</p>

<p align="center">
  <a href="assets/Switcharoo-Research-Poster-32x40.pdf">📄 View Our Research Poster</a>
</p>

---

## 🎯 Purpose

This app provides an inclusive gaming experience for users who rely on assistive technology, particularly switch access devices. Each game is designed with accessibility in mind, offering simple, cause-and-effect interactions that work seamlessly with adaptive input methods.

### Our Mission

A way to address the lack of accessible and engaging tools for children with diverse abilities so that they can develop motor and cognitive skills through playful, inclusive learning experiences.

### Design Goals

1. Align game experiences with **learning themes** and the **developmental goals** of children
2. Provide educators and caregivers with a **supportive, effortless, low-cost** tool
3. Prioritize **user autonomy**, **simplicity**, and **accessibility**

## ✨ Features

### 🎮 Game Library

Currently includes three fully accessible games:

- **Pop The Balloon** — A cause-and-effect game where players tap to pop one of 8 randomly positioned balloons. Features responsive layouts, animated GIFs, and custom backgrounds.
- **Stacking Blocks** — A hand-eye coordination game using physics-based block stacking mechanics.
- **Sorting Game** — A classification game focused on shape recognition and sorting.

Three additional games are planned: Treasure Hunt, Crossy Roads, and Music Play.

### 🌟 Core Features

- **Favorites System** — Save and quickly access your favorite games
- **Game Information** — Detailed descriptions, themes, and switch requirements for each game
- **Responsive Design** — Adaptive layouts for mobile (1 column) and tablet/desktop (3 columns)
- **Tab Navigation** — Organized sections: Library, Favorites, Settings, and Help
- **Switch Access Ready** — Built with external switch compatibility using react-native-keyevent
- **Haptic Feedback** — Tactile responses for user interactions

### 🔧 Planned Accessibility Settings

- High Contrast Mode
- Sound Controls
- Haptics Toggle
- Switch Enable/Disable

## 🛠 Tech Stack

**Core Framework:**
- React Native 0.76.9 with Expo 52
- TypeScript/JavaScript
- File-based routing with expo-router

**UI & Styling:**
- NativeWind (Tailwind CSS for React Native)
- Custom Fredoka font family
- Expo Vector Icons

**Accessibility & Input:**
- expo-haptics for tactile feedback
- react-native-keyevent for switch input
- react-native-gesture-handler for touch interactions

**Game Development:**
- react-native-game-engine for physics
- @shopify/react-native-skia for graphics
- react-native-reanimated for animations

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or later)
- npm or yarn
- Expo CLI
- iOS Simulator (Mac) or Android Emulator (optional)

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd huskyADAPT-sata
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npx expo start
   ```

4. Run on your preferred platform:
   - Press `i` for iOS simulator
   - Press `a` for Android emulator
   - Press `w` for web browser
   - Scan the QR code with Expo Go on your mobile device

## 📁 Project Structure

```
/app                        # Main app screens (file-based routing)
  /(games)                  # Game implementations
  /index.tsx                # Library screen (home)
  /FavoritesScreen.tsx      # Favorites view
  /SettingsScreen.tsx       # App settings
  /HelpScreen.tsx           # Help & FAQ

/components                 # Reusable UI components
  /GameTile.jsx             # Game selection tiles
  /GameHeader.tsx           # In-game header
  /InfoScreen.jsx           # Game info modal
  /game_components          # Game-specific components

/assets                     # Images, GIFs, and data files
  /gamesData.json           # Game metadata
  /settingsData.json        # Settings configuration
  /helpData.json            # FAQ content
  /(games)/Assets           # Game-specific assets
```

## 🎨 Key Features of Each Game

### Pop The Balloon
- 8 balloons in responsive 2x4 grid layout
- Random balloon positioning within screen sections
- Animated popping effects with GIFs
- Custom background image with responsive scaling
- State tracking for popped balloons

### Stacking Blocks
- Physics-based block dropping mechanics
- Continuous loop animation
- Hand-eye coordination training

### Sorting Game
- Shape-based classification
- Visual feedback for correct/incorrect sorting

## 🧪 Development

### Available Scripts

```bash
npm run ios           # Run on iOS
npm run android       # Run on Android
npm run web           # Run on web
npm test              # Run tests with Jest
npm run lint          # Run linter
```

### Testing

This project uses Jest with jest-expo preset. Run tests with:

```bash
npm test
```

## 🤝 Contributing

Contributions are welcome! This project aims to improve accessibility in gaming. If you have ideas for new games, accessibility features, or improvements, please feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📚 Learn More

To learn more about the technologies used in this project:

- [Expo Documentation](https://docs.expo.dev/)
- [React Native Documentation](https://reactnative.dev/)
- [NativeWind Documentation](https://www.nativewind.dev/)
- [Switch Access Guidelines](https://www.w3.org/WAI/perspective-videos/switch/)

## 📄 License

[Add your license information here]

## 👥 My Team

- Ella Cao
- James Tran
- Arshita Misra
- Mishti Dhawan
- Sneha Birru
- Helen Liu

## 🙏 Acknowledgments

Built with accessibility and inclusion at the forefront, aiming to make gaming accessible to everyone.

Special thanks to [HuskyADAPT](https://depts.washington.edu/adaptuw/) (Accessible Design And Play Technology) at the University of Washington for supporting this project.

---

**Platform Support:** iOS • Android • Web
