# C-Clamp Assembly

This folder contains a full mechanical modeling project for a **C-Clamp**, a common workholding device used in manufacturing, welding, and woodworking. The project includes parametric part files, assembly models, motion study, engineering drawings, and animation views.

---

## 🛠 Project Overview

- **Objective**: To model a fully functional and manufacturable mechanical clamp using SOLIDWORKS.
- **Scope**:
  - Part modeling using design intent
  - Assembly constraints and motion
  - Drawing creation with exploded views and BOM
  - Motion study with animation

---

## 📂 Folder Contents

| File Type             | Description |
|-----------------------|-------------|
| `Part1_Frame_C-CClamp` | Main structural body of the clamp |
| `Part2_ThreadedShaft_C-Clamp` | Shaft that provides clamping force through rotation |
| `Part3_Pad1`           | Contact surface that presses the object |
| `Part4_Handle`         | T-handle used to rotate the threaded shaft |
| `Part5_Lockpin` (x3)   | Pins used to fix and lock components |
| `Part6_Coverplate`     | Plate to hold internal parts in place |
| `Part7_ClampButton`    | Engages/retracts locking or movement |
| `Part8_Spring`         | Provides return force or preload |
| `Part9_ToothedBlock`   | Prevents unintentional shaft rotation |
| `ISO 7046-1 – M2 x 6`  | Standard screws used (x4) |
| `C-Clamp Assembly`     | Full assembly file |
| `C-Clamp Assembly Drawing` | 2D technical drawing with BOM and exploded view |
| `C-Clamp Motion`       | Motion study animation of clamp operation |
| `C-Clamp Motion Front/Side` | Views showing motion configuration |

---

## 🔩 Component Roles

- **Frame**: Rigid part that holds the overall structure.
- **Threaded Shaft**: Converts rotary motion into linear force for clamping.
- **Pad**: Provides the clamping surface; presses against the object.
- **Handle**: Allows user to apply torque to threaded shaft.
- **Spring + Button**: Used for quick-release or restoring positions.
- **Lockpins**: Mechanical fasteners to retain parts.
- **Toothed Block**: Prevents back-rotation of shaft due to load.
- **Coverplate**: Closes and protects inner components.

---

## 🎞 Motion Study

The project includes a SOLIDWORKS motion study showing the functional behavior of the clamp as the threaded shaft rotates and moves the pad linearly.

---

## 🧠 Learning Outcomes

- Advanced part modeling (threads, fillets, profiles)
- Assembly mates and dynamic motion
- Exploded view creation and BOM management
- ISO standard hardware integration

---

**Author**:  
**Amir Souhail**  
Research and Development Engineer  
La Spezia, Italy  
amir.souhail@gmail.com
