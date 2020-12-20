Details of the paper
--------------------
Title: Disparity in the quality of COVID-19 data reporting across India.
Authors: Varun Vasudevan, Abeynaya Gnanasekaran, Varsha Sankar, Siddarth A. Vasudevan, James Zou

Date of study: May 19, 2020 to June 1, 2020


Description for tidy_scoring_data.xlsx
--------------------------------------
**Columns**: State or Union Territory

**Rows**: Indicators used to measure the quality of COVID-19 data reporting

**Cell values**:
	- Rows 2 to 45
		- 0 indicates that the state didn't get a score for that indicator
		- 1 indicates a full score for that indicator
		- NA indicates that the indicator is Not Applicable ('NA') for that state 
	- Row 46
		- NA is not applicable. NA is assigned if a state doesn't report any data.
		- 1 means no violation of privacy 
		- -1 means a violation of privacy
		
Additional Comments
--------------------
The following should be taken into consideration while normalizing scores.
- Chandigarh doesn't have districts.
- Andaman & Nicobar Islands, Goa, Ladakh and Tripura didn't have any deaths until June 1


