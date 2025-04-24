🌀 Digital Twin Fan Simulation with Three.js

This project is a simulation of a digital twin of a fan using the Three.js library. It provides a 3D visualization of a fan with interactive and dynamic behavior, mimicking the operations of a real-world device.


<img width="1470" alt="Screenshot 2025-04-25 at 12 53 46 AM" src="https://github.com/user-attachments/assets/d5489889-e1f6-4f4b-af6f-6b8a6bd6f872" />

🌟 Features

🎨 3D Scene Composition

Initializes a THREE.Scene, THREE.PerspectiveCamera, and THREE.WebGLRenderer.
Dynamically creates a virtual environment with lighting, shadows, and materials.

🌬️ Fan Simulation

Custom fan model built with THREE.CylinderGeometry and THREE.BoxGeometry.
Fan blade rotation mimics real-world motor movement.
Rotation speed dynamically adjustable with code-based control.

💡 Lighting System

Simulates realistic lighting using THREE.PointLight and THREE.AmbientLight.
Shadows and highlights bring depth and realism to the scene.

📦 Modular Structure

Object construction and scene management separated into reusable code blocks.
Parameters like fan speed and blade count easily configurable in code.
🧭 Camera & Controls

OrbitControls allow smooth camera interaction (rotate, pan, zoom).
Camera positioned dynamically based on screen resolution and fan placement.
🎞️ Animation Loop

Custom animation frame loop driven by requestAnimationFrame.
Syncs fan rotation with system frame rate for smooth movement.

⚙️ Real-Time Parameter Updates

Fan speed, direction, and animation parameters adjustable at runtime.
Uses simple JS variables for control—ready for future GUI or IoT integration.

📦 Built With

Three.js - JavaScript 3D Library
JavaScript (ES6)
Webpack / Vite / Vanilla HTML (depending on integration)
🛠️ Installation

Clone the repository:
git clone https://github.com/yourusername/fan-digital-twin.git
cd fan-digital-twin
Install dependencies (if using a bundler):
npm install
Run the development server:
npm run dev
Or open the index.html directly in your browser if not using a build tool.
📁 File Structure

📁 fan-digital-twin/
├── index.html
├── main-4.js           # Main simulation logic
├── styles.css          # Optional styling
└── assets/             # Models, textures, etc.

🔍 How It Works

A Scene, Camera, and Renderer are created using Three.js.
A 3D fan object is loaded or procedurally created.
The fan blades rotate continuously or based on control inputs.
Lighting and shadows enhance the realism of the simulation.

🎮 Controls

Camera: Orbit controls to zoom and pan.
Fan Speed: GUI slider to control rotation speed.
Start/Stop: Buttons to simulate power control (optional).


