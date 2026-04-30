# Movie Feedback Analysis Project

## Overview
This is a comprehensive data science and big data analytics (DSBDA) project that analyzes movie feedback data. The project performs data cleaning, exploratory data analysis, visualization, and predictive modeling on movie feedback datasets.

## Project Structure
- **movie_feedback_analysis.ipynb** - Main Jupyter Notebook containing all analysis, visualizations, and models
- **movie_feedback_raw.csv** - Raw movie feedback dataset (before cleaning)
- **movie_feedback_cleaned.csv** - Cleaned and processed dataset ready for analysis
- **fig0_actual_vs_predicted.png** - Prediction accuracy visualization
- **fig1_bar_genre.png** - Genre distribution bar chart
- **fig2_line_monthly.png** - Monthly trend analysis
- **fig3_pie_platform.png** - Platform distribution pie chart
- **fig4_heatmap.png** - Correlation heatmap
- **fig5_scatter.png** - Scatter plot analysis
- **fig6_dashboard.png** - Dashboard overview

## Features
✨ Data Cleaning & Preprocessing
✨ Exploratory Data Analysis (EDA)
✨ Statistical Analysis
✨ Data Visualization (multiple chart types)
✨ Machine Learning Model Development
✨ Predictive Analytics
✨ Dashboard Generation

## Prerequisites
- Python 3.8+
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- plotly (optional, for interactive visualizations)

## Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/sejalambekar04/dsbda-project.git
cd dsbda-project
```

### 2. Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Required Dependencies
```bash
pip install -r requirements.txt
```

Or install packages individually:
```bash
pip install jupyter pandas numpy matplotlib seaborn scikit-learn plotly
```

## Running the Project

### Option 1: Using Jupyter Notebook
```bash
jupyter notebook movie_feedback_analysis.ipynb
```

Then:
1. Open your browser (usually http://localhost:8888)
2. Navigate to and click on **movie_feedback_analysis.ipynb**
3. Run cells sequentially using Shift+Enter or use "Run All" from the Cell menu

### Option 2: Using JupyterLab
```bash
jupyter lab movie_feedback_analysis.ipynb
```

## Project Workflow

1. **Data Loading** - Import raw CSV data
2. **Data Cleaning** - Handle missing values, outliers, and data validation
3. **Exploratory Analysis** - Understand data distributions and relationships
4. **Visualization** - Create multiple visualization types:
   - Bar charts (genre analysis)
   - Line charts (temporal trends)
   - Pie charts (platform distribution)
   - Heatmaps (correlation analysis)
   - Scatter plots (relationships)
5. **Statistical Analysis** - Perform descriptive and inferential statistics
6. **Model Development** - Build predictive models
7. **Results & Dashboard** - Generate visualizations and summary dashboard

## Key Datasets

### movie_feedback_raw.csv
Original dataset containing raw movie feedback data with potential inconsistencies

### movie_feedback_cleaned.csv
Processed and cleaned version ready for analysis, with:
- Missing values handled
- Outliers addressed
- Data standardization applied
- Feature engineering completed

## Output Visualizations

- **fig0_actual_vs_predicted.png** - Model performance metrics
- **fig1_bar_genre.png** - Distribution of movies by genre
- **fig2_line_monthly.png** - Feedback trends over time
- **fig3_pie_platform.png** - Platform usage breakdown
- **fig4_heatmap.png** - Feature correlation matrix
- **fig5_scatter.png** - Relationship between key variables
- **fig6_dashboard.png** - Executive summary dashboard

## Requirements File

Create a **requirements.txt** file:
```
jupyter==1.0.0
pandas==1.5.3
numpy==1.24.0
matplotlib==3.7.1
seaborn==0.12.2
scikit-learn==1.3.0
plotly==5.14.0
```

## Troubleshooting

**Issue: Jupyter Notebook not starting**
- Ensure Jupyter is installed: `pip install jupyter`
- Try: `jupyter notebook --ip=127.0.0.1`

**Issue: Missing module errors**
- Install the missing package: `pip install [package_name]`
- Restart the Jupyter kernel after installation

**Issue: Data file not found**
- Ensure CSV files are in the same directory as the notebook
- Check file paths in the notebook match actual file names

## Language & Technologies
- **Language**: Jupyter Notebook (Python)
- **Data Processing**: pandas, numpy
- **Visualization**: matplotlib, seaborn, plotly
- **Machine Learning**: scikit-learn

## Author
- **sejalambekar04**

## License
This project is open source and available under the MIT License.

## Contributing
Contributions are welcome! Please feel free to submit pull requests or open issues for bugs and feature requests.

## Support
For questions or issues, please open an issue on the GitHub repository.

---

**Last Updated**: April 30, 2026
