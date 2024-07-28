# KEPLER_ML_project

### --Author: Krishna Vamsy K

## Introduction
This project aims to classify exoplanet candidates (ie. Flase positive or confirmed) using Kepler space telescope data. We leverage machine learning techniques to analyze and predict celestial bodies' characteristics based on light intensity.

## Dataset
The dataset used in this project is sourced from https://www.kaggle.com/datasets/nasa/kepler-exoplanet-search-results/data.
<br>
It includes data of star brightness, which is crucial for detecting exoplanets.

## Dataset Columns

The dataset includes several important columns, which are described below:
- **kepoi_name:**
  - Definition: A KOI (Kepler Object of Interest) is a target identified by the Kepler Project that displays at least one transit-like sequence within Kepler time-series photometry.
  - Characteristics: Appears to be of astrophysical origin and initially consistent with a planetary transit hypothesis.
- **kepler_name:**
  - Definition: These names are intended to clearly indicate a class of objects that have been confirmed or validated as planets.
  - Characteristics: Represents a step up from the planet candidate designation.
- **koi_disposition:**
  - Definition: The disposition in the literature towards this exoplanet candidate.
  - Possible Values:
    - CANDIDATE
    - FALSE POSITIVE
    - NOT DISPOSITIONED
    - CONFIRMED
- **koi_pdisposition:**
  - Definition: The disposition Kepler data analysis has towards this exoplanet candidate.
  - Possible Values:
    - FALSE POSITIVE
    - NOT DISPOSITIONED
    - CANDIDATE
- **koi_score:**
  - Definition: A value between 0 and 1 that indicates the confidence in the KOI disposition.
  - Characteristics:
    - For CANDIDATEs: A higher value indicates more confidence in its disposition.
    - For FALSE POSITIVEs: A higher value indicates less confidence in that disposition.



