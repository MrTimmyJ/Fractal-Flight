# Fractal-Flight
Gamedev.js Jam 2025: Balance

[Play now on itch.io](https://sourcecodesorcerer.itch.io/fractal-flight)

Author: Timothy Johnson <br>
Date: April 13, 2025 to April 26, 2025

Float through a vibrant, generative sky of fractal clouds and balance your glider through a neon dreamworld.
Explore a hypnotic blend of art and motion where every sky is uniquely formed.

## Overview

&nbsp;&nbsp;&nbsp;&nbsp;Fractal Flight is a minimalist flight experience created for the Gamedev.js Jam 2025 under the theme Balance.
You pilot a paraglider across a procedurally generated fractal sky, balancing your movement through shifting psychedelic clouds above a glowing neon cityscape.

🧩 Features

    🪂 Simple paraglider physics with relaxing controls

    🌈 Generative fractal skies—different every time you play

    🏙️ Futuristic neon city as a scrolling background

    🖌️ Psychedelic visuals and color transitions

    🎮 Lightweight and web-based—just click to play

🎮 Gameplay
Use the arrow keys or WASD to gently glide left, right, up, and down. The goal is to maintain your flight path through visually chaotic skies—don’t get overwhelmed by the beauty!

| Tile Type  | Effect                                   |
| ---------- | ---------------------------------------- |
| 🟩 Healthy | Heals health or restores food            |
| 🟫 Neutral | No benefit or penalty — just wasted time |
| 🟥 Trap    | Harms or kills you instantly             |

Goal: Survive the dungeon and reach the end before your health or food runs out.
Move with care — you won't know the tile type until you step on it!

### Controls:

| Key   | Action      |
| ----- | ----------- |
| ↑ / W | Glide Up    |
| ↓ / S | Glide Down  |
| ← / A | Turn Left   |
| → / D | Turn Right  |
| ESC   | Quit        |

📁 Code Structure

. <br>
├── index.html &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Entry point <br>
├── style.css &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Basic styling <br>
├── main.js &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Core game logic (glider, sky, animation) <br>
├── /shaders/ &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Shader files for fractal visuals <br>
└── /assets/ &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Cityscape, glider model, etc. <br>


⚙️ How It Works

    Glider Mechanics: A simple physics loop mimics gliding through the air using Three.js vector math.

    Fractal Sky: Procedurally rendered with fragment shaders or generated noise to build complex skies.

    City Background: A parallax scrolling image and shapes add depth beneath the clouds.

    Color Shifts: The sky colors pulse and flow using time-based hue shifts.
    
🖼️ Screenshots / Visuals

![tileddungeon_banner](https://github.com/user-attachments/assets/a917df8a-7dde-4533-8437-6e1dafae908f)

🧰 Technologies Used

    🌐 JavaScript

    🎨 Three.js (WebGL)

    🧪 GLSL shaders (for fractal and color effects)

    🖥️ HTML/CSS

🚀 Getting Started

    To run the game:

    1. Clone or download the repo:

        git clone https://github.com/yourusername/fractal-flight.git
        cd fractal-flight

    2. Open index.html in a browser.

        No build tools needed. Just launch it!

🌱 Planned Features

    🗺️ Fog of war mechanic (hidden tiles)

    ⛏️ Equipment and item pickups

    🐍 Enemy tiles with turn-based combat

    💬 NPC events or lore tiles

    📜 Indication of what the surrounding tiles might be

🪪 License

This open-source project is available under the [MIT License](https://opensource.org/license/mit).

