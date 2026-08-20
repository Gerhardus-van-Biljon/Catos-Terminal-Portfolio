# 🐱 CatOS Terminal Portfolio
A personal portfolio styled An interactive pixel art cat terminal built with React, TypeScript and Figma. Features an animated 64x64 pixel cat with ear and tail movements and interactive massages, multiple color themes, and hidden easter egg commands 🐾🍭.
**Made with cats in mind by Gerhardus van Biljon**

![CatOS Terminal](https://img.shields.io/badge/CatOS-v1.0.2-brightgreen)
![React](https://img.shields.io/badge/React-18+-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5+-blue)
![Tailwind](https://img.shields.io/badge/Tailwind-4.0-cyan)

## 🚀 Live Preview
currently down

## ✨ Features

- 🎨 **Animated Pixel Cat**: 64x64 pixel art cat with ear movement animations
- 🌈 **Multiple Themes**: 6 beautiful color themes with dynamic error colors
- 🖥️ **Terminal Interface**: Authentic terminal experience with command history
- 🎭 **Hidden Easter Eggs**: Secret commands to interact with the cat
- 📱 **Responsive Design**: Works on desktop and mobile devices
- ⚡ **Real-time Updates**: Dynamic theme switching affects all previous messages
- 🎯 **Glitch Effects**: Theme-specific error animations

## 🚀 Getting Started

### Installation

```bash
# Clone the repository
git clone <repository-url>

# Install dependencies
npm install

# Start the development server
npm start
```

## 🎮 Commands

### Main Commands

| Command | Description |
|---------|-------------|
| `help` | Show all available commands |
| `bio` | Display developer biography |
| `about` | About CatOS Terminal |
| `contact` | Contact information |
| `projects` | View current projects |
| `status` | Show system status |
| `themes` | List available themes |
| `theme <name>` | Change color theme |
| `animation` | Toggle cat animations |
| `show` | Show/hide cat display |
| `clear` | Clear terminal history |
| `cat` | Show ASCII cat |

### System Commands

| Command | Description |
|---------|-------------|
| `date` | Show current date/time |
| `whoami` | Show current user |
| `pwd` | Show current directory |
| `ls` | List directory contents |
| `echo <text>` | Echo text back |
| `exit` | Try to exit (spoiler: you can't!) |

### 🥚 Easter Egg Commands (Hidden)

These commands are not shown in the help menu - discover them by experimenting!

| Command | Effect | Cat Display |
|---------|--------|-------------|
| `meow` | Cat meows loudly | "*meows loudly* 🐱" |
| `purr` | Cat purrs contentedly | "*purring contentedly* 😸" |
| `pet` | Pet the cat | "*enjoying head pets* 🥰" |
| `boop` | Boop the cat's nose | "*nose has been booped* 👃" |
| `treat` | Offer treats to the cat | "*waiting for treats* 🍖" |

*Note: Easter egg effects appear under the pixel cat for 3 seconds*

## 🎨 Available Themes

| Theme | Description | Error Color |
|-------|-------------|-------------|
| `matrix` | Green Matrix-style theme | Bright red (`#ff3333`) |
| `kimbie` | Warm amber woodland theme | Theme foreground |
| `dracula` | Purple cyberpunk theme | Bright pink (`#ff79c6`) |
| `abyss` | Deep ocean blue theme | Bright pink (`#ff79c6`) |
| `normal` | Professional gray theme | Soft red (`#ff6b6b`) |
| `chocolate` | Rich brown theme | Warm red (`#ff4757`) |

### Switching Themes

```bash
# Change to any theme
theme matrix
theme dracula
theme chocolate
# ... etc
```

## 🐱 Cat Features

### Animations
- **Ear Movements**: 4 distinct ear positions that cycle automatically
- **Tail Swishing**: Subtle tail movement in sitting position
- **Frame Rate**: 2 FPS (500ms intervals) for smooth animation
- **Toggle**: Use `animation` command to pause/resume

### Interactive Responses
The cat responds to easter egg commands with:
- Real-time message updates under the pixel art
- Temporary 3-second displays
- Contextual emoji reactions
- Ear movement responses

## 🛠️ Technical Details

### Built With
- **React 18+** - UI framework
- **TypeScript 5+** - Type safety
- **Tailwind CSS 4.0** - Styling
- **CSS Custom Properties** - Dynamic theming

### Architecture
- **Modular Components**: Separated concerns for maintainability
- **State Management**: React hooks with context API
- **Theme System**: CSS custom properties for instant switching
- **Animation Engine**: Interval-based frame cycling
- **Command Parser**: Flexible command processing with error handling

### File Structure
```
├── App.tsx                 # Main application component
├── components/
│   ├── Terminal.tsx        # Main terminal interface
│   ├── AppController.tsx   # State management
│   └── ...
├── catPoses.ts            # Pixel art cat animation frames
├── themes.ts              # Color theme definitions
└── README.md              # This file
```

## 🎭 Error System

### Theme-Specific Errors
Each theme has unique error messages and colors:

- **Matrix**: "SYSTEM BREACH", "The Matrix has been corrupted..."
- **Dracula**: "BLOOD MOON ERROR", "The vampires are restless..."
- **Abyss**: "DEEP SEA ERROR", "Tentacles emerging from the void..."
- **Normal**: "BUSINESS CRITICAL", "Productivity metrics failing..."
- **Chocolate**: "COCOA OVERFLOW", "Sweet dreams turning to nightmares..."

### Dynamic Color Updates
When switching themes, all previous error messages automatically update to use the new theme's error color.

## 🌟 Pro Tips

1. **Explore Commands**: Try typing random things - you might discover hidden features!
2. **Theme Switching**: Error messages change colors when you switch themes
3. **Cat Interaction**: Use easter egg commands to see the cat react
4. **Animation Control**: Toggle animations to save battery on mobile
5. **Command History**: Use ↑/↓ arrows to navigate command history
6. **Tab Completion**: Press Tab to autocomplete commands


## 🤝 Contributing

Feel free to contribute by:
- Adding new themes
- Creating new cat animations
- Adding more easter egg commands
- Improving the terminal experience
- Adding new features

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Inspired by classic terminal interfaces
- Pixel art cat designed with love for cats
- Color themes inspired by popular developer themes
- Special thanks to all cat lovers who will enjoy this project!

---



*"In ancient times cats were worshipped as gods; they have not forgotten this." - Terry Pratchett*
