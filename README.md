

## Employee Sentiment and Engagement Analysis
This project analyzes employee sentiment and engagement using the test.csv dataset, which contains email messages from employees. The analysis includes sentiment labeling, exploratory data analysis (EDA), employee score calculation, ranking, flight risk identification, and predictive modeling to provide insights into employee engagement and retention.

# Summary
-  Top Three Positive and Negative Employees
    Based on monthly sentiment scores (Positive: +1, Negative: -1, Neutral: 0), the following employees consistently ranked in the top three for positive and negative sentiment across multiple months:

    1. Top Positive Employees:

        - sally.beck@enron.com: Frequently ranked #1 (e.g., February 2010, June 2010) with scores like +5, reflecting strong engagement.
        - kay.mann@enron.com: Appeared in top ranks (e.g., March 2011) with positive scores, indicating constructive communication.
        - vince.kaminski@enron.com: Noted for high positive scores in months like November 2010.


    - Top Negative Employees:

        - don.baughman@enron.com: Consistently ranked in top negative (e.g., June 2010, November 2011) with scores as low as -4, signaling dissatisfaction.
        - eric.bass@enron.com: Appeared in negative rankings (e.g., July 2010) with scores like -3, showing periodic disengagement.
        - tanya.tamarchenko@enron.com: Ranked negatively in months like September 2010, with low scores.



## Flight Risk Employees
    Employees flagged as flight risks sent 4 or more negative messages within any rolling 30-day period, indicating potential disengagement and turnover risk:

        - don.baughman@enron.com
        - eric.bass@enron.com
        - tanya.tamarchenko@enron.com
        - Additional employees may be flagged depending on specific 30-day windows, but these were the most consistent.

# Key Insights

    1. Sentiment Distribution: Neutral messages dominated, followed by Positive, with Negative messages indicating specific concerns. June 2010 and November 2011 showed spikes in negative sentiment, likely tied to organizational stressors.
    2. Employee Variability: Sally.beck@enron.com exhibited strong positive engagement, while don.baughman@enron.com showed persistent negative sentiment, correlating with flight risk status.
    3. Temporal Patterns: February 2011 had high positive scores, suggesting positive events, while June 2010 and November 2011 were negative, possibly due to deadlines or transitions.
    4. Flight Risk Correlation: Employees with negative rankings (e.g., don.baughman@enron.com) were often flight risks, reinforcing the link between negative sentiment and turnover risk.
    5. Predictive Insights: Linear regression showed a moderate correlation between prior and current month scores, suggesting sentiment trends are somewhat predictable.

## Recommendations

    1. Targeted Retention for Flight Risks: Engage don.baughman@enron.com and eric.bass@enron.com with one-on-one meetings to address concerns (e.g., workload, career growth) to reduce turnover risk.
    2. Leverage Positive Employees: Utilize sally.beck@enron.com and kay.mann@enron.com as team leaders or mentors to boost morale and foster positive communication.
    3. Address Temporal Stressors: Investigate events in June 2010 and November 2011 to identify stressors (e.g., project deadlines, transitions) and implement support measures like clearer communication or resource allocation.
    4. Continuous Monitoring: Regularly update sentiment analysis and flight risk identification to proactively manage engagement, especially during high-risk periods.
    5. Enhance Predictive Models: Incorporate additional features (e.g., message frequency, recipient analysis) to improve the accuracy of sentiment trend predictions.

## Project Structure

    Scripts: Created greentree.ipynb files. Created sentiment labeling, eda, employee scores, employee ranking, flight risk, flight risk employees and predictive_modeli in one file name greentree.ipynb.


## Outputs:
    - test_with_sentiment.csv: Augmented dataset with sentiment labels.
    - monthly_scores.csv: Monthly employee scores.
    - top_positive_employees.csv & top_negative_employees.csv: Employee rankings.
    - flight_risk_employees.txt: List of flight risk employees.




                        Thank You.






