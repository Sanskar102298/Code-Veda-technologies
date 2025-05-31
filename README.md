# Code-Veda-Technologies
# Stock Market Price Analysis Project

This project implements data preprocessing, sentiment analysis, and linear regression modeling for stock market price prediction and sentiment analysis of market-related text data.
All required files have been attached to this repository, and the assigned tasks have been completed; please note that some elements may be subject to minor revisions or updates
Project Structure
       stock-market-analysis
 ┣ 📜 data_cleaning.py
 ┣ 📜 SentimentanalysisGC.py
 ┣ 📜 LinearRegression.py
 ┣ 📜 Cleaned_Stock_Prices.csv
 ┣ 📜 Cleaned_Sentiment_Dataset.csv
 ┗ 📜 Preprocessed_Sentiment_Dataset.csv
```

## Data Processing Pipeline

### 1. Data Cleaning (`data_cleaning.py`)
- Loads raw stock price dataset
- Handles missing values using median imputation
- Removes duplicate entries
- Standardizes date and symbol columns
- Outputs cleaned data to `Cleaned_Stock_Prices.csv`

Key operations:
```python
- Missing value imputation
- Date standardization
- Symbol standardization
- Duplicate removal
```

### 2. Sentiment Analysis (`SentimentanalysisGC.py`)
- Preprocesses text data using NLTK
- Implements lemmatization and stemming
- Removes stopwords and special characters
- Generates sentiment analysis metrics

Features:
- Text preprocessing
- Sentiment classification
- Statistical analysis
- Visualization of sentiment distribution

### 3. Linear Regression Model (`LinearRegression.py`)
- Implements simple linear regression
- Predicts closing prices based on opening prices
- Includes model evaluation metrics
- Visualizes predictions vs actual values

Model metrics:
- Mean Squared Error (MSE)
- R-squared (R²)
- Regression line visualization

## Requirements

```
pandas==2.0.3
numpy
scikit-learn
matplotlib
nltk
tqdm
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/stock-market-analysis.git
cd stock-market-analysis
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage

1. Run data cleaning:
```bash
python data_cleaning.py
```

2. Run sentiment analysis:
```bash
python SentimentanalysisGC.py
```

3. Run linear regression:
```bash
python LinearRegression.py
```

## Output Files

- `Cleaned_Stock_Prices.csv`: Cleaned stock market data
- `Preprocessed_Sentiment_Dataset.csv`: Processed sentiment analysis results
- `SLR_Plot.jpeg`: Linear regression visualization

## Model Performance

The linear regression model evaluates:
- Stock price predictions
- Model accuracy metrics
- Visualization of predictions vs actual values

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments

- NLTK for natural language processing
- scikit-learn for machine learning implementation
- pandas for data manipulation
