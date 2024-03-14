AWS Lambda is a [[Serverless]] Compute service that lets developers run code without servers.

This is similar to [[Vercel]] where developers can deploy and run their full-stack [[Next.js]] applications. It is however important to note when serving a large number of requests it is more cost-effective to use servers rather than going for [[Serverless|serverless]]

AWS Lambda allows Developers have to organize their code into Lambda functions (in one of the available languages) The service will run and scale the functions as required, and the developer only has to pay for the compute time. There is no charge for idle time, unlike [[EC2 (Elastic Compute Cloud)|EC2]] where even if the code is not running there is a charge involved.

## Advantages

1. AWS Lambda can be used when an application needs to scale up and down rapidly. We can compare this with IPL matches, when the match is live demand is extremely high, and after 3-4 hours when the match is over, demand is zero!
2. Developers are only responsible for the Code, the underlying infrastructure is managed by AWS Lambda.
## When to use Lambda

1. File processing - with [[S3 (Simple Storage Service)|Amazon S3]]
2. Stream processing - with [[Amazon Kinesis]]

