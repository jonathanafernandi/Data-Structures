# Data-Structures

A C case study for the **COMP6048001 – Data Structures** course (Bina Nusantara University, School of Computer Science), implementing a **Red-Black Tree** insertion algorithm and an interactive **AVL Tree** program with insert, delete, and traversal operations.

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Author](#author)
- [Notes](#notes)

## Overview

This project implements two self-balancing binary search tree structures:

1. **Red-Black Tree**: builds a tree from a fixed insertion sequence, maintaining color and rotation invariants, then prints the result via inorder traversal.
2. **AVL Tree**: an interactive program supporting insertion, deletion, and traversal (preorder, inorder, postorder) with automatic height-based rebalancing.

## Project Structure

```
Data-Structures/
├── src/
│   ├── algorithm-1.cpp   # Red-Black Tree insertion + inorder traversal
│   └── algorithm-2.cpp   # AVL Tree insert/delete/traversal
├── docs/
│   └── 2602089143-JonathanAlvindoFernandi_AoL-CaseStudy.pdf # Manual tree-building diagrams
├── .gitignore
└── README.md
```

## Getting Started

### Prerequisites

- A C compiler such as `g++` (via [MinGW](https://www.mingw-w64.org/) on Windows, or pre-installed on Linux/macOS)
- Git

### Clone the Repository

```bash
git clone https://github.com/jonathanafernandi/Data-Structures.git
cd Data-Structures
```

### Compile

```bash
g++ src/algorithm-1.cpp -o algorithm-1
g++ src/algorithm-2.cpp -o algorithm-2
```

## Usage

Run the Red-Black Tree program:

```bash
./algorithm-1
```

Expected output:

```
Inorder Traversal of Created Tree
3 5 18 21 22 29 41 45 48 51
```

Run the AVL Tree program:

```bash
./algorithm-2
```

```
1. Insertion
2. Deletion
3. Traversal
4. Exit
Choose: 
```

## Author

**Jonathan Alvindo Fernandi**  
Computer Science, School of Computer Science, Bina Nusantara University  
Course: COMP6048001 – Data Structures (Class LC01)

## Notes

- All solutions are implemented in C using dynamic memory allocation (`malloc`) for tree nodes.
