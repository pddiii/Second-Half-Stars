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

| Name            | Average Percentile Difference | Average Percentile (1st Half) | Average Percentile (2nd Half) |
|-----------------|-------------------------------|-------------------------------|-------------------------------|
| Bryce Miller    | +52 Percentiles               | 36th Percentile               | 88th Percentile               |
| Hunter Brown    | +50 Percentiles               | 24th Percentile               | 74th Percentile               |
| JP Sears        | +47 Percentiles               | 17th Percentile               | 64th Percentile               |
| Framber Valdez  | +46 Percentiles               | 41st Percentile               | 87th Percentile               |
| Pablo López     | +41 Percentiles               | 32nd Percentile               | 73rd Percentile               |
| Zach Eflin      | +35 Percentiles               | 39th Percentile               | 75th Percentile               |
| Bailey Ober     | +35 Percentiles               | 38th Percentile               | 73rd Percentile               |
| Michael King    | +34 Percentiles               | 44th Percentile               | 78th Percentile               |
| Jose Quintana   | +29 Percentiles               | 20th Percentile               | 50th Percentile               |
| Austin Gomber   | +21 Percentiles               | 26th Percentile               | 47th Percentile               |

### Batters Results

| Name            | Average Percentile Difference | Average Percentile (1st Half) | Average Percentile (2nd Half) |
|-----------------|-------------------------------|-------------------------------|-------------------------------|
| Eugenio Suárez| +54 Percentiles| 21st Percentile               | 75th Percentile               |
| Corbin Carroll| +43 Percentiles| 38th Percentile               | 81st Percentile               |
| Jorge Soler| +39 Percentiles               | 25th Percentile               | 64th Percentile               |
| Manny Machado| +39 Percentiles               | 33rd Percentile               | 72nd Percentile               |
| Colt Keith| +32 Percentiles               | 22nd Percentile               | 54th Percentile               |
| Brenton Doyle| +30 Percentiles               | 36th Percentile               | 66th Percentile               |
| Oneil Cruz| +30 Percentiles               | 35th Percentile               | 65th Percentile               |
| Luis García Jr.| +30 Percentiles               | 40th Percentile               | 70th Percentile               |
| Yainer Diaz| +30 Percentiles               | 35th Percentile               | 64th Percentile               |
| Gleyber Torres| +28 Percentiles               | 26th Percentile               | 54th Percentile               |
