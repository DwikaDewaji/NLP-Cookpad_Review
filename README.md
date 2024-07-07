# NLP Sentiment Analysis for Cookpad App Reviews on Google Play Store

This project carries out sentiment analysis of user reviews of the Cookpad application on the Google Play Store using Natural Language Processing (NLP) techniques.

## List of contents
- [Introduction](#introduction)
- [Features](#features)
- [Usability](#usability)
- [Project Structure](#project-structure)
- [Contribution](#contribution)
- [License](#license)

## Introduction
This project aims to understand how Cookpad app users respond to the app through the reviews they leave on the Google Play Store. Using NLP techniques, it can be classified these reviews into different sentiment categories such as positive or negative.

## Features
- **Collecting Data**: Scraping user reviews from Google Play Store.
- **Pre-Processing Data**: Removes noise and cleans data for accurate analysis.
- **Sentiment Analysis**: Using NLP models to determine review sentiment.
- **Data Visualization**: Graphs and plots for visualization of sentiment distribution.


## Usability
1. Run the data collection script to get the latest reviews from Google Play Store:
    ```sh
    python Scrap_data.ipynb
    ```
2. Run a sentiment analysis script to classify reviews:
    ```sh
    python Sentiment_Analysis_NLP.ipynb
    ```


## Project Structure
- `ulasan_aplikasi_cookpad2.csv`: Folder to store raw data and processing results.
- `Scrap_data.ipynbpy`: Scrap data from playstore.
- `Sentiment_Analysis_NLP.ipynb`: Perform sentiment analysis.
- `requirements.txt`: List of required dependencies.

## Contribution
Contributions are very welcome! Please fork this repository and create a pull request with your proposed changes.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more information.

