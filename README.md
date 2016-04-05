# securevm-autodeploy-postman
Postman RESTAPI Examples
Some example REST API scripts using Postman.  This uses some environment variables to setup a CloudLink SecureVM instance quickly
Tested on CloudLink 5.5 and ScaleIO 2.0

Created by James Scott


<b>CloudLink_Encrypt_Device.json.postman_collection</b> : Encrypts an SDS device in CloudLink

<b>ScaleIO_Encrypt_SDS.json.postman_collection</b> : Adds an Encrypted SDS
<b>CloudLink_Initial_Setup.json.postman_collection</b> : Setups up a clean CloudLink Center 
(No previous secadmin login can have been done)

<b>CloudLink_Add_Network.json.postman_collection</b> : Adds a Network range to the default CloudLink group

<b>Complete_SDS_Test.json.postman_collection</b> : Runs a complete example, encrypts a device in CLC then adds this to MDM


These are very basic examples, with a number of assumptions/limitations:
- Currently only demos a single device on a single SDS machine (Works on a single IP)
- Expects a single protection domain
