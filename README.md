# Start-up Seminar (B4) - Machine-Learning 2025-06-04

**Author**: Shunta Kochi  
**Duration**: 2h (lecture + notebook exercises)



## Table of Contents

1. [Overview](#overview)  
2. [Technologies Used](#technologies-used)
3. [Directory Structure](#directory-structure)  
4. [Getting Started](#getting-started)

## Overview
This repository contains materials for a 2-hour seminar titled "Start-up Seminar for B4", delivered by Shunta Kochi on 2025-06-04. The seminar introduces undergraduate students to machine learning concepts and workflows through both lecture slides and hands-on exercises.

The contents are organized as follows:
- Lecture Slides(`slide/seminar-slide.md`)
- Exercises(`notebooks/ml_intro.ipynb`)


## Technologies Used
<p style="display: inline-block;">
  <img src=https://img.shields.io/badge/-Python-F2C63C.svg?logo=python&style=for-the-badge>
  <img src="https://img.shields.io/badge/-Jupyter-F37626.svg?logo=jupyter&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-Pandas-150458.svg?logo=pandas&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-NumPy-013243.svg?logo=numpy&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-Scikit--Learn-F7931E.svg?logo=scikit-learn&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-XGBoost-EC5520.svg?logo=apache&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-Matplotlib-11557C.svg?logo=plotly&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-Seaborn-42A5F5.svg?style=for-the-badge" />
  <img src="https://img.shields.io/badge/-Marp-1E1E1E.svg?logo=markdown&logoColor=white&style=for-the-badge" />
</p>



## Directory Structure
```
.
├── images
│   ├── cross-validation.drawio
│   ├── cross-validation.png
│   ├── hold-out.drawio
│   ├── hold-out.png
│   ├── label-encoding.drawio
│   ├── label-encoding.png
│   ├── onehot-encoding.drawio
│   ├── onehot-encoding.png
│   ├── workflow.drawio
│   └── workflow.png
├── notebooks
│   ├── ml_intro_answer.ipynb
│   └── ml_intro.ipynb
├── poetry.lock
├── poetry.toml
├── pyproject.toml
├── README.md
├── setup.sh
├── slide
│   └── seminar-slide.md
└── theme.css
```

## Getting Started

1. **Clone the repository:**
```bash
git clone git@github.com:Shunta6855/startup-seminar.git
cd startup-seminar
```

2. **Run the setup.sh**
```bash
bash ./setup.sh
```

3. **[macOS only] Install libomp for XGBoost parallelization support:**
```bash
brew install libomp
```

4. **Let's get started with the exercises!**