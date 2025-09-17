# Dev_journal_csd215_F25  AWS Cloud foundations course

## AWS introductory module
- Gives us a general overview of what are we supposed to expect from the whole course, and how to use AWS academy.

## Module 1 - Cloud concepts overview

**INTRODUCTION TO CLOUD COMPUTING**

- What is cloud computing?
  - **on demand delivery of  IT resources via the internet with pay as you go pricing.**
  - enables you to stop thinking of you **infrastructure** as hardware, instead, **think of it as software**
  
- Infrastructure as hardware
  -  Hardware solutions are physical
  -  require staff, space, security, planning, and capital expenditure
  -  You need to predict your needs, capacity by guessing theoretical maximum peaks
  -  if you don't reach your expected peak, then you are paying extra resources unused
  -  but if you exceed your maximum peak, then you dont have the capacity to meet your needs
  -  and if your needs change, you must spend the time, money and resources required to implement a new solution
 
- Infrastrucutre as software
  - Flexible
  - cna change more quickly, easy and cost-effectively than hardware solutions
  - eliminate heavy-lifting tasks, like maintenance capacity planning.
  - enables to focus on what matters


3 Main cloud service models

  - **IaaS (infrastructure as a Service)**: basic building blocks for cloud it and provide you with access to networking features, computers and data storage space. Highest level of flexibility and management over your IT resources
  - **PaaS (Platform as a Service**) : reduce you the need of manage the underlying infrastructure, usually hardware and Operating systems, and enables you to focus on the deployment and management of your apps
  - **SaaS (Software as a Service)**: provides with a complete product, that the service provider runs and manage. Most cases refers to end user appss. You DONT HAVE to worry about how the service is maintained or how the underlying infrastructured is managed. just think about how to use that particular piece of software


Cloud computing deployment models

- **Cloud based app**: fully developed in the cloud. apps can either be created on the cloud or migrated to it.
- **Hybrid**  : is a way to connect your existing between cloud based infrastructure and apps and existing resources that are not in the cloud.
- **On-premises** (private cloud): use virtualization and resource management tools, it does not provide many of the benefits of cloud computing, sometimes provide dedicated resources

Similarities between AWS and traditional IT

Almost anything you can implement with traditional IT can also be implemented as an AWs cloud computing service
<img width="1008" height="574" alt="{3B5BB6A5-749A-4A8A-A7BB-628057E5594C}" src="https://github.com/user-attachments/assets/65eb75fc-01f0-411a-8589-380632912f10" />


**ADVANTAGES OF CLOUD COMPUTING**

1. Trade capital expense for variable expense: capex are funds that a company uses to aquire, upgrade and maintain physical assests, (basically you pay it wheter you use it or not)
 Instead, variable expenses you pay only for the amount you consume, maintenance is reduced
2. Benefit from massive economies of scale: big cloud providors have huge amounts of costumers, so they can get the resourses at lower prices, which means that the lower prices will go as well to the costumers when paying just what you use
3. Stop guessing capacity: Eliminate the guessing about your infrastrucutre capacity needs. With cloud computing you can access as much or as little as you need in the moment, scaling up and down as required.
4. Increase speed and agility: IT resources are just a click away, you reduce the time it takes to make those resources available to your developers from weeks to minutes.
5. stop spending money on running and mainaining data centers: Focus on the business needs instead of the heavy lifting, of racking stacking and powering servers
6. Go global in minutes: You can deploy an app in multiple regions whith just a few clicks.


**INTRODUCTION TO AMAZON WEB SERVICES (AWS)**

What is a web service?

- Any piece of software that makes itself available over the internet in a standarized format.\
- It is not tied to any operating system or programming languaje. It is self describing via an interface definition file and it is **discoverable**

AWS

- AWS is a secure platform that offers a broad set of cloud based products
- Delivered over the internet and you have on demand access to IT resources
- offers flexibility
- you can pay for only the resources that you use, operational expense
- AWS services work together like building blocks, to build sophisticated and scalable solutions

Categories

<img width="861" height="491" alt="image" src="https://github.com/user-attachments/assets/a772f9a5-d92f-4f03-8409-b13689790b79" />

Which to use depend on your business needs and tech requirements

