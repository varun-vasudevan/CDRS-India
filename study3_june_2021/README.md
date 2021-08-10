Assessment of COVID-19 data reporting in 100+ websites and apps in India
--------------------------------------------------------------------------------
Authors: Varun Vasudevan, Abeynaya Gnanasekaran, Bhavik Bansal, Chandrakant Lahariya, Giridara Gopal Parameswaran, and James Zou

Date of study: May 22, 2021 to June 5, 2021

## Table of contents

- [surveillance_reporting.csv](#surveillance)
- [vaccination_monitoring_data_reporting.csv](#vaccination)
- [vacant_bed_reporting.csv](#bed)
- [list_of_digital_platforms_websites_and_mobile_apps.xlsx](#platforms) 

<!-- toc -->

surveillance_reporting.csv <a name="surveillance"></a>
--------------------------------------

**Columns**: Subnational (State or Union Territory)

**Rows**: Indicators used to measure the quality of COVID-19 surveillance reporting

**Cell values**:

  - Rows 2 to 45
      - 0 indicates that the subnational didn't get a score for that indicator
      - 1 indicates a full score for that indicator
      - NA indicates that the indicator is Not Applicable ('NA') for that subnational
      - A 0 is assigned for 'ease of access' and 'availability in English' for subnationals that do not report any data on their platforms. 
  - Row 46
      - 1 means no violation of privacy 
      - -1 means a violation of privacy
      - A 0 is assigned if data from the subnational is only available through MyGov, i.e., no data is reported on any subnational government platforms.
### Additional Comments
The following should be taken into consideration while normalizing scores.
- Chandigarh doesn't have districts.

## vaccination_monitoring_data_reporting.csv <a name="vaccination"></a>

**Rows**: Subnational (State or Union Territory)

**Columns**: Granular vaccination monitoring indicators 

**Cell values**: 0 indicates *not reporting*, 1 indicates *is reporting*

**Note:** We do not discuss vaccination stratified by gender in the paper. However, we note that none of the subnationals are reporting that for each dose.

## vacant_bed_reporting.csv <a name="bed"></a>

**Rows**: Subnational (State or Union Territory)

**Columns**: (1) Vacant Oxygen / ICU / Ventilator bed reporting status (2) Comments

**Cell values**: 0 indicates *not reporting*, 1 indicates *is reporting*

## list_of_digital_platforms_websites_and_mobile_apps.xlsx <a name="platforms"></a>

This excel sheet contains the list of all national and subnational digital platforms that we used for assessment.  

