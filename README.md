# Project Title: Cricket Statistics Analysis

## Description
This project involves the analysis of cricket statistics derived from a dataset obtained from [ESPN Cricinfo](https://www.espncricinfo.com/records/most-runs-in-career-284269). The primary objective is to clean, transform, and analyze the dataset to extract meaningful insights about the highest-scoring players in cricket history.

## Key Steps
1. **Data Loading**: The dataset is loaded from a CSV file, which contains statistics on the highest-scoring cricket players.
2. **Data Cleaning and Transformation**:
   - Columns are renamed for better readability.
   - Player names and countries are split into separate columns.
   - The career start and end years are extracted, and the original span column is dropped.
   - Special characters are removed from the data to facilitate numerical calculations.
   - The data types of various columns are transformed for appropriate analysis.
3. **Analysis**:
   - Calculating the average career length of players.
   - Determining the average batting strike rate for players with over 10 years of experience.
   - Counting the number of cricketers who played before 1990.
   - Finding the highest innings score by each country.
   - Analyzing averages of hundreds, fifties, and ducks (zero runs) by country.
   - Calculating players' average matches per year.
   - Identifying players who take the least innings to score fifties and hundreds.
   - Displaying players with the highest number of centuries and ducks.

## Insights Extracted
- The project reveals trends in player performance based on various metrics, such as career length and scoring efficiency.
- A comparative analysis of player performance by country provides insights into cricketing excellence across nations.

## Technologies Used
- **Python**: The primary programming language for data analysis.
- **Pandas**: Used for data cleaning, transformation, and analysis.
- **Jupyter Notebook**: For documenting the analysis process in an interactive format.

## Future Improvements
- Incorporating visualizations to represent insights graphically.
- Extending the analysis to include more recent data or additional metrics.

## Repository Structure
- `highest_scoring_players.csv`: The dataset used for analysis.
- `Cricket_Statistics_Analysis.ipynb`: The Jupyter Notebook containing the code and analysis.

## How to Run
1. Ensure you have Python and Jupyter Notebook installed.
2. Clone this repository or download the files.
3. Install the required packages:
   ```bash
   pip install pandas