<img width="729" height="414" alt="image" src="https://github.com/user-attachments/assets/bf1cdb5e-8489-4584-97ad-5cf7fbdb8b19" />

Three ways to interact with AWS

1. AWS management console. Graphical interface
2. CLI. Access to services by discrete commands or scripts
3. Software DEvelopmennt Kits (SDKs). Access services directly from you code.


**MOVING TO THE AWS CLOUD, THE CLOUD ADOPTION FRAMEWORK**

- For most organizations, cloud adaption does not happen immediately
- **technology, people and processes** are the three things that must be in alignment for a successful cloud adaption
-  Cloud adaption framework: a document created to help organizations design and travel an accelerated path to successful cloud adoption
-  Provides guidance and best practices to help organizations identify gaps in skills and processes.
-  Organizes guidance into 6 areas to focus, called **perspectives**
  1. Business (business capabilities, business managers, finance managers, budget owners, strategy stakeholders): Create a strong business case for cloud adaption, and prioritize cloud adoption initiatives. 
  2. Governance (business capabilities, chief information officer, program managers, enterprise architects, business analysts and protfolio managers): focus on skils and processes needed to align It strategy and goals 
  3. People (business capabilities, human resources, staffing and people managers): evaluate organizational structures and roles, new skill and process requirements and identify gaps.
  4. Security (technical capabilities, Chief information security officer, IT security manager, IT security analysys): meets its security objectives
  5. Platform (technical capabilities, chief of technology officer, IT managers and solutions architects): understand and communicate the nature of It systems and their relationships.
  6. Operations (technical capabilities, IT operation managers and IT suppor managers): define how day-to-day, quarter-to-quarter and year-to-year business will be conducted.

- Each perspective consists of a set of capabilities, which covers distinct responsibilities owned or managed by related stakeholders

## Module 2 - Cloud economics and Billing

**FUNDAMENTALS OF PRICING**

1. Compute: charged per hour or second, 
2. Storage: charged typically per GB
3. Data Transfer: outbound is aggregated and charged, inbound has no charge, typically per GB

- No charge for: inbound data transferm data transfer between services whithing the same AWS region

- Pay for what you use
- Pay less when you reserve
- Pay less when you use more
- Pay even less when AWS grows
- <img width="527" height="191" alt="image" src="https://github.com/user-attachments/assets/54823441-7326-4281-a4aa-b52a8e297ccd" />

- Invest in reserved instances (RIs)
  - Save up to 75%
  - All Upront Reserved Instance (AURI) + %
  - Partial Upront Reserved Instance (PURI) +/- %
  - No Upront Payments Reserved Instance (NURI) - %


- No long term contracts are required
- All services are available on demand
- You can get volume based discounts
- Tiered pricing, for some services
- Multiple storage services deliver lower storage costs based on needs

- AWS Constantly focuses on reducing costs
- has lower pricing 75 times  September 2019
- Future higher performing resources replace current resources for no extra charge
- every costumer has different needs
- costume pricing is available for high volume projects with unique requirements

AWS free tier for one year
Services with no charge 
- Amazon VPC
- Elastic Beanstalk
- Auto Scaling
- AWS CloudFormation
- AWS Identity and Access Management (IAM)
- (Might be charges associated for instances that those use)

**TOTAL COST OF OWNERSHIP**

- on premises infrastructure are developed on the businesses own computers and servers (several fixed costs), scaling up can be expensive and time consuming, scaling down does not reduces fixed costs
- cloud infrastructure is purchased from a service provider (AWS), who builds and maintains the facilities and hardware. Customer pays for what is used, scaling up and down is simple.

  
Total cost of ownership is the financial estimate to help identify direct and indirect costs of a system.
- Includes the cost of a service, plus all the costs associated with owning the service
- in a cloud service, TCOs are used to compare the costs of running an entire infrastructure environment or specific workload on premises versus one running on a cloud based infrastructure.
- Companies use this comparison for budgeting purposes or to make decisions about the optimal deployment solution.

Costs: 
1. Server costs: for the hardware and the software, and fecilities to house the equipment
2. Storage costs: hardware, administration and facilities
3. Network costs for hardware, administration and facilities
4. IT labor costs: required to administer the entire solution.


