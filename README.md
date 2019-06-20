# EntityFramework.Core.Generators
T4 templates to generate models for Stored Procedures and Views for Microsoft Sql 2012 and above.

# Settings
You can set the schema name of the views you want to generate models for. Preferably do not use dbo as you would probably want to control which views are accessible in the model. Some views may be your own...

Example:
string schemaName="Myschema";
string connectionString = standard connection string used to execute the queries

--What is your basenamespace for alla to be created under
string basenamespace = "Project.DataLayer"; 

--Wow this is bad naming FIXME
string namespaceString = basenamespace + ".Data";
string modelnamespaceString = basenamespace + ".Models";

--Name of the EF.Core context to be generated
string contextName= "PenserCrmDbContext";
string modelName= "Models";
bool generateContextConstructor=true;

# Views
tba

# Stored Procedures
tba
