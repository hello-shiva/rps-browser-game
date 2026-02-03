🪨✂️📄 Rock Paper Scissors Game

A web-based Rock Paper Scissors game built using HTML, CSS, and JavaScript. The player plays against the computer, and the winner is decided based on standard game rules.It allows users to play against the computer with real-time score updates and instant results. The project demonstrates DOM manipulation, event handling, and basic game logic in a simple and interactive way.

📌 Features

> Click-based gameplay
> Random computer moves
> Live score tracking
> Win / Lose / Draw messages
> Interactive UI
> Responsive hover effects

🛠️ Technologies Used

Technology	      Purpose<br>
HTML	            Structure<br>
CSS              	Styling<br>
JavaScript	      Game Logic<br>

📂 Project Structure

Rock-Paper-Scissors/
│
├── index.html       # Main HTML file<br>
├── style.css        # Styling file<br>
├── app.js           # JavaScript logic<br>
├── rock.webp        # Rock image<br>
├── paper.webp       # Paper image<br>
└── scissors.webp    # Scissors image<br>

▶️ How to Run the Game

1. Download or clone the project.
2. Open the folder.
3. Double-click on index.html.
4. The game will open in your browser.
5. Click on Rock, Paper, or Scissors to play.

*No internet connection required.*

🎮 How to Play

1. Choose any option:
 > Rock
 > Paper
 > Scissors
2. The computer will choose randomly.
3. Result is displayed:
 > 🟢 Green → You Win
 > 🔴 Red → You Lose
 > 🔵 Cyan → Draw
4. Scores update automatically.

⚙️ Game Rules

**Player	        Computer	        Result**
  Rock	          Scissors	        Win
  Rock	          Paper	            Lose
  Paper	          Rock	            Win
  Paper	          Scissors	        Lose
  Scissors	      Paper            	Win
  Scissors	      Rock	            Lose

  *Same choice → Draw*

🧠 Game Logic Overview

1. User Click Detection
 > Each choice listens for click events.
 >>> choice.addEventListener("click", ...)
2. Computer Choice
 > Generated randomly using:
 >>> Math.floor(Math.random() * 3);
3. Winner Decision
 > Game logic compares both choices and decides winner.
4. Score Update
 > Scores are updated dynamically using DOM manipulation.

🎨 UI Design
 
 > Circular buttons
 > Hover effects
 > Centered layout
 > Large score display
 > Message box with colors

*Styled using style.css.*

🚀 Future Improvements (Optional)

You can enhance this project by adding:
 > Sound effects 🔊
 > Restart button 🔄
 > Game history 📜
 > Dark mode 🌙
 > Difficulty levels 🎯
 > Mobile optimization 📱

👨‍💻 Author

Name: Shivam Kumar<br>
Project Type: Beginner Web Project<br>
Purpose: Learning JavaScript & DOM

📜 License
<br>
This project is free to use for learning and educational purposes.
