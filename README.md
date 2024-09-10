# Database Commands Overview

This section outlines the various functions available for performing operations on predefined tables or relations within the database.

## 1. Insert
- **Purpose**: Insert new tuples into the specified table or relation.
- **Input**: 
  - Table name
  - Tuple values
- **Operation**: The provided tuple values will be inserted into the corresponding table.

## 2. Delete
- **Purpose**: Remove rows from a specific table based on a condition.
- **Input**:
  - Table name
  - Condition (to identify rows for deletion)
- **Operation**: The rows matching the condition in the specified table will be deleted.

## 3. Update
- **Purpose**: Update existing rows in a table when there are changes.
- **Input**:
  - Table name
  - Attribute to be updated
  - New value
  - Condition (to identify which rows to update)
- **Operation**: The specified attribute in the rows matching the condition will be updated with the new value.

## 4. Selection
- **Purpose**: Select specific rows based on a condition.
- **Input**:
  - Table name
  - Condition (to filter rows)
- **Operation**: The rows from the table that satisfy the condition will be displayed as output.

## 5. Projection
- **Purpose**: Query the database to display certain attributes of the rows.
- **Input**:
  - Table name
  - Columns to be projected
  - Condition (to filter rows)
- **Operation**: The values of the specified columns from the rows that satisfy the condition will be displayed as output.

## 6. Aggregate
- **Purpose**: Retrieve aggregate values like minimum, maximum, sum, or average of attributes in a table.
- **Input**:
  - Table name
  - Column name
  - Operation (min, max, sum, avg)
  - Condition (optional)
- **Operation**: The result of the aggregate operation (e.g., sum, average) on the selected column will be displayed.

## 7. Search
- **Purpose**: Search for a specific entry in the database.
- **Input**:
  - Table name
  - Column to search
  - Value to search for
- **Operation**: The rows containing the specified value in the given column will be displayed as output.

## 8. User-Defined Queries
These queries are designed to provide specific results related to the game context.

### Best Players of a Guild
- **Purpose**: Retrieve information about the best players in a specified guild.
- **Input**:
  - Guild ID
- **Operation**: Information about the best players in the specified guild will be displayed as output.

### Order of Countries with Best Players
- **Purpose**: Display countries in descending order based on the number of best players.
- **Operation**: A list of countries ordered by the number of best players will be displayed as output.