when comparing an on premises technologies vs cloud solutions, it is important to accurately asses the true costs of both options
- Cloud: most costs upront and readily calculated (RAM, storage, bandwidth)
- on premises technology: must take into account all.
  - Direct costs: power, floor space, storage, IT operations
  - Indirect costs: network and storage infrastructure.

Sample cost comparison:
<img width="562" height="268" alt="image" src="https://github.com/user-attachments/assets/95bb1842-1640-47a6-b9cf-8a2f606a8d22" />

**AWS Pricing calculator**
- Estimate monthly costs
- Identify opportunities yo reduce monthly costs
- Model your solutions before building them
- Explore the price points and calculations behind your estimate
- find the available instance types and contract terms that meet your needs
- Name your estimate and create name groups of services
- make informed decisions when using AWS

- displayed in multiple ways
- combines the upront and monthly estimates
- within a group you can see the estimate for each service

1. Hard benefits: REDUCE... spending on compute, storage, networking and security, hardware and software purchases, operational costs, backup and disaster recovery and operations personnel
   - Cloud total costs of ownership: defines what will be spent on the tech after adoption or what it costs to run the solution
     - Looks at the as-is on-premises infrastructures
     - compares it with the to-be infrastructure state in the cloud
   - Return of investment (ROI) analysis
     - Identifying the hard benefits in terms of direct and visible costa reductions and efficiency improvements.

2. Soft benefits:  value points that are challenging to accurately quantify, include:
   - **Reusing service and app**s that enable you to define solutions by using the same cloud service
   - **Increased developer productivity**
   - **Improved customer satisfaction**
   - **Agile business processes that can quickly respond to new and emerging opportunities**
  

  **AWS ORGANIZATIONS**

Create a separate AWS account to each department or team, so each can have their own clear and defined report about their uses and expenses.\
For this, there is AWS Organizations, which is a service that ties all of this accounts together.
- We use AWS organizations for consolidated billing between separate accounts
- Free account management system
- Organizational tree
- With each branch representing a different department or team
- Include consolidated billing and organization security management capabilities

**Terminology:**
- Organizational units (OU): branch for accounts
- A branch can also contain other branches
- Can only have one parent
- And each branch can only be a member of exactly one branch
- An account is an standard AWS account that contains AWS resources
- <img width="411" height="239" alt="image" src="https://github.com/user-attachments/assets/a831f0f3-b94f-404f-868b-db9f8048a2a3" />

**Key features and benefits:**
- Policy based account management
- Group based account management
- App programming interfaces (APIs) that automate account management
- Consolitated billing

**Identity and Access Management (IAM)**
- AWS organizations does not replace IAM policies
- IAM policies enable you to allow or deny acces to AWS services
- An IAM policy can only be applied to users, groups and roles
- Cannot restrict the AWS account itself
- Asumes that you have access to 2 or more AWS accounts and that you can access to each account as an administrator

**Steps to set AWS organizations**
1. Create Organization, current AWS account as the primary account, and invite other to join and create member.
2. Create organizational units (OU)
3. Create service control policies, and apply restrictions. Organizational control policy
4. Test restrictions: sign in as a member inside each OU and see how the service control policies impact the accounts.

**Accessing AWS organizations**
As other services, organizations can be accesse thru different interfaces
- AWS Management Console, (browser based interface to manage organizations)
- AWS Command Line Interface tools (CLIs)
- Software Development kits (SDKs)
- HTTPs Query application programming interfaces (APIs)

**AWS BILLING AND COST MANAGEMENT**

- Service that you use to pay your AWS bill, monitor your usage and budget your expenses
- Forecast and get an idea of what your costs and usage might be in the future.
- you can set a custom time period and determine if you would like to view your data at a monthly or daily level of granularity
- Filtering and grouping functionality to analyze your data using a variety of dimensions
- AWS Cost and Usage Report Tool to identify opportunities for optimization by understanding your cost and usage data trends and how you are using your AWS implementation
- AWS billing dashboard lets you view the status of your month-to-date expenditure, identify the services that account for the majority of your overall expenditure and understand how costs are trending
  - One of the graphs is the spend summary, shows how much you spent last month, the estimated costs of your AWS usage for the month to date, and a forecast for how you youre likely to spend this month
  - Another graph is the Month-to-date spend by service, whoch shows the top services that you use and the proportion of costs that are attributed to that service

