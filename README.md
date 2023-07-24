# Microsoft Studios Movie Analysis - README

![Movie Analysis](./img/title_img.png)


### Overview

This repository contains the analysis and findings of the Movie Studio Project, which aims to provide insights to Microsoft Studios on achieving financial success in the movie industry. The project explores factors influencing a movie's box office performance and profitability.

Datacleaning & Preparation is contained in the data-preparation.ipynb file.
Data analysis and recommendations are contained the student.ipynb file.

### Approach

To conduct the analysis, we followed these key steps:

1. Data Selection: We identified relevant features of interest, including movie titles, genres, runtime, budget, ratings, directors, and writers.

2. Data Cleaning: We performed data cleaning and preparation on a separate Jupyter Notebook, addressing missing values, casting datatypes, and handling compound entries.

3. Exploratory Data Analysis (EDA): After data preparation, we conducted EDA to gain insights into the relationships between movie attributes and box office performance.

### Features of Interest

The analysis focused on the following features:

- Movie titles
- Genres
- Runtime
- Budget
- Ratings
- Directors
- Writers

### Datasets Used

The following datasets were used for analysis:

1. Title Basics Dataset: Contains movie titles, genres, and runtime information.

2. Tn.movie_budgets Dataset: Includes production budget, domestic gross, worldwide gross, and release date.

3. Tmdb Movies Dataset: Provides movie ratings, vote average, numvotes, and popularity.

4. Movie Info Dataset: Contains director, writer, and rating information.

### Exploratory Data Analysis Findings

Based on the EDA results, we discovered the following:

- Genres: Horror, adventure, comedy, and action movies tend to have higher profitability and popularity at the box office.

- Budget: Movies with budgets between $10 million and $100 million are more likely to achieve positive returns.

- Runtime: Medium-length and long films (90-120 minutes and >120 minutes) consistently demonstrate positive worldwide ROI.

### Recommendations and Conclusions

Drawing from our analysis, we recommend the following strategies for Microsoft Studios:

1. Focus on High-Potential Genres: Prioritize producing horror, adventure, comedy, and action films to increase profitability and popularity.

2. Budget Allocation: Allocate budgets between $10 million and $100 million for optimal financial success.

3. Strategic Movie Runtimes: Consider medium-length and long films for better box office performance.

4. Collaborate with Successful Directors: Collaborate with reputable directors to enhance movie ratings and box office success.

Our analysis offers valuable insights to help Microsoft Studios become a key player in the movie industry and achieve financial success.

For more details and insights, please refer to the analysis notebooks in the `notebooks` directory.

### Directory Structure

- `data`: Contains the raw and cleaned datasets used in the analysis.
- `img`: Contains images and visualizations generated during the EDA.
- `notebooks`: Contains Jupyter Notebooks, including the data cleaning notebook (`Exploratory Data Analysis & Data Cleaning.ipynb`) and the main analysis notebook.
- `README.md`: This file, providing an overview of the project and its contents.


