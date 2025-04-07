# DATA-CLEANING-AND-PREPROCESSING

Step-by-Step Cleaning Process in Excel

1. Removed Duplicates
	•	Used Excel’s Remove Duplicates on all columns.
	•	Rows removed: 12 duplicates found and deleted.

2. Handled Missing Values
	•	Columns with missing values:
	•	director: Many entries missing — left as is since some titles may not have a director listed.
	•	cast: Same situation — left as is.
	•	country: Filled missing values with "Unknown".
	•	date_added: Filled missing dates with "01-Jan-1900" as a placeholder for missing.
	•	rating: Filled missing with "Not Rated".

3. Standardized Text Values
	•	Cleaned country, type, rating fields:
	•	Trimmed spaces, corrected inconsistent formats.
	•	Example: changed "united States" → "United States", "tv-MA" → "TV-MA".

4. Formatted Dates
	•	date_added formatted to dd-mm-yyyy using Excel’s date formatting.

5. Renamed Columns
	•	Standardized all column headers:
	•	Removed spaces, converted to lowercase, e.g.:
	•	Show Id → show_id
	•	Date Added → date_added
	•	Release Year → release_year

6. Checked Data Types
	•	Ensured:
	•	release_year is integer.
	•	date_added is date.
	•	duration is left as text (since it contains both mins and seasons).


SUMMARY:-

Step                                                                                       Description
Removed Duplicates                                                       12 duplicate rows removed.

Handled Missing Values                                                   Filled blanks in country, rating, and date_added with placeholders.

Standardized Text Fields                                                 Country names and ratings cleaned and formatted consistently.

Date Formatting                                                          date_added converted to dd-mm-yyyy.

Column Headers                                                           Renamed to lowercase, underscore-separated for consistency.

Data Types                                                               Checked and cleaned for numeric/date/text consistency.
