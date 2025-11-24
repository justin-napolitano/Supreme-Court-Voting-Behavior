---
slug: github-supreme-court-voting-behavior-note-technical-overview
id: github-supreme-court-voting-behavior-note-technical-overview
title: Supreme Court Voting Behavior
repo: justin-napolitano/Supreme-Court-Voting-Behavior
githubUrl: https://github.com/justin-napolitano/Supreme-Court-Voting-Behavior
generatedAt: '2025-11-24T18:48:11.177Z'
source: github-auto
summary: >-
  This repo analyzes U.S. Supreme Court justices' voting behavior. It dives into
  judicial decision-making models, such as the Legal and Attitudinal Models,
  with case studies like Masterpiece Cakeshop.
tags: []
seoPrimaryKeyword: ''
seoSecondaryKeywords: []
seoOptimized: false
topicFamily: null
topicFamilyConfidence: null
kind: note
entryLayout: note
showInProjects: false
showInNotes: true
showInWriting: false
showInLogs: false
---

This repo analyzes U.S. Supreme Court justices' voting behavior. It dives into judicial decision-making models, such as the Legal and Attitudinal Models, with case studies like Masterpiece Cakeshop.

## Key Components

- **Documentation**: Uses Jupyter Book for structured presentation.
- **Machine Learning**: Code to predict justice votes with TensorFlow and scikit-learn.
- **Data Handling**: Leverages Pandas for data manipulation and visualization with Seaborn and Matplotlib.

## Quick Start

1. **Clone the repo**:

   ```bash
   git clone https://github.com/justin-napolitano/Supreme-Court-Voting-Behavior.git
   cd Supreme-Court-Voting-Behavior
   ```

2. **Set up environment** (optional):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

## Gotchas

Ensure data files are in the `data/` directory before running ML scripts. To run predictions, execute:

```bash
python book/ml/ml-justice-centric.py
```

Building the documentation entails installing Jupyter Book and running the build command.
