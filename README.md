# CHI-Medical-errors
Install Jupyter notebook. Python version >=3.5 is needed.

-- Table 2: "Baseline characteristics of the population" is generated from BASELINE.ipynb

-- Table 3: "Gestation-wise baseline characteristics of the population" is generated from BASELINE.ipynb

-- Table 4: "Significant risks for longer length of stay according to gestation group" is generated from LOS GIT.ipynb

-- Supplementary table 1: "Model comparison for LOS" is generated from Models GIT.ipynb

-- Supplementary table 2: "Distribution of patients in gestation groups" is generated from Distribution_gestation.ipynb

Steps to successfully run individual scripts

#### BASELINE.ipynb ####
1. Install and import the required packages - numpy, matplotlib, seaborn, pandas, tabulate, plotly, statsmodels, itertools
2. Download any of the three available CSVs in a folder
3. Define the path in pd.read_csv in baseline.ipynb
4. Run the script and two baseline tables will be generated (generic population baseline and gestation-wise baseline characteristics).

Note: 1. It will take approximately 20 minutes for the LOS table to render.
      2. Ignore the warnings

