# 📐 Linear Algebra Visual Guide

> Interactive, browser-based visualisations for every concept in Gilbert Strang's *Introduction to Linear Algebra* — no installation, no dependencies, just open and learn.

---

## 🎯 What this is

A collection of self-contained HTML files, one per section, that turn the abstract ideas of linear algebra into things you can **see, drag, rotate, and play with**. Each file works offline and requires nothing beyond a modern browser.

Built alongside active study of Strang's textbook. Chapters 1–6 are the primary focus (GATE DA syllabus); Chapter 7 is included time permitting.

---

## 📚 Book reference

> Strang, G. *Introduction to Linear Algebra* (6th ed.). Wellesley-Cambridge Press.

---

## 🗂 Repository structure

```
linear-algebra-visual-guide/
│
├── ch01-intro-to-vectors/
│   ├── 1.1-vectors-and-linear-combinations.html  ✅
│   ├── 1.2-lengths-and-dot-products.html
│   └── 1.3-matrices.html
│
├── ch02-solving-linear-equations/
│   ├── 2.1-vectors-and-linear-equations.html
│   ├── 2.2-idea-of-elimination.html
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
│   ├── 3.4-complete-solution-Ax=b.html
│   ├── 3.5-independence-basis-dimension.html
│   └── 3.6-dimensions-of-four-subspaces.html
│
├── ch04-orthogonality/
│   ├── 4.1-orthogonality-of-four-subspaces.html
│   ├── 4.2-projections.html
│   ├── 4.3-least-squares-approximations.html
│   └── 4.4-orthogonal-bases-gram-schmidt.html
│
├── ch05-determinants/
│   ├── 5.1-properties-of-determinants.html
│   ├── 5.2-permutations-and-cofactors.html
│   └── 5.3-cramers-rule-inverses-volumes.html
│
├── ch06-eigenvalues-and-eigenvectors/
│   ├── 6.1-introduction-to-eigenvalues.html
│   ├── 6.2-diagonalizing-a-matrix.html
│   ├── 6.3-applications-differential-equations.html
│   ├── 6.4-symmetric-matrices.html
│   ├── 6.5-positive-definite-matrices.html
│   ├── 6.6-similar-matrices.html
│   └── 6.7-singular-value-decomposition-SVD.html
│
├── ch07-linear-transformations/          ← time permitting
│   ├── 7.1-idea-of-linear-transformation.html
│   ├── 7.2-matrix-of-linear-transformation.html
│   └── 7.3-diagonalization-and-pseudoinverse.html
│
└── README.md
```

**Status legend:** ✅ complete · 🚧 in progress · ⬜ not started

---

## ✅ Progress tracker

### Chapter 1 — Introduction to Vectors
| Section | Topic | Status |
|---------|-------|--------|
| 1.1 | Vectors and Linear Combinations | ✅ |
| 1.2 | Lengths and Dot Products | ⬜ |
| 1.3 | Matrices | ⬜ |

### Chapter 2 — Solving Linear Equations
| Section | Topic | Status |
|---------|-------|--------|
| 2.1 | Vectors and Linear Equations | ⬜ |
| 2.2 | The Idea of Elimination | ⬜ |
| 2.3 | Elimination Using Matrices | ⬜ |
| 2.4 | Rules for Matrix Operations | ⬜ |
| 2.5 | Inverse Matrices | ⬜ |
| 2.6 | Elimination = Factorization: A = LU | ⬜ |
| 2.7 | Transposes and Permutations | ⬜ |

### Chapter 3 — Vector Spaces and Subspaces
| Section | Topic | Status |
|---------|-------|--------|
| 3.1 | Spaces of Vectors | ⬜ |
| 3.2 | The Nullspace of A: Solving Ax = 0 | ⬜ |
| 3.3 | The Rank and the Row Reduced Form | ⬜ |
| 3.4 | The Complete Solution to Ax = b | ⬜ |
| 3.5 | Independence, Basis and Dimension | ⬜ |
| 3.6 | Dimensions of the Four Subspaces | ⬜ |

### Chapter 4 — Orthogonality
| Section | Topic | Status |
|---------|-------|--------|
| 4.1 | Orthogonality of the Four Subspaces | ⬜ |
| 4.2 | Projections | ⬜ |
| 4.3 | Least Squares Approximations | ⬜ |
| 4.4 | Orthogonal Bases and Gram-Schmidt | ⬜ |

### Chapter 5 — Determinants
| Section | Topic | Status |
|---------|-------|--------|
| 5.1 | The Properties of Determinants | ⬜ |
| 5.2 | Permutations and Cofactors | ⬜ |
| 5.3 | Cramer's Rule, Inverses, and Volumes | ⬜ |

### Chapter 6 — Eigenvalues and Eigenvectors
| Section | Topic | Status |
|---------|-------|--------|
| 6.1 | Introduction to Eigenvalues | ⬜ |
| 6.2 | Diagonalizing a Matrix | ⬜ |
| 6.3 | Applications to Differential Equations | ⬜ |
| 6.4 | Symmetric Matrices | ⬜ |
| 6.5 | Positive Definite Matrices | ⬜ |
| 6.6 | Similar Matrices | ⬜ |
| 6.7 | Singular Value Decomposition (SVD) | ⬜ |

### Chapter 7 — Linear Transformations *(time permitting)*
| Section | Topic | Status |
|---------|-------|--------|
| 7.1 | The Idea of a Linear Transformation | ⬜ |
| 7.2 | The Matrix of a Linear Transformation | ⬜ |
| 7.3 | Diagonalization and the Pseudoinverse | ⬜ |

---

## 🧩 What each visualisation includes

Every HTML file follows the same pattern:

- **Static diagrams** — key figures from the section, drawn precisely on `<canvas>`
- **Interactive sliders** — manipulate vectors, scalars, or matrix entries in real time
- **Animated sweeps** — watch spans, null spaces, and transformations build up dynamically
- **3D scenes** (where relevant) — orbit, zoom, and rotate using drag/pinch; built with a zero-dependency hand-rolled perspective renderer
- **Inline explanations** — layperson language alongside rigorous definitions, in the spirit of the textbook itself

**Technical constraints (by design):**
- Single `.html` file per section — no build step, no bundler
- Zero external dependencies — works fully offline
- Mobile-friendly — touch orbit, pinch zoom, scrollable nav

---

## 🚀 How to use

```bash
git clone https://github.com/<your-username>/linear-algebra-visual-guide.git
cd linear-algebra-visual-guide

# Open any file directly in your browser
open ch01-intro-to-vectors/1.1-vectors-and-linear-combinations.html
```

No server needed. No `npm install`. Just open and explore.

---

## 💡 Design philosophy

> *"The goal of this book is to explain why, not just how."* — Gilbert Strang

The same principle applies here. Each visualisation tries to answer **why** a concept is true geometrically before showing the algebra. A student who can rotate the span of three vectors in 3D and watch it fill space has a fundamentally different intuition than one who only memorised the definition.

Rigour is not sacrificed — definitions are stated precisely and every interactive element is grounded in the exact mathematics of the section.

---

## 📄 License

Free to use for personal study and educational purposes.

---
