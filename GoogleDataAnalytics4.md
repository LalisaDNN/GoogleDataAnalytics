# Course 4: Process Data from Dirty to Clean
----
## Module 1: The importance of integrity
### Data integrity
- **Data integrity** refers to the accuracy, completeness, consistency, and trustworthiness of data throughout its entire lifecycle.
- Maintaining data integrity is crucial as it directly impacts the reliability and validity of data analysis.

### Challenges of Data Integrity
- _Data replication, transfer, and manipulation processes_ can all introduce risks to data integrity.
- *Human errors, system failures, viruses, malware, and hacking attempts* pose additional threats to data integrity.
- Data constraints (criterias that determine validity):

|**Data constraints**|Definition|Examples|
|----|----|----|
|**Data type**|Values must be of a certain type: date, number, percentage, Boolean, etc.|If the data type is a date, a single number like 30 would fail the constraint and be invalid|
|**Data range**|Values must fall between predefined maximum and minimum value|If the data range is 10-20, a value of 30 would fail the constraint and be invalid|
|**Mandatory**|Values can’t be left blank or empty|If age is mandatory, that value must be filled in|
|**Unique**|Values can't have a duplicate|Two people can’t have the same mobile phone number within the same service area|
|**Regular expression (regex) patterns**|Values must match a prescribed pattern|A phone number must match ###-###-#### (no other characters allowed)|
|**Cross-field validation**|Certain conditions for multiple fields must be satisfied|Values are percentages and values from multiple fields must add up to 100%|
|**Primary-key**|(Databases only) value must be unique per column|A database table can’t have two rows with the same primary key value.|
|**Set-membership**|(Databases only) values for a column must come from a set of discrete values|Value for a column must be set to Yes, No, or Not Applicable|
|**Foreign-key**|(Databases only) values for a column must be unique values coming from a column in another table|In a U.S. taxpayer database, the State column must be a valid state or territory with the set of acceptable values defined in a separate States table|
|**Accuracy**|The degree to which the data conforms to the actual entity being measured or described|If values for zip codes are validated by street location, the accuracy of the data goes up.|
|**Completeness**|The degree to which the data contains all desired components or measures|If data for personal profiles required hair and eye color, and both are collected, the data is complete.|
|**Consistency**|The degree to which the data is repeatable from different points of entry or collection|If a customer has the same address in the sales and repair databases, the data is consistent.|



----
## Module 2: Clean data for more accurate insights



----
## Module 3: Data cleaning with SQL



----
## Module 4: Verify and report cleaning results



----
## Module 5:
