**Description:**
This project focuses on analyzing a dataset titled HousingValuation.csv to understand various factors that influence property sale prices. The analysis includes data wrangling, visualization, and building models using various R libraries. The script reads the dataset, inspects its structure, and performs operations such as one-hot encoding for categorical variables. Additionally, several data visualization libraries are loaded to create meaningful plots and graphs.

**Instructions for Running the Project:**
Environment Setup:
Ensure you have R installed on your machine.
Install the following necessary R packages using the commands:
install.packages("psych")
install.packages("dplyr")
install.packages("caret")
install.packages("tidyr")
install.packages("ggplot2")
install.packages("corrplot")
install.packages("plotly")
install.packages("GGally")

Dataset:
Make sure the dataset HousingValuation.csv is placed in the correct working directory.
The dataset should contain columns like LotArea, LotShape, LandContour, Utilities, etc.

Running the Script:
After setting up the environment, open the R script or notebook in RStudio.
Run each section to perform the analysis:
The script starts by loading and inspecting the dataset.
Categorical variables are transformed into numerical values for modeling.
Visualizations and data explorations are created using ggplot2, corrplot, and plotly.

Analysis Flow:
Data inspection and exploration.
One-hot encoding for categorical variables.
Various visualizations to explore the data.
Potential further analysis, including predictive modeling (if included later in the script).
