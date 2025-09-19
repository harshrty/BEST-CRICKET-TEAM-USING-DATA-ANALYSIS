Data-Driven Cricket Team Selection
This project uses data analytics to move beyond subjective team selection and create a systematic, data-driven framework for identifying the optimal cricket team. By analyzing historical performance data from T20, ODI, and IPL formats , this analysis identifies top-performing players and builds a well-balanced team based on objective metrics.



The core problem this project addresses is the inherent bias and inconsistency in traditional team selection, which often relies on subjective judgment rather than quantifiable performance. This model provides an objective, performance-driven alternative.


Methodology
The project follows a systematic data analysis workflow:


Data Collection: Player and match statistics were scraped from ESPN Cricinfo. The scraping was performed using Python scripts leveraging the 


BeautifulSoup and Requests libraries.



Data Preprocessing: The raw scraped data was extensively cleaned. This involved handling missing values , removing duplicate entries , and standardizing metrics (e.g., strike rates, economy rates) to ensure consistency across the datasets.



Feature Selection: Key performance indicators (KPIs) were selected to evaluate players based on their specific roles:


Batting Metrics: Strike Rate, Batting Average, Boundary Percentage.


Bowling Metrics: Economy Rate, Bowling Strike Rate, Dot Ball Percentage.


All-Rounder Metrics: A balance of both batting and bowling KPIs.


Analysis & Team Selection: The cleaned data was analyzed using descriptive statistics and 

role-based filtering. Strict, predefined criteria were applied to filter and rank players for each role (e.g., Openers, Specialist Fast Bowlers, All-Rounders) to shortlist the final squad.

Key Results & Optimal Team
The analysis successfully identified top-tier players who consistently meet the objective performance criteria.

Key Insights

Top Performers Identified: The model shortlisted standout players, including David Warner (Avg SR 124.00, 1256 runs) , 

Jos Buttler (Batting Avg 50.76) , 

Suryakumar Yadav (SR 158.56) , and 

Jasprit Bumrah (Economy 6.81, Dot Ball 46.90%).


Metric Importance Confirmed: The findings validated the critical role of a high strike rate in T20 matches and the significant impact of a low 

bowling economy on team performance.

Final Team Composition
The final optimal team was selected based on the role-based criteria. The squad includes a balanced mix of top-order batters, finishers, specialist bowlers, and all-rounders.

Final Selected Squad (Partial List):


Batters: Virat Kohli (C) , David Warner , Suryakumar Yadav , Travis Head 



Wicketkeepers: Jos Buttler , Heinrich Klaasen 



All-Rounders: Glenn Maxwell , Marcus Stoinis , Glenn Phillips 



Specialist Bowlers: Jasprit Bumrah , Arshdeep Singh , Taskin Ahmed 

Future Scope
This project serves as a strong foundation for more advanced sports analytics. Future improvements could include:


Real-Time Data: Incorporating real-time match data to provide dynamic, in-tournament analysis and selection recommendations.


Machine Learning Models: Utilizing machine learning (e.g., regression, clustering) to predict player performance and optimize team composition for specific opponents or conditions.


Expanded Datasets: Expanding the analysis to include other major domestic leagues like the Big Bash League (BBL) and Caribbean Premier League (CPL).


Interactive Visualizations: Creating interactive dashboards (e.g., using Tableau or Power BI) for easier exploration of player stats and team insights.
