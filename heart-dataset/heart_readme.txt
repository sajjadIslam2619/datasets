================================================================================
HEART DATASET - README
================================================================================

Dataset Source (Original)
-------------------------
The heart dataset was collected from the UCI Machine Learning Repository:

  URL: https://archive.ics.uci.edu/dataset/145/statlog+heart

  Citation: Statlog (Heart) [Dataset]. UCI Machine Learning Repository.
            https://doi.org/10.24432/C57303

  License: Creative Commons Attribution 4.0 International (CC BY 4.0)


Dataset Description
-------------------
- Dataset: Statlog (Heart)
- Instances: 270 (original)
- Features: 13
- Task: Classification (absence or presence of heart disease)
- Feature types: Categorical, Real (continuous, binary, ordered, nominal)


Modifications
-------------
Missing values have been introduced in this copy of the dataset for educational
or analysis purposes. Specifically:
  - 3 missing values were introduced in the 'ca' (number of major vessels) column
  - 5 missing values were introduced in the 'thal' column

Missing values may appear as Null, NaN, or empty values.


Attribute Information (Original)
--------------------------------
 1. age                        - Age
 2. sex                        - Sex
 3. chest pain type             - 4 values
 4. resting blood pressure     - (rest-bp)
 5. serum cholesterol          - mg/dl (serum-chol)
 6. fasting blood sugar > 120   - Binary (fasting-blood-sugar)
 7. resting electrocardiographic results - (0, 1, 2)
 8. maximum heart rate achieved - (max-heart-rate)
 9. exercise induced angina    - Binary (angina)
10. oldpeak                    - ST depression induced by exercise relative to rest
11. slope                      - Slope of peak exercise ST segment
12. ca                         - Number of major vessels (0-3) colored by fluoroscopy
13. thal                       - 3 = normal; 6 = fixed defect; 7 = reversible defect

Target: Absence (1) or presence (2) of heart disease


Files
-----
- heart_dataset.ipynb          : Jupyter notebook with loading, missing-value
                                  introduction, and analysis
- heart_dataset_with_missing_values.csv : Dataset with introduced missing values
- readme.txt                   : This file


================================================================================
Last updated: February 2025
================================================================================
