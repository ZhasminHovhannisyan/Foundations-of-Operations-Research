# Foundations of Operations Research

Working repository for **Foundations of Operations Research**, a Master's course at Politecnico di Milano (POLIMI), academic year **2026/27**, winter semester.

Lecture PDFs are edited in place. Earlier (clean) versions remain available through the git history of the same files.

Official lecture slides and lab material are also distributed on WeBeep.

## Operations Research

Operations Research (O.R.) is a branch of applied mathematics in which mathematical models and quantitative methods (for example optimization, game theory, and simulation) are used to analyze complex decision-making problems and find (near-)optimal solutions.

The overall goal is to help make better decisions. The field sits at the interface of applied mathematics, computer science, economics, and industrial engineering.

## Course objectives

- Analyze a decision-making problem, build an optimization model, identify an appropriate algorithm, and interpret the output.
- Understand main optimization methods, including graph optimization, project planning, linear programming (LP), and integer linear programming (ILP).
- Use a modeling language (Python) and a state-of-the-art solver (CPLEX or Gurobi).

## Syllabus

1. Introduction
2. Graph and network optimization
3. Linear Programming (LP)
4. Integer Linear Programming (ILP)

## Repository structure

```
.
├── Lecture Slides/     lecture PDFs (annotated in place)
├── labs/               computer labs and projects (to be added)
├── LICENSE
└── README.md
```

- **`Lecture Slides/`** — current lecture handouts. Notes are written on these files; do not duplicate “clean” vs “annotated” copies. To recover a previous revision: `git log -- "Lecture Slides/<file>.pdf"` and check out the desired commit.
- **`labs/`** — reserved for exercise/computer-lab sessions and later project work (models, notebooks, solver scripts). This directory will be added when the first lab material is committed.

## Teaching material and references

Slides and exercise/lab material: this repository and WeBeep.

Complementary texts:

- M. Fischetti, *Introduction to Mathematical Optimization*, 2019.
- F. Hillier and G. J. Lieberman, *Introduction to Operations Research*, McGraw-Hill, 2021.

Graph algorithms:

- R. K. Ahuja, T. L. Magnanti, and J. B. Orlin, *Network Flows: Theory, Algorithms, and Applications*, Prentice Hall, 1993.

Linear programming and introduction to integer programming:

- D. Bertsimas and J. Tsitsiklis, *Introduction to Linear Optimization*, Athena Scientific, 1997.

## License

All rights reserved. See `LICENSE`.

The license covers the entire repository (slides, notes, code, and documentation). Public visibility on GitHub is not a grant of reuse: others may view or clone for personal reading only. Copying, redistribution, modification, commercial use, and reuse of the teaching materials are not permitted. Lecture slides remain copyright of their authors and Politecnico di Milano.
