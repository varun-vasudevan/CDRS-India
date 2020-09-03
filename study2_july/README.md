Variation in COVID-19 data reporting across India - six months into the pandemic
--------------------------------------------------------------------------------
Authors: Varun Vasudevan, Abeynaya Gnanasekaran, Varsha Sankar, Siddarth A. Vasudevan, James Zou

Date of study: July 12, 2020 to July 25, 2020


Description for tidy_scoring_data.csv
--------------------------------------
**Columns**: State or Union Territory

**Rows**: Metrics used to measure the quality of COVID-19 data reporting

**Cell values**:
  - Rows 2 to 45
      - 0 indicates that the state didn't get a score for that metric
      - 1 indicates a full score for that metric
      - empty cell indicates that the metric is Not Applicable ('NA') for that state 
  - Rows 46 to 50
      - NA is not applicable. Example, if a state doesn't report any data on   "confirmed", then "no compromise in privacy Confirmed" is NA for that state.
      - 1 means no violation of privacy 
      - -1 means a violation of privacy
		
Additional Comments
--------------------
- Chandigarh doesn't have districts.
- Lakshadweep was excluded because it had less than 10 cases as of July 12, 2020
- Andaman & Nicobar Islands, Manipur, Mizoram and Sikkim didn't have any deaths until July 25, 2020
- Rows 46 to 50 were merged to calculate the privacy score. 
    - Merged entry is -1 if at least one entry is -1
    - Merged entry is 0 if all entries are 0
    - Otherwise, merged entry is a 1

