# 🔩 Gripper Assembly – Mechanical Design & Motion Study

This repository contains the design and motion study of a compact mechanical gripper driven by a micro servo motor. The system is gear-actuated, fully modeled in SOLIDWORKS, and intended for general-purpose mechanical and robotic applications.

## 🧰 Key Features

- Compact dual-jaw gripping mechanism
- Gear-synchronized motion for symmetrical actuation
- Driven by a TowerPro 9g micro servo
- Fully parametric design in SOLIDWORKS
- Exploded view with detailed bill of materials (BOM)
- Simulated motion study exported as a GIF

## 📁 Folder Structure

Gripper-Assembly/
├── images/
│   ├── Gripper_Assembly.JPG              # Final rendered assembly
│   ├── Gripper_Assembly_Figure.JPG       # Exploded view with BOM and dimensions
│   └── Motion_Study.gif                  # Motion simulation
├── README.md                             # Project documentation
└── [CAD Files]                           # Optional: .SLDPRT, .SLDASM, .STEP

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

**✅ Final Assembly:**

![Gripper Assembly](images/Gripper_Assembly.JPG)

**🧩 Exploded View with BOM:**

![Exploded View](images/Gripper_Assembly_Figure.JPG)

**🎞️ Motion Study (GIF):**

![Motion Study](images/Motion_Study.gif)

The motion study demonstrates the synchronized rotation of the gears driving the jaws to open and close with precision. It visually validates the kinematic chain under servo input.

## 🧑‍💼 Author

**Amir Souhail**  
Research and Development Engineer  
La Spezia, Italy  
📧 amir.souhail@gmail.com
