# 📘 Project: IPL-Analysis-2008-2024-

## 🔹Interduction
  **Objective:**

The goal of this project was to perform end-to-end data analysis on IPL matches from 2008 to 2024 to uncover patterns, key player statistics, team performance, and decision-making insights (e.g., toss decision impact) using interactive Tableau dashboards.

## 🔹Data Collection

* Sourced IPL datasets from public sources such as Kaggle or official IPL records.

* Datasets included:

   * Match details (winner, toss winner, decision, etc.)

   * Player statistics (runs, wickets, strike rate, economy)

   * Team performance

   * Tournament stats (fours, sixes, etc.)

## 🔹3. Data Preparation

* Cleaned and preprocessed the data using Excel:

    * Handled null values and inconsistent naming (e.g., "Kings XI Punjab" vs "Punjab Kings")

    * Standardized player names and team names

    * Extracted new fields like:

         * Year/Season

         * Toss Win Decision (Bat/Field)

         * Performance metrics (Batting SR, Bowling Average)

* Joined multiple tables (matches, deliveries, players) using VLOOKUPs or Tableau joins/blends.

## 🔹Key Measures & KPIs

   * Defined and calculated the following metrics in Tableau:

   * Batting KPIs:

     * Total Runs, Strike Rate, 100s, 50s, 4s, 6s

     * Matches Played, Highest Score

   * Bowling KPIs:

     * Total Wickets, Economy (ECO), Average, Bowling SR

   * Team Stats:

     * Wins based on toss decisions

     * Titles won

  * Aggregate Tournament Metrics:

     * Total 4s and 6s per season
   
## 🔹Dashboard Design

Created multiple interactive dashboards in Tableau:

   📌 Main Dashboard: Overview

   * Title Winner

   * Orange Cap (Top run-scorer)

   * Purple Cap (Top wicket-taker)

   * Tournament Total 4s and 6s

   * Filter by Season

  📌 Toss Decision Impact

   * Bar chart of wins based on toss decision (team-wise)

   * Donut chart for % win when choosing to bat/field

   * Interactive slicer for Toss Decision

  📌 Player Performance Dashboards

   * Batsmen Status:

     * Table of players with Runs, Strike Rate, Matches, 100s, etc.

   * Bowling Status:

     * Table of bowlers with Overs bowled, Economy, Average, and Wickets

  ![image](https://github.com/vamsikrishna-boss/-IPL-Analysis-2008-2024-/blob/main/Screenshot%202025-04-10%20232343-1.png)

   ![image](https://github.com/vamsikrishna-boss/-IPL-Analysis-2008-2024-/blob/main/Screenshot%202025-04-10%20232447.png)
    
## 🔹 Interactivity 

  * Used parameter controls and filters for season selection.

  * Incorporated images and logos for visual appeal (team logos, player images).

  * Implemented color coding and gradient shades for numeric values (heatmap effect).

## 🔹 Insights Derived

  * Teams that chose to field after winning the toss had a higher win % (64.29%).

  * V. Kohli led as top run-scorer with 8014 runs, while Y. Chahal was the leading wicket-taker with 205 wickets.

  * Certain teams like Mumbai Indians and Chennai Super Kings showed consistent performance across seasons.

## 🔹 Outcome & Value

  * Enabled data-driven insights into IPL history from 2008 to 2024.

  * Enhanced decision-making for toss choices and team strategies.

  * Developed a user-friendly, dynamic dashboard for fans, analysts, and strategists.
 







  


