# KPI200-Index-Extraction

<Logic>
Step1. Reading the page source and Prettify
* using urllib.request's urlopen : URL Reading
* using bs4's beautifulsoup : Tag Classify
* source.prettify() : Indentation

Step2. Extract the only data needed
* using the Key word
* Extract for the single data and make function to adjust all data
* Dates : using date_format function
* Prices

Step3. Save as a list

