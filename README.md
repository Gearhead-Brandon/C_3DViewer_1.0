# 3DViewer v1.0

## Project Description
**3DViewer v1.0** is a **C** program designed for visualizing 3D wireframe models. It allows loading **.obj** files, performing affine transformations, and customizing display parameters.

## Key Features
- **Load models** from `.obj` files (support for vertices and faces).
- **Model transformations**:
  - Translation along **X, Y, Z** axes.
  - Rotation around **X, Y, Z** axes.
  - Scaling of the model.
- **Graphical User Interface (GUI)**:
  - File selection button and filename display.
  - Visualization area for the 3D wireframe model.
  - Controls for transformations (buttons, input fields).
  - Model information (filename, number of vertices and edges).
- **Performance**:
  - Proper handling of models with **up to 1,000,000 vertices** without freezing (>0.5 sec).

## Bonus Features
- **Visualization settings**:
  - Selection of projection type (**parallel, central**).
  - Customization of edge style, color, and thickness.
  - Vertex display customization (shape, size, color).
  - Background color selection.
  - **Settings persistence** between program restarts.
- **Recording & Export**:
  - Save rendered images as **BMP, JPEG**.
  - Record **GIF animations** (640x480, 10fps, 5s).

## Technical Details
- **Language**: C11.
- **Compiler**: GCC.
- **GUI Libraries**: GTK+, Qt, or other compatible C libraries.
- **Build System**: Makefile with standard targets (`all`, `install`, `uninstall`, `clean`, `tests`, etc.).
- **Coding Style**: Google C Style Guide.
- **Unit Testing**: Full coverage for model loading and affine transformations.
