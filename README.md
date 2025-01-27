# find-new-clients-for-your-business-by-monitoring-crunchbase

# Crunchbase Lead Generator

This project is a Python-based tool that scrapes company data from Crunchbase and uses machine learning to identify potential leads based on funding information. The tool employs Selenium for web scraping and a Random Forest classifier for predictive modeling.

## Features

- Scrapes company data from Crunchbase, including funding amounts, industries, locations, employee counts, and founding years.
- Generates sample data for testing purposes.
- Performs Exploratory Data Analysis (EDA) to visualize funding distributions, industry counts, and more.
- Trains a Random Forest model to predict the likelihood of a company being a potential lead based on its features.
- Identifies and lists potential leads based on a specified probability threshold.

## Prerequisites

- Python 3.x
- Required Python packages:
  - pandas
  - numpy
  - selenium
  - beautifulsoup4
  - seaborn
  - matplotlib
  - scikit-learn

You can install the required packages using pip:

```bash
pip install pandas numpy selenium beautifulsoup4 seaborn matplotlib scikit-learn
```

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/crunchbase-lead-generator.git
   cd crunchbase-lead-generator
   ```

2. Ensure you have the Chrome WebDriver installed and available in your system's PATH. You can download it from [ChromeDriver](https://sites.google.com/chromium.org/driver/).

## Usage

1. Run the script:

   ```bash
   python crunchbase_lead_generator.py
   ```

2. The script will attempt to scrape data from Crunchbase. If it fails, it will fall back to generating sample data.

3. The output will include:
   - A summary of the collected data.
   - Visualizations from the Exploratory Data Analysis.
   - Model performance metrics.
   - A list of potential leads based on the trained model.

## Example Output

The script will print the number of companies collected, display EDA visualizations, and show the top potential leads based on the model's predictions.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Selenium](https://www.selenium.dev/) for web scraping.
- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/) for HTML parsing.
- [Scikit-learn](https://scikit-learn.org/) for machine learning.

