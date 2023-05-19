"# Azure_ELT_QA" 

This is a series of demo projects completed as I began working with Azure Data Factory.
The data flows iterate into higher complexity as I itegrated more automation, parameterization, and stored procedures within Azure.
The latest version is a fully automated ingestion service -  
  The process is triggered upon csv placement within the data store. 
  The csv is parsed to determine the schema, table created, and data ingested into the database automatically.
  Certain data is then cleansed for QA purposes.
  A stored procedure is then called to run a frequency distribution on each column, and store the results in the analytics table "a_"[tablename].
