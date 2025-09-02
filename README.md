# Electric Motor Mount – Hybrid Design (3D Print + Cement)

This project develops an **electric motor mount** designed for both educational and light industrial applications.  
The concept combines **additive manufacturing (3D printing)** with a **cement filling**, achieving a robust, low-cost, and replicable part that can be produced even in workshops with limited resources.

---

## 📌 Project Goals
- Design a mount that securely holds a standard **IEC electric motor**.  
- Use a **3D-printed shell** as a permanent formwork.  
- Increase **mass and stiffness** through a **cement filling**.  
- Apply **injection molding design rules** (wall thickness, ribs, draft) so the design can scale to industrial production.

---

## 🛠️ Design Features
- **Top base:** 240 × 132 mm, adjusted to the motor footprint.  
- **Bottom base:** 264 × 156 mm, proportioned for stability and balanced aesthetics.  
- **Cement cavity height:** 30–40 mm (tunable).  
- **Motor foot pocket:** 134 × 107 × 10 mm with Ø9 × 18 mm slots for M8 bolts.  
- **Internal and side ribs**, sized according to injection molding rules (thickness ≈ 0.6 × wall, height ≤ 3 × wall, 1° draft).  
- **Rounded corners** (R1–R2 mm) for better material flow.  
- **Draft angle:** 1–2° on all vertical walls.  

---

## 📊 Mass Calculation (example)
With nominal dimensions:  
- Cement (30 mm height): ~1.9 kg  
- Printed shell (PETG/PLA, 5–6 mm): ~0.4 kg  
- Bolts & inserts: ~0.08 kg  
- **Total mass ≈ 2.36 kg**

Every additional 10 mm of cement adds ~0.63 kg.  

---

## 📐 Repository Structure
- `CAD/` → Parametric models (FreeCAD / STEP).  
- `STL/` → Printable files for 3D printing.  
- `docs/` → Technical drawings, calculations, and assembly notes.  

---

## 🚀 How to Use
1. **3D print** the shell (PETG recommended for strength and temperature resistance).  
2. **Seal** the inner walls with a thin epoxy or acrylic coating to protect against cement water.  
3. **Pour cement** while lightly vibrating to remove air bubbles.  
4. **Mount the motor** using M8 bolts in the top pocket.  
5. *(Optional)* Add an **anti-vibration pad** (EVA foam or neoprene) under the bottom base.  

---

## 🔬 Applications
- **Technical education:** demonstration of hybrid design and resource optimization.  
- **Rapid prototyping:** validation of geometry before injection molding.  
- **Industrial production:** scalable to plastic injection with proper rib and wall tuning.  

---

## 📄 License
This project is released under the **MIT License**.  
You are free to use, modify, and adapt it with attribution.

---

## 🤝 Contributions
Contributions are welcome in:  
- Rib design and weight optimization.  
- Structural and mass calculations.  
- Alternative materials for shell and filling.  
- Injection molding adaptations for industrial scale.

---

## 👤 Author
Developed by **Pedro Martín**, engineer and professor, as part of an educational initiative in technical institutes with limited resources.

