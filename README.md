<div align="center">

# 📐 Strang Linear Algebra Visual

**Interactive visual guides for every concept in Strang's *Introduction to Linear Algebra***

*Every arrow, every plane, every transformation — made tangible.*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![HTML](https://img.shields.io/badge/Built%20with-HTML%2FJS%2FCanvas-orange)](#)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-zero-brightgreen)](#)
[![Offline Ready](https://img.shields.io/badge/Works-Offline-blue)](#)

</div>

---

## 🎯 What is this?

A growing collection of **self-contained, offline-ready HTML visualisations** — one per section — covering the full arc of Gilbert Strang's *Introduction to Linear Algebra* (6th ed.).

Each file opens in any browser with no install, no server, no internet. Just download and learn.

> *"The goal is not just to see the answer — but to see why it has to be that way."*

---

## 📚 Table of Contents & Progress

### Chapter 1 — Introduction to Vectors
| Section | Topic | Status |
|---------|-------|--------|
| 1.1 | Vectors and Linear Combinations | ✅ Done |
| 1.2 | Lengths and Dot Products | 🔲 Planned |
| 1.3 | Matrices | 🔲 Planned |

### Chapter 2 — Solving Linear Equations
| Section | Topic | Status |
|---------|-------|--------|
| 2.1 | Vectors and Linear Equations | 🔲 Planned |
| 2.2 | The Idea of Elimination | 🔲 Planned |
| 2.3 | Elimination Using Matrices | 🔲 Planned |
| 2.4 | Rules for Matrix Operations | 🔲 Planned |
| 2.5 | Inverse Matrices | 🔲 Planned |
| 2.6 | Elimination = Factorization: A = LU | 🔲 Planned |
| 2.7 | Transposes and Permutations | 🔲 Planned |

### Chapter 3 — Vector Spaces and Subspaces
| Section | Topic | Status |
|---------|-------|--------|
| 3.1 | Spaces of Vectors | 🔲 Planned |
| 3.2 | The Nullspace of A: Solving Ax = 0 | 🔲 Planned |
| 3.3 | The Rank and the Row Reduced Form | 🔲 Planned |
| 3.4 | The Complete Solution to Ax = b | 🔲 Planned |
| 3.5 | Independence, Basis and Dimension | 🔲 Planned |
| 3.6 | Dimensions of the Four Subspaces | 🔲 Planned |

### Chapter 4 — Orthogonality
| Section | Topic | Status |
|---------|-------|--------|
| 4.1 | Orthogonality of the Four Subspaces | 🔲 Planned |
| 4.2 | Projections | 🔲 Planned |
| 4.3 | Least Squares Approximations | 🔲 Planned |
| 4.4 | Orthogonal Bases and Gram-Schmidt | 🔲 Planned |

### Chapter 5 — Determinants
| Section | Topic | Status |
|---------|-------|--------|
| 5.1 | The Properties of Determinants | 🔲 Planned |
| 5.2 | Permutations and Cofactors | 🔲 Planned |
| 5.3 | Cramer's Rule, Inverses, and Volumes | 🔲 Planned |

### Chapter 6 — Eigenvalues and Eigenvectors
| Section | Topic | Status |
|---------|-------|--------|
| 6.1 | Introduction to Eigenvalues | 🔲 Planned |
| 6.2 | Diagonalizing a Matrix | 🔲 Planned |
| 6.3 | Applications to Differential Equations | 🔲 Planned |
| 6.4 | Symmetric Matrices | 🔲 Planned |
| 6.5 | Positive Definite Matrices | 🔲 Planned |
| 6.6 | Similar Matrices | 🔲 Planned |
| 6.7 | Singular Value Decomposition (SVD) | 🔲 Planned |

### Chapter 7 — Linear Transformations
| Section | Topic | Status |
|---------|-------|--------|
| 7.1 | The Idea of a Linear Transformation | 🔲 Planned |
| 7.2 | The Matrix of a Linear Transformation | 🔲 Planned |
| 7.3 | Diagonalization and the Pseudoinverse | 🔲 Planned |

### Chapter 8 — Applications
| Section | Topic | Status |
|---------|-------|--------|
| 8.1 | Matrices in Engineering | 🔲 Planned |
| 8.2 | Graphs and Networks | 🔲 Planned |
| 8.3 | Markov Matrices, Population, and Economics | 🔲 Planned |
| 8.4 | Linear Programming | 🔲 Planned |
| 8.5 | Fourier Series: Linear Algebra for Functions | 🔲 Planned |
| 8.6 | Linear Algebra for Statistics and Probability | 🔲 Planned |
| 8.7 | Computer Graphics | 🔲 Planned |

### Chapter 9 — Numerical Linear Algebra
| Section | Topic | Status |
|---------|-------|--------|
| 9.1 | Gaussian Elimination in Practice | 🔲 Planned |
| 9.2 | Norms and Condition Numbers | 🔲 Planned |
| 9.3 | Iterative Methods and Preconditioners | 🔲 Planned |

### Chapter 10 — Complex Vectors and Matrices
| Section | Topic | Status |
|---------|-------|--------|
| 10.1 | Complex Numbers | 🔲 Planned |
| 10.2 | Hermitian and Unitary Matrices | 🔲 Planned |
| 10.3 | The Fast Fourier Transform | 🔲 Planned |

---

## 🗂 Repository Structure

```
strang-linear-algebra-visual/
│
├── README.md
│
├── ch1-introduction-to-vectors/
│   ├── 1.1-vectors-and-linear-combinations.html  ✅
│   ├── 1.2-lengths-and-dot-products.html
│   └── 1.3-matrices.html
│
├── ch2-solving-linear-equations/
│   ├── 2.1-vectors-and-linear-equations.html
│   ├── 2.2-idea-of-elimination.html
│   └── ...
│
├── ch3-vector-spaces/
├── ch4-orthogonality/
├── ch5-determinants/
├── ch6-eigenvalues/
├── ch7-linear-transformations/
├── ch8-applications/
├── ch9-numerical/
└── ch10-complex/
```

---

## 🚀 How to Use

### Option A — Just open the file
Download any `.html` file and open it in a browser. That's it. No server needed.

```bash
git clone https://github.com/YOUR_USERNAME/strang-linear-algebra-visual
cd strang-linear-algebra-visual
open ch1-introduction-to-vectors/1.1-vectors-and-linear-combinations.html
```

### Option B — Browse locally with a simple server
```bash
cd strang-linear-algebra-visual
python -m http.server 8000
# then visit http://localhost:8000
```

---

## 🛠 Design Principles

Every visualisation in this repo follows these rules:

| Principle | Why |
|-----------|-----|
| **Zero dependencies** | Opens offline, no CDN failures, no version drift |
| **Single HTML file per section** | Download one file, learn one concept |
| **Interactive, not static** | Sliders, drag-to-orbit, animated sweeps — not just pictures |
| **Rigour preserved** | Precise mathematical language alongside geometric intuition |
| **Mobile-first** | Touch drag, pinch zoom, scrollable nav — works on a phone screen |
| **Dark + light canvas** | 2D panels on warm paper; 3D scenes on dark background for depth |

---

## ✨ Feature highlights (Section 1.1)

The completed **1.1 — Vectors and Linear Combinations** file showcases what each section aims for:

- **Vector Addition tab** — live parallelogram rule with a shaded parallelogram, head-to-tail construction, and subtraction as the other diagonal
- **Scalar Multiplication tab** — slider from −3 to 3; arrow stretches, shrinks, and reverses in real time
- **Linear Combinations tab** — independent c and d sliders; dashed parallelogram updates live
- **Span (2D) tab** — animated dot-spray showing: one vector → line, two independent → full plane, two dependent → still just a line
- **3D Vectors tab** — fully orbitable 3D scene (drag + pinch), three modes: bare vectors / combination with tip-to-tail dashes / 1 200-point span cloud

All 3D rendering is done with a **hand-rolled perspective projection** on `<canvas>` — no Three.js, no WebGL.

---

## 🤝 Contributing

Contributions are welcome! If you want to build a visualisation for a section:

1. Fork the repo
2. Create a branch: `git checkout -b viz/ch2-elimination`
3. Build your `.html` file following the design principles above
4. Open a PR with a short description of what the interactive elements show

**Good first sections to tackle:** 2.2 (Elimination — row operations on a live matrix), 3.1 (Subspaces — interactive subspace checker), 6.1 (Eigenvalues — eigenvector direction visualiser).

---

## 📖 Reference

> Strang, G. (2023). *Introduction to Linear Algebra* (6th ed.). Wellesley-Cambridge Press.

MIT OpenCourseWare lectures (18.06) are also an excellent companion: [ocw.mit.edu](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)

---

## 📄 License

MIT — free to use, share, and adapt for any educational purpose.

---

<div align="center">
<sub>Built section by section · one concept at a time</sub>
</div>
