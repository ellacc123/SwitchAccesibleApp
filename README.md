



---

## 🏆 Award Recognition

<table>
  <tr>
    <td width="50%">
      <img src="switchgrouppic.png" alt="Switcharoo team at RESNA 2025" width="100%"/>
    </td>
    <td width="50%">
      <h3>🥈 2nd Place at 2025 RESNA Student Design Challenge</h3>
      <p>Switcharoo was recognized at the <a href="https://www.resna.org/Events/2025-RESNA-Conference/2025-Student-Design-Challenge-Winners">2025 RESNA Conference</a> for innovative assistive technology designs that help people with disabilities function more independently</p>
      <p><strong>→</strong> <a href="assets/Switcharoo-Research-Poster-32x40.pdf">View our research poster</a></p>
    </td>
  </tr>
</table>

---

## 💡 The Problem

Play is critical for child development—but most games aren't designed for children who use switch access devices. These kids deserve fun, engaging experiences too.

**Switcharoo** is a game library built from the ground up for switch accessibility, developed through ethnographic research at local schools and interviews with educators and therapists.

### Design Principles

| | |
|---|---|
| 🎯 **Developmental** | Games align with learning themes and therapeutic goals |
| 🧑‍🏫 **Educator-friendly** | Low-cost, effortless tool for caregivers and therapists |
| ♿ **Accessible-first** | User autonomy, simplicity, and full switch support |

---

## 🎮 Games

<table>
  <tr>
    <td align="center" width="33%">
      <img src="assets/pop-balloon-preview.png" alt="Pop the Balloon" width="200"/><br/>
      <strong>Pop the Balloon</strong><br/>
      <em>Cause & Effect</em><br/>
      <sub>Tap to pop balloons with animated feedback</sub>
    </td>
    <td align="center" width="33%">
      <img src="assets/stacking-blocks-preview.png" alt="Stacking Blocks" width="200"/><br/>
      <strong>Stacking Blocks</strong><br/>
      <em>Timing</em><br/>
      <sub>Physics-based stacking with haptic feedback</sub>
    </td>
    <td align="center" width="33%">
      <img src="assets/sorting-game-preview.png" alt="Sorting Game" width="200"/><br/>
      <strong>Sorting Game</strong><br/>
      <em>Classification</em><br/>
      <sub>Sort shapes with high-contrast mode support</sub>
    </td>
  </tr>
</table>

**Coming soon:** Treasure Hunt, Crossy Roads, Music Play

---

## ✨ Features

**Accessibility**
- External switch support via `react-native-keyevent`
- Automatic scanning patterns across interactive elements
- High contrast mode for visual accessibility
- Haptic feedback for tactile responses
- Screen tap fallback for users without switches

**Dashboard**
- Grid-based game library with large, color-coded tiles
- Single/Group player toggle
- Favorites system with quick access
- Game info modals showing learning themes & switch requirements
- Built-in help center with setup guides

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/your-username/huskyADAPT-sata.git
cd huskyADAPT-sata

# Install dependencies
npm install

# Start development server
npx expo start
```

Then press `i` for iOS, `a` for Android, or `w` for web.

---

## 🛠 Tech Stack

| Category | Technologies |
|----------|-------------|
| **Framework** | React Native 0.76, Expo 52, TypeScript |
| **Styling** | NativeWind (Tailwind CSS), Fredoka font |
| **Accessibility** | expo-haptics, react-native-keyevent, react-native-gesture-handler |
| **Games** | react-native-game-engine, @shopify/react-native-skia, react-native-reanimated |

---

## 📁 Project Structure

```
app/
├── (games)/              # Game screens
├── index.tsx             # Library (home)
├── FavoritesScreen.tsx   # Saved games
├── SettingsScreen.tsx    # Accessibility settings
└── HelpScreen.tsx        # FAQ & troubleshooting

components/
├── GameTile.jsx          # Game selection cards
├── GameHeader.tsx        # In-game navigation
├── InfoScreen.jsx        # Game info modal
└── game_components/      # Game-specific UI

assets/
├── gamesData.json        # Game metadata
└── (games)/Assets/       # Game assets (images, sounds)
```

---

## 👥 Team

Built by students at the University of Washington through [HuskyADAPT](https://depts.washington.edu/adaptuw/) (Accessible Design And Play Technology):

**James Tran** · **Arshita Misra** · **Mishti Dhawan** · **Sneha Birru** · **Helen Liu** · **Ella Cao**

---

## 🤝 Contributing

We welcome contributions! See something that could be more accessible? Have an idea for a new game?

1. Fork the repo
2. Create your branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📚 Resources

- [Expo Documentation](https://docs.expo.dev/)
- [React Native Documentation](https://reactnative.dev/)
- [W3C Switch Access Guidelines](https://www.w3.org/WAI/perspective-videos/switch/)
- [HuskyADAPT at UW](https://depts.washington.edu/adaptuw/)

---

<p align="center">
  <sub>Built with ♿ accessibility and ❤️ inclusion at the forefront</sub>
</p>
