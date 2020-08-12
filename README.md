# Cisco ACI MSO API Collection

This repo contains a couple of Postman collections of the Cisco ACI Multi-Site Orchestrator APIs

You can use the below links to import them directly into your Postman environment.

## MSO Schema Service API
[![Run in Postman](https://run.pstmn.io/button.svg)](https://www.getpostman.com/collections/b6e445486649967c8732)

Allows you to create, update, patch, or delete schemas, as well as query for information associated with a schema.

## MSO Site Service API

[![Run in Postman](https://run.pstmn.io/button.svg)](https://www.getpostman.com/collections/97d4d433efb66bb41114)
 
Allows you to create, update, patch or delete a Site on MSC. (in progress)


# Configuration

You'll need to create an environment in Postman and set the following variables:

| **variable_name** | **info**                                                                                      |
|---------------|--------------------------------------------------------------------------------------------|
| mso           | MSO IP address                                                                                     |
| username      | Auth username                                                                                   |
| password      | Auth password                                                                                   |
| msoToken      | Can have any initial value. It is used to automate the Bearer Token copy to all  requests. |