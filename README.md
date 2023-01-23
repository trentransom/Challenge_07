# ETF Analyzer

## Overview
This app uses sqlalchemy to retrieve data from a database and analyze it using pandas.

## Requirements

- Python 3.7 or Later
- The following libraries
    - Pandas
    - SQLAlchemy
    - Numpy
    - hvplot.pandas
    - voila

If you do not have any of these libraries you can download them into your dev environment with the command:
```
conda install <name of library>
```

## Features

Users will be able to use advanced queries to call a database through sqlalchemy and display the resulting jupyter notebook in a web app using voila.
run `voila etf_analyzer.ipynb` in your terminal.
It will appear like this in your web browser:

[Download Screen Recording](./Screen%20Recording%202023-01-22%20at%2011.11.34%20PM.mov)
