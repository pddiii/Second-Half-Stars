# Second-Half-Stars

Discussing MLB's second half of 2024 top players.

## Data Source

All statistical data was sourced from FanGraphs utilizing their custom reports.

## Data Cleaning

[Click Here to view the Data Cleaning Process](cleaning.ipynb)

## Decision Process

I split the 2024 MLB Season into two halfs:

- June 27th and before
- June 28th through Sep 15th

I utilized the variables below. I percentile ranked the batters, and pitchers separately using their respective variables. Then I looked at the average differences (2nd half - 1st half) of these percentiles, and ranked them in descending order (because a percentile closer to 1 is better than closer to 0)

## Variables

### Batters

| Variable | Description               |
|----------|---------------------------|
| Def      | Defensive value (Fangraphs)|
| Off      | Offensive value (Fangraphs)|
| wRC+     | Weighted Runs Created Plus |
| BB%+     | Walk percentage plus       |
| OBP+     | On-base percentage plus    |
| SLG+     | Slugging percentage plus   |
| ISO+     | Isolated power plus        |
| WPA      | Win Probability Added      |
| Clutch   | Clutch performance         |
| WAR      | Wins Above Replacement (Fangraphs)|
| K%+      | Strikeout percentage plus  |

### Pitchers

| Variable | Description                         |
|----------|-------------------------------------|
| K/BB+    | Strikeout-to-walk ratio plus         |
| WPA      | Win Probability Added               |
| WAR      | Wins Above Replacement              |
| Clutch   | Clutch performance                  |
| ERA-     | Earned Run Average minus            |
| FIP-     | Fielding Independent Pitching minus |
| AVG+     | Batting average plus                |
| WHIP+    | Walks plus Hits per Inning Pitched plus |
| HR/9+    | Home runs allowed per nine innings plus |

## Results

### Pitchers Results

| Name            | Average Percentile Difference |
|-----------------|-------------------------------|
| Bryce Miller    | +52 Percentiles               |
| Hunter Brown    | +50 Percentiles               |
| JP Sears        | +47 Percentiles               |
| Framber Valdez  | +46 Percentiles               |
| Pablo López     | +41 Percentiles               |
| Zach Eflin      | +35 Percentiles               |
| Bailey Ober     | +35 Percentiles               |
| Michael King    | +34 Percentiles               |
| Jose Quintana   | +29 Percentiles               |
| Austin Gomber   | +21 Percentiles               |

### Batters Results

| Name            | Average Percentile Difference |
|-----------------|-------------------------------|
| Eugenio Suárez  | +54 Percentiles               |
| Corbin Carroll  | +43 Percentiles               |
| Jorge Soler     | +39 Percentiles               |
| Manny Machado   | +39 Percentiles               |
| Colt Keith      | +32 Percentiles               |
| Brenton Doyle   | +30 Percentiles               |
| Oneil Cruz      | +30 Percentiles               |
| Luis García Jr. | +30 Percentiles               |
| Yainer Diaz     | +30 Percentiles               |
| Gleyber Torres  | +28 Percentiles               |
