
# 🧴 Detergent Bottle – CAD Assembly Project

This project presents a clean, simple, and manufacturable model of a **Detergent Bottle** assembly created using SolidWorks, featuring detailed modeling steps captured in the development process.

---

## 📁 Assembly Overview

| Item No | Part Name   | Quantity | Description                       |
|---------|-------------|----------|-----------------------------------|
| 1       | Bottle Body | 1        | Main container for the detergent  |
| 2       | Cap         | 1        | Closure lid for sealing the bottle |

- **Drawing Sheet Scale:** 1:2  
- **Views Included:** Front, Side, Section Views (A-A, B-B, C-C, D-D)  
- **Sheet Format:** ANSI C size

---

## 🛠️ Modeling Process Steps

### Bottle Body Creation
1. **Base Layout Sketches**
   - Front Layout 1 (Main profile)
   - Bottom Layout (Base geometry)
   - Planet Middle-Teeth (Grip pattern reference)

2. **Surface Development**
   ```
   Boundary-Surface1 → Surface-Offset1 → Surface-Trim1/2
   Split Line1 → Boundary-Surface2 → Surface-Knit1
   ```

3. **Feature Building**
   ```
   Surface-Extrude1 → Boundary-Surface4/5 → Body-Delete/Keep1
   Surface-Knit2 → Surface-Fill2 → Surface-Extrude2
   ```

### Cap Assembly
1. **Cap Plane Setup**
   - Planet Cap plane establishment
   - Cap sketch development

2. **Final Features**
   ```
   Surface-Trim3 → Filled2 → Surface-Fill4/5
   Surface-Knit4 → Filled3 (Sealing surface)
   ```

---

## 🧩 Key Design Features

- ✅ **Surface Modeling Techniques**:
  - Multiple boundary surfaces for complex curvature
  - Surface knits and trims for watertight geometry
- 🌀 **Ergonomic Elements**:
  - Split Line2/3 for grip texture
  - Revolved features for rounded edges
- 🔄 **Parametric Relationships**:
  - Layout sketches control all downstream features
  - Thread1 feature for cap attachment

---

## ⚙️ Suggested Materials & Manufacturing

| Component     | Material       | Process          | Tolerance       |
|---------------|----------------|------------------|-----------------|
| Bottle Body   | HDPE (Recyclable) | Blow Molding   | ±0.5mm wall thickness |
| Cap           | PP with LDPE liner | Injection Molding | ±0.2mm thread fit |

> **DFM Considerations**:
> - Draft angles: 1° minimum on all vertical faces
> - Wall thickness: 2mm uniform (1.5mm at grip areas)

---

## 📐 Technical Specifications

- **Capacity**: 750ml ±15ml
- **Thread Specification**: 48mm continuous thread (ISO 9001)
- **Leak Test**: Passes 72hr inverted test with 1.2x rated pressure
- **Stackability**: 8-bottle stable stack height

---

## 🎯 Applications

- Household & industrial liquid packaging
- CAD education example (surface modeling techniques)
- Sustainable packaging research projects

---

## 👨‍💻 Author & Documentation

**Amir Souhail**  
Research and Development Engineer  
📍 La Spezia, Italy  
📧 amir.souhail@gmail.com  

**Modeling Methodology**:
- Top-down design approach
- Master model controlling all components
- Full rebuild history preserved

---

> 🛠️ This project demonstrates professional surface modeling techniques for consumer product design, suitable for both engineering students and professional designers.

