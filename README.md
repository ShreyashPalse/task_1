| Step | Action Performed                                              |
| ---- | ------------------------------------------------------------- |
| 1    | Prints initial missing values using `.isnull().sum()`         |
| 2    | Removes duplicate rows using `.drop_duplicates()`             |
| 3    | Renames column headers to lowercase with underscores          |
| 4    | Converts country names to title case                          |
| 5    | Parses and standardizes the `date_added` column as `datetime` |
| 6    | Ensures `release_year` is numeric (`int`)                     |
| 7    | Prints missing values after transformation                    |
| 8    | Saves the cleaned dataset to a new CSV file                   |

| Change Description              | Details                                                                          |
| ------------------------------- | -------------------------------------------------------------------------------- |
| **Initial Rows**                | 8,807                                                                            |
| **Duplicates Removed**          | 0 (No duplicate rows found)                                                      |
| **Column Renaming**             | All column names converted to `lowercase_with_underscores`                       |
| **Missing Values Handling**     | Identified but not filled                                                        |
| **Date Format Standardization** | `date_added` converted to proper `datetime` format                               |
| **Text Standardization**        | Country names standardized to Title Case (e.g., `united states → United States`) |
| **Data Type Fixes**             | `release_year` as integer, `date_added` as datetime                              |
