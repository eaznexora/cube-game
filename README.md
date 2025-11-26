# cube-game
A single-file 3D Rubik's Cube Simulator using HTML, CSS, and Three.js

Features
3D Interactive View: Uses Three.js to render a fully rotatable 3D cube.

Smooth Animations: Realistic turning animations for all faces.

Control Methods:

UI Buttons: On-screen controls for mobile/tablet users (U, D, L, R, F, B).

Keyboard Shortcuts: PC users can use standard notation keys to rotate faces.

Mouse Interaction: Click and drag the background to rotate the camera view.

Scramble & Reset: One-click buttons to randomize the cube or return it to the solved state.

Drift Correction: Includes logic to snap cubies to the nearest grid integer to prevent 3D floating point errors from breaking the cube over time.

Instructions
View: Drag anywhere in the empty space to rotate the camera.

Rotate Faces: Use the on-screen buttons or keyboard keys:

F (Front), B (Back), U (Up), D (Down), L (Left), R (Right).

Hold Shift + Key for counter-clockwise (Prime) moves.

Scramble: Click "Scramble" to randomize.
