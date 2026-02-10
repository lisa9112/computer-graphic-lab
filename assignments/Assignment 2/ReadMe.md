Project Description

This project is a C++ OpenGL (3.3 Core Profile) application developed using GLFW and GLAD.
The program renders two cyan-colored obtuse triangles positioned at two distant corners of the screen on an orange background.

The application also demonstrates basic OpenGL concepts such as shader programming, vertex buffers, vertex array objects, and keyboard input handling.
Assignment Requirements

The following requirements are implemented in this project:

1. Draw two cyan colored obtuse triangles

2. Place the triangles at two distant corners of the screen

3. Use an orange background

4. Set the window title to the full name

5. Close the window by pressing the initial letter of the name

6. Use modern OpenGL (version 3.3 Core Profile)
Output Description

Background Color: Orange

Triangle Color: Cyan

Number of Triangles: 2

Triangle Type: Obtuse

Rendering Mode: GL_TRIANGLES


Technologies Used

.Programming Language: C++

.Graphics API: OpenGL 3.3 (Core Profile)

.Libraries:

    .GLFW – Window creation and input handling

    .GLAD – OpenGL function loade
key:L-Close the application window


Project Files

1.main.cpp – Contains:

2.OpenGL initialization

3.Shader compilation and linking

4.VAO and VBO configuration

5.Rendering loop

6.Keyboard input processing

7.README.md – Project documentation


Prerequisites

  OpenGL 3.3 compatible GPU

  GLFW installed

  GLAD properly configured

Technical Details

  Vertex Shader: Processes vertex positions

  Fragment Shader: Outputs a fixed cyan color

  Total Vertices: 6

  Buffers Used: VAO and VBO

  Viewport: 
  Automatically updates on window resize

Conclusion

This project demonstrates the basic workflow of modern OpenGL, including shader usage, vertex buffering, and rendering multiple shapes. It successfully fulfills all the requirements of the given assignment and serves as a foundation for further graphics programming tasks.
