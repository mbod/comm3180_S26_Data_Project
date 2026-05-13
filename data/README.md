## Data files for COMM3180 Group Project

For our final project we used the following data organized in this file. The contents of these files are as following:
- `racialcensusdata.csv` contains the census data on race and hispanic/latino per county on the United States.
    - Data contains GEO_ID which helps identify the spatial data of each county.
- `racialcensusmetadata.csv` contains metadata on the data above.
- `zip_county_092022.csv` contains a crosswalk between ZIP codes and counties.
- `scholarship_and_ME.xlsx` contains data on scholarships
- `athletic_scholarship_table.xlsx` contains data on athletic scholarships
- `division.I.II.III.diversity.xlsx` contains data per athletic division of the NCAA.
- `Glynn_data` folder contains the following data files concerning the College Scorecard
    - `CollegeScorecardDataDictionary.xlsx` contains a dictionary for the data of the following files.
    - `clean_21_data.csv` contains the clean data on the 2020-2021 school year.
    - `clean_22_data.csv` contains the clean data on the 2021-2022 school year.
    - `combined_data.csv` is the data file merging the data from the previous school year.
    - `Most-Recent-Cohorts-Institution.csv`
    - The dataset includes a few different variables which relate to the general diversity of the institution, especially the rates of different racial/ ethnic groups in the university. In addition to the composition of the university based on these groups, there is also information on whether a university is a Historically Black College or University (hbcu), or a predominantly black institution (40%+ of student body is Black). Similar tags are provided for other groups, for example, Hispanic Serving Institutions (HSIs) are defined by The Higher Education Act as not-for-profit colleges and universities where at least 25% of the full-time equivalent undergraduate enrollment is Hispanic. A few control variables are alsoc included. For example the percent_pell varibale refers to the percent of the school receiving pell grants, while admit_rate refers to the admission rate of a universtiy, with higher admit rates indicatingthat a school is less exclusive, generally. Furthermore, we have each university name, its state and zip code, and its completion rate. 

This folder also contains data obtained by manipulating existing data and compiling new information on top of it. These files include:
- `racial_comp_county.csv` contains the racial distribution of each county and also includes extra rows with the diversity_index, similarity_to_national, and similarity_to_state.
- `racial_comp_state.csv` contains the racial distribution of each state including diversity_index and state_vector, which was used to compute the similarity scores of the county and university.
- `racial_comp_univ.csv` contains the racial distribution of each university, including race_proportion_vector and diversity_index
- `university_similarity.csv` contains the racial analysis data for each school, including diversity_index, similarity_to_county, similarity_to_state, and similarity_to_national.
    
