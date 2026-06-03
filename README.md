# 📐 Linear Algebra Visual Guide

> Interactive, browser-based visualisations for every concept in Gilbert Strang's *Introduction to Linear Algebra* — open any `.html` file and learn.

No installation. No build step. No internet required. Every file is a single self-contained HTML page that runs offline in any modern browser.

---

## 🗺 Repository structure

```
linear-algebra-visual-guide/
│
├── ch01-introduction-to-vectors/
│   ├── 1.1-vectors-and-linear-combinations.html  ✅
│   ├── 1.2-lengths-and-dot-products.html
│   └── 1.3-matrices.html
│
├── ch02-solving-linear-equations/
│   ├── 2.1-vectors-and-linear-equations.html
│   ├── 2.2-the-idea-of-elimination.html
│   ├── 2.3-elimination-using-matrices.html
│   ├── 2.4-rules-for-matrix-operations.html
│   ├── 2.5-inverse-matrices.html
│   ├── 2.6-elimination-factorization-LU.html
│   └── 2.7-transposes-and-permutations.html
│
├── ch03-vector-spaces-and-subspaces/
│   ├── 3.1-spaces-of-vectors.html
│   ├── 3.2-nullspace-solving-Ax=0.html
│   ├── 3.3-rank-and-row-reduced-form.html
│   ├── 3.4-complete-solution-to-Ax=b.html
│   ├── 3.5-independence-basis-and-dimension.html
│   └── 3.6-dimensions-of-the-four-subspaces.html
│
├── ch04-orthogonality/
│   ├── 4.1-orthogonality-of-four-subspaces.html
│   ├── 4.2-projections.html
│   ├── 4.3-least-squares-approximations.html
│   └── 4.4-orthogonal-bases-and-gram-schmidt.html
│
├── ch05-determinants/
│   ├── 5.1-properties-of-determinants.html
│   ├── 5.2-permutations-and-cofactors.html
│   └── 5.3-cramers-rule-inverses-and-volumes.html
│
├── ch06-eigenvalues-and-eigenvectors/
│   ├── 6.1-introduction-to-eigenvalues.html
│   ├── 6.2-diagonalizing-a-matrix.html
│   ├── 6.3-applications-to-differential-equations.html
│   ├── 6.4-symmetric-matrices.html
│   ├── 6.5-positive-definite-matrices.html
│   ├── 6.6-similar-matrices.html
│   └── 6.7-singular-value-decomposition-SVD.html
│
├── ch07-linear-transformations/
│   ├── 7.1-idea-of-a-linear-transformation.html
│   ├── 7.2-matrix-of-a-linear-transformation.html
│   └── 7.3-diagonalization-and-pseudoinverse.html
│
├── ch08-applications/
│   ├── 8.1-matrices-in-engineering.html
│   ├── 8.2-graphs-and-networks.html
│   ├── 8.3-markov-matrices-population-economics.html
│   ├── 8.4-linear-programming.html
│   ├── 8.5-fourier-series.html
│   ├── 8.6-linear-algebra-for-statistics.html
│   └── 8.7-computer-graphics.html
│
├── ch09-numerical-linear-algebra/
│   ├── 9.1-gaussian-elimination-in-practice.html
│   ├── 9.2-norms-and-condition-numbers.html
│   └── 9.3-iterative-methods-and-preconditioners.html
│
├── ch10-complex-vectors-and-matrices/
│   ├── 10.1-complex-numbers.html
│   ├── 10.2-hermitian-and-unitary-matrices.html
│   └── 10.3-fast-fourier-transform.html
│
└── README.md
```

---

## ✅ Progress

| Chapter | Title | Sections | Done |
|---------|-------|----------|------|
| 1 | Introduction to Vectors | 3 | 1 / 3 |
| 2 | Solving Linear Equations | 7 | 0 / 7 |
| 3 | Vector Spaces and Subspaces | 6 | 0 / 6 |
| 4 | Orthogonality | 4 | 0 / 4 |
| 5 | Determinants | 3 | 0 / 3 |
| 6 | Eigenvalues and Eigenvectors | 7 | 0 / 7 |
| 7 | Linear Transformations | 3 | 0 / 3 |
| 8 | Applications | 7 | 0 / 7 |
| 9 | Numerical Linear Algebra | 3 | 0 / 3 |
| 10 | Complex Vectors and Matrices | 3 | 0 / 3 |
| **Total** | | **46** | **1 / 46** |

---

## 🖥 What each visualisation includes

Every `.html` file is built on the same principles:

- **Interactive diagrams** — sliders, drag, and click to change parameters and see results update in real time
- **2D and 3D views** — 3D scenes use a hand-rolled canvas renderer (no Three.js) so files stay fully offline
- **Rigorous + accessible** — mathematical definitions are stated precisely, with geometric intuition explained alongside
- **Live computation** — vector components, matrix entries, and results shown numerically as you interact
- **Zero dependencies** — pure HTML, CSS, and vanilla JavaScript; no frameworks, no CDN calls

---

## 🚀 How to use

**Option 1 — just open a file**
```bash
git clone https://github.com/YOUR_USERNAME/linear-algebra-visual-guide
cd linear-algebra-visual-guide
open ch01-introduction-to-vectors/1.1-vectors-and-linear-combinations.html
```

**Option 2 — serve locally** (useful if your browser blocks local file access)
```bash
cd linear-algebra-visual-guide
python3 -m http.server 8080
# then visit http://localhost:8080
```

**Option 3 — GitHub Pages**
Enable GitHub Pages on the `main` branch in repo Settings → Pages, and every file will be accessible at:
```
https://YOUR_USERNAME.github.io/linear-algebra-visual-guide/
```

---

## 🔍 Highlighted visualisations

### ✅ 1.1 Vectors and Linear Combinations
Five interactive tabs covering the whole section:
- **Vector Addition** — parallelogram rule, head-to-tail construction, subtraction
- **Scalar Multiplication** — stretch, shrink, reverse with a live slider
- **Linear Combinations** — independently control c and d in cv + dw
- **Span (2D)** — animate how combinations fill a line, a plane, or stay stuck (dependent case)
- **3D Vectors** — fully orbitable 3D scene with vectors, combinations cu+dv+ew, and a 1 200-point span cloud

*More coming soon...*

---

## 📚 Reference textbook

> Strang, G. (2023). *Introduction to Linear Algebra* (6th ed.). Wellesley-Cambridge Press.

MIT OpenCourseWare companion: [18.06 Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)

---

## 🛠 Contributing

Contributions welcome! If you want to build a visualisation for a section:

1. Fork the repo
2. Create your file at the correct path (e.g. `ch02-solving-linear-equations/2.2-the-idea-of-elimination.html`)
3. Keep it self-contained — no external imports
4. Open a pull request with a short description of what the visualisation shows

**Design conventions:**
- Colour scheme: red `#c0392b` for first vector · blue `#1a5fa8` for second · green `#1a8a3c` for results · orange `#d4560a` for highlights
- Font: Lora (serif body) + Source Code Pro (numbers/code)
- Background: `#f8f4ee` (warm off-white)
- All sliders should show a live numeric readout

---

## 📄 License

MIT — free to use, adapt, and share for learning purposes.
