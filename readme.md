# Evaluating BrailleR and its effective usage

### BrailleR intro
BrailleR is a relatively new R package, released in 2023, designed to improve accessibility to the R programming environment for blind and visually impaired users. The package enhances usability by converting visual outputs, such as plots, into text-based descriptions (alt-text) that can be accessed through screen readers.

The aim of our project is to demonstrate the functionality of BrailleR and evaluate its effectiveness and accessibility by assessing the quality of the alt-text it generates. To achieve this, we will create and analyze alt-text for several commonly used visualizations, including bar plots, pie charts, histograms, and heatmaps. Effective alt-text should provide both concise and detailed descriptions, accurately translate visual data into meaningful text, and avoid excessive use of keywords optimized for search engines.

### Dataset
We will be using two different datasets, namely, the World Happiness Report dataset and the Gold Price dataset from Kaggle to create insightful visualizations through which we can explore the capabilities of BrailleR.

The World Happiness Report Dataset contains data from the World Happiness Report, which measures global happiness levels based on survey responses and socio-economic indicators.  The dataset provides valuable insights into the well-being of populations across different countries and regions, enabling analyses of trends and comparisons in happiness levels worldwide. This dataset has 156 unique values and 8 attributes. The different attributes are as below:
| **Column Name**             | **Data Type** | **Description**                                                                 |
|------------------------------|---------------|---------------------------------------------------------------------------------|
| `Overall rank`              | Integer       | The overall ranking of the country based on the happiness score.               |
| `Country or region`         | Character     | The name of the country or region.                                             |
| `Score`                     | Numeric       | The average happiness score for the country (on a scale of 0-10).              |
| `GDP per capita`            | Numeric       | The GDP per capita, representing economic prosperity.                          |
| `Social support`            | Numeric       | Measure of social support from family and friends.                             |
| `Healthy life expectancy`   | Numeric       | The average life expectancy adjusted for health.                               |
| `Freedom to make life choices` | Numeric    | The perceived freedom of individuals to make life choices.                     |
| `Generosity`                | Numeric       | Measure of altruistic behavior within the population.                          |
| `Perceptions of corruption` | Numeric       | The perceived level of corruption in government and businesses (lower is better).|

Source for World Happiness Report dataset: https://www.kaggle.com/datasets/unsdsn/world-happiness


The Gold Price dataset contains historical data on gold prices over five years. This dataset is useful for financial analysis, time-series forecasting, and studying price trends in the gold market. It has 1,256 rows of data representing daily trading data over five years and 9 attributes which are as follows:
| **Column Name**     | **Data Type** | **Description**                                                                |
|----------------------|---------------|--------------------------------------------------------------------------------|
| `Date`               | Date          | The trading date for the given data entry.                                      |
| `Open`               | Numeric       | The opening price of gold for that specific trading day.                        |
| `High`               | Numeric       | The highest price of gold reached during the trading day.                      |
| `Low`                | Numeric       | The lowest price of gold recorded during the trading day.                      |
| `Close`              | Numeric       | The closing price of gold for that specific trading day.                        |
| `Volume`             | Numeric       | The total trading volume of gold for that specific day.                         |
| `Dividends`          | Numeric       | The dividends paid (if applicable), usually for stock-based investments (might be zero for gold). |
| `Stock Splits`       | Numeric       | The number of stock splits (if applicable; generally not relevant for gold prices).|
| `Capital Gains`      | Numeric       | The capital gains earned on gold investments (typically zero for raw gold prices). |

Source for Gold Prices for 5 years: https://www.kaggle.com/datasets/kusumakar/gold-prices-for-5-years-financial-predictions

### Project Repository Structure

1. data: 
  Gold Prices.csv
  world_happiness_report_2019.csv
  
2. index.qmd - Project Write-Up

3. project_2.Rmd - Project Code

4. proposal.qmd - Project Proposal

5. readme.md

6. presentation.pdf - Project Presentation Poster

