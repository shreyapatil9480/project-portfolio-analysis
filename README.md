# Project Portfolio Analysis for Business & Data Analysts

This repository contains a self-contained analytics project designed to showcase data analysis, visualization, and predictive modeling skills. It is ideal for candidates pursuing roles such as business analyst, program manager, or data analyst. The project includes:

- **Synthetic dataset**: A CSV file (`project_data.csv`) representing 500 fictional projects with features such as budget, duration, team size, complexity, risk level, stakeholder engagement, and historical success rate.
- **Exploratory analysis**: A Jupyter Notebook (`analysis.ipynb`) that loads the dataset, performs exploratory data analysis (EDA) using descriptive statistics and visualizations (histograms, correlation matrix), and highlights relationships between features and project success.
- **Predictive modeling**: The notebook builds and evaluates two predictive models—Logistic Regression and Random Forest—to estimate the probability of project success. It includes data preprocessing (one‑hot encoding, scaling), model training, evaluation metrics, confusion matrices, and feature importance plots.
- **Requirements file**: A `requirements.txt` file listing the Python dependencies needed to reproduce the analysis.

## Dataset Overview

The synthetic dataset simulates a portfolio of projects across different domains (software development, infrastructure, marketing, research, data science, operations). Each row corresponds to a project with the following columns:

| Column | Description |
| --- | --- |
| `project_id` | Unique identifier for each project |
| `project_type` | Categorical type of project (e.g. Software Development, Marketing) |
| `budget_kUSD` | Project budget in thousands of US dollars |
| `duration_months` | Duration of the project in months |
| `team_size` | Number of team members involved |
| `complexity` | Complexity rating on a scale from 1 (low) to 5 (high) |
| `risk_level` | Risk level on a scale from 1 (low) to 5 (high) |
| `stakeholder_engagement` | Stakeholder engagement rating on a scale from 1 (low) to 5 (high) |
| `prev_success_rate` | Historical success rate of similar projects (0–1) |
| `project_success` | Target variable: 1 if the project was successful, 0 otherwise |

## How to Use This Project

1. **Clone the repository** (or download the ZIP file if preferred):

   ```bash
   git clone https://github.com/yourusername/project-portfolio-analysis.git
   cd project-portfolio-analysis
   ```

2. **Set up a Python environment**. It is recommended to use a virtual environment via `venv` or `conda`.

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:

   ```bash
   jupyter notebook analysis.ipynb
   ```

   The notebook will walk you through the exploratory analysis, visualizations, data preprocessing steps, and predictive modeling. You can modify and extend the notebook as needed.

## Extending the Project

This project is intentionally open‑ended and can be extended to demonstrate more advanced skills:

- **Feature engineering**: Add new synthetic features such as resource allocation ratios, milestones achieved, or stakeholder satisfaction scores.
- **Hyperparameter tuning**: Use grid search or random search to optimize model hyperparameters.
- **Model comparison**: Introduce additional algorithms (e.g. Gradient Boosting, XGBoost) and compare their performance.
- **Dashboards**: Build an interactive dashboard using tools like Dash or Streamlit to visualize key metrics and model outcomes.

Feel free to fork the repository and build upon it. Pull requests are welcome!

## License

This project is released under the MIT License. See the [LICENSE](LICENSE) file for details.
