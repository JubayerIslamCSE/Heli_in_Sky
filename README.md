# Heli in Sky  🚁

A 3D Computer Graphics project built using C++ and OpenGL/GLUT that simulates a helicopter flying through a dynamic sky environment. This project showcases 3D modeling, scene rendering, and advanced lighting techniques.

---

## ✨ Features

* **3D Helicopter Model:** Detailed helicopter structure rendered using geometric primitives and custom transformations.
* **Dynamic Lighting:** Realistic illumination system featuring ambient, diffuse, and specular components (configured via `lighting.cpp`).
* **Environment Scene:** A skyward environment (`scene.cpp`) providing context and a sense of scale for the helicopter flight.
* **Interactive Controls:** (Optional - update this based on your controls) Keyboard/mouse inputs to control the helicopter's movement or adjust camera perspectives.

---

## 📁 Repository Structure

* `main.cpp` - The entry point of the application; handles the main rendering loop and window initialization.
* `helicopter.cpp` & `helicopter.h` - Contains the logic and structure for rendering the 3D helicopter.
* `lighting.cpp` & `lighting.h` - Manages light sources, materials, and shading effects.
* `scene.cpp` & `scene.h` - Controls the environment, background elements, and overall sky scene setup.

---

## 🚀 Getting Started

### Prerequisites

To compile and run this project, you need a C++ compiler and the OpenGL/GLUT development libraries installed on your system.

#### For Ubuntu/Linux:
```bash
sudo apt-get update
sudo apt-get install freeglut3-dev mesa-common-dev libglu1-mesa-dev
