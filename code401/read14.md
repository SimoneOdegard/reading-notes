# Read 14

## Review, Research, and Discussion

**What’s the difference between a FIFO and a standard queue?** Standard queues provide at-least-once delivery, which means that each message is delivered at least once. FIFO queues provide exactly-once processing, which means that each message is delivered once and remains available until a consumer processes it and deletes it. [resource](https://aws.amazon.com/sqs/faqs/#:~:text=Standard%20queues%20provide%20at%2Dleast,processes%20it%20and%20deletes%20it.)

**How can the server be assured a message was properly received?** You can use status checks, which are performed every minute, that returns a pass or fail status. If checks pass then the instance is OK. [resource](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/monitoring-system-instance-status-check.html)

**What classic design pattern is best represented by event driven programming?** The observer design pattern. [resource](https://www.sitepoint.com/javascript-design-patterns-observer-pattern/)

**How do you test an event driven system?**
1. Ensure supporting topics exist
2. Start the application under test
3. Send some input events
4. Wait until the applicaiton has finished processing the test input
5. Assert that it looks right
[resource](https://www.confluent.io/blog/testing-event-driven-systems/)

## Terms

- **FIFO Queue** FIFO queues provide exactly-once processing, which means that each message is delivered once and remains available until a consumer processes it and deletes it. Duplicates are not introduced into the queue. [resource](https://aws.amazon.com/sqs/faqs/#:~:text=Standard%20queues%20provide%20at%2Dleast,processes%20it%20and%20deletes%20it.)
- **Pub/Sub** Pub/sub: The messaging infrastructure keeps track of subscriptions. When an event is published, it sends the event to each subscriber. After an event is received, it cannot be replayed, and new subscribers do not see the event. [resource](https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/event-driven#:~:text=An%20event%20driven%20architecture%20can,do%20not%20see%20the%20event.)

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**
A lot of these are new terms for me. But I'm excited to learn more!

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
1. AWS: SNS, and SQS
1. Pub/Sub
1. Understanding queueing service a bit better.

**What are you most excited about trying to implement or see how it works?** AWS!!! I'm super excited to learn more and work with AWS.

## Readings
[AWS SNS and SQS](https://www.youtube.com/watch?v=mXk0MNjlO7A)

[<== Back](https://simoneodegard.github.io/reading-notes/)