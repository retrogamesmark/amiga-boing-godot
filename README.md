# amiga-boing-godot
Amiga Boing Ball Demo recreated in Godot (GDScript). The classic Amiga demo of the Boing ball is rendered entirely from bitplane data and Amiga-style colour hex codes, with palette cycling, bouncing physics, and real-time shadow effects, all coded from scratch.


## Update
  Creating a test Godot project file synced with GitHub before uploading the project files here.



## Features
- **Amiga-style Boing Ball**  
  Rendered from raw bitplanes and indexed colours (no pre-drawn textures).
- **Palette Cycling**  
  Dynamic palette updates simulate the Amiga hardware effect.
- **Physics-based Bounce**  
  Ball motion with configurable limits, gravity-like scrolling, and "boing" sound triggers.
- **Real-time Shadows**  
  Ball shadow fades with bounce height, layered correctly under the grid.
- **Sound Support**  
  Authentic "boing" effects with optional pitch/volume randomisation.
- **Optimized Rendering**  
  Uses precomputed index tables and image updates for efficient per-frame drawing.



## Project Files
- **ball.gd**  
  Ball rendering, palette updates, update bounce physics, and shadow handling.
- **ball_physics.gd**  
  Updates and returns the ball position and direction.
- **grid.gd**  
  Background grid lines (Amiga-style floor effect).
- **image_utils.gd**  
  Bitplane image conversion and hi-res texture helpers.
- **palette_cycler.gd**  
  Handles palette cycling per frame.
- **palette_utils.gd**  
  Colour conversions and safe palette editing.
- **sound_music.gd**  
  Sound playback and randomisation.
- **boing_theme.gd**  
  Theme/template for colours and settings.
- **active_theme.gd**  
  Active theme manager.
- **global_settings.gd**  
  Central config (physics, colours, options).
- **ball_data.gd**  
  Bitplane and colour data (Amiga palette).



  ## Screenshots
- **AMIGA Theme**  
  Screenshot of the demo using the AMIGA theme.


<img width="1272" height="795" alt="amiga-boing-amiga-theme-screenshot" src="https://github.com/user-attachments/assets/04d94611-021a-40d9-82d5-5581c47fc322" />


  
- **BLUE Theme**  
  Screenshot of the demo using the BLUE theme.


<img width="1272" height="795" alt="amiga-boing-blue-theme-screenshot" src="https://github.com/user-attachments/assets/9c09fb08-3b05-448e-bb6c-1eb29115a6c4" />



