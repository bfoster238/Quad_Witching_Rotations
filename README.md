# Quad Witching Sector ETF Performance Analysis

This Python project analyzes the performance of the 11 major sector ETFs following Quad Witching dates over the past 10 years. The program uses `yfinance` to download historical daily data and allows users to compare the cumulative returns of the top and bottom half of sector ETFs for a given number of weeks after each Quad Witching date.

## Project Overview

### Features:
- Fetches Quad Witching dates for the past 10 years (third Friday of March, June, September, and December).
- Downloads daily historical data for the 11 major sector ETFs:
  - XLC, XLY, XLP, XLE, XLF, XLV, XLI, XLK, XLU, XLRE, XLB
- Calculates cumulative returns of the top and bottom half ETFs based on their performance after each Quad Witching date.
- Uses an interactive widget to select how many weeks after the Quad Witching date to start the analysis (from 0 to 12 weeks).
- Displays a bar chart comparing the cumulative returns of the top and bottom halves for each Quad Witching date.
- Shows the percentage of times the top half outperformed the bottom half, and vice versa.

### Visualization:
- **Bar chart** showing the cumulative returns of the top half and bottom half ETFs for each Quad Witching date.
- Displays percentages of how often the top half and bottom half ETFs outperform.
