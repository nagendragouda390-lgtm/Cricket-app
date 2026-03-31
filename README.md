# Cricket App Documentation

## IPL 20-Over Match Analysis

This document provides an analysis of the IPL match between Gujarat Titans and Punjab Kings, utilizing matplotlib for visualization.

### Overview
The Indian Premier League (IPL) is a professional Twenty20 cricket league in India. In this analysis, we will review a match between Gujarat Titans and Punjab Kings, focusing on key statistics and visualizations.

### Match Summary
- **Match Date**: 2026-03-30
- **Teams**: Gujarat Titans vs Punjab Kings
- **Location**: Narendra Modi Stadium, Ahmedabad
- **Result**: Gujarat Titans won by X runs/ wickets

### Key Statistics
- Total Runs Scored: 160 (GT) - 150 (PK)
- Top Scorer: GT Player A - 60 runs
- Best Bowler: PK Player B - 4 wickets

### Visualization using Matplotlib
We have used matplotlib to create compelling visualizations of the match data:

```python
import matplotlib.pyplot as plt

# Sample data
teams = ['Gujarat Titans', 'Punjab Kings']
run_scores = [160, 150]

plt.bar(teams, run_scores, color=['blue', 'red'])
plt.title('IPL Match Analysis: GT vs PK')
plt.xlabel('Teams')
plt.ylabel('Runs Scored')
plt.show()
```

This code snippet creates a bar chart to represent the runs scored by both teams during the match.