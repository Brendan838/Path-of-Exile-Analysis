# Path of Exile Market Analysis - Project 1

## Overview

This repository contains Project 1 of the University of Minnesota Data Visualization and Analytics Boot Camp. The project's goal was to develop a hypothesis based on public datasets, load the data into pandas DataFrames for analysis and manipulation, and create visualizations using matplotlib to present findings.

Our final presentation, shared with the class, can be viewed in `Project Slide Show.pdf`.

---

## Project Description

Our data analysis provided in this presentation can be shown in the following notebooks:

- **`currency.ipynb`**:
  - Provides a data analysis comparing the relative costs of different types of in-game currencies.
  
- **`items.ipynb`**:
  - Analyzes items purchased in the game.
  - Identifies items with potential early-season resale values of 2x or greater.

- **`StockAPI.ipynb`**:
  - Compares the primary in-game currency, Chaos Orbs, to the Japanese Yen.

---

## Instructions

- **Data Sources**:
  - CSV files from [poe.ninja](https://poe.ninja/data) are stored in the `Resources` folder.
  - NOTE: The files needed for `items.ipynb`  was too large to upload to github. Please download [here](https://poe.ninja/api/data/getdump?name=Necropolis) and add `Necroplis.items.csv` to the resources folder before running the `items.ipynb` notebook.
  -Obtain API Key (no registration required) from [Alpha Vantage](https://www.alphavantage.co/) and add key to `config.py`
  
## Authors

This project was completed by a team of students as part of the University of Minnesota Data Visualization and Analytics Boot Camp. Brendan Smith, Sam Carty, Lance Peterson, Jacob Fischbach, and Dylan Mavencamp.

---

