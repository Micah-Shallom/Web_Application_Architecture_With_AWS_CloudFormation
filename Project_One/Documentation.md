## Project Architecture
AWS CloudFormation is an infrastructure as code (IaC) service that allows you to easily model, provision, and manage AWS and third-party resources.

We will be building the below architecture by automatically provisioning services using AWS CloudFormation.

![Architectural_Diagram](./img/AWSWebApp.jpeg)

The above infrastructure consists of the following segments
- Networking
    - VPC
    - Internet Gateway
    - Elastic IP Address
    - NAT Gateway
    - Public and Private Subnets
- Servers and Security Groups
    - EC2
    - Security Groups
- Storage and Databases

### Networking Infrastructures Creation
![logged_in_cli](./img/1.logged_in_cli.png)
![creation_in_progress](./img/2.create_in_progress.png)
![completed_stack_creation](./img/3.network_segment_done.png)