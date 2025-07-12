# Three.js Journey

## Setup
Download [Node.js](https://nodejs.org/en/download/).
Run this followed commands:

``` bash
# Install dependencies (only the first time)
npm install

# Run the local server at localhost:8080
npm run dev

# Build for production in the dist/ directory
npm run build
```
📝 What I've Learned So Far
✅ 1. Scene
How to create a THREE.Scene() to hold all objects, lights, and cameras.

✅ 2. Camera
Setting up PerspectiveCamera to view the scene with correct field of view, aspect ratio, near and far clipping planes.

Positioning the camera to see objects properly.

✅ 3. Geometries
Creating basic geometries such as:

BoxGeometry

SphereGeometry

PlaneGeometry

Understanding vertices, faces, and how geometries are built.

✅ 4. Materials & Textures
Applying materials like MeshBasicMaterial and MeshStandardMaterial.

Loading textures to add realism, including:

Color (diffuse) maps

Normal maps

Roughness maps

Using the TextureLoader to import and apply them to meshes.

✅ 5. Mesh
Combining geometries and materials into meshes to display them in the scene.

✅ 6. 3D Text
Creating 3D text using TextGeometry.

Loading custom fonts with FontLoader and styling text with bevel, size, and height options.

✅ 7. Renderer
Setting up the WebGL renderer to render the scene and camera view to the browser canvas.

✅ 8. Controls

