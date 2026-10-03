<div align="center">

# 🧸 TOYBOX.EXE

### **THE TOYS ARE MOVING. DON'T LOOK AWAY.**

[![GitHub Stars](https://img.shields.io/github/stars/Punitpritam788/toybox-exe?style=for-the-badge\&logo=github\&label=STARS)](https://github.com/Punitpritam788/toybox-exe)
[![GitHub Forks](https://img.shields.io/github/forks/Punitpritam788/toybox-exe?style=for-the-badge\&logo=github\&label=FORKS)](https://github.com/Punitpritam788/toybox-exe/network/members)
[![GitHub Issues](https://img.shields.io/github/issues/Punitpritam788/toybox-exe?style=for-the-badge\&logo=github\&label=ISSUES)](https://github.com/Punitpritam788/toybox-exe/issues)
[![GitHub License](https://img.shields.io/github/license/Punitpritam788/toybox-exe?style=for-the-badge\&logo=github\&label=LICENSE)](https://github.com/Punitpritam788/toybox-exe)
[![HTML5](https://img.shields.io/badge/HTML5-Game-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-Game-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Three.js](https://img.shields.io/badge/Three.js-3D-black?style=for-the-badge\&logo=three.js)](https://threejs.org/)

<br>

> **A corrupted game. A locked room. Five power cells. Three shapes.**
>
> **And something that moves when you stop looking.**

<br>

### 🎮 [PLAY THE GAME](#-getting-started) · 👁️ [EXPLORE THE CODE](https://github.com/Punitpritam788/toybox-exe)

</div>

---

## 📼 The Story

**1993. 3:07 AM.**

You are the night QA tester for a cancelled CD-ROM horror game.

The machine boots.

The save file is corrupted.

The player is missing.

The monitor says your status is **NOT FOUND**.

Then the game asks for your name.

You type it.

And suddenly, there is no desk anymore.

There is only the **Shape Room**.

A dark room filled with cubes, spheres, cones, blood stains and strange messages written across the walls. Somewhere inside the room are five power cells keeping the level together.

But there is a problem.

Every time you take one, the game loads something new.

The toys.

They were supposed to be harmless.

They aren't.

The dead developer's daughter, **Lily**, has been coded into the toys, and something inside the level wants a new **PLAYER 1**.

Find the cells.

Read the pages.

Remember the shape order.

Open `EXIT.EXE`.

And whatever you do...

**don't let the game finish compiling you.**

---

# 🧸 What Is TOYBOX.EXE?

**TOYBOX.EXE** is a single-file, browser-based 3D horror puzzle game built with **HTML, CSS, JavaScript, Three.js and the Web Audio API**.

The game combines:

* 🧩 Randomized shape-based environments
* 🔋 Resource-based exploration
* 👁️ Sight-sensitive enemy behavior
* 🧸 Procedurally assembled toy monsters
* 📄 Environmental storytelling
* 🔺 Shape-based puzzle solving
* 🎵 Procedural horror audio
* 📺 CRT and VHS-inspired visual effects
* 🩸 Dynamic blood and fear effects
* 👻 Random horror events
* 😱 Full-screen jumpscares
* 🚪 A timed escape sequence
* 💾 Multiple endings and performance-based ranking

The entire game logic is contained inside one HTML file rather than relying on a traditional game-engine project structure.

---

# 👁️ Core Gameplay

## 🔋 Collect 5 Power Cells

Explore the Shape Room and find **five power cells**.

Each collected cell:

* Recharges your flashlight
* Updates the HUD
* Plays an audio cue
* Triggers visual distortion
* Can introduce another toy into the room

Your flashlight is not infinite.

**When the light gets weaker, the room gets much harder to read.**

---

## 📄 Find the Pages

There are **four story pages** hidden throughout the room.

They contain:

* Developer logs
* Lily's story
* Information about the power cells
* The shape puzzle solution
* The identity of the mysterious QA tester
* Clues about what the player actually is

The pages are not just collectibles.

They gradually reveal what is happening inside the game.

---

# 🔺 Solve Lily's Shape Puzzle

At the eastern side of the room are three pedestals.

Each pedestal contains one shape:

```text
■  Cube
●  Sphere
▲  Cone
```

The correct order is randomized every time the game starts.

A strange board reveals Lily's order.

Interact with each pedestal using **E** and cycle the shapes until all three match the required combination.

When the combination is correct:

```text
✔ SHAPES SOLVED
```

The exit sequence becomes available.

---

# 🧸 The Toys

The enemies are not imported character models.

They are **procedurally constructed from basic 3D shapes**.

Each toy can receive randomized:

* Body type
* Head
* Eyes
* Teeth
* Hat/accessory
* Size
* Rotation
* Movement speed
* Wandering behavior
* Animation phase

This means the toys can look slightly different from one another while still being generated entirely in code.

---

# 👁️ Don't Look Away

The toys use a lightweight visibility-based behavior system.

They can:

```text
Wander
   ↓
Detect player
   ↓
Move toward player
   ↓
Slow down when watched
   ↓
Move faster when unseen
   ↓
Occasionally lunge forward
```

Looking directly at a toy can slow its movement.

Looking away gives it more freedom to approach.

Some toys can also make sudden forward jumps when they are outside your view.

So the question isn't simply:

> **"Where is the enemy?"**

It is:

> **"What happens when I stop watching it?"**

---

# 🎵 Sound Is Part of the Gameplay

TOYBOX.EXE does not depend on a collection of external audio files for its horror atmosphere.

The game generates audio dynamically through the **Web Audio API**.

The sound system includes:

```text
plink()     → strange ambient notes
beat()      → heartbeat
blip()      → interaction sounds
screech()   → jumpscare sound
whisper()   → distorted whisper/noise
stinger()   → horror sting
laugh()     → distorted laugh
tap()       → movement/footstep-style sounds
siren()     → escape sequence
```

The result is a constantly changing electronic horror soundscape rather than a conventional soundtrack.

---

# 🎧 Use Headphones

The game uses directional and layered audio effects to increase tension.

You may hear:

* Toys moving nearby
* Strange electronic tones
* Heartbeats when danger rises
* Whisper-like noise
* Sudden stingers
* Jumpscare sounds
* The escape siren

**Headphones are recommended.**

---

# 📺 CRT Horror Visuals

The entire game is processed through a deliberately corrupted display aesthetic.

The visual system combines:

* Green monochrome grading
* Scanlines
* Film/CRT grain
* Vignette
* Blood-tinted edges
* Screen shake
* FOV distortion
* Glitch transformations
* Random color corruption
* Fog changes
* Flickering flashlight

The game intentionally renders at a reduced internal resolution and scales it up with pixelated rendering to preserve the retro low-resolution look.

---

# 🩸 Fear System

The game tracks a dynamic **fear** value.

Fear can increase through:

* Losing lives
* Getting close to toys
* Losing flashlight charge
* Discovering more story pages

Fear then influences other systems such as:

```text
Fear
 ├── Ambient lighting
 ├── Background noise
 ├── Heartbeat intensity
 ├── Screen movement
 ├── Blood effect
 └── Enemy behavior
```

So the horror atmosphere is not completely static.

The closer you get to danger, the more aggressively the game can distort your experience.

---

# 🎶 The Decoy

Press:

```text
Q
```

to throw a small music-box decoy.

The idea is simple:

```text
Throw the decoy
      ↓
Toys hear it
      ↓
Toys move toward the sound
      ↓
You move in the opposite direction
      ↓
RUN
```

You have a limited number of decoys, so use them strategically.

Not every problem should be solved by running.

---

# 😈 Not Every Power Cell Is Real

The room contains fake power-cell objects.

Approaching one can trigger:

```text
"It was a toy."
```

The fake can disappear, spawn a fast enemy, trigger a horror sting, and activate a jumpscare.

So even something that appears helpful can be a trap.

---

# 🚪 EXIT.EXE

The exit is not immediately available.

You need to:

```text
5 Power Cells
       +
Shape Puzzle Solved
       ↓
Reach the Door
       ↓
EXIT.EXE COMPILING
       ↓
SURVIVE THE PANIC PHASE
       ↓
Door Opens
       ↓
ESCAPE
```

Once the compilation begins, the game enters a much more dangerous state.

More toys appear.

The toys become more aggressive.

The screen becomes more corrupted.

A siren starts.

The player has to hold out until the exit finishes opening.

---

# 💀 Lives & Endings

You begin with:

```text
♥ ♥ ♥
```

Getting caught can cost a life.

Lose all your lives and the save file is overwritten.

Survive the final escape and the game reveals another layer of the story.

The victory screen also calculates a simple performance rank based on:

* Remaining lives
* Number of pages discovered
* Completion time

Possible ranks include:

```text
S
A
B
```

The ending itself suggests that escaping the room may not mean escaping the game.

---

# 🎮 Controls

| Input        | Action                  |
| ------------ | ----------------------- |
| `W A S D`    | Move                    |
| `Arrow Keys` | Move                    |
| `Mouse`      | Look around             |
| `Shift`      | Run                     |
| `E`          | Interact / Read / Close |
| `Q`          | Throw decoy music box   |
| Mouse click  | Start / Resume          |

The game uses browser pointer-lock controls for first-person camera movement.

---

# 🖥️ Technical Overview

## Built With

| Technology        | Purpose                           |
| ----------------- | --------------------------------- |
| **HTML5**         | Game container and interface      |
| **CSS3**          | CRT, blood, glitch and UI effects |
| **JavaScript**    | Core game logic                   |
| **Three.js**      | 3D rendering                      |
| **Web Audio API** | Procedural horror sound           |
| **Canvas 2D**     | Textures and jumpscare graphics   |

Three.js is loaded directly through a CDN and the game is rendered through a WebGL canvas.

---

# 🧠 Procedural Generation

The room is not completely hand-placed.

The code randomly generates:

* Object positions
* Object colors
* Object sizes
* Shape types
* Toy variations
* Toy movement parameters
* Power-cell locations
* Page locations
* Fake pickups
* Horror events
* Shape puzzle solution
* Ambient musical notes

A placement helper attempts to prevent important objects from spawning too close together, creating a different room layout between runs.

---

# 🏗️ Game Architecture

Although everything lives in one HTML file, the code can conceptually be divided into these systems:

```text
TOYBOX.EXE
│
├── Visual Layer
│   ├── CRT filter
│   ├── Scanlines
│   ├── Grain
│   ├── Blood
│   └── Glitches
│
├── World
│   ├── Floor
│   ├── Walls
│   ├── Ceiling
│   ├── Shapes
│   └── Decorations
│
├── Gameplay
│   ├── Player
│   ├── Flashlight
│   ├── Batteries
│   ├── Pages
│   ├── Puzzle
│   └── Exit
│
├── Enemies
│   ├── Procedural Toys
│   ├── Wandering
│   ├── Chasing
│   ├── Visibility
│   └── Decoy response
│
├── Horror
│   ├── Random events
│   ├── Fear system
│   ├── Jumpscares
│   └── Screen glitches
│
└── Audio
    ├── Ambient tones
    ├── Heartbeat
    ├── Footsteps
    ├── Whispers
    └── Escape siren
```

---

# ⚡ Performance Philosophy

The game is intentionally lightweight.

Rather than relying on detailed 3D assets and complex physics, the implementation uses:

* Primitive Three.js geometry
* Simple distance-based collision
* Lightweight enemy movement
* Procedural textures
* Procedural audio
* Reduced internal rendering resolution

This keeps the game compact while still creating a recognizable horror atmosphere.

---

# 📂 Project Structure

The core project can remain extremely simple:

```text
toybox-exe/
│
├── TOYBOX.EXE.html
└── README.md
```

The main game file contains the game's:

* HTML
* CSS
* JavaScript
* 3D world
* Enemy logic
* Audio logic
* Story
* UI
* Endings

---

# 🚀 Getting Started

## 1. Clone the repository

```bash
git clone https://github.com/Punitpritam788/toybox-exe.git
```

## 2. Open the game

Open:

```text
TOYBOX.EXE.html
```

in a modern desktop browser.

## 3. Enter the game

Click:

```text
ENTER THE GAME
```

Allow pointer lock and start exploring.

---

# 🌐 Running With GitHub Pages

Because the game is a client-side HTML project, it can be hosted as a static webpage.

A simple GitHub Pages deployment can use the HTML file as the main entry point.

For easiest deployment, rename the main file to:

```text
index.html
```

and enable **GitHub Pages** from the repository settings.

---

# 👻 Horror Design Principles

TOYBOX.EXE is designed around a few simple ideas:

### 01 — Uncertainty

You don't always know whether something is useful or dangerous.

### 02 — Visibility

Looking at enemies changes how they behave.

### 03 — Resource Pressure

Your flashlight and decoys are limited.

### 04 — Escalation

Progress makes the room more dangerous.

### 05 — Environmental Storytelling

The room itself contains pieces of the story.

### 06 — Unreliable Reality

Glitches, corrupted messages and fake objects make the game world difficult to trust.

---

# 🧩 Why Shapes?

The game's world deliberately uses basic geometric forms:

```text
Cube
Sphere
Cone
Cylinder
Torus
```

These simple shapes are treated like children's toys, but the corrupted CRT presentation turns them into something unsettling.

The result is a strange visual contrast:

> **Simple geometry + childhood toys + corrupted software + horror**

That combination forms the identity of the game.

---

# 📸 Screenshots

Add screenshots or GIFs here:

```text
/docs/screenshots/
├── title-screen.png
├── shape-room.png
├── toy-chase.png
├── puzzle.png
├── jumpscare.png
└── exit.exe.png
```

Suggested GitHub layout:

```markdown
## 📸 Screenshots

<p align="center">
  <img src="docs/screenshots/title-screen.png" width="48%">
  <img src="docs/screenshots/shape-room.png" width="48%">
</p>

<p align="center">
  <img src="docs/screenshots/toy-chase.png" width="48%">
  <img src="docs/screenshots/exit.exe.png" width="48%">
</p>
```

---

# 🎥 Gameplay Video

Add your gameplay trailer here:

```markdown
## 🎥 Gameplay

[▶️ Watch the Gameplay Trailer](YOUR_VIDEO_LINK)
```

---

# 🛠️ Future Ideas

Possible directions for future versions:

* [ ] More toy types
* [ ] More randomized rooms
* [ ] Additional puzzle variants
* [ ] More story pages
* [ ] Multiple enemy behaviors
* [ ] More endings
* [ ] Additional jumpscares
* [ ] Better environmental audio
* [ ] Mobile controls
* [ ] Save/load system
* [ ] More advanced lighting
* [ ] Expanded lore
* [ ] More CRT corruption effects

---

# ⚠️ Browser Notes

The game uses:

* WebGL
* Pointer Lock
* Web Audio
* JavaScript-generated graphics and sound

A modern browser is recommended.

Headphones are also recommended.

---

# 📜 License

Add your chosen license here.

For example:

```text
MIT License
```

or create a custom license for the project.

---

<div align="center">

## 🧸 THE TOYS ARE STILL HERE.

### **DON'T LOOK AWAY.**

<br>

**TOYBOX.EXE**

`PLAYER 1 NOT FOUND`

`NORA.SAV [CORRUPT]`

`EXIT.EXE COMPILING...`

</div>
