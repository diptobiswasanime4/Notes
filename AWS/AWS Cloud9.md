AWS Cloud9 is an [[Integrated Development Environment (IDE)]] that offers rich code-editing experience supporting several [[Programming Language|programming languages]], and [[Runtime|runtimes]] with a built-in [[Terminal]]

## How does AWS Cloud9 work ?

Users can access AWS Cloud9 through a [[Web Browser|web browser]]

A computing resource like an [[EC2 (Elastic Compute Cloud)|EC2 instance]] connects to the environment. Lastly the code is stored in an [[AWS CodeCommit]] repository or any other type of remote repository.

![[Cloud9.png]]

### Cloud9 Environments and Computing Resources

We can do the following in our environment:

1. Store project files in the instance
2. Clone a remote code repository
3. Work with a combo of local and remote files

We can also connect our environments with Computing resources.

1. Instruct AWS Cloud9 to create an [[EC2 (Elastic Compute Cloud)|EC2 instance]]. This is also called **EC2 environment**
2. Instruct AWS Cloud9 to connect to an env to an existing Cloud Computing Resource. This is also called **SSH environment**

### When to use Cloud9

1. Working with several programming languages and the [[AWS Cloud Development Kit (CDK)]]
2. Working with a code running in a [[Docker|Docker container]]
3. Using remote code repositories
4. Collaborating with other developers real-time