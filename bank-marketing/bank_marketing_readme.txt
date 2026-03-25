================================================================================
BANK MARKETING DATASET - README
================================================================================

Dataset Source (Original)
-------------------------
This dataset is derived from the Bank Marketing dataset in the UCI Machine
Learning Repository (direct marketing / phone campaign data from a Portuguese
banking institution):

  URL: https://archive.ics.uci.edu/dataset/222/bank+marketing

  Citation: Moro, S., Rita, P., & Cortez, P. (2014). Bank Marketing [Dataset].
            UCI Machine Learning Repository. https://doi.org/10.24432/C5K306

  Introductory paper: Moro, S., Cortez, P., & Rita, P. (2014). A data-driven
            approach to predict the success of bank telemarketing.
            Decision Support Systems.

  License: Creative Commons Attribution 4.0 International (CC BY 4.0)


Dataset Description
-------------------
- Dataset: Bank Marketing (full-bank style: all examples, 16 inputs + class)
- Instances: 45,211
- Input features: 16
- Task: Binary classification — predict whether the client subscribes to a
        term deposit (original labels: "yes" / "no")
- Feature types: Integer and categorical (per UCI variable descriptions)
- Missing values (UCI): Officially none; several fields use an explicit
        category "unknown" where information was not recorded.


Modifications (this copy)
-------------------------
This file is a slightly modified version of the standard UCI release:

  - The outcome column was renamed from `y` to `target` for clarity. Values
    remain "yes" and "no" as in the original dataset.

All feature names, encodings, and row content otherwise follow the original
bank marketing campaign records. The file uses semicolon (`;`) as the field
separator (common for this dataset variant).


Attribute Information (aligned with UCI)
------------------------------------------
Bank client data:
 1. age          - Age (numeric)
 2. job          - Type of job (categorical)
 3. marital      - Marital status (categorical)
 4. education    - Education level (categorical)
 5. default      - Credit in default? (binary: yes/no)
 6. balance      - Average yearly balance, euros (numeric)
 7. housing      - Housing loan? (binary: yes/no)
 8. loan         - Personal loan? (binary: yes/no)

Last contact (current campaign):
 9. contact       - Communication type (e.g. cellular, telephone, unknown)
10. day           - Last contact day of month (numeric)
11. month         - Last contact month (categorical)
12. duration      - Last contact duration, seconds (numeric)

Other campaign attributes:
13. campaign      - Number of contacts in this campaign for this client
14. pdays         - Days since previous contact (-1 = not previously contacted)
15. previous      - Number of contacts before this campaign
16. poutcome      - Outcome of previous campaign (categorical)

Target: target — client subscribed a term deposit? (binary: "yes", "no")
         (UCI name: y)


Files
-----
- bank-marketing.csv        : Tabular data (semicolon-separated)
- bank_marketing_readme.txt : This file


================================================================================
Last updated: March 2026
================================================================================
