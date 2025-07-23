# Architecture Marvel: Padma Bridge

This project is a graphical simulation and visualization of the Padma Bridge, created using C++ and OpenGL. It showcases the architectural marvel of the Padma Bridge through animated graphics, representing various elements of the bridge and its surroundings such as vehicles, clouds, lamp posts, and environmental features.

## Authors

- Raufull Islam Rauf (ID: 21-45779-3)
- Sadia Afrose (ID: 21-45820-3)
- Rafayet Zaaman Abir (ID: 21-45791-3)
- MD. Naimul Islam (ID: 21-45801-3)

## Features

- **Padma Bridge Visualization:** Realistic graphical representation of the Padma Bridge.
- **Animated Environment:** Moving vehicles, clouds, and dynamic scenery using OpenGL.
- **Interactive Controls:** Keyboard input allows switching between different display modes.
- **Multiple Scenes:** Different visualizations and perspectives of the bridge and its surroundings.
- **Customizable Elements:** Colors, positions, and shapes are rendered using primitive OpenGL functions.

## Getting Started

### Prerequisites

- C++ Compiler (e.g., GCC, MinGW, Visual Studio)
- OpenGL Utility Toolkit (GLUT)
- Windows OS (code includes `<windows.h>`, but can be adapted for other platforms with minor changes)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sadi-ii/Architecture-Marvel--Padma-Bridge.git
   ```
2. Ensure your system has OpenGL and GLUT installed.
3. Open the project in your preferred C++ IDE or build using the command line.

### Building & Running

1. Compile the source code (`main.cpp`):
   - Example with g++:
     ```bash
     g++ -o PadmaBridge "Architecture Marvel- Padma Bridge/main.cpp" -lglut -lGLU -lGL
     ```
2. Run the executable:
   ```bash
   ./PadmaBridge
   ```

### Controls

- **Arrow Keys:** Use the UP and DOWN arrow keys to switch between different display modes.
- The window will open with a 720x720 resolution, displaying animated scenes of the Padma Bridge.

## Project Structure

- `main.cpp`: Core source file containing all logic for rendering and animation.
- All rendering is done procedurally using OpenGL primitives and custom animation logic.

## Example Screenshots

*(Add screenshots of the running simulation here)*

## License

*(No license specified. Add your preferred license if needed.)*

## Acknowledgements

- Built for educational purposes to demonstrate OpenGL graphics and pay tribute to the Padma Bridge as an engineering achievement.

---

**For any issues or feature requests, please open an issue in the repository.**
