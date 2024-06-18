**for setting up MySQL:**
- create a schema named **'saad'** in your mySQL workbench.
- change the values of *username* and *password* according to the settings of your mySQL connection because mine is not set to its default user and pass.
- after creating the schema, click the dropdown then right click the **tables folder**. select the `table data import wizard`.
- in the wizard, browse the .json file you downloaded. you may only import one table data at a time, so you have to repeat the wizard until all tables are imported to the schema.
- in the *`idp_signatures`* table, I didn't include the blob data type columns **'employee_signature', 'supervisor_signature', and 'dept_head_signature'**. please ADD these columns manually.
- ALSO: setting up JDBC connection
- my connector.jar may be different from your connector.jar; please double check the libraries. replace the connector.jar with the connector.jar your device has.
