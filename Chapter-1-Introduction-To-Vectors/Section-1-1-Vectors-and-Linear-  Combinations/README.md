# 📐 Section 1.1 — Vectors & Linear Combinations
### An interactive visual guide to Gilbert Strang's *Introduction to Linear Algebra*

A self-contained, offline-ready HTML file that teaches the core ideas of Section 1.1 through interactive diagrams and a full 3D viewer — no frameworks, no build step, no internet connection required.

---

## ✨ Features

| Tab | What you can do |
|-----|----------------|
| **Vector Addition** | See the parallelogram rule and head-to-tail construction live; also shows v − w as the other diagonal |
| **Scalar Multiplication** | Drag a slider from −3 to 3 and watch the arrow stretch, shrink, and reverse |
| **Linear Combinations** | Independently control scalars *c* and *d* for cv + dw; live readout of the result vector |
| **Span (2D)** | Animate three cases: a line (1 vector), a full plane (2 independent vectors), and the dependent/redundant case |
| **3D Vectors** | Fully interactive 3D scene — orbit by dragging, zoom by pinching or scrolling |

### 3D Viewer modes
- **Show u, v, w** — three vectors plotted as arrows in xyz space with labelled axes
- **Combination cu + dv + ew** — three sliders scale each vector; the yellow result arrow and a live component readout update in real time; dashed lines show the 3D tip-to-tail construction
- **Span cloud** — 1,200 random combinations rendered as coloured dots, demonstrating that three independent vectors span all of ℝ³

---

## 🚀 Usage

```bash
# Clone or download the repo, then just open the file
open section1_1_vectors.html          # macOS
start section1_1_vectors.html         # Windows
xdg-open section1_1_vectors.html      # Linux
```

Or drag the file straight into any browser tab. Works fully offline — there are **no external dependencies**.

---

## 🛠 Technical details

- **Pure HTML / CSS / JavaScript** — single self-contained file
- **Zero dependencies** — no Three.js, no D3, no React; 3D rendering uses a hand-rolled perspective projection on a `<canvas>` element
- **3D math** — spherical-coordinate camera orbit, manual projection from world space to screen space, cone arrow-heads drawn from scratch
- **Mobile-friendly** — touch drag to orbit, two-finger pinch to zoom, horizontal-scroll nav bar

---

## 📖 Concepts covered

| Concept | Where |
|---------|-------|
| Column vectors and components | All panels |
| Vector addition (head-to-tail & parallelogram) | Vector Addition tab |
| Vector subtraction as addition of −w | Vector Addition tab |
| Scalar multiplication; the zero vector | Scalar Mult. tab |
| Linear combinations cv + dw | Linear Combinations tab |
| The four special combinations (sum, difference, zero, scalar multiple) | Linear Combinations tab |
| Span of one vector → line | Span tab |
| Span of two independent vectors → plane | Span tab |
| Linear dependence — a redundant vector adds no new direction | Span tab |
| 3D vectors with three components | 3D Vectors tab |
| Span of three independent vectors → all of ℝ³ | 3D Vectors tab |

---

## 📚 Reference

Based on **Chapter 1, Section 1.1** of:

> Strang, G. (2023). *Introduction to Linear Algebra* (6th ed.). Wellesley-Cambridge Press.

Key ideas from the text reproduced visually:
- *"The vectors cv lie along a line. When w is not on that line, the combinations cv + dw fill the whole two-dimensional plane."*
- Figure 1.1 (parallelogram), Figure 1.2 (3D vectors), Figure 1.3 (line and plane from span)

---

## 🗂 File structure

```
section1_1_vectors.html   ← everything; open this in a browser
README.md                 ← this file
```

---

## 📄 License

Free to use for personal study and educational purposes.
