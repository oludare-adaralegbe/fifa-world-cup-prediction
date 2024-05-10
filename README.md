# FIFA World Cup Prediction - A Data Analysis Project
This project tackles the exciting challenge of predicting the FIFA World Cup winner using Python and various data analysis techniques. The codebase is built upon the foundations provided by a fantastic tutorial by The PyCoach (https://www.youtube.com/watch?v=yat7soj__4w).

## Key Skills Demonstrated:
1. **Web Scraping**: Utilising libraries like Pandas, Selenium, and BeautifulSoup to gather football data from the web.
2. **Data Cleaning and Transformation**: wrangling and preparing the scraped data for analysis, ensuring its accuracy and completeness.
3. **Prediction**: Employing the Poisson distribution, a statistical model suited for count data, to predict the outcome of the World Cup.

## Project Highlights:
1. **Data Gathering**: Successfully scraped historical FIFA World Cup data, encompassing team performance metrics and other relevant factors. This included incorporating missing data for an additional year not covered in the original source.
2. **Data Preprocessing**: Cleaned and transformed the data to address missing values, inconsistencies, and prepare it for modelling.
3. **Code Enhancements**: The code was further refined by rewriting sections for better readability, adding detailed comments to improve understanding, and adapting it to handle the additional year of data.
4. **Predictive Modelling**: Built a Poisson regression model to estimate the win probability for each team, ultimately predicting the World Cup winner.

## Insights Gained:
1. The model’s prediction did not align with historical result.
2. The Poisson distribution effectively models win probabilities for teams with varying goal-scoring tendencies.

## Future Considerations:
1. Integration of additional data sources (e.g., player statistics, team rankings) could enhance the model's accuracy.
2. Exploring alternative machine learning algorithms might yield even more insightful predictions.
