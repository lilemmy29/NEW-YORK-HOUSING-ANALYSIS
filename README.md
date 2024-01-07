# NEW-YORK-HOUSING-ANALYSIS
## Overview
This repository contains a comprehensive analysis of the New York Housing Market, offering valuable insights into the factors influencing house prices in the region. The analysis utilizes a regression model to explore relationships between various features and property prices.

## Dataset
The dataset used for this analysis is sourced from Kaggle and includes information such as broker titles, house types, prices, bedroom and bathroom counts, property square footage, addresses, state, administrative and local areas, street names, and geographical coordinates. 

## Analysis Highlights
### Model Summary
R-squared (Explained Variance): 0.986
Adjusted R-squared: 0.984
F-statistic (Model Fit): 841.3
These metrics indicate a highly accurate model for predicting house prices, with nearly 98.6% of the variability explained by the selected features.

### Key Coefficients and Interpretations
BEDS (Bedrooms): Coefficient: -97,590

Interpretation: An increase in bedrooms associates with a decrease of approximately $97,590 in predicted house prices.
BATH (Bathrooms): Coefficient: $356,000

Interpretation: Each additional bathroom corresponds to an average increase of $356,000 in house prices.
PROPERTYSQFT (Property Square Footage): Coefficient: $634.2430

Interpretation: Each additional square foot leads to an increase of approximately $634 in predicted house prices.
P-values
All reported coefficients exhibit p-values below 0.05, indicating statistical significance and strengthening confidence in the model's findings.

Interpretation of Selected Variables
TYPE_Condo for sale: Coefficient: $1,051,000

Interpretation: Condos for sale command, on average, a million-dollar premium compared to other property types.
STATE_Astoria, NY 11101: Coefficient: $1,500,000

Interpretation: Properties in Astoria, NY 11101, carry an average price premium of $1.5 million, emphasizing the impact of location on property values.
Usage
Feel free to explore the Jupyter Notebook for a detailed walkthrough of the analysis. You can run the notebook locally with Jupyter or other compatible environments.

## Contributing
If you find areas of improvement or want to contribute to the analysis, please fork the repository, make your changes, and submit a pull request. We welcome collaboration and additional insights.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
Special thanks to Kaggle user nelgiriyewithana for providing the New York Housing Market dataset.
