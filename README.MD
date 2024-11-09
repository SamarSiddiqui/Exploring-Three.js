# Memory Joggers (Because Three.js Might Ghost You)

- Before we start, to actually be able to display anything with three.js, we need three things: **Scene**, **Camera** and **Renderer**, **so that we can render the scene with camera.**

- Create Scene: Set up a scene, camera (PerspectiveCamera), and renderer.
- Camera Attributes: Set field of view, aspect ratio, and clipping planes for visibility and performance.
- Renderer Setup: Define the render size (e.g., window dimensions) and add the <canvas> to HTML.
- Add Geometry: Create a cube with BoxGeometry, color it using MeshBasicMaterial, and apply it using Mesh.
- Render Loop: Implement a loop to render the scene.