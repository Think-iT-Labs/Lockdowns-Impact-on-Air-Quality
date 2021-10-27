# Capstone Project for DSAA-Kulimi Data Camp Rwanda

# Lockdowns-Impact-on-Air-Quality

## Intro

In completion of the DSAA-Kulimi Data Camp Rwanda program, we propose this project for our learners to contribute to and practice their acquired data science knowledge and skills while at the same time contributing to one of the hottest topics related to the impact of Covid-19 on Climate Change across the planet.


Due to the fast spread of Covid-19 all over the world in early 2020, most cities across the globe opted for lockdowns. Yet this solution, had various different outcomes, besides slowing or stopping the spread of the virus. In this study we would like to focus on **the impact of lockdowns on air quality**. 

## Data

The World Air Quality Index team have been taking measurements from stations planted in 380 cities around the world, 3 times a day since 2015. The dataset we provide will only take into consideration air quality records worldwide during the years 2019, 2020, and 2021. In these records, we calculate the min, max, median and standard deviation for each air pollutant specie 

The dataset is structured as follows:
- Date: The date of the record 
- Country: Country code in ISO 3166-1 alpha-2
- City: The city where the record has been taken
- Specie: The air pollutant specie (PM2.5, PM10, O3, humidity, etc.)
- Count: The number of values in the sample taken
- Min: The minimum of the sample values
- Max: The maximum of the sample values 
- Median: The median of the sample values
- The variance of the sample values


## Contributing
To contribute to this repository, kindly fork this repository.
<!-- TODO: Add specific description of the steps to take for the reopo to remain organized and to apply best practices while working on the project-->

## Installation
Once the repository is cloned on your local machine, run the following code in your command line interface:
>pip install -r requirements.txt
Then run your Jupyter notebook.

## Code quality standards
- Style convention [pep8](https://www.python.org/dev/peps/pep-0008/)
