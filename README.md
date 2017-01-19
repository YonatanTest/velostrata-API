# Velostrata API

In addition to GUI, Velostrata enables managing by third party management tools for automation, monitoring and catalogs. A REST API is provided, as well as powershell implementation (using REST). Other implementations are provided here for reference and use. 

The API enables third party to manage:

1.	Cloud Extensions 

2.	VMs 

3.	Tasks


The API is served by a REST Web service, protected with basic HTTP authentication.

REST URL structure: https:///velostrata/api//

API input and output objects are serialized in JSON format.

Access is allowed for a single user named ‘apiuser’, the password is the subscription ID that was provided by the customer during Mgmt OVA deployment. 

This repository includes:
- The REST API documentation in the YAML format. 
- Reference implementations TBD (powershell, python etc.)- 
