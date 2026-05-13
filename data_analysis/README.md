## Data analysis notebooks for COMM3180 Group Data Project

This folder contains Jupyter notebooks for data exploration and analysis.

### `dataset_cleaning_ignore.ipynb`
This notebook details the cleaning procedure of the data on the College Scorecard. It primarily keeps only the data columns that are relevant to our analysis.
### `glynn_provisional_analysis.ipynb`
This notebook explores Hypothesis 1 (College Scorecard): Students who attend more racially and demographically diverse universities will demonstrate higher median earnings after graduation, reflecting the broad economic and social benefits of diverse educational environments.
### `census_county.ipynb`
This notebook explores the census data. It combines the data columns on two or more races into one to make the analysis easier. This notebook also has the code computing the Herfindahl–Hirschman index for the racial diversity of the counties. Moreover, it stores the racial proportion of each county to calculate similarity scores between each county and their corresponding state.
### `athletic_scholarship.ipynb`
This notebook explores the hypothesis that higher athletic scholarship for atheltes will equate to high success later post gradution. These schools that have more money for athletic scholarship should hypothetically be able to prepare their students better for a post graduate experience.
### `university_racial`
This notebook uses the data from the College Scorecard and uses the output from `census_county.ipynb` to calculate the diversity and similarity scores for each university.
### `similarity_regression`
This notebook uses uses the output from `university_racial.ipynb` and the data from `glynn_provisional_analysis.ipynb` to conduct data analysis on the relation between diversity and similarity of universities and median income 4 years after graduation, as well as controlling for key variables.
### `DI.DII.NAIA.ipynb`
This notebook looks at the regression of median earnings in 2022 to determine whether a school’s athletic division status — DI, DII, or NAIA — is a meaningful predictor of its graduates’ post-graduation financial outcomes.