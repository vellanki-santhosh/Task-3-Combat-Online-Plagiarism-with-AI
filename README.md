# SM Task 3

This project contains a Jupyter notebook that implements a plagiarism detection pipeline. The notebook compares documents using three similarity methods, combines the scores into a final verdict, and generates visual and tabular reports.

## What It Does

- Cleans and normalizes text with tokenization, stop-word removal, and lemmatization.
- Computes similarity with TF-IDF cosine similarity, a RapidFuzz-based fuzzy ensemble, and Jaccard n-gram similarity.
- Combines the scores into a single plagiarism severity label.
- Produces an HTML report, CSV results, and visualizations such as a heatmap, score breakdown chart, and severity pie chart.

## Files

- `SM_task3.ipynb` - main notebook with the full pipeline and sample runs.
- `reports/` - generated output folder created by the notebook.
- `starter_docs/` - sample text files created by the notebook for demo runs.

## Requirements

The notebook installs these Python packages:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- nltk
- rapidfuzz

## How to Run

1. Open `SM_task3.ipynb` in VS Code or Jupyter.
2. Run the cells from top to bottom.
3. The notebook will download the required NLTK resources the first time it runs.
4. Review the generated outputs in the `reports/` folder.

## Output Files

The notebook can generate the following files:

- `reports/plagiarism_report.html`
- `reports/results.csv`
- `reports/similarity_heatmap.png`
- `reports/score_breakdown.png`
- `reports/severity_pie.png`

## Notes

- The notebook includes a built-in sample dataset for demonstration.
- You can also load your own `.txt` files by using the `load_txt_files()` helper in the notebook.# Task-3-Combat-Online-Plagiarism-with-AI