Tools:
- AWS budgets
- AWS costs and usage reports
- AWS Costs explorer, visualize understand and manage AWS costs over time
- AWS bills page, lists the costs that you incurred over the past month for each AWS service
- Monthly bill and a breakdown
- AWS budgets to create notifications for when you go over your budget for the month, budgets can be tracked monthly, quarterly, or yearly level and you can customiza start and end dates.
- AWS costs and Usage report is a single location for accessing comprehensive infromamtion about your AWS costs and usage. Lists the usage for each service category that is used by an account, in hourly, or daily line items. and any tax that you activated.

**TECHNICAL SUPPORT MODELS**

- AWS support: unique combinations of tools and expertise to support projects
- Account assistance: Technical Account Manager (TAM)
- Best practices: AWS truster advisor (online resource that optimzes expenses and tells you what youre doing right and where you need to watch out)
- Account assistance: AWS Support Concierge

Plans
1. Basic: free, support for account and billing questions and service limit increases
2. Developer support: support for early development on AWs
3. Business Suport: customers that run production workloads
4. Enterprise support: customers that run business and mission critical workloads

Case severity and response times:

<img width="755" height="271" alt="image" src="https://github.com/user-attachments/assets/b7b66987-f149-4db9-baca-8476eb57ef0c" />


## Module 3: AWS Global Infrastructure Overview

- 22 current AWS regions
- Physical geographical area one or more availability zones in turn to consist of one or more data centers
- Regions are isolated from each other
-  When you store data in one region, it is not replicated in others
-  It is your responsibility to replicate data across regions if your buusiness needs require it
-  With AWS management Console to enable or disable regions

**Selecting a Region**

- Few factors to consider when selecting a regino, such as:
  - data governance and legal requirements 
  - Proximity to customers (latency): (to test it you can use a website like CloudPing)
  - Services available within the region
  - Costs (Vary by region)
 
**Availability zones**

- Each region has multiple availability zones (fully isolated partition of the AWS infrastructure)
  - Currentyl 69 availability zones
  - Consist of discrete data centers
  - Designated for fault isolation
  - Every availability zone contains multiple data centre (typically 3)
  - Have their own power infrastructure
  - Physically separated by several kms (all availability zones are within 100kms of each other)
  - <img width="195" height="236" alt="{332D3E28-4AEC-4BE8-B0E7-ED1D32CA3073}" src="https://github.com/user-attachments/assets/85d6baa9-1f58-4b86-9ee0-e191a04c3a95" />
  - Interconnected using high-speed private networking
  - You choose your own availability zones
  - Recommend replicating data and resources across AZs for resiliency
 
**Data centers**

- Location of where the actual data resides
- Customers do not specify a data center for the deployment of their resources
- designed for security
- Failures can occur that affect the availability of instances in the same location.

Data center designed

- Redundant design, that anticipates and tolerated failure while maintaining service levels
- Critical system components are backed up to ensure availability
- AWS continuously monitors service usage to ensure capacity
- Locations are not disclosed and all acces to them is restricted
- In case of failure automate processes mode data traffic aaway from the affected area

AWS uses custom network equipment from multiple original device manufacturers (ODMs) 

**Points of presence**

<img width="544" height="361" alt="image" src="https://github.com/user-attachments/assets/4eb868d1-5026-4382-82bc-bb0a8d24bebf" />

- Amazon CloudFront is a Content Delivery Network (CDN) distribute content to end users to reduce latency.
- Amazon Route 53 is a Domain Name System (DNS) service.
- AWS points of presence located in most of the major cities around the world
- Continuously measuring internet connectivity, performance and computing to find the best way to route requests.
-  187 Points of presence
-  176 edge locations and 11 REgional edge caches: used when you have content that is not accessed frequently enough to remain in an edge location

**Benefits provided by the infrasturcture**

- Elasticity and scalability: resources can rapidly adjust dynamically
- Fault tolerance: component redundancy
- High availability: minimal to no human interversion, minimized downtime

**AWS services and service Categories**

<img width="797" height="359" alt="image" src="https://github.com/user-attachments/assets/3bdac2bd-096b-482a-aaf7-1507e3c07e13" />

