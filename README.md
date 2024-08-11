# Comprehensive Health and Well-Being Study Among Singaporean Seniors

This repository contains the code used for analyzing the impact of a 10-week community health program designed to improve the well-being of seniors aged 60 and above in Singapore. The study evaluates various health constructs such as cognitive performance, sleep quality, BMI, and Waist-Hip Ratio (WHR), and explores the relationships between these constructs to better understand their contribution to overall well-being.

## Project Overview

### Purpose
The project aims to:
1. **Evaluate the impact** of a holistic community health program on modifiable lifestyle factors among seniors.
2. **Investigate the relationships** between social, psychological, and physical factors that contribute to enhanced well-being in elderly communities.

### Key Findings
- **Sleep Quality**: Significant improvement observed from pre- to post-intervention (TP1 to TP2), with a reduction in mean sleep score.
- **Waist-Hip Ratio (WHR)**: Statistically significant reduction from TP1 to TP2, indicating improved fat distribution and reduced health risks.
- **Body Mass Index (BMI)**: Modest changes observed, with some gender-specific differences in WHR.
- **Cognitive Performance**: Strongly influenced by education level, BMI, and medical conditions, but less so by age or gender.

## Repository Contents

- **Code**: The entire workflow—from data preparation and SQLite database creation to analysis—is streamlined within a single R script. The script handles: 
    - **Data Preprocessing**: Cleaning and preparing the dataset for analysis.
    - **Database Creation**: Organizing the data from TP1 and TP2 into an SQLite database, facilitating efficient querying.
    - **SQL Querying**: Using SQL to extract and aggregate data for subsequent statistical analysis.
    - **Statistical Analysis**: Performing t-tests, linear regression models, and other statistical analyses to draw insights.
    - **Visualization**: Creating plots and visualizations to represent the analysis results.

- **Figures**: Visual representations of the analysis results:
  - `bmi_change.png`: Visualization of the change in BMI between TP1 and TP2.
  - `sleep_change.png`: Visualization of the change in sleep quality between TP1 and TP2.
  - `whr_change.png`: Visualization of the change in Waist-Hip Ratio between TP1 and TP2.
  - `whr_change.png`: Visualization of the change in Waist-Hip Ratio between TP1 and TP2.
  
- **`README.md`**: This README file.

## Setup and Installation

1. **Clone the repository**:
```sh
git clone https://github.com/sillyteelypixie/totalwellbeingsg.git
cd totalwellbeingsg
```

## Contributing

Collaborations are welcome! If you would like to contribute to improve this project, please fork the repository and submit a pull request with your proposed changes.

For any questions or feedback, feel free to contact me at:

- **Email**: kfteo@wisc.edu
- **GitHub**: (https://github.com/sillyteelypixie)
