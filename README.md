# upper_lowercase_output
### LOWER() AND UPPER()
LOWER() function is applied to the values in the  selected column
UPPER() function is applied to the values in the   selected column

### USE CASE
The use of converting text to lowercase or uppercase in a database query, as demonstrated by the LOWER() and UPPER() functions, serves several purposes:

#### Consistency in Comparison:

When comparing or searching for data, it ensures case-insensitive comparisons. For example, if you want to find a customer by name, regardless of whether the input is in uppercase or lowercase, transforming the input and the stored data to a common case (either lowercase or uppercase) ensures accurate and consistent matching.

#### Uniform Display:
It helps in presenting data in a consistent format. Displaying names or text in a consistent case format (either all uppercase or all lowercase) can enhance the visual presentation of information in reports or user interfaces.

#### Sorting:
When ordering or sorting data, transforming the text to a specific case ensures that the sorting is done in a consistent manner. This is especially useful when sorting strings in a case-insensitive manner.

#### Data Normalization:
It contributes to data normalization by reducing the potential for duplicate entries due to variations in case. This is important for maintaining data integrity and avoiding issues related to case sensitivity.

#### Search Queries:
It facilitates case-insensitive searches. For instance, when using LIKE or similar search conditions in SQL queries, transforming both the search term and the stored data to a common case ensures that the search is not case-sensitive.

#### Data Cleaning:
It can be used for data-cleaning purposes. By standardizing the case of text data, you can clean up inconsistencies that might arise from data entry errors or variations.

## SUMMARY
Using LOWER() and UPPER() functions in SQL queries helps to ensure data consistency, facilitate accurate comparisons, and improve the overall quality and usability of the data in a database.
