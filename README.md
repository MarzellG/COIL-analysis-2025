# COIL Pre/Post Survey Analysis

This repository contains Python code and a Google Colab notebook for analyzing pre- and post-survey data collected during a Collaborative Online International Learning (COIL) unit.

## Repository Structure

- `coil_survey_analysis.ipynb`: Google Colab notebook performing statistical analysis
- `README.md`: Project description (this file)

## Requirements

- Python 3.9+
- Libraries:
  - pandas
  - numpy
  - scipy
  - matplotlib (optional for visualizations)

All libraries are available by default in Google Colab.

## Usage

1. Open the Google Colab notebook.
2. Run all cells.
3. The notebook will:
   - Simulate sample pre/post participant scores
   - Perform paired t-tests
   - Calculate Cohen's d effect sizes
   - Display results and bar charts

If you have real participant-level data, replace the simulation step with actual data loading.

## Sample Dataset

The sample analysis uses the following pre/post mean and standard deviation data:

| Variable | Pre_Mean | Pre_SD | Post_Mean | Post_SD |
|:---------|:--------:|:------:|:---------:|:-------:|
| Cultural Self-Awareness | 3.13 | 0.68 | 3.37 | 0.61 |
| Knowledge of Cultural Worldview Frameworks | 2.50 | 0.68 | 2.93 | 0.52 |
| Empathy | 2.93 | 0.45 | 3.23 | 0.50 |
| Verbal and Nonverbal Communication | 2.83 | 0.65 | 3.03 | 0.49 |
| Curiosity | 2.47 | 0.63 | 2.90 | 0.76 |
| Openness | 2.90 | 0.71 | 3.03 | 0.72 |
| Overall Intercultural Knowledge and Competence | 2.79 | 0.63 | 3.08 | 0.60 |

**Note**: Replace with your actual survey data when available.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Citation

If you use this notebook or code for your project or publication, please cite:

> [Marzell Gray], \"COIL Pre/Post Survey Analysis Code,\" GitHub, 2025. Available: https://github.com/yourusername/coil-survey-analysis

---

Feel free to open an issue or pull request if you have questions or improvements!
