# RetrowaveWaveGenerator

Ocean Wave Generator (Vaporwave Wireframe Edition)
This is an interactive 3D ocean wave simulation built with Three.js, featuring a distinct vaporwave aesthetic and several physics-like effects. Explore dynamic wireframe waves, control environmental factors, and even float a tiny wireframe boat on the undulating surface.

<img width="1920" height="911" alt="image" src="https://github.com/user-attachments/assets/a6b128a8-f672-46af-b965-8c357e2a33cf" />


Features
Vaporwave Aesthetic: Neon wireframe lines, deep purple/blue background, and atmospheric fog create a retro-futuristic visual experience.

Dynamic 3D Waves: Waves are generated using a superposition of sine waves, providing a mathematically-based fluid simulation.

Interactive Camera: Use your mouse (click and drag to rotate, scroll to zoom) to explore the 3D wave field from any angle.

Adjustable Wave Parameters: Control various aspects of the waves in real-time:

Amplitude: The height of the waves.

Wavelength: The distance between wave crests.

Speed: How fast the waves propagate.

Grid Density: The resolution of the wireframe grid.

Line Width: The thickness of the wireframe lines.

Number of Wave Layers: Adds complexity by combining multiple sine wave components.

Line Color Hue: Shifts the primary color of the wireframe lines.

Fog Density: Controls the atmospheric fog effect.

Physics-like Effects:

Wind Direction & Force: Simulates a directional drift of the wave field.

Amplitude Decay: Waves appear to lose height as they recede into the distance.

Choppiness: Adds subtle, randomized turbulence to the wave surface.

Crest Sharpness: Distorts wave peaks for a more realistic, pointed appearance.

Interactive Wireframe Boat: A small boat floats on the waves, dynamically adjusting its vertical position to the wave height at its location.

Adjustable Graph Bottom Depth: Control the "floor" of the ocean, which also influences wave height based on the amplitude decay.

Compact UI with Tooltips: Sliders are neatly arranged at the bottom of the screen, and hovering over each provides a detailed explanation.

Full-Screen Display: The wave simulation takes up the entire browser window for an immersive experience.

Technologies Used
HTML5: Structure of the web page.

CSS3 (Tailwind CSS): Styling and responsive layout.

JavaScript: Core logic for the simulation and UI interaction.

Three.js (r128): Powerful 3D JavaScript library for rendering the scene, waves, and boat.

Three.js OrbitControls: Enables intuitive camera navigation.

How to Run
Save the Code: Save the provided HTML code into a file named index.html.

Open in Browser: Open index.html in a modern web browser (e.g., Chrome, Firefox, Edge).

The simulation will start automatically, and the controls will appear at the bottom of the screen.

Controls
The interactive sliders at the bottom of the screen allow you to modify the wave and environment parameters in real-time. Hover over each slider for a detailed description.

Amplitude: Controls the vertical height of the waves.

Wavelength (px): Adjusts the horizontal distance between wave crests.

Speed: Modifies how quickly the wave patterns move.

Grid Density: Changes the number of lines in the wireframe grid (higher density = more detailed waves).

Line Width: Sets the visual thickness of the wireframe lines.

Number of Wave Layers: Increases the complexity of the wave pattern by adding more overlapping wave components.

Line Color Hue: Shifts the base color of the wireframe lines across the color spectrum.

Fog Density: Controls how quickly objects fade into the background fog.

Wind Direction (°): Sets the angle (0-360 degrees) from which the wind pushes the waves.

Wind Force: Determines the strength of the wind's influence on wave drift.

Amplitude Decay: Simulates energy loss; waves further away (in Z-depth) will have reduced amplitude.

Choppiness: Adds small, random vertical fluctuations for a more turbulent water surface.

Crest Sharpness: Distorts the wave shape to make crests more pointed and troughs flatter.

Boat X Pos: Adjusts the boat's horizontal (left/right) position.

Boat Z Pos: Adjusts the boat's depth (forward/backward) position.

Graph Bottom Depth: Moves the invisible "floor" of the simulation up or down, affecting wave height based on amplitude decay.

Camera Controls:

Click and Drag: Rotate the camera around the scene.

Scroll Wheel: Zoom in and out.

Future Enhancements
More Advanced Wave Physics: Implement Gerstner waves for more realistic wave profiles or even a basic particle-based fluid simulation.

Interaction: Add mouse interaction to create ripples or disturbances on the water surface.

Environment: Introduce dynamic skyboxes, sun/moon, or other atmospheric effects.

Multiple Boats/Objects: Allow adding more interactive elements to the scene.

Performance Optimization: For very high grid densities, explore advanced Three.js techniques or WebGL shaders for improved performance.
