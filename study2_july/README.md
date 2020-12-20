Variation in COVID-19 Data Reporting Across India: 6 Months into the Pandemic
--------------------------------------------------------------------------------
Authors: Varun Vasudevan, Abeynaya Gnanasekaran, Varsha Sankar, Siddarth A. Vasudevan, James Zou

Date of study: July 12, 2020 to July 25, 2020


Description for tidy_scoring_data.xlsx
--------------------------------------
**Columns**: State or Union Territory

**Rows**: Indicators used to measure the quality of COVID-19 data reporting

**Cell values**:
  - Rows 2 to 45
      - 0 indicates that the state didn't get a score for that metric
      - 1 indicates a full score for that metric
      - NA indicates that the indicator is Not Applicable ('NA') for that state 
  - Rows 46
      - NA is not applicable. NA is assigned if the state doesn't report any data.
      - 1 means no violation of privacy 
      - -1 means a violation of privacy
		
Additional Comments
--------------------
The following should be taken into consideration while normalizing scores.
- Chandigarh doesn't have districts.
- Lakshadweep was excluded because it had less than 10 cases as of July 12, 2020
- Andaman & Nicobar Islands, Manipur, Mizoram and Sikkim didn't have any deaths until July 25, 2020
