# Statistical-A-B-Test-Analysis-Cookie-Cats-Mobile-Game

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Data Analysis](https://img.shields.io/badge/Domain-Product_Analytics-success.svg)

## Overview
This repository contains a complete end-to-end A/B testing analysis for a mobile puzzle game ("Cookie Cats"). The objective of the experiment was to determine the business and product impact of moving the first time-gate from **Level 30 (Control)** to **Level 40 (Treatment)**. 

The analysis evaluates how this change affects player behavior, specifically focusing on continuous engagement (total game rounds) and binary retention metrics (Day 1 and Day 7 returning users).

## Repository Structure
```text
├── data/
│   └── cookie_cats.csv             # The raw dataset containing user A/B test results
├── notebook/
│   └── ab_test.ipynb          # Jupyter notebook containing the full EDA and statistical testing
└── README.md
