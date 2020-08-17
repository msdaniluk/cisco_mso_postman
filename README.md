[![published](https://static.production.devnetcloud.com/codeexchange/assets/images/devnet-published.svg)](https://developer.cisco.com/codeexchange/github/repo/msdaniluk/cisco_mso_postman)
# Cisco ACI MSO API Collection

This repo contains a couple of Postman collections of the Cisco ACI Multi-Site Orchestrator APIs

You can use the below links to import them directly into your Postman environment.
## How to import the collections into Postman

+ Download the Postman application for your OS [Postman Downloads](https://www.postman.com/downloads/)
+ To open the Postman application
+ Click on the file tab and then click import
+ Choose the folder method you want to import an item
+ Choose the `MSO Schema Service API.postman_collection.json` or `MSO Site Service API.postman_collection.json` files to import and press open. Postman will automatically import the item.

## MSO Schema Service API
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/aedfbf9cb1941c01e110)

Allows you to create, update, patch, or delete schemas, as well as query for information associated with a schema.

## MSO Site Service API

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/8ffe8bfe085f9f1cf6d1)
 
Allows you to create, update, patch or delete a Site on MSC. (in progress)


# Configuration

You'll need to create an environment in Postman and set the following variables:

| **variable_name** | **info**                                                                                      |
|---------------|--------------------------------------------------------------------------------------------|
| mso           | MSO IP address                                                                                     |
| username      | Auth username                                                                                   |
| password      | Auth password                                                                                   |
| msoToken      | Can have any initial value. It is used to automate the Bearer Token copy to all  requests. |