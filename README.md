# 🚆 Metro Rail Simulation (C++ & OpenGL GLUT)

A complete, real-time Metro Rail Simulation developed using **C++ and OpenGL (GLUT)**.

This project was built as a **Final Year Computer Graphics Project** and demonstrates classic raster graphics algorithms, 2D transformations, animation using timers, and a fully implemented state machine for realistic metro behavior.

---

# 📌 Project Features

- 🚄 Metro train with multiple coaches  
- 🚉 Metro station platform  
- 🏙️ Multiple background buildings  
- ☀️ Sun / 🌙 Moon (Day/Night mode)  
- ☁️ Moving clouds  
- 🚦 Working signal system (Red / Green)  
- 👥 Animated passengers  
- 🔁 Infinite simulation loop  
- 🎮 Keyboard controls  

---

# 🧠 Algorithms Implemented

This project strictly implements the following Computer Graphics algorithms manually (not using built-in OpenGL primitives):

### 1️⃣ DDA Line Algorithm
Used for:
- Station text rendering
- Wheel spokes
- Some outlines

### 2️⃣ Bresenham Line Algorithm
Used for:
- Railway tracks
- Platform edges
- Building borders
- Object outlines

### 3️⃣ Midpoint Circle Algorithm
Used for:
- Train wheels
- Signal lights
- Sun / Moon
- Passenger heads

---

# 🔄 Transformations Used

### ✅ Translation
- Train movement
- Passenger walking
- Cloud animation

### ✅ Rotation
- Wheel rotation
- Passenger leg animation

### ✅ Scaling
- Buildings
- Clouds
- Passengers
- Scene objects

---

# 🚦 Train State Machine (Core Logic)

The metro follows a complete finite state machine:

1. Train starts moving
2. Train arrives at station
3. Train stops
4. Signal turns RED
5. Train doors open
6. Passengers walk toward door
7. Passengers disappear after boarding
8. Train doors close
9. Signal turns GREEN
10. Train starts moving again
11. Process repeats infinitely

This ensures structured and realistic train behavior.

---

# 👥 Passenger System

- Minimum 2 passengers
- Realistic walking animation
- Leg movement simulation
- Passengers disappear after entering train
- New passengers spawn every cycle

---

# 🎮 Controls

| Key | Action |
|------|--------|
| **D** | Switch to Day Mode |
| **N** | Switch to Night Mode |
| **ESC** | Exit Program |

---

# 🖥️ Screenshots

> Add your screenshots inside an `images/` folder.

Example:

```markdown
![Day Mode](images/day_mode.png)
![Night Mode](images/night_mode.png)
```

---

# ⚙️ Technical Specifications

- Language: **C++**
- Graphics Library: **OpenGL (GLUT / FreeGLUT)**
- Animation Method: `glutTimerFunc()`
- Rendering Mode: 2D Orthographic Projection
- Structure: Single-file implementation
- Compatible with: **CodeBlocks + GLUT**

---

# 📂 Project Structure

```
Metro-Rail-Simulation/
│
├── metro_simulation.cpp
├── README.md
└── images/
    ├── day_mode.png
    └── night_mode.png
```

---

# 🛠️ How to Compile & Run (CodeBlocks)

## Step 1: Setup OpenGL + GLUT

Make sure you have:
- OpenGL installed
- FreeGLUT or GLUT properly configured
- Required DLL files in system or project folder

## Step 2: Link Libraries

Go to:

```
Project → Build Options → Linker Settings
```

Add:

```
opengl32
glu32
freeglut
```

(or `glut32` depending on your configuration)

## Step 3: Build & Run

Click **Build and Run**

---

# 📸 How to Add Screenshots to GitHub

### Step 1
Create a folder named:

```
images
```

### Step 2
Upload screenshots inside that folder:
- `day_mode.png`
- `night_mode.png`

### Step 3
Add this inside README:

```markdown
![Day Mode](images/day_mode.png)
![Night Mode](images/night_mode.png)
```

GitHub will automatically display the images.

---

# 🎓 Academic Value

This project demonstrates:

- Classic raster graphics algorithms
- State machine modeling
- Real-time animation
- 2D transformations
- Scene composition
- Event-driven programming
- Structured graphics pipeline

Suitable for:
- Final Year Computer Graphics Course
- OpenGL Laboratory Projects
- Graphics Algorithm Demonstration

---

# 🚀 Possible Future Improvements

- Sound effects
- More passengers
- Camera zoom feature
- Train speed control
- 3D version using modern OpenGL
- Texture mapping

---

# 📜 License

This project is developed for educational and academic purposes.

---

# 👨‍💻 Author

Final Year Computer Graphics Project  
Developed using C++ and OpenGL GLUT

---

⭐ If you found this project useful, feel free to star the repository!
