---
slug: github-supreme-court-voting-behavior
id: github-supreme-court-voting-behavior
title: Supreme Court Voting Behavior Analysis with Machine Learning
repo: justin-napolitano/Supreme-Court-Voting-Behavior
githubUrl: https://github.com/justin-napolitano/Supreme-Court-Voting-Behavior
generatedAt: '2025-11-24T21:36:36.431Z'
source: github-auto
summary: >-
  Explore voting behavior of U.S. Supreme Court justices using machine learning and case studies,
  with a focus on decision-making models.
tags:
  - python
  - machine learning
  - tensorflow
  - scikit-learn
  - pandas
  - data visualization
  - jupyter book
seoPrimaryKeyword: supreme court voting behavior analysis
seoSecondaryKeywords:
  - judicial decision-making models
  - case studies on voting patterns
  - python machine learning project
  - data analysis with pandas
  - jupyter book documentation
seoOptimized: true
topicFamily: datascience
topicFamilyConfidence: 0.9
kind: project
entryLayout: project
showInProjects: true
showInNotes: false
showInWriting: false
showInLogs: false
---

This repository contains research and analysis on the voting behavior of the United States Supreme Court justices. It explores different models of judicial decision-making, including the Legal Model and the Attitudinal Model, with a focus on case studies such as Masterpiece Cakeshop, Ltd. v. Colorado Civil Rights Commission.

## Features

- Comprehensive literature review and theoretical background on Supreme Court decision-making models.
- Detailed case studies analyzing voting patterns and ideological influences.
- Machine learning code for predicting justice votes based on historical data.
- Structured Jupyter Book format for documentation and research dissemination.

## Tech Stack

- Markdown and Jupyter Book for documentation.
- Python with TensorFlow and scikit-learn for machine learning analysis.
- Pandas for data manipulation.
- Seaborn and Matplotlib for data visualization.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- pip package manager

### Installation

1. Clone the repository:

```bash
git clone https://github.com/justin-napolitano/Supreme-Court-Voting-Behavior.git
cd Supreme-Court-Voting-Behavior
```

2. (Optional) Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

3. Install required Python packages:

```bash
pip install -r requirements.txt
```

*(Note: requirements.txt is assumed to be created with necessary packages like tensorflow, pandas, scikit-learn, seaborn, matplotlib, shap)*

### Running the Machine Learning Analysis

The ML scripts are located in the `book/ml/` directory. To run the justice-centric or case-centric prediction scripts, execute the respective Python files after ensuring the data files are in place under the `data/` directory.

Example:

```bash
python book/ml/ml-justice-centric.py
```

### Building the Documentation

This project uses Jupyter Book for documentation. To build the book:

```bash
pip install -U jupyter-book
jupyter-book build book/
```

Open the generated HTML files in `book/_build/html`.

## Project Structure

```
Supreme-Court-Voting-Behavior/
├── book/                     # Jupyter Book source files
│   ├── intro.md              # Introduction and background
│   ├── legal-model/          # Chapters on the Legal Model
│   ├── attitudinal-model/    # Chapters on the Attitudinal Model
│   ├── masterpiece-cake/     # Case study on Masterpiece Cakeshop
│   ├── ml/                   # Machine learning scripts and notebooks
│   ├── bibliography/         # Bibliographic references
│   ├── _config.yml           # Jupyter Book configuration
│   ├── _toc.yml              # Table of contents
│   └── ...
├── SupremeCourtDescionMaking.docx  # Research document
├── data/                     # Data files for ML
└── README.md                 # This file
```

## Future Work / Roadmap

- Expand and improve the literature review sections.
- Enhance documentation and code comments for ML scripts.
- Add executable Jupyter notebooks for ML analyses.
- Refine and validate machine learning models for voting prediction.
- Include installation and configuration guides for Jupyter Book tools.
- Extend case studies and include more recent Supreme Court decisions.
- Improve data preprocessing and feature engineering for ML models.

---

For contributions or questions, please contact Justin Napolitano at contribute@court-behavior.io.


---

# License

This project does not currently specify a license. Please contact the author for permissions.


