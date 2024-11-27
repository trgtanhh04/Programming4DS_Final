# Final Project: Global Football Data Analysis 🌍⚽

## 📜 Description
This project is the **Final Project for Programming for Data Science** course, focusing on analyzing a global football dataset from Kaggle. The dataset contains over 47,000 international football results from 1872 to 2024, covering FIFA World Cup, friendly matches, and other tournaments. The goal is to clean, explore, and analyze the data to uncover insights about football trends, team performance, and individual players.

## 📂 Dataset
- **Source**: [Kaggle - International Football Results](https://www.kaggle.com)
- **Content**: The dataset includes 47,917 results of international football matches, ranging from official FIFA World Cup matches to friendly games, starting from 1872 until 2024.
  
### Dataset Files:
- **results.csv**: Contains match details, including:
  - `date`: Date of the match
  - `home_team`: Name of the home team
  - `away_team`: Name of the away team
  - `home_score`: Final score of the home team (including extra time, excluding penalty shootouts)
  - `away_score`: Final score of the away team (including extra time, excluding penalty shootouts)
  - `tournament`: Name of the tournament
  - `city`: City or town where the match was played
  - `country`: Country where the match took place
  - `neutral`: Indicates if the match was played at a neutral venue (TRUE/FALSE)

- **shootouts.csv**: Contains penalty shootout details, including:
  - `date`: Date of the match
  - `home_team`: Home team
  - `away_team`: Away team
  - `winner`: Winner of the penalty shootout
  - `first_shooter`: Team that went first in the shootout

- **goalscorers.csv**: Contains goal scorer details, including:
  - `date`: Date of the match
  - `home_team`: Home team
  - `away_team`: Away team
  - `team`: Team that scored
  - `scorer`: Name of the goal scorer
  - `own_goal`: Indicates whether it was an own goal
  - `penalty`: Indicates whether the goal was a penalty

### Notes:
- Team names are standardized to current names for consistency (e.g., "Northern Ireland" instead of "Ireland" for matches prior to 1882).
- Country names are recorded as they were at the time of the match (e.g., "Gold Coast" for Ghana in the 1950s).

## 🎯 Objectives
The primary objectives of this project are:  
1. Perform exploratory data analysis (EDA) on the dataset.  
2. Clean and preprocess the data to ensure consistency and accuracy.  
3. Visualize key trends in global football.  
4. Answer meaningful questions such as:  
   - What factors influence a team's success?  
   - Which players perform the best under specific conditions?  
   - How has football evolved over the years based on the data?

## 🛠️ Tools and Technologies
- **Programming Language**: Python  
- **Libraries**:  
  - `pandas` for data manipulation  
  - `numpy` for numerical operations  
  - `matplotlib` and `seaborn` for data visualization  
  - `scikit-learn` for potential machine learning insights  
- **Environment**: Jupyter Notebook

## 👥 Team Members
| MSSV         | Name             | Gmail                | GitHub Link                    |
|--------------|------------------|----------------------|--------------------------------|
| 123456789    | John Doe         | john.doe@gmail.com    | [GitHub Profile](https://github.com/johndoe) |
| 987654321    | Jane Smith       | jane.smith@gmail.com  | [GitHub Profile](https://github.com/janesmith) |
| 112233445    | Tiến Anh         | tien.anh@example.com | [GitHub Profile](https://github.com/tienanh) |

## 📊 Key Insights
Insights from the analysis will be documented here as the project progresses.

## 🚀 How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
