# NYU CSCI-UA 480 — Computer Graphics (Selected Projects)

This repository showcases selected assignments from **NYU CSCI-UA 480: Computer Graphics**. 
The focus is on solid, correct implementations of core graphics techniques and clear explanations of the rendering pipeline, 
rather than oversized frameworks. Projects demonstrate competence with shaders, transformations, lighting, mesh processing, and real-time rendering patterns.

**Tech Stack:** C/C++ · GLSL

## Project Highlights
- **`Extra Credit`** — Experimental or extended graphics features, Shader experiments, and OpenGL.
- **`HW2`** — GLSL shaders, Lighting & shading, Transforms & camera, and OpenGL/GLFW/GLEW.
- **`HW3`** — OBJ mesh loading, GLSL shaders, Lighting models (Phong/Gouraud), Rasterization, and Transforms & camera.
- **`HW5`** — GLSL shaders, Lighting & shading, Advanced camera controls, and OpenGL/GLFW/GLEW.

## What to Look For (Reviewer Notes)

- **Shader correctness & readability:** clear separation of vertex vs. fragment responsibilities; numerically stable lighting calculations.

- **Transformation pipeline discipline:** consistent model→view→projection application; right-handed/left-handed conventions called out in comments.

- **Data structures & performance:** appropriate buffer usage (VBO/VAO/EBO), minimal state churn, and O(n) vs O(n log n) considerations for mesh ops.

- **Robustness:** handling of degenerate geometry, normal recalculation, and parameter validation.

- **Documentation:** in-file comments explaining GPU/CPU responsibilities and the rationale behind algorithmic choices.
