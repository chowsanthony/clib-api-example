
# CDISC Biomdical Concepts
## SDTM Dataset Specialization for QRS Duration Aggregate

The data provided represents a detailed structure of variables related to the `QRS Duration Aggregate` dataset specialization, denoted by the ID: `QRSAG`.
It corresponds to the `EG` domain in the Study Data Tabulation Model (SDTM).
                        
Here is a detailed breakdown of the key elements of this dataset specialization:

- High-Level Information:
	 - This dataset is specialized for `QRS Duration Aggregate`, identified with the ID of `QRSAG`.
	 - It corresponds to the `EG` domain and and draws its source from `EG.EGTESTCD`.
	 - The dataset is designed to be compliant with the SDTMIG versions `3-2` to ``.

- Variable Details:

	1. **EGTESTCD**
		- Data element definition: `N/A`
		- Variable is non-standard: `False`
		- Role: `Topic`
		- Variable must be present: `True`
		- Variable must Be populated: `False`

		- Data Type: `N/A`
		- Length: `N/A`
		- Origin Type: `N/A`
		- Origin Source: `N/A`
		- Variable is a target: `N/A`

		- Assigned Term: `{'conceptId': 'C117779', 'value': 'QRSAG'}`

		- Codelist Concept ID: `C71153`
		- Submission Value: `EGTESTCD`
		- Concept URL: `https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C71153`
		- Value List: ``

		- Relationship: `EGTESTCD is the code for the value in (IS_DECODED_BY) EGTEST`


	1. **EGTEST**
		- Data element definition: `N/A`
		- Variable is non-standard: `False`
		- Role: `Qualifier`
		- Variable must be present: `True`
		- Variable must Be populated: `False`

		- Data Type: `N/A`
		- Length: `N/A`
		- Origin Type: `N/A`
		- Origin Source: `N/A`
		- Variable is a target: `N/A`

		- Assigned Term: `{'conceptId': 'C117779', 'value': 'QRS Duration, Aggregate'}`

		- Codelist Concept ID: `C71152`
		- Submission Value: `EGTEST`
		- Concept URL: `https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C71152`
		- Value List: ``

		- Relationship: `EGTEST decodes the value in (DECODES) EGTESTCD`


	1. **EGORRES**
		- Data element definition: `C25330`
		- Variable is non-standard: `False`
		- Role: `Qualifier`
		- Variable must be present: `True`
		- Variable must Be populated: `False`

		- Data Type: `text`
		- Length: `8`
		- Origin Type: `Collected`
		- Origin Source: `N/A`
		- Variable is a target: `True`

		- Assigned Term: `N/A`

		- Codelist Concept ID: `N/A`
		- Submission Value: `N/A`
		- Concept URL: `N/A`
		- Value List: ``

		- Relationship: `EGORRES is the result of the test in (IS_RESULT_OF) EGTESTCD`


	1. **EGORRESU**
		- Data element definition: `C42574`
		- Variable is non-standard: `False`
		- Role: `Qualifier`
		- Variable must be present: `True`
		- Variable must Be populated: `False`

		- Data Type: `N/A`
		- Length: `N/A`
		- Origin Type: `N/A`
		- Origin Source: `N/A`
		- Variable is a target: `True`

		- Assigned Term: `N/A`

		- Codelist Concept ID: `C71620`
		- Submission Value: `UNIT`
		- Concept URL: `https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C71620`
		- Value List: `ms, s`

		- Relationship: `EGORRESU is the unit for the value in (IS_UNIT_FOR) EGORRES`


	1. **EGSTRESC**
		- Data element definition: `C25330`
		- Variable is non-standard: `False`
		- Role: `Qualifier`
		- Variable must be present: `True`
		- Variable must Be populated: `False`

		- Data Type: `text`
		- Length: `8`
		- Origin Type: `Collected`
		- Origin Source: `N/A`
		- Variable is a target: `True`

		- Assigned Term: `N/A`

		- Codelist Concept ID: `N/A`
		- Submission Value: `N/A`
		- Concept URL: `N/A`
		- Value List: ``

		- Relationship: `EGSTRESC is the result of the test in (IS_RESULT_OF) EGTESTCD`


	1. **EGSTRESN**
		- Data element definition: `C25330`
		- Variable is non-standard: `False`
		- Role: `Qualifier`
		- Variable must be present: `True`
		- Variable must Be populated: `False`

		- Data Type: `float`
		- Length: `8`
		- Origin Type: `Collected`
		- Origin Source: `N/A`
		- Variable is a target: `True`

		- Assigned Term: `N/A`

		- Codelist Concept ID: `N/A`
		- Submission Value: `N/A`
		- Concept URL: `N/A`
		- Value List: ``

		- Relationship: `EGSTRESN is the result of the test in (IS_RESULT_OF) EGTESTCD`


	1. **EGSTRESU**
		- Data element definition: `C42574`
		- Variable is non-standard: `False`
		- Role: `Qualifier`
		- Variable must be present: `True`
		- Variable must Be populated: `False`

		- Data Type: `N/A`
		- Length: `N/A`
		- Origin Type: `N/A`
		- Origin Source: `N/A`
		- Variable is a target: `True`

		- Assigned Term: `{'conceptId': 'C41140', 'value': 'ms'}`

		- Codelist Concept ID: `C71620`
		- Submission Value: `UNIT`
		- Concept URL: `https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C71620`
		- Value List: ``

		- Relationship: `EGSTRESU is the unit for the value in (IS_UNIT_FOR) EGSTRESN`


	1. **EGCAT**
		- Data element definition: `C25372`
		- Variable is non-standard: `False`
		- Role: `Qualifier`
		- Variable must be present: `False`
		- Variable must Be populated: `False`

		- Data Type: `N/A`
		- Length: `N/A`
		- Origin Type: `N/A`
		- Origin Source: `N/A`
		- Variable is a target: `N/A`

		- Assigned Term: `{'value': 'INTERVAL'}`

		- Codelist Concept ID: `N/A`
		- Submission Value: `N/A`
		- Concept URL: `N/A`
		- Value List: ``

		- Relationship: `EGCAT groups values in (GROUPS) EGTESTCD`


	1. **EGPOS**
		- Data element definition: `C62164`
		- Variable is non-standard: `False`
		- Role: `Qualifier`
		- Variable must be present: `False`
		- Variable must Be populated: `False`

		- Data Type: `N/A`
		- Length: `N/A`
		- Origin Type: `N/A`
		- Origin Source: `N/A`
		- Variable is a target: `N/A`

		- Assigned Term: `N/A`

		- Codelist Concept ID: `C71148`
		- Submission Value: `POSITION`
		- Concept URL: `https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C71148`
		- Value List: ``

		- Relationship: `EGPOS was the subject position during performance of the test in (IS_SUBJECT_STATE_FOR) EGTESTCD`


	1. **EGMETHOD**
		- Data element definition: `C82535`
		- Variable is non-standard: `False`
		- Role: `Qualifier`
		- Variable must be present: `True`
		- Variable must Be populated: `False`

		- Data Type: `N/A`
		- Length: `N/A`
		- Origin Type: `N/A`
		- Origin Source: `N/A`
		- Variable is a target: `N/A`

		- Assigned Term: `N/A`

		- Codelist Concept ID: `C71151`
		- Submission Value: `EGMETHOD`
		- Concept URL: `https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C71151`
		- Value List: ``

		- Relationship: `EGMETHOD is the method for the test in (SPECIFIES) EGTESTCD`


	1. **EGEVAL**
		- Data element definition: `C51824`
		- Variable is non-standard: `False`
		- Role: `Qualifier`
		- Variable must be present: `False`
		- Variable must Be populated: `False`

		- Data Type: `N/A`
		- Length: `N/A`
		- Origin Type: `N/A`
		- Origin Source: `N/A`
		- Variable is a target: `N/A`

		- Assigned Term: `N/A`

		- Codelist Concept ID: `C78735`
		- Submission Value: `EVAL`
		- Concept URL: `https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C78735`
		- Value List: `ADJUDICATION COMMITTEE, INDEPENDENT ASSESSOR, INVESTIGATOR, VENDOR`

		- Relationship: `EGEVAL is the role of the assessor who performed the test in (PERFORMS) EGTESTCD`


	1. **EGDTC**
		- Data element definition: `C82515`
		- Variable is non-standard: `False`
		- Role: `Timing`
		- Variable must be present: `True`
		- Variable must Be populated: `False`

		- Data Type: `N/A`
		- Length: `N/A`
		- Origin Type: `N/A`
		- Origin Source: `N/A`
		- Variable is a target: `N/A`

		- Assigned Term: `N/A`

		- Codelist Concept ID: `N/A`
		- Submission Value: `N/A`
		- Concept URL: `N/A`
		- Value List: ``

		- Relationship: `EGDTC is the date of occurrence for (IS_TIMING_FOR) EGTESTCD`


	1. **EGENDTC**
		- Data element definition: `C82516`
		- Variable is non-standard: `False`
		- Role: `Timing`
		- Variable must be present: `False`
		- Variable must Be populated: `False`

		- Data Type: `N/A`
		- Length: `N/A`
		- Origin Type: `N/A`
		- Origin Source: `N/A`
		- Variable is a target: `N/A`

		- Assigned Term: `N/A`

		- Codelist Concept ID: `N/A`
		- Submission Value: `N/A`
		- Concept URL: `N/A`
		- Value List: ``

		- Relationship: `EGENDTC is the end date for (IS_TIMING_FOR) EGTESTCD`
