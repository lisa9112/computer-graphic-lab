# Name: Sadia Akter Liza
# Id: 0432320005101110
# OpenGL Dual-Shader Star Project

This project is a C++ application using **OpenGL 3.3** that renders a "Star" shape (two overlapping triangles). It demonstrates the management of multiple **Vertex Array Objects (VAOs)** and switching between different **Shader Programs** during a single render cycle.

---

## 🛠️ Tech Stack
* **Language:** C++
* **Graphics API:** OpenGL 3.3 (Core Profile)
* **Window Management:** GLFW
* **Function Loading:** GLAD

---

## 🎨 Key Features
* **Dual VAO/VBO Setup:** Each triangle has its own vertex data and buffer management.
* **Multiple Shader Programs:** The code links two separate shader programs (`shaderProgramBlue` and `shaderProgramGreen`) to demonstrate shader switching.
* **Custom Background:** Uses a bright **Yellow** clear color (`1.0, 1.0, 0.0`) for the background.
* **Responsive Viewport:** Includes a callback function to adjust the rendering area when the window is resized.

---

## 📂 File Structure
- `main.cpp`: Contains the shader source code, vertex data, and the main render loop.
- `glad.c / glad.h`: OpenGL function loader.
- `glfw3.h`: Library for window and input handling.

---

## 🚀 Build & Run
1. **Setup:** Ensure you have the GLFW and GLAD libraries linked in your development environment.
2. **Compile (GCC Example):**
   ```bash
   g++ main.cpp glad.c -lglfw -lGL -lX11 -lpthread -lXrandr -lXi -ldl -o StarProject
---

## ⌨️ Controls

| Action | Key |
| :--- | :--- |
| **Close Window** | Press **L** |
| **Resize** | Drag window edges to scale the viewport |

---

## 💡 Important Note

Currently, both `fragmentShader1Source` and `fragmentShader2Source` are set to output the same **Cyan** color: `vec4(0.0f, 1.0f, 1.0f, 1.0f)`.

To see the "Blue" and "Green" difference as intended by the variable names in the code, you can manually modify the `FragColor` values in the source strings:

* **For Blue:** Change `fragmentShader1Source` to `vec4(0.0f, 0.0f, 1.0f, 1.0f);`
* **For Green:** Change `fragmentShader2Source` to `vec4(0.0f, 1.0f, 0.0f, 1.0f);`

---
