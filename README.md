# warehouse-excerpt
This repo contains selected items from a private project, Data Warehouse.

<p><b>identify_zkgu_personal_Persons</b> and <b>identify_zkgu_personal_Person</b> provide a Python-based mechanism to identify person entities implemented as MS SQL Server stored procedure. Identification is needed in order to link entities from different sources - e.g. staff database, accounting database, educational programs database and so on. 
<p>It is based on the absense of globally-recognizable unique entity identifiers and is based on layered identification: if a single attribute is insufficient (for example, person name is not unique), it adds second identifying attribute (position, department, date of birth) and so on. It allows for simple identification in most cases while supporting an in-depth processing of difficult cases when multiple persons share many common attributes.
