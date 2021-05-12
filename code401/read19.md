# Read 19

## Review, Research, and Discussion

**Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server** They both work with key authentication, HTTPS, CORS, Finegrain Access Control, and Rate limiting. [resource](https://www.express-gateway.io/eg-vs-amazon-aws-api-gateway/)

**List the AWS Database offerings and talk about the pros and cons of each**
AWS Free Tier has an always free, 12 months free, and short term free trial options. [resource](https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=*all&awsf.Free%20Tier%20Categories=categories%23databases&trk=ps_a134p000004ew2dAAA&trkCampaign=acq_paid_search_brand&sc_channel=PS&sc_campaign=acquisition_US&sc_publisher=Google&sc_category=Database&sc_country=US&sc_geo=NAMER&sc_outcome=acq&sc_detail=aws%20sql%20database&sc_content=Sql%20Server_e&sc_matchtype=e&sc_segment=463367431157&sc_medium=ACQ-P|PS-GO|Brand|Desktop|SU|Database|Solution|US|EN|Text&s_kwcid=AL!4422!3!463367431157!e!!g!!aws%20sql%20database&ef_id=CjwKCAjw1uiEBhBzEiwAO9B_HQbnehJgJIhMEu97wSM_WNUJyfCzBgTNirAMgjQ9kDUTHcIJSaooXhoCXioQAvD_BwE:G:s&s_kwcid=AL!4422!3!463367431157!e!!g!!aws%20sql%20database)

**Pros**
- Purpose-built
- Scalability
- Fully managed
- Secure and highly available

**Cons**
- Prices
[resource](https://aws.amazon.com/products/databases/)

**What’s the difference between a FIFO and a standard queue?** Standard queues provide at-least-once delivery, which means that each message is delivered at least once. FIFO queues provide exactly-once processing, which means that each message is delivered once and remains available until a consumer processes it and deletes it. [resource](https://aws.amazon.com/sqs/faqs/#:~:text=Standard%20queues%20provide%20at%2Dleast,processes%20it%20and%20deletes%20it.)

**How can the server be assured a message was properly received?** Published messages are stored across multiple, geographically-separated servers and data centers. If a subscribed endpoint isn't available, Amazon SNS executes a message delivery retry policy. To preserve any messages that aren't delivered before the delivery retry policy ends, you can create a dead-letter queue. [resource](https://aws.amazon.com/sns/?whats-new-cards.sort-by=item.additionalFields.postDateTime&whats-new-cards.sort-order=desc)

## Terms
- **Serverless API** It enables a serverless architecture for web applications. When using API Gateway together with other AWS services, it’s possible to build a fully functional customer-facing web application without maintaining a single server yourself. [resource](https://www.serverless.com/amazon-api-gateway)
- **Triggers** Triggers are pieces of code that will automatically respond to any events. [resource](https://dashbird.io/blog/what-are-aws-lambda-triggers/#:~:text=Triggers%20are%20pieces%20of%20code,ARN%20with%20your%20Lambda%20function.)
- **Dynamo vs Mongo** DynamoDB is a fully managed AWS service, MongoDB can be self installed or fully managed with MongoDB Atlas. ... DynamoDB uses tables, items and attributes, MongoDB uses JSON-like documents. DynamoDB supports limited data types and smaller item sizes; MongoDB supports more data types and has fewer size restrictions. [resource](https://www.xplenty.com/blog/dynamodb-vs-mongodb-differences/#:~:text=DynamoDB%20is%20a%20fully%20managed,fully%20managed%20with%20MongoDB%20Atlas.&text=DynamoDB%20uses%20tables%2C%20items%20and,and%20has%20fewer%20size%20restrictions.)
- **Dynamoose vs Mongoose** 
  - Dynamoose is a modeling tool for Amazon's DynamoDB (inspired by Mongoose). [resource](https://www.npmjs.com/package/dynamoose)
  - Mongoose provides a straight-forward, schema-based solution to model your application data. It includes built-in type casting, validation, query building, business logic hooks and more, out of the box. [resource](https://mongoosejs.com/)

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**
1. Triggers
1. AWS API Gateway + Lambda functions
1. Pub/sub

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
1. SQS
1. SNS
1. Dynamo and dynamoose

**What are you most excited about trying to implement or see how it works?** Messaging seems fun to implement.

## Readings
- [SQS and SNS Basics](https://www.youtube.com/watch?v=UesxWuZMZqI)
- [AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)
- [SNS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SNS.html)
- [SQS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SQS.html)

[<== Back](https://simoneodegard.github.io/reading-notes/)