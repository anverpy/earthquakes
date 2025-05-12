# 🌎 Earthquake Data Analysis

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat&logo=python)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter)](https://jupyter.org/)
[![GitHub license](https://img.shields.io/badge/License-MIT-brightgreen?style=flat)](LICENSE.md)
[![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-blue?style=flat&logo=pandas)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5%2B-blue?style=flat&logo=python)](https://matplotlib.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-latest-orange?style=flat&logo=scikit-learn)](https://scikit-learn.org/)
[![Plotly](https://img.shields.io/badge/Plotly-Interactive-informational?style=flat&logo=plotly)](https://plotly.com/)

<p align="center">
  <img src="Graphics/earthquake_heatmap.png" width="1000"/>

</p>

Welcome! This repository showcases a robust, end-to-end data science workflow for analyzing global earthquake data. If you're looking for a project that combines real-world data, advanced analytics, and modern Python visualization, you're in the right place.

> **📱 Interactive Dashboard Available!**<br>This analysis powers [Earthquake Analysis Web App](https://github.com/anverpy/scraping-and-data-analysis) , which provides **real-time visualization** and monitoring of seismic events.<br>Check it out to see this analysis in action!

<br>

# 📋 Table of Contents
- [🌎 Earthquake Data Analysis](#-earthquake-data-analysis)
- [📋 Table of Contents](#-table-of-contents)
  - [🚀 Project Highlights](#-project-highlights)
  - [📁 Files](#-files)
  - [🛠️ Requirements](#️-requirements)
  - [📝 How to Use](#-how-to-use)
  - [🎨 Visual Outputs](#-visual-outputs)
  - [💡 Insights](#-insights)
  - [📊 Visual Showcase](#-visual-showcase)
  - [🔄 Related Projects](#-related-projects)
    - [➡️🌐 Earthquake Analysis Dashboard](#️-earthquake-analysis-dashboard)
  - [🤝 About the Author](#-about-the-author)
  - [📜 License](#-license)

<br>

## 🚀 Project Highlights
- **Data Cleaning & Preprocessing:**
  - Advanced missing value imputation (KNN)
  - Feature engineering for magnitude and depth
  - Outlier detection and labeling
- **Exploratory Data Analysis:**
  - Comprehensive statistical summaries 📊
  - Correlation analysis and insights
  - Event type breakdowns
- **Visualizations:**
  - Publication-ready plots in dark mode
  - Interactive Plotly charts (HTML export)
  - Folium heatmaps for spatial analysis
- **Reproducible Workflow:**
  - Every step is documented and executable in the notebook

## 📁 Files
- `notebook.ipynb`: Main analysis notebook (open with VS Code or Jupyter)
- `dataframe.csv`: Raw earthquake dataset
- `cleaned_dataframe.csv`: Cleaned and processed dataset
- `*.html`: Interactive visualizations
- `Graphics/`: Folder containing all static visualizations (PNG files)

## 🛠️ Requirements
- Python 3.8+
- Install all dependencies with:
```bash
pip install -r requirements.txt
```

## 📝 How to Use
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Place your earthquake data as `dataframe.csv` in the root directory (or use the provided sample).
4. Open `notebook.ipynb` in VS Code or Jupyter.
5. Run all cells to reproduce the analysis and generate visualizations.

## 🎨 Visual Outputs
- Magnitude and depth distributions
- Boxplots and histograms by event type
- Correlation heatmaps
- Interactive bar charts (Plotly)
- Global earthquake heatmap (Folium)

## 💡 Insights
- Discover key patterns in seismic activity, including the relationship between magnitude, depth, and event type
- Special focus on the correlation between horizontal error, RMS, and magnitude, with interpretative notes

## 📊 Visual Showcase

<p align="center">
  <a href="earthquake_heatmap.html" download>
    <img src="Graphics/earthquake_heatmap.png" alt="Earthquake Heatmap (Interactive)" width="600"/>
    <br>
    <i>👆 Click to download the interactive heatmap (Earthquake Heatmap)</i>
  </a>
</p>

<p align="center">
  <a href="event_type_distribution_plotly.html" download>
    <img src="Graphics/event_type_distribution.png" alt="Event Type Distribution (Interactive)" width="600"/>
    <br>
    <i>👆 Click to download the interactive visualization (Event Type Distribution)</i>
  </a>
</p>

<p align="center">
  <i>More charts available in the notebook!</i>
</p>

## 🔄 Related Projects
### ➡️[🌐 Earthquake Analysis Dashboard](https://github.com/anverpy/scraping-and-data-analysis)

<p align="center">
  <img src="https://i.imgur.com/oHuO5Mw.png" alt="Earthquake Dashboard Banner" width="800"/>
</p>

The Earthquake Analysis Dashboard is a Streamlit-based web application that:

- Provides an **interactive interface** to explore the data processed in this notebook
- Features real-time **filtering by magnitude, depth, location, and time**
- Includes advanced visualizations including **interactive maps and clustering analysis**
- Allows users to perform their own analysis without coding knowledge

The dashboard uses the data processing pipeline and visualization techniques developed in this project, with additional real-time capabilities.

## 🤝 About the Author

Andrés V. — Data Science & Analytics | 2025

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/andresvergarav/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-brightgreen?style=flat&logo=github)](https://github.com/anverpy)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=flat&logo=gmail)](mailto:andresw206@gmail.com)

---

*If you're interested in data-driven problem solving or collab, feel free to connect or reach out!* 🚀

## 📜 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details. This means you can freely use, modify, distribute, and build upon this work for both personal and commercial purposes, as long as you provide appropriate attribution.
