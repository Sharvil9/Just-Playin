# 🎨 Interactive Particle Flow Field

> "Where particles dance like they're at a rave, but without the questionable life choices" 🕺💃

## 🎥 Watch the Magic

![Particle Flow Demo](Enhanced%20Interactive%20p5.js%20Particle%20Flow%20Field.gif)

## 🚀 What's This All About?

This is an interactive particle flow field visualization that makes your screen look like a digital lava lamp on steroids! Built with p5.js, it's a mesmerizing experience where particles flow, swirl, and dance based on your interactions.

## 🎮 Features That'll Make You Go "Ooooh!"

- **Interactive Flow Field**: Move your mouse and watch particles follow like they're your biggest fans
- **Customizable Parameters**: Like a DJ mixing board, but for particles
- **Smooth Animations**: So smooth, it makes butter jealous
- **Dark Mode**: Because we're not savages who burn retinas

## 🛠️ How to Use (It's Easier Than IKEA Instructions)

1. Clone this repo (or download and unzip if you're old school)
2. Open `index.html` in your favorite browser
3. Move your mouse around like you're conducting an orchestra
4. Play with the controls panel like a mad scientist

## 🎛️ Control Panel Options

The right-side panel lets you tweak everything like a particle DJ:

**Particles:**
*   **Count:** How many little fellas you want dancing.
*   **Base Color:** The starting point for particle color.
*   **Color Mode:**
    *   `Static`: All particles use the Base Color.
    *   `Speed-Based`: Faster particles shift towards one color (e.g., red), slower towards another (e.g., blue).
    *   `Age-Based`: Particle color changes over its lifespan.
*   **Max Speed:** How fast particles can normally travel.
*   **Lifespan:** How many frames a particle lives before respawning.

**Flow Field:**
*   **Field Type:**
    *   `Perlin Noise`: Organic, evolving, noisy flow.
    *   `Sine Wave`: Structured, wave-like horizontal flow.
*   **Noise Scale (Perlin Only):** Controls the 'zoom' level of the Perlin noise pattern.
*   **Evolution Speed (Perlin Only):** How quickly the noise pattern changes over time.
*   **Strength:** How strongly particles follow the flow field vectors.
*   **Noise Detail LoD (Perlin Only):** Level of detail in the noise calculation.
*   **Noise Falloff (Perlin Only):** How much influence higher levels of detail have.
*   **Show Flow Field:** Toggle visibility of the underlying vector field (useful for debugging).

**Appearance & Trails:**
*   **Background Color:** Set the canvas background color.
*   **Trail Style:** How particle trails are rendered (fading background, persistent lines, etc.).
*   **Trail Thickness:**
    *   `Static`: All trails have a fixed thickness.
    *   `Speed-Based`: Faster particles leave thicker trails.

**Interaction:**
*   **Right-Click & Hold:** Repels particles away from the cursor within the specified radius (shown by a red circle).
*   **Right-Click Repel Radius:** Controls the size of the repulsion area.
*   ***Left-Click & Hold (atleast for 5s):** Makes particles gather towards the cursor. Releasing the button *after holding for at least 5 seconds* causes all particles to burst outwards like fireworks!*

**Actions:**
*   **Reset Particles:** Resets all particles to random positions/velocities and clears trails.
*   **Toggle Fullscreen:** Enter/exit fullscreen mode (hides controls).

## 🧪 Technical Stuff (For the Nerds)

- Built with p5.js
- Pure HTML5 Canvas magic
- No external dependencies (except p5.js, but that's like saying water is a dependency for life)
- Responsive design that works on most screens (except maybe your grandma's Nokia)

## 🤝 Contributing

Feel free to:
- Fork it
- Make it better
- Submit a PR
- Or just stare at it for hours (we won't judge)

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details. Basically, do whatever you want with it, just don't blame us if your screen gets hypnotized.

## 🎉 Special Thanks

- p5.js for making this possible
- Coffee for keeping us awake
- The particles for being such good dancers

---
*Peak in if you can see the path taken by the particles.*

Made with ❤️ and a questionable amount of caffeine 