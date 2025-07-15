# Interactive Educational Solar System

**Functional Demo** [Solarium](https://ravendano014.github.io/solarium/) 

**Spanish version:** [Solarium](https://ravendano014.github.io/solarium/solar.html)

This project is an interactive 3D simulation of our solar system, built using HTML, CSS, and JavaScript with the Three.js library. It provides an engaging and educational experience, allowing users to explore planets, moons, asteroids, and comets, view their properties, and control the simulation.

!(https://github.com/ravendano014/solarium/blob/main/Demo_Solarium.jpg)

## Features

- **3D Solar System Visualization:** Realistic models and textures for the Sun, planets, and major moons.
- **Interactive Camera Controls:**
    - **Mouse Rotation:** Click and drag to orbit around the solar system.
    - **Scroll Zoom:** Zoom in and out to get closer or further away from celestial bodies.
    - **Follow Mode:** Click on any planet or moon to automatically follow its orbit. Press `ESC` to exit follow mode.
- **Dynamic Information Panel:** Click on a celestial body to display detailed information about its type, diameter, distance from the Sun, orbital period, rotation period, temperature, number of moons, composition, discovery, fun facts, and relevant missions.
- **Educational Mode:**
    - **Comparisons:** See how selected planets compare to Earth in terms of diameter, distance from the Sun, and orbital period.
    - **Fun Facts:** Discover interesting facts about various celestial bodies.
    - **Missions:** Learn about past and planned space missions to different parts of the solar system.
- **Simulation Controls:**
    - **Pause/Resume:** Stop and restart the simulation.
    - **Speed Adjustment:** Control the speed of the celestial bodies' orbits and rotations using a slider or preset buttons (Slow, Normal, Fast).
- **Toggle Visibility:** Show or hide orbits and celestial body names for a cleaner view.
- **Comprehensive Celestial Bodies:** Includes all eight planets, Earth's Moon, Mars' moons (Phobos, Deimos), Jupiter's Galilean moons (Io, Europa, Ganymede, Callisto), Saturn's major moons (Titan, Enceladus, Mimas, Rhea, Iapetus, Dione, Tethys), Uranus's moons (Miranda, Ariel, Umbriel, Titania, Oberon), Neptune's moons (Triton, Nereid), a simplified asteroid belt, and comets (Halley's Comet, Comet Hale-Bopp).
- **Axial Tilts and Retrograde Motion:** Planets and moons are rendered with their correct axial tilts and exhibit accurate retrograde motion where applicable.
- **Atmosphere Effects:** Realistic atmospheric scattering effects for planets with significant atmospheres (Venus, Earth, Uranus, Neptune, Titan).
- **Enhanced Starfield:** A detailed and visually appealing background of stars.

## Technologies Used

- **HTML5:** Structure of the web page.
- **CSS3:** Styling and layout of the interface elements.
- **JavaScript (ES6+):** Core logic and interactivity.
- **Three.js (r128):** 3D graphics rendering library for creating and animating the solar system.
- **OrbitControls.js:** Three.js extension for camera navigation.
- **CSS2DRenderer.js:** Three.js extension for rendering HTML labels in 3D space.

## How to Run

1. **Save the code:** Copy the entire `Solar.html` code into a file named `Solar.html`.
2. **Open in Browser:** Open the `Solar.html` file in your web browser.

The simulation will load automatically, and you can start exploring!

## Keyboard Controls

- **M**: Toggle visibility of the educational mode panel.
- **N**: Toggle visibility of celestial body names.
- **O**: Toggle visibility of orbital paths.
- **C**: Toggle visibility of the simulation controls panel.
- **H**: Toggle visibility of the help panel (this information).
- **P**: Pause/resume the simulation.
- **F**: Toggle between free camera mode and follow mode (follows the selected celestial body).
- **Click planet/moon**: Select a celestial body to view its information and/or follow it.
- **ESC**: Exit follow mode and deselect the current celestial body.
- **Mouse wheel**: Zoom in/out (in both free and follow modes).
- **Mouse click and drag**: Rotate the camera (in free mode).

## Acknowledgements

- **Three.js:** For the powerful 3D rendering capabilities.
- **NASA/JPL:** For providing high-quality planetary textures.
- **Wikipedia and other astronomical resources:** For detailed planet and moon data.
