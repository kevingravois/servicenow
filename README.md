# ServiceNow Coding Standards

## Table of Contents

1. [Fields](#fields)
2. [Tables](#tables)
3. [Variables](#variables)
4. [Logging](#logging)
4. [Script Includes](#script-includes)
5. [Business Rules](#business-rules)
6. [Access Controls (ACL)](#access-control)
6. [UI Scripts](#ui-scripts)

## Fields
<a name="fields--column-label"></a><a name="1.1"></a>
- [1.1](#fields--column-label) **Column labels**
   * Use capital for first letter of first word then lowercase for all subsequent words.
   * Avoid using any puncuation or special characters.
   * Capitalize all letters for acronyms..

   > Why? Most of the system uses this naming convention. Staying consistent we keep the forms looking clean.

      + `Event time`
      + `Validation plan attached`
      + `Job ID`
    
<a name="fields--column-name"></a><a name="1.2"</a>
- [1.2](#fields--column-name) **Column names**: Try to have the column name match the column label. If the column label is too long use either the first couple of words or make an acronym if applicable.

    > Why? By having the labels and names match it will allow for a more obvious association which will expediate troubleshooting and enhance reporting.
    
    + `column label: Work start column name: u_work_start`
