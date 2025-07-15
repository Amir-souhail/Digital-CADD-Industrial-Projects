# 🔩 Gripper Assembly – Mechanical Design & Motion Study

This repository contains the design and motion study of a compact mechanical gripper driven by a micro servo motor. The system is gear-actuated, fully modeled in SOLIDWORKS, and intended for general-purpose mechanical and robotic applications.

## 🧰 Key Features

- Compact dual-jaw gripping mechanism
- Gear-synchronized motion for symmetrical actuation
- Driven by a TowerPro 9g micro servo
- Fully parametric design in SOLIDWORKS
- Exploded view with detailed bill of materials (BOM)
- Simulated motion study exported as a GIF

## 📐 Bill of Materials & Part Descriptions

| Item No. | Part Name               | Qty | Description |
|----------|-------------------------|-----|-------------|
| 1        | Part3_GR                | 2   | Outer frame plates that support the structure and hold the gears and servo in alignment. |
| 2        | Part4_GR                | 1   | Fixed center base plate providing a mount for the servo and supporting structural rigidity. |
| 3        | Part5_GR                | 1   | Base cover or bottom plate to close and protect the internal gear layout. |
| 4        | Part1_GR                | 4   | Link arms connecting the rotating gears to the gripper jaws, ensuring synchronous motion. |
| 5        | Part2_GR                | 6   | Gears used to transfer rotational motion from the servo to the two gripper jaws symmetrically. |
| 6        | Part8_GR                | 1   | Main gripper jaw (left) actuated by gear rotation. |
| 7        | Part7_GR                | 2   | Gripper finger extensions or pads for improved grip surface contact. |
| 8        | Part6_GR                | 8   | Spacers or standoffs to maintain frame separation and alignment. |
| 9        | TowerPro Micro Servo 9g | 1   | Motor providing actuation power; its rotation drives the input gear. |
| 10       | ISO 7380 – M3 × 12      | 3   | Button-head screws to fasten parts without protruding too much. |
| 11       | ISO 4032 – M3 Nut       | 2   | Standard nuts used with M3 screws for firm mechanical locking. |

## 📸 Visuals

### ✅ Final Assembly
`Gripper Assembly Figure.JPG`  
Rendered view of the complete gripper design in closed-jaw position.

### 🧩 Exploded View
`Gripper Assembly Exploded Figure.JPG`  
Exploded drawing with BOM callouts and overall dimensions.

### 🎞️ Motion Study
`Motion_Study.gif`  
Simulated animation showing the synchronized actuation of the gripper jaws via servo-driven gears.

## 🗂️ Drawings & CAD Files

Each part has its own 2D drawing for manufacturing or documentation purposes:

- `Part1_GR.SLDDRW` – Link Arm Drawing  
- `Part2_GR.SLDDRW` – Gear Drawing  
- `Part3_GR.SLDDRW` – Side Frame Drawing  
- `Part4_5_6_8_GR.SLDDRW` – Combined drawing for base, back plate, spacers, and left jaw  
- `Part7_GR.SLDDRW` – Finger/Pad Drawing  
- `Gripper Assembly.SLDASM` – Main assembly  
- `Gripper Assembly Figure.JPG` – Full render  
- `Gripper Assembly Exploded Figure.JPG` – Annotated exploded view  
- `Motion_Study.gif` – Animated motion simulation  

> *File formats such as `.SLDPRT`, `.SLDDRW`, `.STEP`, and `.GIF` can be included depending on repository size limits or export preferences.*

## 🧑‍💼 Author

**Amir Souhail**  
Research and Development Engineer  
La Spezia, Italy  
📧 amir.souhail@gmail.com