AWS offers a broad set of cloud services.
- 23 different product or service categories, each category consists of one or more servies.
<img width="832" height="400" alt="image" src="https://github.com/user-attachments/assets/88f02283-6829-40fc-a660-87238c30618a" />


**Storage Service**

- Amazon Simple Storage Service (S3): object storage service, offers scalability, data availability and performance.
- Amazon Elastic Blck Store (EBS): high performance block storage that is designed for use with Amazon EC2
- Amazon Elastic File System (EFs): scalable fully managed elastic network file system (NFS) for use with cloud and on premise
- Amazon simple sorage service Galcier: secure durable and low cost S3 cloud storage class for data archiving and long term backup

**Compute Services**

- Amazon Elastic Compute Cloud (EC2): resizable compute capacity as VMs in the cloud
- Amazon EC2 auto Scaling: add or remove EC2 instances
- Amazon Elastic Container Service (ECS): highly scalable, high performance container orchestration, supports docker containers
- Amazon Elastic Container Registry (ECR): storage manage and deploy docker container images
- AWS Elastiv Beanstalk: deploying and scaling web apps and services on familiar servers
- AWS Lambds: run code without provisioning or managing servers.
- Amazon Elastic Kubernetes Service (EKS): deploy manage and scale containerized apps.
- AWS Fargate: run containers without manage servers or clusters

**Database Services**

- Amazon RElational Database Service (RDS): set up, operate and scale a Relational db in the cloud
- Amazon Aurora: MySQL and PostgreSQL compatible relational db
- Amazon Redshift run analycial queries against petabytes of data. Fast performance at any scale
- Amazon DynamoDB: NoSQL db, key valie and document db. single digit milisecond performance at any scale

**Networking and content delivery services**

- Amazon Virtual Private Cloud (VPC): provision logically isolated selections of the AWS cloud
- Elastic Load Balancing: distributes incomming app trafic across multiple targets.
- Amazon CloudFont: fast Content Delivery Network, securely delivers data with low latency and high transfer speed.
- AWS Transit GatewayL enables customers to connect their Amazon VPCs networks to a single gateway
- Amazon Route 53: scalable cloud Domain Name System (DNS)
- AWS Direct Connect: establish a dedicated private network connectino from your data center or office to AWS
- AWS VPN: secure private tunnel from your netwok or device to AWS global network

**Security, identity and compliance services**

- AWS Identity and Access Management: manage access to AWS services ad resources securely.
- AWS Organizations: restrict what services and actions are allowedd in your accounts.
- Amazon Cognito: lets you add user sign in, sign up and access control to your web and mobile apps
- AWS Artifact provides on demand access to AWS security and compliance reports and select online agreements
- AWS Key Management Service (KMS): create and manage encryption keys
- AWS SHield: managed Distributed Denial of Service (DDoS) protection service that safeguards apps running on AWS.

 **AWS Cost Management Services**

- AWS Cost and Usage Report: AWs cost and usage data available, and additional metadata about services pricng and reservations
- AWS Budgets: set budgets that alert when your costs or usages exceed
- AWS Cost Explorer: visualize understand and manage your AWS costs and usage over time

**Management and governance services**

- AWS Management console: interface for accessing your account
- AWS Config: track resource inventory and changes
- Amazon CloudWatch: monitor resources and apps
- AWS Auto Scaling: scale multiple resources to meet demand
- AWS Command Line interface: unified tool to manage services
- AWS Trusted Advisor: optimize performance and security
- AWS Well-Architected Tool reviewing and improving your workloads
- AWS CloudTrail: tracks user activity and API usage.


## Module 4: AWS Cloud Security

**AWS Shared Responsibility model**

- Security and compliance are a shared responsibility between AWS and the customer
- AWs is responsible for protecting the infrastructure that runs all the services offered. (hardware, software, networking...)
- the customer is responsible for the encryption of data at rest and the encryption of data in transit. Manage security security credentials and login

- <img width="505" height="274" alt="{4EF61D4B-8289-486B-B780-F7C69F474DF0}" src="https://github.com/user-attachments/assets/f9b5c598-72d4-4da5-91c9-88ee50ea61a3" />

**Security of the cloud**

