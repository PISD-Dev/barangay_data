# Philippine Barangay Officials — 2023 BSKE

## Latest Release - Ver 1.0

## Description

A structured dataset of Barangay Officials from the National Capital Region elected in the
2023 Barangay and Sangguniang Kabataan Elections. This dataset was consolidated by the Philippine Institute for Student Democracy (PISD) Inc. based on publicly available data from the Department of Interior and Local Government (DILG) 

## Disclaimer

The original data source may contain errors, omissions, and inconsistencies. These may include missing or incomplete telephone numbers, malformed or incorrectly formatted phone numbers, incorrect or misspelled names of officials, and other inaccuracies in the recorded information.

While reasonable efforts have been made to clean, standardize, and validate the dataset, errors from the original source may remain. The cleaned dataset should therefore not be treated as an authoritative or error-free record. Users are encouraged to verify individual records against official or primary sources when accuracy is critical.
## Coverage

- Country: Philippines
- Region: National Capital Region (NCR)
- Election: 2023 BSKE
- Geographic level: Barangay

# Data Dictionary

| Field | Description |
|---|---|
| `TERM` | The electoral or administrative term during which the official is serving. |
| `REGION` | The administrative region where the barangay is located. |
| `CITYMUN` | The city or municipality where the barangay is located. |
| `BARANGAY` | The name of the barangay where the official serves. |
| `POSITION` | The elected or appointed position held by the individual in the barangay government. |
| `TERM IN PRESENT POSITION` | The length of time the individual has served in their current position, based on the available source data. |
| `LASTNAME` | The individual's family or last name. |
| `FIRSTNAME` | The individual's given or first name. |
| `MIDDLENAME` | The individual's middle name, where available. |
| `SUFFIX` | A name suffix associated with the individual, such as `Jr.`, `Sr.`, `II`, or `III`, where applicable. |
| `EMAIL_ADD` | The email address associated with the official, as provided by the source. |
| `BRGY_TELNO` | The telephone or contact number associated with the barangay or official, as provided by the source. |
| `PHONE_TYPE` | The type or classification of telephone number recorded in `BRGY_TELNO`, such as landline or mobile, where specified. |

## Source

Department of the Interior and Local Government (DILG), **Barangay Officials Directory**.

- [Barangay Officials Directory — Search](https://www.dilg.gov.ph/barangay-officials-directory/search)
- [Barangay Officials Directory — Masterlist](https://www.dilg.gov.ph/barangay-officials-directory/masterlist)

Accessed: **September 18 2026**
## Processing

Processing included:

- Standardizing field names and data formats.
- Cleaning and normalizing text values, including names and geographic
  information.
- Standardizing position names and other categorical values.
- Identifying and handling duplicate records.
- Comparing records across available source data to identify inconsistencies.
- Cleaning telephone number fields and identifying malformed or incomplete
  numbers where possible.
- Preserving missing values rather than introducing values that were not
  present in the source.
- Separating and retaining name components such as surname, first name,
  middle name, and suffix where available.
- Performing validation checks for missing, duplicate, and potentially
  inconsistent records.

The processing was performed programmatically where possible to make the
transformation reproducible. No attempt was made to infer or fabricate
information that was not present in the source data.

Because the source data may contain errors or omissions, including incorrect
names, missing telephone numbers, and malformed telephone numbers, the
processed dataset may retain some inaccuracies. The processing should
therefore be understood as a data-cleaning and standardization effort rather
than an independent verification of every record.

## Next Steps

Following the release of this initial dataset, further efforts will be undertaken to identify and resolve errors using publicly available sources. Obvious spelling errors, inconsistent contact details, and other discrepancies will be reviewed and corrected where they can be reliably verified. All corrections will be documented to maintain a transparent record of changes from the original source data.


## License

### Underlying Government Data

The underlying data are sourced from the Department of the Interior and
Local Government (DILG) Barangay Officials Directory. Rights in government
works are subject to Philippine law, including Section 176 of Republic Act
No. 8293 (Intellectual Property Code of the Philippines).

### This Dataset

The cleaning, transformation, normalization, documentation, and other
original contributions in this repository are made available under the
Creative Commons Attribution 4.0 International (CC BY 4.0) license.