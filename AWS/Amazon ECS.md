
Amazon Elastic Container Service (ECS) is a fully managed container orchestration service that allows developers to easily manage, deploy, and scale containerized applications.

## Layers of ECS

1. Capacity - The infrastructure where the containers run
2. Controller - Deploy and manage applications
3. Provisioning - Tools that interact with the scheduler that deploys and manages containers and applications

![[ECS layers.png]]
### ECS Capacity

1. [[EC2 (Elastic Compute Cloud)|EC2 instances]]
2. [[Amazon Fargate]] (Serverless)
3. On-premises

The capacity can be located in:

1. [[Availability Zone|Availability zones]]
2. [[Local zones]]
3. Wavelength zones
4. AWS Regions
5. AWS Outposts

### ECS Controller

This is the scheduler that managers applications.

### ECS Provisioning

There are multiple options:

1. [[AWS Management Console]]
2. [[AWS Command Line Interface (CLI)]]
3. [[AWS SDKs]]
4. Copilot
5. AWS CDK

### Application Lifecycle

![[ECS lifecycle.png]]