# NFL Offensive Play Analysis (2009-2017)

This repository contains the final project for the Data Science 200 course at UC Berkeley's MIDS program. The project focuses on analyzing offensive play trends in the NFL from 2009 to 2017. The analysis leverages a rich dataset of NFL play-by-play data to uncover insights into team strategies, game dynamics, and factors influencing performance.

## **Project Overview**

### **Objective**
The primary goal of this project is to explore trends and strategies in NFL offensive plays from 2009 to 2017. Key questions addressed include:
- How do play types vary with field position and down?
- Does time pressure affect decision-making and errors?
- Is there evidence of home-field advantage?
- How do teams balance run-heavy vs. pass-heavy strategies?

### **Dataset**
The analysis is based on the NFL Play-by-Play dataset (2009-2017), which includes:
- Over 2304 games across nine seasons.
- More than 100 columns detailing game circumstances (e.g., play type, yardage, penalties).

### **Key Features**
- **Data Cleaning**: Adjustments for team relocations (e.g., Rams and Chargers) and inconsistent naming conventions.
- **New Columns Added**:
  - *Quarter Time Category*: Start, Middle, End.
  - *Yardline Groupings*: Binned into 10-yard intervals.
  - *Calculated Metrics*: Total Points, Turnovers.
- **Removed Columns**: Irrelevant or pre-calculated statistics.

---

## **Repository Structure**

### **Files**
1. **`Final_Report.pdf`**: Comprehensive report detailing the analysis and findings.
2. **`Shetty_raw_code.ipynb`**: Jupyter Notebook containing data preprocessing, exploration, and visualization scripts for Home vs Away differences.
3. **`NFL_Play_Analysis_Notebook_Tyler_Gustafson.ipynb`**: Jupyter Notebook containing general data analysis of play types.

### **Key Sections in the Jupyter Notebooks**
1. **Sanity Checking**: Verifying data consistency (e.g., number of games per season).
2. **Exploratory Analysis**: Initial trends in points, turnovers, penalties, and touchdowns.
3. **Impact of Factors on Offense**:
   - Field position and down-based play trends.
   - Time pressure's effect on turnovers and penalties.
   - Home-field advantage analysis.
4. **Team-Specific Insights**:
   - Run vs. pass tendencies.
   - Receiver performance (e.g., Yards After Catch).
   - Winning strategies (e.g., passing vs. running efficiency).

---

## **Highlights of Findings**

### **General Trends**
- Teams favor passing over running (>50% of plays are passes).
- Passing success correlates more strongly with playoff success than running efficiency.

### **Field Position Insights**
- On early downs, teams employ balanced strategies; later downs favor passing unless short yardage is needed.
- Near the red zone, right-sided passes dominate due to lower interception risks.

### **Time Pressure**
- Turnovers and penalties spike during the final minutes of halves, indicating decision-making under pressure is critical.

### **Home Field Advantage**
- A median home advantage of ~4 points per game was observed across teams.
- Referees tend to penalize away teams more frequently than home teams.

### **Team-Specific Strategies**
- The New Orleans Saints were the most pass-heavy team with high success rates due to Drew Brees' leadership.
- Teams like the Cleveland Browns struggled due to frequent quarterback changes.

---

## **Contributors**
This project was created by:
- Abhishek Shetty
- Bikram Khaira
- Tyler Gustafson

---
