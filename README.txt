TERMINAL TO COACH STATION - 3D splat viewer
===========================================

Open:  double-click index.html (Chrome, Edge or Firefox; needs WebGL 2).
       Keep every file in this folder together: index.html, meta.js, splats_NN.js.

Controls
  Replay           plays back the original walk; drag to look around while it plays
  Drag             look around
  W A S D / arrows move (Shift = faster), E / Q up and down, scroll = forward/back
  Touch            drag to look, pinch to move
  Overview         bird's-eye view with the roof cut away
  Yellow line      the route that was walked; chevrons point in the walking direction

Sharing online
  Upload this whole folder to any static web host (GitHub Pages, Netlify,
  Cloudflare Pages, an S3 bucket ...) and share the link to index.html.
  Phones automatically load a lighter version of the scene.

The splat file next to this folder (*_lite.ply) is the same scene as a standard
3D Gaussian splat PLY. It opens in SuperSplat (https://superspl.at/editor), Brush
and other splat viewers.
