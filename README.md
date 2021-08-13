# egov-simple
This is a sample for compatibility test of CUBRID Service Broker with PaaS-TA.

## Create Project
eGovFrame > Start > New Template Project: Simple Homepage

## Create Server
File > New > Other... > Server > Server > Cloud Foundry > Cloud Foundry
> Connect to http://api.paas-ta.org/ with an account generated at https://playpark.paas-ta.org

## Changes
- src\main\java\egovframework\config\CloudConfig.java
- src\main\resources\egovframework\egovProps\globals.properties
- src\main\resources\egovframework\script\all_sht_data_cubrid.sql
- src\main\resources\egovframework\script\all_sht_ddl_cubrid.sql
- src\main\resources\egovframework\spring\com\context-datasource.xml
- src\main\resources\egovframework\spring\com\context-idgen.xml
- src\main\resources\egovframework\spring\com\context-sqlMap.xml
- manifest.yml
- pom.xml
