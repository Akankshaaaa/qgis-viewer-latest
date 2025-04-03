# 3D Viewer 

An interactive 3D model of the site created using 3Dfy and visualised using the QGIS2threejs plugin.

## Live Demo
Visit the live demo at: [https://akankshaaaa.github.io/qgis-viewer/](https://akankshaaaa.github.io/qgis-viewer-latest/)

## Scene Controls

### Desktop Users
- **Rotate**: Left mouse button + Move
- **Zoom**: Mouse Wheel scroll
- **Pan**: Right mouse button + Move

### Touch Device Users
- **Rotate**: One finger drag
- **Zoom**: Two finger pinch in/out
- **Pan**: Two finger drag

## Additional Features

### Navigation Tools
- A navigation compass is available in the top-right corner to help orient yourself in the scene
- Click and drag the compass at the bottom left of the screen to rotate the view
- Click on the compass poles (N,S,E,W) to snap to that view

### Scene Information
- Click on objects in the scene to view their attributes
- Coordinates of clicked points will be displayed
- Layer information is available for selected features

### Measurement Tool
1. Click the "Measure distance" button in the popup panel
2. Click on your starting point in the scene
3. Click on subsequent points to measure distances between them
4. The tool will display:
   - **Total Distance**: The cumulative length of all segments
   - **Horizontal Distance**: The planar distance ignoring elevation
   - **Vertical Distance**: The elevation difference between points
5. Click the right mouse button or press ESC to finish measuring

### Camera Controls
- **Reset View**: Press 'Shift + R' to reset the camera to its initial position
- **Save View**: Press 'Shift + S' to save the current view as an image

### Keyboard Shortcuts
- **Arrow Keys**: Move horizontally
- **Shift + Arrow Keys**: Orbit
- **Ctrl + Arrow Keys**: Rotate
- **Shift + Ctrl + Up/Down**: Zoom In/Out
- **L**: Toggle label visibility
- **R**: Start/Stop orbit animation
- **W**: Toggle wireframe mode

---
