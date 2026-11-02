###

#### 1. General Vibe & Structure

- The whole thing should feel like an interactive story driven entirely by **scrolling your mouse wheel down**. Split it into 6 clear, easy-to-follow scenes (nothing too philosophical):
  1. **Opening Close-up**: When the page loads, the camera is parked super close to a funky 3D geometric shape. Give the mouse a little scroll, the camera pulls back, and boom—you finally see the whole object.
  2. **Breaking Apart**: The shape smoothly shatters into a bunch of smaller pieces just floating around in space. Classic 3D stuff.
  3. **Flying Through a Tunnel**: The camera flies forward straight through a tunnel, like you’re zooming through space or something.
  4. **Wobbly Water Sphere**: Center stage is a sphere whose surface ripples gently like water. Just a neat little visual to look at for a second.
  5. **Grid of Blocks**: A clean grid of tiny cubes or parts neatly lined up, undulating up and down like a gentle wave. Very satisfying, very chill.
  6. **Grand Finale**: All the little scattered bits snap back together into one big cool shape. Fade in a short closing message and a handy "Replay" button for anyone who wants to sit through it all over again.

     \\

#### 2. Camera & Scroll Controls

- **Driven 100% by page scroll**:
  - Scroll down: the camera glides forward, angles shift, and objects morph.
  - Scroll up: everything cleanly reverses in real time—no weird glitches, please.
  - Keep camera motion buttery smooth with some nice dampening so it doesn't give anyone motion sickness.

    \\

#### 3. Visuals & Lighting (Clean and Lightweight)

- Stick to a sleek dark background (dark gray or deep black), paired with whites, grays, and silver tones, maybe with a tiny pop of electric blue just to keep things from looking boring.
- Use standard out-of-the-box materials: simple reflections, standard highlights, maybe a subtle semi-transparent glass effect. Keep it looking crisp without piling on heavy custom shaders that make browsers choke.
- Just drop in two or three standard lights (a key light and some ambient light will do just fine) so the shapes have decent depth and contrast.

  \\

#### 4. Text & Micro-Interactions

- As the user scrolls into each scene, fade in a bold, minimalist chapter title (e.g., `01 MONOLITH`, `02 FRACTURE`, etc.)—just enough to look intentional.
- Mouse movement should trigger subtle parallax on the camera or shapes, just so the page feels alive and not completely frozen when the user stops scrolling.
- Clicking an object can trigger a tiny wobble or a brief highlight flash. Simple, but satisfying.

  \\

#### 5. Deliverables & Requirements

- Deliver ready-to-run code (a single self-contained HTML file or a dead-simple Vite setup using vanilla Three.js).
- Generate all shapes directly in code using standard geometries (cubes, toruses, spheres, etc.). Please do not rely on external `.gltf` links that will inevitably break or take ten years to load.
- Keep the code readable, well-commented, and running at an effortless 60 FPS without turning the user's computer into a space heater.
