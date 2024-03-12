AWS Lambda is a [[Serverless]] Compute service that lets developers run code without servers.

This is sort of similar to [[Vercel]] where developers can deploy and run their full-stack [[Next.js]] applications. It is however important to note when serving a large number of requests it is more cost-effective to use servers rather than going for [[Serverless|serverless]]

Coming back to AWS Lambda, developers have to organize their code into Lambda functions (in one of the available languages) The service will run and scale the functions as required, and the developer only has to pay for the compute time, there is no charge for idle time, unlike [[EC2 (Elastic Compute Cloud)|EC2]] where even if the code is not running there is a charge involved.

## Advantages

AWS Lambda can be used when an application needs to scale up rapidly, then once again scale down to zero very soon! We can compare this with IPL matches, when the match is live demand is extremely high, and after 3 hours it is close to zero.