# Code-Alpha_Sentiment_Analysis

A comprehensive **Sentiment Analysis project** developed using **Python**, **Pandas**, **Matplotlib**, **Seaborn**, and **VADER Sentiment Analysis**. This project analyzes product reviews, determines customer sentiment, visualizes sentiment patterns, and exports the results for further analysis.

---

## Project Overview

This project performs sentiment analysis on product reviews using the **VADER (Valence Aware Dictionary and Sentiment Reasoner)** sentiment analyzer.

The system automatically:

* Cleans review text
* Calculates sentiment scores
* Classifies reviews as Positive, Negative, or Neutral
* Generates visual dashboards
* Exports results to a CSV file

---

## Project Objectives

* Perform text preprocessing.
* Analyze customer reviews using VADER.
* Calculate sentiment scores.
* Classify sentiments automatically.
* Visualize sentiment distributions.
* Compare sentiment across products.
* Export sentiment results.

---

## Repository Structure

```text
Code-Alpha_Sentiment_Analysis/
│
├── Code Alpha Sentiment Analysis (Task 4).py
├── sentiment_analysis.png
├── sentiment_results.csv
├── README.md
└── requirements.txt
```

---

## Technologies Used

* Python 3
* Pandas
* Matplotlib
* Seaborn
* VADER Sentiment Analyzer
* Regular Expressions (re)

---

## Dataset

This project uses a manually created dataset containing product reviews from four products:

* Laptop Pro X
* Wireless Buds
* Smart Watch
* Tablet Z

The dataset contains:

* Positive reviews
* Negative reviews
* Neutral reviews

A total of **24 customer reviews** are analyzed.

---

## Text Preprocessing

The following preprocessing steps are performed:

* Convert text to lowercase.
* Remove unwanted special characters.
* Preserve punctuation required by VADER.
* Clean and standardize review text.

---

## Sentiment Analysis

VADER calculates the following sentiment scores:

* Negative Score (neg)
* Neutral Score (neu)
* Positive Score (pos)
* Compound Score

### Sentiment Classification

| Compound Score         | Sentiment |
| ---------------------- | --------- |
| ≥ 0.05                 | Positive  |
| ≤ -0.05                | Negative  |
| Between -0.05 and 0.05 | Neutral   |

---

## Dashboard Visualizations

The project generates a sentiment dashboard containing:

### 1. Overall Sentiment Distribution

* Bar chart showing the number of positive, neutral, and negative reviews.

### 2. Sentiment Share

* Pie chart representing sentiment percentages.

### 3. Compound Score by Product

* Box plot showing sentiment score distribution for each product.

### 4. Sentiment Breakdown per Product

* Stacked bar chart comparing positive, neutral, and negative reviews across products.

---

## Output Files

The script generates:

```text
sentiment_analysis.png
```

Visualization dashboard.

```text
sentiment_results.csv
```

Exported sentiment scores and classifications.

---

## Console Output

The program displays:

* Product name
* Review text
* Compound score
* Sentiment label
* Sentiment distribution
* Average sentiment score per product

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/AishaDataScientist/Code-Alpha_Sentiment_Analysis.git
```

### 2. Navigate to the Project Folder

```bash
cd Code-Alpha_Sentiment_Analysis
```

### 3. Install Required Libraries

```bash
pip install pandas matplotlib seaborn vaderSentiment
```

### 4. Run the Script

```bash
python "Code Alpha Sentiment Analysis (Task 4).py"
```

---

## Required Libraries

```text
pandas
matplotlib
seaborn
vaderSentiment
```

You can also install them using:

```bash
pip install pandas matplotlib seaborn vaderSentiment
```

---

## Example Output

The final dataset contains:

| Product       | Compound Score | Sentiment |
| ------------- | -------------- | --------- |
| Laptop Pro X  | 0.86           | Positive  |
| Wireless Buds | -0.72          | Negative  |
| Smart Watch   | 0.78           | Positive  |
| Tablet Z      | -0.64          | Negative  |

---

## Learning Outcomes

This project demonstrates:

* Natural Language Processing (NLP)
* Sentiment Analysis
* Text Preprocessing
* VADER Sentiment Analysis
* Data Visualization
* Data Exporting
* Python Programming
* Customer Review Analysis

---

## Future Improvements

* Analyze larger datasets.
* Use real customer reviews from e-commerce websites.
* Apply machine learning sentiment models.
* Implement word clouds.
* Build an interactive dashboard using Streamlit.
* Add real-time sentiment prediction.

---

## Output Preview

After execution, the following files are generated:

```text
sentiment_analysis.png
sentiment_results.csv
```

To display the dashboard image in GitHub:

```markdown
![Sentiment Dashboard](sentiment_analysis.png)
```

---

---

## Author

**Aisha Arif**

GitHub: https://github.com/AishaDataScientist

---
 If you found this project useful, consider giving it a star on GitHub!
