# Human Activity Recognition - Weight Lifting Exercise Prediction

## Project Overview
This project aims to predict the manner in which participants performed barbell lifts using data from accelerometers placed on the belt, forearm, arm, and dumbbell. The "classe" variable in the training set represents the exercise quality (A to E), with A being the correct execution.

## Data Sources
The data comes from the Weight Lifting Exercise Dataset:
- Training data: [pml-training.csv](https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv)
- Test data: [pml-testing.csv](https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv)

Original source: [Groupware@LES](http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har)

## Repository Contents
- `activity_prediction.Rmd`: R Markdown file containing the complete analysis
- `activity_prediction.html`: Compiled HTML version of the report
- `README.md`: This file (project overview)

## Analysis Approach
The report covers:
1. Data cleaning and preprocessing
2. Exploratory data analysis
3. Feature selection process
4. Model building with cross-validation
5. Expected out-of-sample error estimation
6. Predictions for the 20 test cases

## How to Reproduce
1. Clone this repository
2. Open the HTML file in any web browser to view the compiled report
3. To run the analysis yourself, open the R Markdown file in RStudio and knit the document

## Requirements
- R programming environment
- RStudio (recommended)
- Packages listed in the R Markdown file

## Note on Reproducibility
Due to security concerns, the code will not be run during peer evaluation. The HTML version contains all analysis results and can be viewed directly.

## Citations
The data comes from:
Velloso, E.; Bulling, A.; Gellersen, H.; Ugulino, W.; Fuks, H. Qualitative Activity Recognition of Weight Lifting Exercises. Proceedings of 4th International Conference in Cooperation with SIGCHI (Augmented Human '13). Stuttgart, Germany: ACM SIGCHI, 2013.
