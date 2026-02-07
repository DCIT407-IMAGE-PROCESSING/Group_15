# Object Shape Enhancement Using Opening and Closing Operations

![Course](https://img.shields.io/badge/Course-DCIT407-2b6cb0) ![Python](https://img.shields.io/badge/Python-3.7%2B-3776ab) ![OpenCV](https://img.shields.io/badge/OpenCV-4.5%2B-5c3ee8) ![Semester](https://img.shields.io/badge/Semester-2025%2F2026-0ea5e9)

Morphological image processing project focused on Opening and Closing operations for noise removal, gap filling, and shape refinement in binary images.

**Course:** DCIT407 - Digital Image Processing  
**University:** University of Ghana  
**Semester:** Second Semester, 2025/2026

---

## Table of Contents
- [Overview](#overview)
- [Objectives](#objectives)
- [Key Features](#key-features)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Results & Discussion](#results--discussion)
- [Applications](#applications)
- [Team](#team)
- [License](#license)
- [Contact](#contact)

---

## Overview
This project demonstrates how morphological Opening and Closing improve object shapes in images by removing noise, filling gaps, and smoothing boundaries. The work combines theory, implementation, and visual results using Python and OpenCV.

## Objectives
- Explain the theory behind erosion, dilation, opening, and closing.
- Implement the operations and compare their effects.
- Demonstrate improvements on real-world image samples.

## Key Features
- Clean, modular structure for notebooks, source code, and reports
- Adjustable structuring elements (size and shape)
- Side-by-side visual comparisons
- Export-ready processed images

## Repository Structure
```
project-repository/
├── README.md
├── requirements.txt
├── docs/
│   └── README.md
├── images/
│   ├── README.md
│   ├── original/
│   ├── processed/
│   └── comparisons/
├── notebooks/
│   └── README.md
├── src/
│   └── README.md
└── reports/
    └── README.md
```

## Getting Started
### 1) Install Dependencies
```bash
pip install -r requirements.txt
```

### 2) Add the Notebook
Place your main notebook in notebooks/ (e.g., Object_Shape_Enhancement.ipynb).

### 3) Run the Notebook
```bash
jupyter notebook notebooks/Object_Shape_Enhancement.ipynb
```

## Results & Discussion
The notebook includes:
- Opening vs. closing comparisons
- Effects of different structuring elements
- Visual results on documents, medical, and industrial images

## Applications
| Domain | Use Case | Operation |
|---|---|---|
| Medical Imaging | Cell segmentation | Opening & Closing |
| Document Processing | Noise removal | Opening |
| Industrial Inspection | Defect detection | Closing |
| Biometrics | Fingerprint enhancement | Both |

## Team
| Name | Student ID | Role |
|---|---|---|
| Joy Owusu Ansah | 11341365 | Group Leader|
| Emelia Ampofo | 11288825 | Member |
| Sonia Selassie Dean-Snowden | 11120331 | Member |
| Samson Gyampoh | 11257581 | Member |
| Nyamekye Korsah | 11353306 | Member|
| Desmond Opoku Anane | 11126586 | Member |
| Reuben Addo | 11019527 | Member|

| Nyarko Rudolf | 11297285 |Member|

## License
Educational use only for DCIT407. Contact the team for any other use.

## Contact
| Team Member | GitHub | Email | Role |
|---|---|---|---|
| Joy Owusu Ansah | aduuuna | owusujoyansah@gmail.com | Group Leader |

**Course Instructor:** Prof. Ebenezer Owusu  
**Department:** Computer Science, University of Ghana, Legon