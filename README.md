# mulesoft-artifact - Parent POM

## local setup
- add server information on setings.xml
-- <id>anypoint-exchange</id> 

## Replace Anypoint OrgID to correct Anypoint OrgID
- Replace {Anypoint Org ID.} to your correct OrgID
## Currently works only with 
- https://maven.anypoint.mulesoft.com/api/v2/

## _Known issues
- Issue: https://maven.anypoint.mulesoft.com/api/v3/
-- status: 412 Precondition Failed. Feel free to resolve this

## Mule Connectors
- http-connector
- objectstore
- sockets-connector

## Mule Modules
- apikit
- java
- validation
- xml
 
 ## Runtime
- app.runtime
- mule.maven.plugin.version
- munit.version
- mule.weave.assertions

## Available properties
- mule-sftp-connector.version
- mule-email-connector.version
- mule-file-connector.version
- mule-db-connector.version
- mule-salesforce-connector.version