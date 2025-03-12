
# CDISC Biomdical Concepts
## SDTM Dataset Specialization for Flare Size

The data provided represents a detailed structure of variables related to the `Flare Size` dataset specialization, denoted by the ID: `FLARESZ`.
It corresponds to the `SR` domain in the Study Data Tabulation Model (SDTM).
                        
Here is a detailed breakdown of the key elements of this dataset specialization:

- High-Level Information:
	 - This dataset is specialized for `Flare Size`, identified with the ID of `FLARESZ`.
	 - It corresponds to the `SR` domain and and draws its source from `SR.SRTESTCD`.
	 - The dataset is designed to be compliant with the SDTMIG versions `3-2` to ``.

- Variable Details:

	1. **SRTESTCD**
		- Data element definition: `N/A`
		- Variable is non-standard: `False`
		- Role: `Topic`
		- Variable must be present: `True`
		- Variable must Be populated: `True`

		- Data Type: `N/A`
		- Length: `N/A`
		- Origin Type: `N/A`
		- Origin Source: `N/A`
		- Variable is a target: `N/A`

		- Assigned Term: `{'conceptId': 'C112283', 'value': 'FLARESZ'}`

		- Codelist Concept ID: `C112024`
		- Submission Value: `SRTESTCD`
		- Concept URL: `https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C112024`
		- Value List: ``

		- Relationship: `SRTESTCD is the code for the value in (IS_DECODED_BY) SRTEST`


	1. **SRTEST**
		- Data element definition: `N/A`
		- Variable is non-standard: `False`
		- Role: `Qualifier`
		- Variable must be present: `True`
		- Variable must Be populated: `True`

		- Data Type: `N/A`
		- Length: `N/A`
		- Origin Type: `N/A`
		- Origin Source: `N/A`
		- Variable is a target: `N/A`

		- Assigned Term: `{'conceptId': 'C112283', 'value': 'Flare Size'}`

		- Codelist Concept ID: `C112023`
		- Submission Value: `SRTEST`
		- Concept URL: `https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C112023`
		- Value List: ``

		- Relationship: `SRTEST decodes the value in (DECODES) SRTESTCD`


	1. **SROBJ**
		- Data element definition: `N/A`
		- Variable is non-standard: `False`
		- Role: `Qualifier`
		- Variable must be present: `True`
		- Variable must Be populated: `True`

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

		- Relationship: `SROBJ is the object of the observation in (IS_ATTRIBUTE_FOR) SRTESTCD`


	1. **SRORRES**
		- Data element definition: `C70856`
		- Variable is non-standard: `False`
		- Role: `Qualifier`
		- Variable must be present: `True`
		- Variable must Be populated: `False`

		- Data Type: `text`
		- Length: `10`
		- Origin Type: `Collected`
		- Origin Source: `Investigator`
		- Variable is a target: `True`

		- Assigned Term: `N/A`

		- Codelist Concept ID: `C66733`
		- Submission Value: `SIZE`
		- Concept URL: `https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C66733`
		- Value List: `LARGE, MEDIUM, SMALL`

		- Relationship: `SRORRES is the result of the test in (IS_RESULT_OF) SRTESTCD`


	1. **SRSTRESC**
		- Data element definition: `C70856`
		- Variable is non-standard: `False`
		- Role: `Qualifier`
		- Variable must be present: `True`
		- Variable must Be populated: `False`

		- Data Type: `text`
		- Length: `10`
		- Origin Type: `Collected`
		- Origin Source: `Investigator`
		- Variable is a target: `True`

		- Assigned Term: `N/A`

		- Codelist Concept ID: `C66733`
		- Submission Value: `SIZE`
		- Concept URL: `https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C66733`
		- Value List: `LARGE, MEDIUM, SMALL`

		- Relationship: `SRSTRESC is the result of the test in (IS_RESULT_OF) SRTESTCD`


	1. **SRLOC**
		- Data element definition: `C13717`
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

		- Codelist Concept ID: `C74456`
		- Submission Value: `LOC`
		- Concept URL: `https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C74456`
		- Value List: ``

		- Relationship: `SRLOC specifies the anatomical location of the performance of the test in (SPECIFIES) SRTESTCD`


	1. **SRLAT**
		- Data element definition: `C25185`
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

		- Codelist Concept ID: `C99073`
		- Submission Value: `LAT`
		- Concept URL: `https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C99073`
		- Value List: ``

		- Relationship: `SRLAT further specifies the anatomical location in (SPECIFIES) SRLOC`


	1. **SRMETHOD**
		- Data element definition: `C82535`
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

		- Codelist Concept ID: `C85492`
		- Submission Value: `METHOD`
		- Concept URL: `https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C85492`
		- Value List: ``

		- Relationship: `SRMETHOD is the method for the test in (SPECIFIES) SRTESTCD`


	1. **SRDTC**
		- Data element definition: `C82515`
		- Variable is non-standard: `False`
		- Role: `Timing`
		- Variable must be present: `True`
		- Variable must Be populated: `False`

		- Data Type: `N/A`
		- Length: `N/A`
		- Origin Type: `Collected`
		- Origin Source: `Investigator`
		- Variable is a target: `N/A`

		- Assigned Term: `N/A`

		- Codelist Concept ID: `N/A`
		- Submission Value: `N/A`
		- Concept URL: `N/A`
		- Value List: ``

		- Relationship: `SRDTC is the start date for (IS_TIMING_FOR) SRTESTCD`
