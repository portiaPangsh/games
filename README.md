# 🎮 Sudoku Game

An elegant, feature-rich Sudoku puzzle game built with vanilla JavaScript.

## ✨ Features

- 🎯 **Three Difficulty Levels**: Easy, Medium, and Hard
- 📝 **Notes Mode**: Mark possible numbers (pencil marks) before committing
- ✏️ **Number Mode**: Enter final answers directly
- ✅ **Solution Checker**: Validate your progress
- 💡 **Hint System**: Get help when stuck
- ⏱️ **Timer**: Track your solving time
- 🎨 **Beautiful UI**: Soft pink-blue gradient design with smooth animations
- 📱 **Responsive**: Works on desktop and mobile

## 🎮 How to Play

1. **Choose Difficulty**: Select Easy, Medium, or Hard
2. **Select a Cell**: Click on any empty cell
3. **Choose Mode**:
   - **Number Mode**: Press 1-9 to enter your final answer
   - **Notes Mode**: Press 1-9 to mark possible numbers (toggle on/off)
4. **Delete**: Press Backspace or Delete to clear a cell
5. **Check**: Click "Check Solution" to validate your answers
6. **Hint**: Click "Get Hint" for help
7. **Win**: Complete the puzzle correctly to see your time!

## 🚀 Demo

**Live Demo**: [https://portiapangsh.github.io/sudoku-game](https://portiapangsh.github.io/sudoku-game)

## 🛠️ Technical Stack

- **HTML5** - Semantic structure
- **CSS3** - Modern styling with gradients, animations, and flexbox/grid
- **Vanilla JavaScript** - No frameworks, pure JS
- **Google Fonts** - Quicksand & IBM Plex Mono

## 📋 Key Features Implementation

### Notes/Pencil Marks
- Toggle between Number Mode and Notes Mode
- Display up to 9 small numbers in a 3×3 grid per cell
- Automatically clear notes when entering a final number

### Puzzle Generation
- Generates valid Sudoku puzzles using backtracking algorithm
- Removes cells based on difficulty level (35/45/55 for Easy/Medium/Hard)
- Ensures unique solution

### Smart Validation
- Real-time error checking with visual feedback
- Shake animation for incorrect entries
- Color-coded feedback system

## 🎨 Design

- **Color Scheme**: Soft pink (#f5a3c7) and blue (#81b1f7) gradients
- **Typography**: Quicksand for headers, IBM Plex Mono for numbers
- **Responsive**: Mobile-friendly grid layout
- **Animations**: Smooth transitions and micro-interactions

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)

## 🚀 Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/portiaPangsh/sudoku-game.git
   ```

2. Open `index.html` in your browser - that's it! No build process needed.

## 📝 Future Enhancements

- [ ] Save/load game state
- [ ] User authentication with Firebase
- [ ] Game history and statistics
- [ ] Dark mode toggle
- [ ] Multiple color themes
- [ ] Leaderboard
- [ ] Daily challenges

## 👩‍💻 Author

**Portia Pang**
- Portfolio: [portiapangsh.github.io](https://portiapangsh.github.io)
- GitHub: [@portiaPangsh](https://github.com/portiaPangsh)

## 📄 License

MIT License - feel free to use this project for learning or your own portfolio!

---

Made with ❤️ by Portia