- AWS is responsible of the **security OF the cloud**:
  - AWS Services (Compute, storage, database, networking)
  - AWS Global infrastructure (Regions (availability zones), edge locations)
 
- And AWS is responsible for the physical infrastructure that hosts your resources:
  - Physical security of data centers
  - Hardware infrastructure
  - Software infrastructure
  - Network infrastructure
 
**Customer responsibility**

- On the other side, the customer is responsible for the **security IN the cloud**
- You are responsible for what you deploy using AWS services:
  - Securing any instance operating systems
  - Securing the apps
  - Security group configuratinos
  - Firewall configurations
  - Network configurations
  - Secure account management

**Service characteristics and security responsibility**

1. Infrastructure as a Service (IaaS):
   - Basically you are operating most of the server, similar to on premise
   - Highest level of flexibility and management control
   - More responsibility of the resources you create and manage
   - Customer configures the access controls
  
2. Platform as a Service (PaaS):
   - Manage the server but with most of the infrastructure hidden
   - Remove the need for the customer to manage the underlying infrastructure
   - AWS handles the opreating system, database patching, firewall config, disaster recovery.
   - Customer can focus entirely on managing code or data
  
3. Software as a Service (SaaS):
   - Services centrally hosted software that is typically accessible via web browser, mobile appor APIs
   - Licenced on a subscription or a pay as you go
   - Customers do not need to manage the infrastructure thaty supports the service
  
**AWS Identity and Access Management**

- A service that allows you to control access to compute, storage, database and apps services in the cloud
- Use IAM to access AWS services
- Free service
- Define users, groups roles, and access controls
- Available to all regions in the cloud
- Who can access the resource, which resources can be accessed and what can the user do to the resource
- How resources can be accessed

**IAM essential components**

1. User: Usually a person or app that can authenticate with an AWS account
2. Group: Collection of IAM users that are granted identical authorization, groups cannot be nested
3. Policy: document which defines access to one or more services
4. Role: mechanism to granting temporary access to AWS services, similar to a user, but assumable by any user that needed, temporary credentials

**Authenticate as an IAM user to gain access**

- Authentication is a basic computer security concept: a user or system must first prove their identity
- When you define an IAM user, select what types of access the user is permitted to use:
  - Programmatic access: provides AWS CLI and AWS SDK access, and authenticate using:
    1. Access key Id
    2. Secret access key
  - AWS Management Console access:
    1. user name
    2. pasword
    3. If enabled Multi factor Authentication, prompts for an authentication code

**IAM Multi Factor Authentication (MFA)**

- Provides increased security
- In addition to user name and password, MFA requires a unique authentication code to access AWS services



**IAM Authorization**

<img width="631" height="280" alt="image" src="https://github.com/user-attachments/assets/4f863371-3ef5-48b2-b607-aab31d237f94" />
- By default, IAM users do not have access to anything
- You need to explicitly grant access to each service
- Principle of least privilege: only the minimal privilege needed for the users

**IAM Policies**

