---
services: cosmos-db
platforms: nodejs
author: andrewhoh
---

# Developing a Node.js app with DocumentDB using Azure Cosmos DB
Azure Cosmos DB is a globally distributed multi-model database. One of the supported APIs is the DocumentDB API, which provides a JSON document model with SQL querying and JavaScript procedural logic. This sample shows you how to use the Azure Cosmos DB with the DocumentDB API to store and access data from a Node.js application.

## Running this sample
* Before you can run this sample, you must have the following perquisites:
	* An active Azure DocumentDB account - If you don't have an account, refer to the [Create a DocumentDB account](https://azure.microsoft.com/en-us/documentation/articles/documentdb-create-account/) article.
	* [Node.js](https://nodejs.org/en/) version v0.10.29 or higher.
	* [Git](http://git-scm.com/).

2. Clone this repository using `git clone git@github.com:arramac/azure-cosmosdb-documentdb-nodejs-getting-started.git`

3. Next, substitute the endpoint and authorization key in `config.js` with your Cosmos DB account's values.

	```
	config.endpoint = "~your DocumentDB endpoint here~";
	config.authKey = "~your auth key here~";
	```

5. Run `npm install` in a terminal to install required npm modules
 
6. Run `node app.js` in a terminal to start your start your node application.

## About the code
The code included in this sample is intended to get you quickly started with a Node.js console application that connects to Azure Cosmos DB with the DocumentDB API.

## More information

- [Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/introduction)
- [Azure Cosmos DB : DocumentDB API](https://docs.microsoft.com/azure/documentdb/documentdb-introduction)
- [Azure DocumentDB Node.js SDK](https://docs.microsoft.com/azure/documentdb/documentdb-sdk-node)
- [Azure DocumentDB Node.js SDK Reference Documentation](http://azure.github.io/azure-documentdb-node/)
