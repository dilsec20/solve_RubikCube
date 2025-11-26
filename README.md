solve Rubik Cube 
link - https://dilsec20.github.io/solve_RubikCube/
CUBE.AI - Gemini-Powered Rubik's Cube Simulator 🧊🤖

CUBE.AI is not just a 3D Rubik's Cube simulator; it's an intelligent, interactive experience powered by Google's Gemini API.

Beyond standard scrambling and solving, this project features a "sentient" AI companion that watches your moves, offers coaching advice, and generates algorithmic patterns on the fly.

✨ Key Features

🤖 Gemini Live Integration

Sentient Commentary: The cube reacts to your actions (scrambling, solving, idling) with witty, context-aware personality.

Interactive Chatbot: A full chat interface on the left allows you to converse with the AI about cubing strategies, algorithms, or general chat.

AI Coach 🧠: Stuck on a scramble? The "Coach" button analyzes the exact history of your moves and gives you a strategic hint (e.g., "Focus on the White Cross first") without spoiling the full solution.

Dream Patterns ✨: Ask Gemini to generate beautiful, valid cube patterns (like "Checkerboard" or "Cube in a Cube") and watch them apply automatically.

🎮 3D Simulation & Controls

Three.js Engine: High-performance 3D rendering with realistic lighting, materials, and smooth animations.

Smart Controls: Manual control buttons (U, D, L, R, F, B) are view-aware. Pressing "Right" rotates the face currently on the right side of your screen, regardless of how you have rotated the camera.

Auto-Rotate: A 360° spin mode to inspect your cube from all angles.

⚡ Algorithmic Solver

Layer-by-Layer AI: A robust internal solver that can resolve the cube from any scrambled state using the beginner's method logic.

Move Optimization: The engine mathematically reverses your scramble history and optimizes the path (e.g., converting 3 right turns into 1 left turn) for efficiency.

🚀 Getting Started

Prerequisites

You need a modern web browser and a Google Gemini API Key.

Get an API Key:

Visit Google AI Studio.

Create a free API key.

Installation

Clone or Download this repository.

Open the file: Open rubiks_cube.html in any code editor (VS Code, Notepad++, etc.).

Insert API Key:

Scroll to around line ~175 in the script section.

Find the variable: const apiKey = "";

Paste your key inside the quotes:

const apiKey = "AIzaSyYourActualKeyHere..."; 


Run: Double-click rubiks_cube.html to open it in your browser.

🛠️ Technologies Used

Frontend: HTML5, JavaScript (ES6+)

Styling: Tailwind CSS (via CDN)

3D Graphics: Three.js (via CDN)

Artificial Intelligence: Google Gemini API (gemini-2.5-flash-preview)

Fonts: Orbitron (Google Fonts)

📸 Screenshots

Chat Interface

3D Interaction

Chat with the AI about strategy

Smooth 3D rotations and solving

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📄 License

Distributed under the MIT License. See LICENSE for more information.

Built with ❤️ and ☕ by [Your Name]
