# Exploratory and Explanatory Data Visualization Project (California Housing Dataset)

## by Ojikutu Aisha

### Introduction

This project demonstrates the significance and value of data visualization techniques in the data analysis process. The project is divided into two parts: Exploratory Data Visualization (Part I) and Explanatory Data Visualization (Part II). The primary aim is to systematically explore and analyze a selected dataset using Python visualization libraries and then create polished explanatory visualizations to communicate the findings effectively.

### Project Overview

Part I - Exploratory Data Visualization
In this part, we conducted an exploratory data analysis on a selected dataset. We used Python data science and visualization libraries such as NumPy, pandas, Matplotlib, and Seaborn to explore the dataset's variables and gain insights into its structure, patterns, and relationships. The process involved moving from simple univariate relationships to multivariate relationships, documenting our observations and questions along the way.

Part II - Explanatory Data Visualization
In Part II, we transformed our exploratory visualizations from Part I into polished explanatory visualizations. We created a short presentation to illustrate interesting properties, trends, and relationships discovered in the dataset. The goal was to communicate our findings effectively, ensuring design integrity in the visualizations.

### Dataset

We selected the "California Housing" dataset, which contains 20,640 observations and 10 features, including geographical and housing-related variables. The dataset's features include longitude, latitude, housing median age, total rooms, total bedrooms, population, households, median income, median house value, and ocean proximity. The dataset source can be found here.

### Summary of Findings

During our exploration, we made several key observations:

There is a high positive correlation between income and house value, indicating that a household's average income is related to their home's value.
Homes near the ocean or bay area tend to be more expensive, regardless of age.
There is a linear relationship between median income and median house value.
Housing median age does not exhibit a strong relationship with median house value.
Key Insights for Presentation
For our explanatory presentation, we focused on the following insights:

Illustrating the correlation between median income and median house value using a scatter plot.
Displaying distributions of median income, housing median age, and median house value using appropriate visualizations.
Highlighting the impact of geographical location (ocean proximity) on house values.
How to View the Presentation
To view the presentation slide deck, follow these steps:

Convert the Part_II_slide_deck_template.ipynb notebook file to a slide deck using the provided Cell Toolbar and Slide Type assignments.
Generate the slide deck by running the following command in the last code cell of the notebook:
css
Copy code
!jupyter nbconvert Part_II_slide_deck_template.ipynb --to slides --post serve --no-input --no-prompt

### Conclusion

This project underscores the importance of data visualization in data analysis. Through exploratory analysis and explanatory visualization, we gained insights into relationships within the dataset. Our findings highlighted the role of factors such as income and geographical location in influencing house values. By effectively communicating these insights, we demonstrate the power of visualizations in conveying complex information.
