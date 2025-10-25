# Rock Paper Scissors Game - README

## 📋 Project Overview
An interactive Rock Paper Scissors game built with vanilla JavaScript, HTML, and CSS. This web application allows users to play the classic hand game against the computer with real-time score tracking and visual feedback.

## ✨ Features
- **Classic Gameplay**: Traditional Rock Paper Scissors rules
- **Visual Choices**: Emoji-based buttons for rock (👊), paper (✋), and scissors (✌)
- **Real-time Score Tracking**: Live score display for both player and computer
- **Instant Results**: Immediate feedback with color-coded outcomes
- **Responsive Design**: Clean, centered layout that works on various devices
- **Visual Feedback**: Color changes for wins (green), losses (red), and ties (yellow)

## 🛠️ Technologies Used
- **HTML5**: Semantic structure and game interface
- **CSS3**: Flexbox layout, transitions, and modern styling
- **JavaScript**: Game logic, random computer choices, and DOM manipulation

## 📁 Project Structure
```
rock-paper-scissors-project/
│
├── Rock - Paper - Scissor.html     # Main HTML file
├── Rock - Paper - Scissor style.css # Stylesheet for the game
├── Rock - Paper - Scissor script.js # JavaScript game logic
└── README.md                       # Project documentation
```

## 🎮 How to Play
1. Open `Rock - Paper - Scissor.html` in a web browser
2. Click one of the three buttons to make your choice:
   - 👊 Rock
   - ✋ Paper  
   - ✌ Scissors
3. The computer will randomly select its choice
4. View the results and updated scores
5. Continue playing to see who reaches the highest score!

## 🎯 Game Rules
- **Rock** beats **Scissors** 👊 > ✌
- **Scissors** beats **Paper** ✌ > ✋
- **Paper** beats **Rock** ✋ > 👊
- Same choices result in a tie

## 💻 Code Highlights
- **Random Computer Selection**: Uses `Math.random()` for unpredictable computer choices
- **Efficient Game Logic**: Switch statements for clean win/lose/tie determination
- **Dynamic Styling**: CSS class toggling for color-coded results
- **Real-time Updates**: Immediate score and display updates

## 🎨 Design Features
- Large, intuitive emoji buttons (7.5rem font size)
- Circular buttons with hover effects and smooth transitions
- Color-coded results:
  - Green for wins
  - Red for losses  
  - Yellow for ties
- Bold, readable typography with appropriate sizing hierarchy
- Centered, organized layout using CSS Flexbox

## 🔧 Potential Enhancements
- Add game round limits (first to 5 wins)
- Implement game history or statistics
- Add sound effects for choices and results
- Include animations for choices (shaking hands, etc.)
- Add multiplayer functionality (player vs player)
- Implement difficulty levels (smarter computer AI)
- Add choice confirmation with countdown
- Include local storage for persistent high scores

## 📝 Learning Outcomes
This project demonstrates:
- Game logic implementation in JavaScript
- Random number generation for computer AI
- DOM manipulation and dynamic content updates
- Event handling and user interaction
- CSS styling for interactive elements
- State management for score tracking
- Conditional logic and switch statements

