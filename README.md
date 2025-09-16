# IPL-Matches-Data-Analysis-Using-Excel
This project uses Excel to clean, process, and analyze IPL match data. It maps team and match details, flags unusual outcomes, highlights big wins, and visualizes insights like win modes, toss impact, and top venues through interactive charts.

Task 1:
1.Normalize Text: Apply PROPER() and TRIM() on Venue_Name, City_Name, and Host_Country.
2.Team Lookups: Use VLOOKUP()/LOOKUP() to map ID to name.
• Team_Name_Id → Team_Name & Team_ Short_ Code
• Opponent_Team_Id → Opponent_ Team_Name
• Toss_Winner_Id → Toss_Winner
_Name
• Match_Winner_Id → Match_Winner_Name
3.Flag rows with IS_Result=0 or Win_Type in {Tie, No Result) as non-standard outcomes.

Task 2:
1.Win Mode Split: Compute % of wins by chasing versus defending.
2.Toss Impact: Compute Toss to Match Win Conversion Rate per team.
3.Identify top 10 largest win margins by runs and by wickets with team names.
4.Top 10 venues and cities by number of matches; compute win-mode distribution per venue.

Task 3:
1.Highlight D/L matches.
2.Emphasize Big Wins: Won_By ≥ 50 runs or ≥ 8 wickets.
3.Flag Data Alerts: IS_Result=0 or null Match_Winner_Id.

Task 4:
1.Bar Chart: Top 10 teams by total wins (label with counts).
2.Stacked Column: Season-wise distribution of by runs vs by wickets wins.
3.Line Chart: Share of Toss_Decision = field over seasons (trend).
