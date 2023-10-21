# Predicting the Age of Abalone from Physical Measurements

Dive deep into the regression analysis of predicting abalones' age based on their physical measurements. This analysis utilizes both Linear Regression and K-Nearest Neighbors (KNN) modeling techniques.

## Table of Contents

1. [Overview](#overview)
2. [Dataset & Citation](#dataset--citation)
3. [Key Insights](#key-insights)
4. [Performance Metrics](#performance-metrics)
5. [Conclusions](#conclusions)
6. [Dependencies](#dependencies)
7. [License](#license)

## Overview

This analysis focuses on predicting the age of abalones (indicated by the number of rings) using various physical characteristics. The models employed for this task include Linear Regression and K-Nearest Neighbors regression.

## Dataset & Citation

The dataset is sourced from the [UCI Machine Learning Repository](https://doi.org/10.24432/C55C7W). 

**Citation:**  
Nash, Warwick; Sellers, Tracy; Talbot, Simon; Cawthorn, Andrew; and Ford, Wes. (1995). Abalone. UCI Machine Learning Repository.

## Key Insights

- **Data Distribution:** The data showcases diverse distributions across the 'Sex' categories. For outlier detection and appropriate treatment, the dataset was segmented based on 'Sex'.
- **Feature Importance:** Important features were identified using the Recursive Feature Elimination (RFE) technique.
- **Model Comparison:** Post K-value tuning, the KNN model outshines the initial linear regression model in age prediction tasks.

## Performance Metrics

- The tuned KNN model surpasses the initial linear regression model in age prediction accuracy. Notably, after K-value optimization, the KNN model exhibits improved results against its linear regression counterpart.

## Conclusions

Both models, while displaying a fair degree of accuracy, fall short of optimal performance in predicting abalones' age. This underlines the necessity for more intricate study and analysis.

## Dependencies

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## License

MIT License

Copyright (c) 2023 Ben Khalesi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
