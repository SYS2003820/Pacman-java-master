Pac-Man (Java, Swing)
A basic Pac-Man clone built in Java Swing.
This is the original unmodified version — no added start screens, scores, or extra features.

🎯 Features
Pac-Man movement with arrow keys.

Ghosts moving around the map.

Simple maze layout.

Collect food pellets to increase score.

Win condition when all pellets are eaten.

Game over if caught by a ghost.

🧰 Tech Stack
Language: Java (JDK 8+)

UI: Java Swing / AWT

IDE: Any (VS Code, IntelliJ IDEA, Eclipse)

📂 Project Structure (Original)
javascript
Copy code
pacman-java/
├─ PacMan.java       // Main game panel and loop
├─ Ghost.java        // Ghost movement logic
├─ Map.java          // Maze data
├─ images/           // PNG sprites
└─ ...
🚀 Running the Game
1) Prerequisites
Install Java JDK 8+.

Optional: Install VS Code with the Java Extension Pack.

2) Run in VS Code
Open the folder in VS Code.

Open PacMan.java.

Click the green Run ▶ button above public static void main.

3) Run from Command Line
bash
Copy code
# Compile
javac *.java

# Run
java PacMan
🎮 Controls
Arrow Keys → Move Pac-Man

ESC → Exit game