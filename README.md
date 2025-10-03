# amiga-boing-godot
Amiga Boing Ball Demo recreated in Godot (GDScript). The classic Amiga demo of the Boing ball is rendered entirely from bitplane data and Amiga-style color hex codes, with palette cycling, bouncing physics, and real-time shadow effects, all coded from scratch.

## Features
- **Amiga-style Boing Ball**  
  Rendered from raw bitplanes + indexed colors (no pre-drawn textures).
- **Palette Cycling**  
  Dynamic palette updates simulate the Amiga hardware effect.
- **Physics-based Bounce**  
  Ball motion with configurable limits, gravity-like scrolling, and "boing" sound triggers.
- **Real-time Shadows**  
  Ball shadow fades with bounce height, always layered correctly under the grid.
- **Sound Support**  
  Authentic "boing" effects with optional pitch/volume randomization.
- **Optimized Rendering**  
  Uses precomputed index tables + image updates for efficient per-frame drawing.



## Project Files
- **ball.gd**  
  Ball rendering, palette updates, update bounce physics, and shadow handling.
- **ball_physics.gd**  
  Updates and returns the ball position, movement direction.
- **grid.gd**  
  Background grid lines (Amiga-style floor effect).
- **image_utils.gd**  
  Bitplane → image conversion + hi-res texture helpers.
- **palette_cycler.gd**  
  Handles palette cycling per frame.
- **palette_utils.gd**  
  Color conversions + safe palette editing.
- **sound_music.gd / sound_utils.gd**  
  Sound playback and randomization.
- **boing_theme.gd**  
  Theme/template for colors and settings.
- **active_theme.gd**  
  Active theme manager.
- **global_settings.gd**  
  Central config (physics, colors, options).
- **ball_data.gd**  
  Bitplane + color data (Amiga palette).
