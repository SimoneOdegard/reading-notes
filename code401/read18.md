# Read 09

## Review, Research, and Discussion

**What are serverless functions?** A serverless function is a programmatic function written by a software developer for a single purpose. [resource](https://blog.hubspot.com/website/serverless-functions)

**If you were to create a system that emulated Lambda functions, how would you do it?** You can mock an event and add additional mock data to the context passed to the lambda function. The .env will be where you place your deployment configuration. [resource](https://www.npmjs.com/package/node-lambda)

**Describe how a CDN works** The goal of CDN is to reduce latency. It does this by reducing the physical distance that the request has to travel. A stored cached version of the website content lives in multiple geographical locations around the world. These are called points of presence(PoPs). Each request for content will cause the end user to be mapped to an optimally-located CDN server. It will locate the files and if it fails to do so, it will look for the content on the other servers in the CDN platform. Any data that can be digitized can be delivered through a CDN. [resource](https://www.akamai.com/us/en/cdn/what-is-a-cdn.jsp)

## Terms
- **Serverless Functions** A serverless function is a programmatic function written by a software developer for a single purpose. [resource](https://blog.hubspot.com/website/serverless-functions)
- **Cloud Storage** Cloud storage is a cloud computing model that stores data on the Internet through a cloud computing provider who manages and operates data storage as a service. [resource](https://aws.amazon.com/what-is-cloud-storage/)
- **CDN** A CDN (Content Delivery Network) is a highly-distributed platform of servers that helps minimize delays in loading web page content by reducing the physical distance between the server and the user. This helps users around the world view the same high-quality content without slow loading times. [resource](https://www.akamai.com/us/en/cdn/what-is-a-cdn.jsp)

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**
1. CDN, content delivery network
1. Cloud storage
1. RESTful APIs

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
1. DynamoDB
1. Amazon API Gateway
1. Serverless functions

**What are you most excited about trying to implement or see how it works?** Implementing DynamoDB sounds like it will be interesting. I heard that it's similar to MongoDB.

## Readings
- [AWS API Gateway Overview](https://www.serverless.com/amazon-api-gateway)
- [AWS API Gateway](https://aws.amazon.com/api-gateway/)
- [AWS DynamoDB Guide](https://www.dynamodbguide.com/what-is-dynamo-db/)
- [AWS DynamoDB](https://aws.amazon.com/dynamodb/)
- [Dynamoose](https://dynamoosejs.com/getting_started/Introduction/)

[<== Back](https://simoneodegard.github.io/reading-notes/)