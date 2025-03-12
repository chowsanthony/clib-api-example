
# CDISC Biomdical Concepts
## SDTM Dataset Specialization for Neutrophils, Segmented/Leukocytes in Blood

The data provided represents a detailed structure of variables related to the `Neutrophils, Segmented/Leukocytes in Blood` dataset specialization, denoted by the ID: `NEUTSGLEBLD`.
It corresponds to the `LB` domain in the Study Data Tabulation Model (SDTM).
                        
Here is a detailed breakdown of the key elements of this dataset specialization:

- High-Level Information:
	 - This dataset is specialized for `Neutrophils, Segmented/Leukocytes in Blood`, identified with the ID of `NEUTSGLEBLD`.
	 - It corresponds to the `LB` domain and and draws its source from `LB.LBTESTCD`.
	 - The dataset is designed to be compliant with the SDTMIG versions `3-2` to ``.

- Variable Details:

	1. **LBTESTCD**
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

		- Assigned Term: `{'conceptId': 'C82045', 'value': 'NEUTSGLE'}`

		- Codelist Concept ID: `C65047`
		- Submission Value: `LBTESTCD`
		- Concept URL: `https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C65047`
		- Value List: ``

		- Relationship: `LBTESTCD is the code for the value in (IS_DECODED_BY) LBTEST`


	1. **LBTEST**
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

		- Assigned Term: `{'conceptId': 'C82045', 'value': 'Neutrophils, Segmented/Leukocytes'}`

		- Codelist Concept ID: `C67154`
		- Submission Value: `LBTEST`
		- Concept URL: `https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C67154`
		- Value List: ``

		- Relationship: `LBTEST decodes the value in (DECODES) LBTESTCD`


	1. **LBCAT**
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

		- Assigned Term: `{'value': 'HEMATOLOGY'}`

		- Codelist Concept ID: `N/A`
		- Submission Value: `N/A`
		- Concept URL: `N/A`
		- Value List: ``

		- Relationship: `LBCAT groups values in (GROUPS) LBTESTCD`


	1. **LBORRES**
		- Data element definition: `C36292`
		- Variable is non-standard: `False`
		- Role: `Qualifier`
		- Variable must be present: `True`
		- Variable must Be populated: `False`

		- Data Type: `float`
		- Length: `12`
		- Origin Type: `Collected`
		- Origin Source: `Vendor`
		- Variable is a target: `True`

		- Assigned Term: `N/A`

		- Codelist Concept ID: `N/A`
		- Submission Value: `N/A`
		- Concept URL: `N/A`
		- Value List: ``

		- Relationship: `LBORRES is the result of the test in (IS_RESULT_OF) LBTESTCD`


	1. **LBORRESU**
		- Data element definition: `C48570`
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
		- Value List: `%, fraction of 1`

		- Relationship: `LBORRESU is the unit for the value in (IS_UNIT_FOR) LBORRES`


	1. **LBSTRESC**
		- Data element definition: `C36292`
		- Variable is non-standard: `False`
		- Role: `Qualifier`
		- Variable must be present: `True`
		- Variable must Be populated: `False`

		- Data Type: `float`
		- Length: `12`
		- Origin Type: `Collected`
		- Origin Source: `Vendor`
		- Variable is a target: `True`

		- Assigned Term: `N/A`

		- Codelist Concept ID: `N/A`
		- Submission Value: `N/A`
		- Concept URL: `N/A`
		- Value List: ``

		- Relationship: `LBSTRESC is the result of the test in (IS_RESULT_OF) LBTESTCD`


	1. **LBSTRESN**
		- Data element definition: `C36292`
		- Variable is non-standard: `False`
		- Role: `Qualifier`
		- Variable must be present: `True`
		- Variable must Be populated: `False`

		- Data Type: `float`
		- Length: `12`
		- Origin Type: `Collected`
		- Origin Source: `Vendor`
		- Variable is a target: `True`

		- Assigned Term: `N/A`

		- Codelist Concept ID: `N/A`
		- Submission Value: `N/A`
		- Concept URL: `N/A`
		- Value List: ``

		- Relationship: `LBSTRESN is the result of the test in (IS_RESULT_OF) LBTESTCD`


	1. **LBSTRESU**
		- Data element definition: `C48570`
		- Variable is non-standard: `False`
		- Role: `Qualifier`
		- Variable must be present: `True`
		- Variable must Be populated: `False`

		- Data Type: `N/A`
		- Length: `N/A`
		- Origin Type: `N/A`
		- Origin Source: `N/A`
		- Variable is a target: `True`

		- Assigned Term: `{'conceptId': 'C105484', 'value': 'fraction of 1'}`

		- Codelist Concept ID: `C71620`
		- Submission Value: `UNIT`
		- Concept URL: `https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C71620`
		- Value List: ``

		- Relationship: `LBSTRESU is the unit for the value in (IS_UNIT_FOR) LBSTRESN`


	1. **LBLOINC**
		- Data element definition: `N/A`
		- Variable is non-standard: `False`
		- Role: `Qualifier`
		- Variable must be present: `False`
		- Variable must Be populated: `False`

		- Data Type: `N/A`
		- Length: `N/A`
		- Origin Type: `N/A`
		- Origin Source: `N/A`
		- Variable is a target: `N/A`

		- Assigned Term: `{'value': '26505-8'}`

		- Codelist Concept ID: `N/A`
		- Submission Value: `N/A`
		- Concept URL: `N/A`
		- Value List: ``

		- Relationship: `LBLOINC identifies an observation described by (IDENTIFIES_OBSERVATION) LBTESTCD`


	1. **LBSPEC**
		- Data element definition: `C70713`
		- Variable is non-standard: `False`
		- Role: `Qualifier`
		- Variable must be present: `True`
		- Variable must Be populated: `False`

		- Data Type: `N/A`
		- Length: `N/A`
		- Origin Type: `N/A`
		- Origin Source: `N/A`
		- Variable is a target: `N/A`

		- Assigned Term: `{'conceptId': 'C12434', 'value': 'BLOOD'}`

		- Codelist Concept ID: `C78734`
		- Submission Value: `SPECTYPE`
		- Concept URL: `https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C78734`
		- Value List: ``

		- Relationship: `LBSPEC is the specimen tested in (IS_SPECIMEN_TESTED_IN) LBTESTCD`


	1. **LBFAST**
		- Data element definition: `C83309`
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

		- Codelist Concept ID: `C66742`
		- Submission Value: `NY`
		- Concept URL: `https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C66742`
		- Value List: `N, Y`

		- Relationship: `LBFAST is the subject's fasting status during the performance of the test in (IS_SUBJECT_STATE_FOR) LBTESTCD`
