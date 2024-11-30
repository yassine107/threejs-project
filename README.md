# README: 3D Model Viewer - *Textured_mesh_1*

## Overview
This project is a 3D model viewer that allows you to load and interact with 3D models exported from **3D Zephyr**. The viewer supports the `.glb` format, enabling users to visualize textured meshes in a browser environment. The project uses **Three.js** to render the models and includes user-friendly controls for an interactive experience.

The viewer can be easily launched locally using the **Live Server** extension in **Visual Studio Code (VS Code)**.

---

## Features
- **Model Visualization**: Supports `.glb` files with textures and animations.
- **Interactive Controls**: Rotate, zoom, and pan the model using mouse gestures.
- **Real-Time Loading Feedback**: Displays a loading bar and success/error messages.
- **Responsive Design**: Adapts to different screen sizes with automatic resizing.

---

## Tools and Technologies
1. **3D Zephyr**: Used to create and export the 3D model (*Textured_mesh_1.glb*).
2. **Three.js**: A WebGL-based library for rendering 3D graphics in the browser.
   - Modules used:
     - `GLTFLoader`: To load `.glb` files.
     - `OrbitControls`: To enable interactive model controls.
3. **VS Code Live Server Extension**: For local hosting of the project.

---

## Installation and Usage
### Prerequisites
1. **Visual Studio Code**: Download and install [VS Code](https://code.visualstudio.com/).
2. **Live Server Extension**:
   - Install the "Live Server" extension in VS Code from the Extensions Marketplace.

### Steps to Run
1. Clone or download the project repository.
2. Place your `.glb` model file in the `models/` directory and ensure it's named `Textured_mesh_1.glb`.
3. Open the project folder in **VS Code**.
4. Right-click on the `index.html` file and select **"Open with Live Server"**.
5. The viewer will launch in your default browser.

---

## File Structure
```plaintext
/
├── index.html          # Main HTML file with embedded JavaScript
├── models/             # Directory to store the .glb file
│   └── Textured_mesh_1.glb
└── README.md           # This README file
```

---

## User Instructions
- **Rotating the Model**: Click and drag with the left mouse button.
- **Zooming In/Out**: Use the scroll wheel.
- **Panning the Model**: Click and drag with the right mouse button or hold `Shift` while dragging.

---

## Known Issues
- Ensure the `Textured_mesh_1.glb` file path is correct (`./models/Textured_mesh_1.glb`). Incorrect paths will result in a loading error.
- Large models may take time to load depending on the system's performance.

---

## Credits
- **3D Zephyr**: For creating and exporting the model.
- **Three.js**: For rendering the 3D model.
- **Live Server Extension**: For enabling a local development server.

---

## License
This project is open-source and free to use for educational and non-commercial purposes. Please credit the author if used in public projects.

