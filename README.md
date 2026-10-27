# UK MOT Fail Rates by Car Model 2025

First-time MOT fail rates for **238 car models** in Great Britain in **2025**, by age of car, with the six most common areas each model failed on. Built from DVSA's own anonymised MOT test records (33.2 million initial tests of cars and light vans).

Use it to compare how often different models fail their MOT, how fail rates rise with age, and what typically fails (tyres, lamps, brakes, suspension and so on).

## Files
- **mot_fail_rates_by_model_2025.csv**: one row per model: number of initial tests, fail rate for all ages, and fail rate by age band (3-5, 6-8, 9-11, 12-15, 16+ years). An age column is blank when that age had fewer than 200 tests.
- **mot_top_failure_areas_by_model_2025.csv**: per model, the 6 areas of DVSA's inspection manual with the highest share of tests failing in that area. One test can fail in several areas.
- **mot_national_2025.csv**: all cars and light vans in Great Britain, overall and by age band.

## Method
- Initial MOT tests of class 4 vehicles (cars and light vans) in 2025.
- Fail rate = (fails + PRS) / tests, as DVSA calculates its own initial failure rate. PRS = failed, then fixed at the test centre within an hour and passed.
- Age = whole years from the vehicle's first use to the test date.
- Models with at least 1,000 tests. A model is the name DVSA records; trim names (e.g. "Zetec") are grouped under the model and BMW model numbers (e.g. "320") under their series. MINI hatchbacks are not listed because DVSA records many of them only as "MINI".

## Also on
- Kaggle: https://www.kaggle.com/datasets/sonnyp101/uk-mot-fail-rates-by-car-model-2025

## Source and licence
Source: DVSA, anonymised MOT tests and results. Contains public sector information licensed under the [Open Government Licence v3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/).

Compiled by [CompareAutoParts.co.uk](https://compareautoparts.co.uk/mot-pass-rates), where the same figures are shown with the best and worst models at the same age: https://compareautoparts.co.uk/mot-pass-rates

If you use this data, please credit "DVSA MOT data, compiled by CompareAutoParts.co.uk" with a link to the page above.
