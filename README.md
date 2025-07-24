
# Sentiment Analysis Project

## Overview
This project performs **Sentiment Analysis** on text data using Python. It uses the **TextBlob** library to evaluate the sentiment polarity of textual content, classifying it as **positive, negative, or neutral**. This repository includes the Google Colab notebook (`sentiment_analysis.ipynb`) where the entire process is implemented.

---

## Steps Performed
1. **Data Collection**:
   - Load dataset (CSV with text data).
   - Example sources: Amazon product reviews, social media posts, etc.

2. **Data Processing**:
   - Clean text data (removing special characters).
   - Analyze sentiment using TextBlob.

3. **Visualization**:
   - Display sentiment polarity distribution.
   - Visualize results with **Matplotlib**.

4. **Results**:
   - Generate positive, negative, and neutral sentiment classification.
   - Provide insights and trends in data.

---

## Project Files
- **`sentiment_analysis.ipynb`**: Main notebook with all analysis steps.
- **`dataset.csv`** (optional): Dataset containing text data (upload or link to source).
- **`README.md`**: Project documentation.

---

## How to Run
### 1. Open the Notebook
- Use **Google Colab** or Jupyter Notebook to open `sentiment_analysis.ipynb`.

### 2. Install Required Libraries
```bash
!pip install textblob pandas matplotlib
!python -m textblob.download_corpora
```

### 3. Run the Notebook
- Execute all cells to perform sentiment analysis.

---

## Example Code
```python
from textblob import TextBlob

text = "I love using this product!"
analysis = TextBlob(text)
print(analysis.sentiment.polarity)  # Outputs polarity score
```

---

## Technologies Used
- **Python**: Main programming language.
- **TextBlob**: Sentiment analysis library.
- **Pandas**: Data handling.
- **Matplotlib**: Data visualization.

---

## Author
Harpreet Singh  
GitHub: https://github.com/Happy2301


