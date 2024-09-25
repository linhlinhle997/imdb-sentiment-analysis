# Sentiment Analysis on IMDb Dataset
This project aims to perform sentiment analysis on the IMDb dataset, classifying movie reviews as positive or negative using various machine learning algorithms.

## Feature Engineering
- **Label Encoding**: Converted categorical sentiment labels (positive/negative) into numerical format to facilitate easier processing by machine learning algorithms.
- **TF-IDF Vectorization**: Employed TF-IDF vectorization to transform cleaned text data into a numerical representation, highlighting the importance of words in each review relative to the entire dataset.


## Model Training and Evaluation
- **Decision Tree Classifier**
- **Random Forest Classifier**

## Requirements
Ensure you have the necessary dependencies by installing the requirements
``` bash
pip install -r requirements.txt
```

## Usage
1. Clone the repository:
``` bash
git clone https://github.com/linhlinhle997/imdb-sentiment-analysis.git
```
2. Navigate to the project directory:
``` bash
cd imdb-sentiment-analysis
```
3. Open the Jupyter Notebook and execute the cells to analyze sentiment in the IMDB dataset