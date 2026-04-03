# 🧠 IOAI Preparation — Linear Algebra & Machine Learning Foundations

Self-study notes and hands-on code for preparing for the **International Olympiad in Artificial Intelligence (IOAI)**. This repository documents my day-by-day progress through the math, coding, and ML concepts needed to compete.

---

## 📂 Repository Structure

```
ioai-prep/
├── README.md
└── day1/
    ├── Day_1.ipynb          # Jupyter notebook with code, exercises & notes
    └── day1_lesson.html     # Polished interactive lesson (open in browser)
```

---

## Day 1 — Vectors, Matrices, Transformations & Eigenvalues

**Goal:** Build a rock-solid intuition for linear algebra — the backbone of all machine learning.

### What's Covered

| Section | Topic | Key Ideas |
|---------|-------|-----------|
| 01 | **What Is a Vector?** | Four perspectives: Physics (arrow), Math (vector space element), CS (list of numbers), ML (data point in high-dimensional space). Notation, column vs row vectors, NumPy shapes. |
| 02 | **Vector Operations** | Addition (tip-to-tail), scalar multiplication (stretching/flipping), dot product (similarity measure), cosine similarity, orthogonality. |
| 03 | **Linear Combinations, Span & Independence** | Linear combinations, span of vector sets, linear independence, basis vectors, connection to PCA. |
| 04 | **What Is a Matrix?** | Matrices as grids of numbers — and the deeper view: matrices *are* transformations (3Blue1Brown's core insight). |
| 05 | **Matrices as Transformations** | Geometric interpretation of matrix multiplication. Visualizing how a matrix warps the unit square. Matplotlib code to plot before/after transformations. |
| 06 | **Determinants** | The area/volume scaling factor of a transformation. |
| 07 | **Solving Linear Systems** | `np.linalg.solve`, plus a from-scratch implementation of **Gaussian elimination** with partial pivoting and back-substitution. |

### Code Highlights

- **Cosine similarity function** — the same metric used in embedding search, recommendation systems, and transformer attention.
- **`plot_transformation()`** — a reusable visualization that shows how any 2×2 matrix warps the unit square and moves the basis vectors.
- **`gauss_solve()`** — a complete Gaussian elimination solver built from scratch, including partial pivoting for numerical stability.

### Key Takeaways

- A 28×28 grayscale image is just a vector in ℝ⁷⁸⁴ — flatten the pixels into one list.
- The dot product is the foundation of neural networks: inputs · weights.
- Attention in transformers = dot products between query and key vectors.
- PCA finds a new basis that captures maximum variance — built entirely on span, independence, and basis concepts from Day 1.

---

## 🛠 How to Use

1. **Jupyter Notebook** — Open `day1/Day_1.ipynb` in Jupyter Lab/Notebook or VS Code. Run cells interactively and experiment.
2. **HTML Lesson** — Open `day1/day1_lesson.html` in any browser for a beautifully formatted reference with all the theory.

### Requirements

```
numpy
matplotlib
```

---

## 🗓 Study Plan

- [x] **Day 1** — Vectors, Matrices, Transformations & Eigenvalues
- [ ] **Day 2** — *(coming soon)*
- [ ] **Day 3** — *(coming soon)*

---

## 📚 Resources

- [3Blue1Brown — Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) — the visual foundation for Day 1
- [NumPy Documentation](https://numpy.org/doc/)
- [IOAI Official Site](https://ioai.org/)

---

## License

This is a personal study repository. Notes and code are shared for educational purposes.
