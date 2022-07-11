# Cordiance-experential-project

String Matching using Longest Common Subsequence with Words between two sentences

## Project Description:

This project is an experiential Algorithm course project in collaboration with the Cordiance Company. The goal of this project is to get the closest possible UNSPSC code match for the Avalara Tax description. To begin this project, we were provided with two data files: UNSPSC and Avalara.

UNSPSC file contains code to be matched and it is divided into 4 levels:

- Commodity level

- Class level

- Family level

- Segment level

Avalara file contains Avalara Tax System code, its description and additional information related to the same.

The goal of this project is to get the closest possible UNSPSC code match for the Avalara Tax description.

## Algorithm:

![alt text](https://github.com/kasivisu4/cordiance-experential-project/blob/main/Algorithm.png?raw=true)

## Documentation:

https://github.com/kasivisu4/cordiance-experential-project/blob/main/Group3-Final%20Report.pdf

## Code Details:

The program to the project is written in Python language with help of Jupyter lab. All the cells are in sequence order from top to bottom. Each step mentioned in the algorithm is the function in the code. At the end of the notebook we will get the output in final_result object.

https://github.com/kasivisu4/cordiance-experential-project/blob/main/Experential_project_code.ipynb

## Test Cases:

We created a test dataset of 30 records by manually mapping the corresponding UNSPSC code to Avalara description. Our algorithm is divided into two phases

- Phase 1(Possible Outcome): In this phase, we were able to get one possibility for each level. Out of 30 we were able to match 27 possibilities
- Phase 2: In this phase, we will get the max possibility of all the levels from phase 1. Out of 30 records we were able to match 20 records which gives us the accuracy of **66.7%**.

https://github.com/kasivisu4/cordiance-experential-project/blob/main/TestRecords.xlsx

## Observable Custom StopWords Visualizations:

We have performed word count on the Avalara File and tried to visualize the zoomable tree map for identifying the custom stop words

https://observablehq.com/@kasivisu4/avalara-data-analysis

## Contributors:

Akhila Sulgante

Kasi Viswanath ![![](https://github.com/remarkablemark.png?size=50)](https://github.com/remarkablemark)

Shital Waters

© 2022 MIT
