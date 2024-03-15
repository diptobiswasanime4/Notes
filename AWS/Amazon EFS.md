Amazon Elastic File System (EFS) is a serverless, elastic, scalable file storage, where users can share files without provisioning any storage capacity.

Amazon EFS is accessible across all common AWS services like:

1. [[EC2 (Elastic Compute Cloud)|EC2]]
2. [[Lambda]]
3. [[Amazon ECS]]
4. [[Amazon Fargate]]

Amazon EFS allows users to store files as:

1. Regional (recommended) - Files are stored in multiple [[Availability Zone|Availability zones]] in an [[AWS Region]] that gives high availability.
2. One zone - This is when files are stored in a single [[Availability Zone|Availability zone]]

There are also two modes of Amazon EFS:

1. General Purpose
2. [[Elasticity|Elastic]] - that automatically scales up and down