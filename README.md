# Phishing Email Analysis

Data analysis and visualization project analyzing phishing and legitimate emails using Python, Pandas, Seaborn, and WordCloud.

## Overview

This project analyzes a dataset of approximately 82,500 emails labeled as either spam (phishing) or legitimate. The analysis demonstrates data import, exploration, visualization, and text analysis techniques to understand patterns and differences between phishing and legitimate emails.

## Dataset

**Source:** [Phishing Email Dataset on Kaggle](https://www.kaggle.com/datasets/naserabdullahalam/phishing-email-dataset/data)

**File Used:** CEAS_08.csv

**Citation:**
```
Alam, Naser Abdullah. (2024). Phishing Email Dataset. Kaggle.
https://www.kaggle.com/datasets/naserabdullahalam/phishing-email-dataset
```

## Features

The analysis includes:

- **Data Import & Exploration**
  - Loading CSV data with Pandas
  - Exploring dataset structure and statistics
  - Analyzing email characteristics (body length, subject length)
  - Identifying missing values and data quality issues

- **Data Visualizations (Seaborn)**
  - Distribution of phishing vs legitimate emails (count plot)
  - Email body length distribution (histogram with KDE)
  - Subject length comparison (box plot)
  - Body length distribution (violin plot)

- **Text Analysis (WordCloud)**
  - Word cloud for phishing emails
  - Word cloud for legitimate emails
  - Side-by-side comparison visualization

## Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **WordCloud** - Text visualization

## Installation

### Requirements

Install the required packages:

```bash
pip install pandas matplotlib seaborn wordcloud
```

Or if using Google Colab, only WordCloud needs to be installed:

```python
!pip install wordcloud
```

## Usage

### Local Setup

1. Clone this repository:
```bash
git clone https://github.com/BengalPirate/Data_analysis_on_Phishing_email_dataset.git
cd Data_analysis_on_Phishing_email_dataset
```

2. Download the CEAS_08.csv dataset from Kaggle and place it in the `archive/` folder

3. Open the Jupyter Notebook:
```bash
jupyter notebook "Data analysis and visualization.ipynb"
```

4. Run all cells to execute the analysis

### Google Colab Setup

1. Upload the notebook to [Google Colab](https://colab.research.google.com)

2. Create an `archive` folder and upload the CEAS_08.csv file

3. Install WordCloud:
```python
!pip install wordcloud
```

4. Run all cells

## Project Structure

```
.
├── archive/
│   └── CEAS_08.csv              # Phishing email dataset (not included)
├── Data analysis and visualization.ipynb  # Main analysis notebook
└── README.md                     # Project documentation
```

## Key Findings

The analysis reveals:

- Clear differences in language patterns between phishing and legitimate emails
- Distinct characteristics in email body and subject lengths
- Common keywords and phrases used in phishing attempts
- Distribution patterns that could be useful for detection systems

## Learning Objectives

This project demonstrates:

1. ✅ Import and explore CSV data using Pandas
2. ✅ Create meaningful visualizations using Seaborn to understand data distributions and patterns
3. ✅ Generate word clouds to visualize common words in email content, highlighting differences between phishing and legitimate emails

## Visualizations

The notebook generates multiple visualizations including:

- Email type distribution charts
- Statistical comparisons of email characteristics
- Word clouds showing most common words in phishing vs legitimate emails
- Side-by-side visual comparisons

## License

This project is for educational purposes. Please cite the original dataset creators when using this work:

```
Alam, Naser Abdullah. (2024). Phishing Email Dataset. Kaggle.
https://www.kaggle.com/datasets/naserabdullahalam/phishing-email-dataset
```

## Author

Brandon Newton

## Acknowledgments

- Dataset provided by Naser Abdullah Alam via Kaggle
- CEAS (Collaboration, Electronic messaging, Anti-Abuse and Spam) Challenge 2008
