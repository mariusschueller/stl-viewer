# STL Viewer with Three.js

Based on https://tonybox.net/posts/simple-stl-viewer/

## Installation

### 1. Initalize Submodules

This uses three.js, which is linked as a submodule.

```
  git submodule init
  git submodule update
```

### 2. Run a web server

You can run any web server for this.  It won't work locally, since it uses ajax to download the STL file.

You can use python's built in HTTP server, or any other HTTP server.

```
  python3 -m http.server
```
