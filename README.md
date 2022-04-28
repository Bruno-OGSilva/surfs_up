# surfs_up

## Project Overview

Extract and analyse the temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

Analysis key deliverables:

1. Determine the Summary Statistics for June
2. Determine the Summary Statistics for December
3. A written report for the statistical analysis (README.md)


This project was fully developed in Python, code can be checked at the following links:

[SurfsUp_Challenge.ipynb](https://github.com/Bruno-OGSilva/surfs_up/blob/cda11d3249b5cedf7139bfe70415831773cb2048/SurfsUp_Challenge.ipynb)

## Resources

- Data Source: `hawaii.sqlite`
- Data Tools: `Python SQL toolkit (SQLAlchemy)`, `Object Relational Mapper`, `pandas`, `numpy`
- Software: SQLlite, Python 3.9.2, Flask, Jupyter Notebook

## Results

* Summary Statistics DataFrame: June vs December Temperatures

![](https://github.com/Bruno-OGSilva/surfs_up/blob/78d0a74121574cb53d2106bf2c32e520833156ea/Assets/Stat%20compare.png)

* June Recorded Temps Visualization (Temperature and Frequency)

![](https://github.com/Bruno-OGSilva/surfs_up/blob/473d92d5c69e38206359cfd72a804e5d6a185c74/Assets/Jun%20Temps.png)

* December Recorded Temps Visualization (Temperature and Frequency)

![](https://github.com/Bruno-OGSilva/surfs_up/blob/473d92d5c69e38206359cfd72a804e5d6a185c74/Assets/Dec%20Temps.png)

## Key Differences in Weather: Oahu, Hawaii

* The average temperature in June 4 degrees higher than the average temp in December (74F vs 71F).

* The frequency of temperatures recorded in June tends to have a much more normal, tight bell curve distribution, cooroborated by the smaller std measure of June temps vs December temps
* The December temperatures have a higher standard deviation than June teperatures, this is driven by the Dec having a wider range from the min temp to the max temp.
* June had 12% more data colection than December (1,700 vs 1,517)

## Summary