- Document using JSON
- Two types: 
  1. Identity based policies: Attach policy to any IAM identity (user, group, role), actions that may or may not be performed
  2. Resource based policies: attached to a resource (what actions a specified principal can perform on that resource under what conditions.
 
- <img width="766" height="338" alt="image" src="https://github.com/user-attachments/assets/55c21720-ae37-49f1-8303-ccf79b623bc4" />
- The deny statements are the default ones, and if there is a conflict between an allow and a deny statement, the deny will allways win.

**IAM Permissions**
<img width="483" height="165" alt="image" src="https://github.com/user-attachments/assets/211a603f-8514-455b-9ac9-06cb72145cfe" />


**Securing a new AWS account**

- When you first create an AWS account, you begin with a single sign in identity that has complete access to all services **AWS account root user** 
- Best practice is to not use this account for day to day interaction
- Use IAM to create users, asign permissions to these users, following the principle of least privilege
1. Stop using the root account as soon as possible:
  1. while signed in the root account, create an IAM user for yourself 
  2. Create an IAM group, give it full administrator permissions and add the IAM user to the group
  3. Disable and remove your account root user access keys
  4. Enable a password policy for users
  5. Sign in with your new IAM user credentials
  6. Store your account root users credentials in a safe place
 
 2. Enable multi factor authentication (MFA)
    - Require MFA for your account root user and for all IAM users
    - Control access to AWS service APIs
   
 3. Use AWS CLoudTrail
    - Service that logs all API requests to resources in your account
    - Enables operational auditing on your account
   
 4. Enable a billing report, such as the AWS cost and USage report
    - Billing reports provide infromation aboutyour use of AWS resources and estimated costs for that use
    - AWS delivers the reportas to an amazon S3 bucked that you specify
    - AWS Cost and Usage Report tracks your AWS usage and provides estimated charges associated with your AWS account, either by the hour or by the day

**Securing accounts**

**AWS Organizations service**

- Group AWS accounts into Organizational Units (OUs)
- Integration and support for IAM
- Use service control policies to establish control over the AWS services and aPI actions that each account can access
- Service control policies feature:
  - Centralized control over accounts
  - Ensures that accounts comply with access control guidelines
  - SCPs are similar to IAM permissions policies (similar syntax, SCP never grants permissinos, specify the maximum permissions for an organizations)
 
**AWS Key Management Service (KMS)**
- Manage encryption keys
- ENables to control the use of encryption across AWS services and in your apps
- Integrates CloudTrain to log all key usage

**Amazon cognito**
- Adds users sign up sign in and access control to your web and mobile app
- Sclaes to milliosn of users
- Suports with social identity providers such as facebook, google and amazon

**AWS shield**
- Managed distributed delial of Service (DDoS) protection service
- Safeguards apps running on AWS
- Provides always on detection and automatic inline mitigations
- AWS Shield standard enabled for no additional cost
- Use it to minimize app downtime and latency

**SECURING DATA**

- Data encryption is an essential tool to use when your objective is to protect digital data
- Take data that is legible and encodes it so that it is unreadable to anyone who does not have access to the secret key that can be used to decode it
- Data at rest is data that is physically stored on a disk or on tape
- AWS KMS encryption and decryption are handled automatically
- Data in transit is data moving accross a network
- Encryptino of data in transit is accomplished using Transport Layer Security (TLS) with an open standar cipher (AES-256) formerly called Secure Sockets Layer (SSL)
- AWS certificate manager is a service that enables to manage, provision and deploy SSL and TSL certificates for use with AWS services
- Web traffic that runs over HTTP is not secured, however web traffic that runs over Secure HTTP or HTTPS is encrypted using TSL or SSL certificates
- AWS services support data in transit encryption

**SECURING AMAZON S3 BUCKETS AND OBJECTS**

- By default, all buckets and objects are private and protected, and only accounts with explicit access can access it
- Tools to control access to amazon S3 buckets and objects:
  - Amazon S3 Block Public access (these settings override any other policies or permissions)
  - IAM policies (specify users or roles that can access specific buckets or objects)
  - Bucket policies (define access to specific buckets or objects, usually when a user cannot authenticate with IAM)
  - Access Control Lists (ACLs) (not commonly used because predates IAM)
  - AWS Trusted Advisor (bucket permission check feature useful for discovering if any buckets in your account have permissions)
 
**WORKING TO ENSURE COMPLIANCE**

- Compliance programs
  - external certifying bodies and independent auditors to provide customers with information about policies, processes and controls that are established and operated by AWS
  - requirements for stablishing, implementin, maintaining and continuinly improving an Information Security Management sysytem
  - Laws, regulations and privacy
  - Alignments and frameworks
 
- AWS Config
  - Service that enables you to assess audit and evaluate tha configuratinos of AWS resources
  - Maintains a history of your configuration
  - automatically evaluate recorded configurations
  - review changes
  - review deatiled config histories
  - Simplify compliance auditing and secure analysis
  - REgional service, you need to enable it in each region that you need
 
- AWS Artifact
  - Resource for compliance-related information
  - Provides access to security and compliance reports and select online agreements
  - Can access example downloads
  - Access AWS artifact directly from the AWS Management console

## Module 5: networking and content delivery

**Networking basics**

- Network: 2 or more machines that are connected together to share resources
-  Logically partitioned into subnets
-  Requires a networking devide (router, switch)

-  IP addresses:
  - Internet protocol address
  - Uninque numbers that identifies a machine
  - IPv4: 32 bit addresses 000.0.0.0
  - IPv6: 128 bit addresses 0000:0000:0000:0000:0000:0000:0000:0000
  - Network identifier (routing prefix) fixed bits of the address
  - Host identifier the flexible bits of the address
  - /24 means that the first 24 bits are fixed which means that the last 8 bits are flexible for the host machine, which in this case can go from 0 to 255
  - <img width="351" height="189" alt="{214F3DD2-ACE7-4A78-BA39-CBFF6E02726A}" src="https://github.com/user-attachments/assets/eba3a4e3-870b-45b9-9690-ee449a950719" />

**Amazon VPC**

- Amazon Virtual Pritave Cloud: service that lets you provision a logically isolated section of the AWS cloud, where you can launch your services
- Gives you control over your virtual resources (selection of your ip addresses, subnets, route tables and gateways)
- Customize network config
- Multiple layers of security
- Provision VPCs
  - Logically isolated fro mother VPCs
  - Dedicated to your AWS account
  - Belong to a single region (can spam multiple availability zones)
  - Subnets belong to a single availability zone, can be classified as public or private

  **IP addressing**
- You assign your own IP addresses
- CIDR blocks, the range of private IP addresses IPv4: /16 (65536 ip addresses) - /28 (16 addresses)
- IPv6 is also supported
- You can create multiple subnets in one network but the CIDR blocks cannot overlapse
- Reserved IP addresses:
  -  Each subnet requires a CIDR block
  -  Each CIDR block reserves 5 IP addresses within that block that you cannot use
  -  Network Address, VPC local router (internal communications), Domain Name System resolution, Future Use, Network broadcas address
- Public IP address types:
  - Elastic IP address: Assocuated with an AWS account, can be allocated and remapped anytime, additional costs might apply
  - Public IPv4 address: Manually assigned through an Elastic IP address, Automatically assigned through the auto-assign public IP address setings at the subnet level
- Elastic network interface:
  - Virtual network interface that you can attach or unattach from an instance in a VPC
  - When you move an instance from one network to another, traffic is redirected to the new instance
  - Each instance has a default network interface
- Route tables and routes:
  - set of rules that directs traffic from your subnet
  - each route specifies a destination and a target
  - every route table contains a local route for communication within the VPS
  - Each subnet must be associated with at most one rout table

**VPC NETWORKING**

- Internet gateway:
  - VPC component that allows communication between instances in your VPS and the internet
  - provide a target in the route tables
  - perform network address translation for instances that were assigned public IPv4 addresses
  - <img width="471" height="206" alt="image" src="https://github.com/user-attachments/assets/3b1abcff-9532-4435-9276-51cb68f8e719" />
- Network address translation (NAT) gateway
  - Enables instances in a private subnet to connect with the internet or other services
  - But also prevents the internet from initiating a connection with those instances
  -  <img width="558" height="264" alt="image" src="https://github.com/user-attachments/assets/8bfc6a33-b3ca-4a65-8d03-b8da96685613" />
  
**VPC SHARING**
- Share VPCs with other AWS accounts in the smae organization
- Enables multiple accounts to create their own application resources
- The account that owns the VPC shares one or more subnets with other accounts

**VPC PEERING**
- networking connection between two VPCs that enables you to route traffic between them privately.
- You can create these connections in the same account, in another accounts, or even accross regions
- It can just be between 2 VPCs, data transfered from one VPC to another, will stop in the second one, it cannot travel to a third VPC

**AWS Site to site VPN**
- Virtual Private Network connection
  1. Create a new virtual gateway device
  2. Define the configuration of the VPN device or the customer gateway
  3. Create a custom route table
  4. Establish an AWS Site to site VPN
  5. Configure routing to pass traffic thorough the connection
 
**AWS direct connect**
- To prevent that distance negatively affect the network performance
- Direct connect enables you to establish a dedicated, private network connection between your network and one DX location (direct connection)

**VPC endpoints**
- Virtual device that enables to privately connect your VPC to supported AWS services
- Gateway endpoints
- Interface endpoints

**AWS Transit gateway**
<img width="675" height="317" alt="image" src="https://github.com/user-attachments/assets/fb8c9db1-abbb-4e73-9549-f2f2c6e9b6e0" />











 
