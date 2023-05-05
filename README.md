# SF Giants Clutch Batting Analysis --sql-project
## Project Objective
The project objective is to identify which players perform the best in the later stages of close games with the opportunity to take the lead or tie. The problem this project aims to solve is to help the San Francisco Giants make informed decisions about player selection and deployment during critical game situations. By analyzing data from the 2022 season, the project will determine which players have historically performed the best in these situations and provide insights to the baseball operations team.
## Baseball Operations Analyst SF Giants 
The San Francisco Giants are a Major League Baseball team based in San Francisco, California. The position selected is for a Baseball Operations Analyst. The main responsibility of this position is to analyze baseball-related data using SQL and provide insights to help identify players who are likely to perform well and contribute to the team's success. This position will work closely with the baseball operations team, including the general manager, coaches, and scouts, to develop strategies to improve team performance. The job posting is related to the project of combining sports and data analytics, which has become increasingly important in the sports industry in recent years, and it's no different in baseball. The job posting emphasizes the need for someone who has a passion for sports and an interest in using data to gain a competitive edge. So I chose a project that would focus into one specific area of substitutions (pinch hitting) in the latter portion of close games.
## Data
For this project, data was collected from two main sources. The first source was basketball-reference, which was web scraped to obtain stats for overall 2022 season batting as well as batting splits against left-handed pitchers and right-handed pitchers. This data provided information on how players performed throughout the season and against specific types of pitchers.
The second source of data was baseball savant, where publicly available data was downloaded in CSV format. The data was filtered to identify performance of players in critical game situations where there was a chance to tie or take the lead. This data provided insight into how players performed in high-pressure situations and was used to determine which players had historically performed well in these situations.
The characteristics of the data used for this project included various challenges such as unnecessary data in tables, no primary keys on baseball-reference, and the need for data from multiple web pages. Despite these challenges, the data provided valuable insights into player performance in high-pressure situations, which allowed me to provide insights.
## Notebooks
Links to the notebook and a description of the notebook's purpose
data_collection.ipynb https://github.com/rgomma/sql-project/blob/main/data_collection.ipynb
  used to web scrape baseball-reference and import datasets into aws rds mysql server
sql_analysis.ipynb https://github.com/rgomma/sql-project/blob/main/sql_analysis.ipynb
  perfomed my analysis with sql inside a jupyter notebook
## Future Improvements
Would have collected data from more than 1 year and aalyzed more advanced stats to see if they provided a better insight.
