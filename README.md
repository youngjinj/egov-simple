# egov-simple
This is a sample for compatibility test of CUBRID Service Broker with PaaS-TA.

## Create Project
eGovFrame > Start > New Template Project: Simple Homepage

## Create Server
File > New > Other... > Server > Server > Cloud Foundry > Cloud Foundry
> Connect to http://api.paas-ta.org/ with an account generated at https://playpark.paas-ta.org

## Changes
- egov-simple\src\main\java\egovframework\config\CloudConfig.java
- egov-simple\src\main\resources\egovframework\egovProps\globals.properties
- egov-simple\src\main\resources\egovframework\script\all_sht_data_cubrid.sql
- egov-simple\src\main\resources\egovframework\script\all_sht_ddl_cubrid.sql
- egov-simple\src\main\resources\egovframework\spring\com\context-datasource.xml
- egov-simple\src\main\resources\egovframework\spring\com\context-idgen.xml
- egov-simple\src\main\resources\egovframework\spring\com\context-sqlMap.xml
- egov-simple\manifest.yml
- egov-simple\pom.xml
