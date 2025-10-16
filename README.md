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

**VPC Security**

Security groups
- Act at the instance level,
- Way to filter traffic to and from your instances
- Rules to manage instance traffic
- Are sealed shut to inbound traffic
- Equivalent to firewall to your EC2 instances
- Outbound traffic is always allowed

Network access control lists (ACLs)

- Work at the subnet level
- Each subnet must be associated with an ACL
- One to one ACL and subnet
- An ACL has separate inbound and outbound rules, and each rule can allow or deny traffic
- There is a default ACL, if you dont especify one: default network ACLs allow all inbound and outbound IPv4 traffic
- Stateless

Differences
<img width="443" height="170" alt="image" src="https://github.com/user-attachments/assets/12977e22-8590-49b1-9af4-18247f677c63" />

**Amazon Route 53**

- Domain Name System web service 
- Register Domain names
- Fully compliant with ipv4 and ipv6
- Route users to the internet by translating domain names like www.example.com to ip addresses that computers use to connect to each other

Supported routing
- Simple routing: single server environments
- Weighted routing: assign weights to resource record sets to specify the frequency
- Latency routing: help improve your gloval apps
- Geolocation routing: route traffic based on the location of the users
- Geoproximity routing: Based on the location of your resources
- Failover routing: Fail over to a backup site (health check to be configured)
- Multivalue answer routing: Combine any of the other routings

DNS Failover: 
- Improve the availability of the apps that run on AWS
  - Configuring backup and fialover scenarions for your own apps
  - Enabling highly available multi region architecrutes on AWS
  - Creating health checks
 <img width="573" height="300" alt="image" src="https://github.com/user-attachments/assets/41c8ce6e-4ff6-409e-aa68-4ae39f7cfbfa" />

**Amazon CloudFront**

- Network performance latency
- the distance significantly affects performance, that is why is necessary a content delivery network
- CloudFront is a fast, global and secure Content Delivery Network service
- High transfer speeds
- Pay as you go pricing
- Self service offering
- Relies on route 53 geo location routing
- Edge location: network of data centers that CloudFront uses to serve popular content quickly to customers

NAT gateway: Network Address Translation gateway


## Module 6: compute

**Compute services**
<img width="597" height="251" alt="{D7DF7C10-16C3-4174-80C7-EB2424280E25}" src="https://github.com/user-attachments/assets/0d547353-5f5e-495f-9da0-f074f14c000e" />
- **Amazon Elastic Compute Cloud (Amazon EC2)** provides resizable virtual machines
- **Amazon EC2 Auto Scaling** supports application availability by allowing you to define conditions that will automatically launch or terminate EC2 instances
- **Amazon Elastic Container Registry (Amazon ECR)** is used to store and retrieve Docker images.
- **Amazon Elastic Container Service (Amazon ECS) **is a container orchestration service that supports Docker
- **VMware Cloud** on AWS enables you to provision a hybrid cloud without custom hardware
- **AWS Elastic Beanstalk** provides a simple way to run and manage web applications
- **AWS Lambda** is a serverless compute solution. You pay only for the compute time that you use
- **Amazon Elastic Kubernetes Service (Amazon EKS)** enables you to run managed Kubernetes on AWS
- **Amazon Lightsail** provides a simple-to-use service for building an application or website
- **AWS Batch** provides a tool for running batch jobs at any scale
- **AWS Fargate** provides a way to run containers that reduce the need for you to manage servers or clusters
- **AWS Outposts** provides a way to run select AWS services in your on-premises data center
- **AWS Serverless Application Repository** provides a way to discover, deploy, and publish serverless applications

**Categories of compute services**
1. Infrastructure as a Service: Instance based, Provides virtual machines Amazon EC2, flexibility and leaves many of the server management responsibilities to you
2. Serverless computing: Function based, low cost. AWS Lambda, zero administration compute platform, run code without managin or porovisioning servers
4. Container-based computing: Instance based. Amazon ECS, EKS, Fargate, ECR. sign up and execute jobs quickly
5. Platform as a Service: Web apps. AWS Elastic Beanstalk. Focus on code AWS provides with all the app services that you need

**Optimal compute service**

- Depend on the use case
  - What is your app design?
  - What are your usage patterns
  - Which configuration settings will you want to manage?
 
**Amazon EC2 Elastic Cloud Computing**

- Provides virtual machines (EC2 instances) where you can host the same kinds of apps you can run in traditional on premises server
- Common uses
  - App server
  - Web server
  - Database server
  - Game server
  - Mail server
  - Media server
  - Catalog server
  - File server
  - Computing server
  - Proxy server
 
- Full admin over the OS that runs in these VMs
- You can lunch any number of instances of any size into availability zones anywhere in the world
- Control traffic to and from instances
- - **AMI Amazon Machine Image**: Provides information that is required to launch an EC2 instance 
- Key decisions to make when launching an EC2 instance
  1. Which Amazon Machine Image (AMI) to launch from.
     - Quick start: linux and windows AMIs that are provided by AWS
     - My AMIs: AMis that you've created
     - AWS Marketplace: Preconfigured templates by third parties
     - Community AMIs: AMIs created by people all around the world (use at your own risk)
     - <img width="603" height="281" alt="image" src="https://github.com/user-attachments/assets/350466df-098c-476d-8691-72bff6287ee0" />

  2. Select an instance type
     - Consider your case
     - The instance type determines:
       - Memory (RAM)
       - Processing power (CPU)
       - Disk space and disk type (Storage)
       - Network performance
     - Instance type categories:
       - General purpose
       - Compute optimized
       - Memory optimized
       - Storage optimized
       - Accelerated computing
     -  Instance type naming:
       - t3.large
       - t family name
       - 3 generation number
       - large is the size
    - <img width="537" height="214" alt="image" src="https://github.com/user-attachments/assets/266caf9c-eb2c-4470-8cee-94af8b846749" />
    - Important to select also taking into account the networking needs of your development

  3. Specify network settings
     - Region must be selected before starting the launch EC2 instance
     - Withing the region you can select to deploy the instance in an existing subnet or VPC
     - You can create a new subnet or VPC if wanted
     - If not specified VPC it will be deployed in a default VPC adding a public IP address

  4. Attach IAM role (optional)
     - For when running an app that must make secure API calls to other services
     -  Instance profile is a container for an IAM role
    
  5. User data script (optional)
     - Can automate the completion o installation or configurations at instance launch
     - Customize the runtime environment of your instance
     - Can be used strategically
     - Must be written in a format that is compatible with a command prompt window or powershell
    
  6. Specify storage
     - Configure the root volume
     - Attach additional storage volumes (optional)
     - For each volume:
       - Size of the disk
       - Volume type
       - if the volume will be deleted when the instance is terminated
       - If the encryption should be used
     - Storage options:
       - Amazon Elastic Block Store (EBS): durable, block level storage volumes, you can stop the instance and start it again and the data will be there
       - Amazon EC2 Instance Store: EPhemeral storage is provided on disks that are attached to the host computer, if the instance stops, data will be deleted
       - Other options (not for the root volume): Amazon Elastic File System (EFS), Amazon Simple Storage Service (S3)
  7. Add tags
     - Label that you assign to an AWS resource
     - Tagging is how you attach metadata to an EC2 instance
     - Potential benefits of tagging: filtering, automation, cost allocation, and access control

  8. Security groups settings
     - set of firewall rules that control traffic to the instance
     - Create rules that specify the source and which ports that network communication can use
     - If not selected rules, the default rules will be applied

  9. Identify or create the key pair
     - You can select an existing key, or create a new key pair
     - Consists of a public key (that AWS stores) and a private key (that you store)
     - It enables secure connections to the instance
     - For windows AMIs, use the private key to obtain the administrator password that you need to log in to your instance
     - For Linux AMIs, use the private key to use SSH to securely connect to your instance
    
**You can also lauunch an EC2 instance with the AWS Command Line Interface**
- Programmatically
- <img width="308" height="144" alt="image" src="https://github.com/user-attachments/assets/fe7835fd-77bc-433b-b13e-1d43d55d9ce4" />
- Successfully create the EC2 instance if the command is properly formatted, the resourses already exists, you have permissions to run the command, and you have sufficient capacity in AWS account
- If the command is successfull, the command responds with the instance ID and other information about it.
- <img width="520" height="263" alt="image" src="https://github.com/user-attachments/assets/2765304f-7310-4489-a08a-d5f51b565594" />

**Consider using an Elastic IP address**
- Rebooting an instance will not change any IP addresses or DNS hostnames
- When an instance is stopped and started again the ip address and external DNS hostname will change
- For a persistent public IP address use an elastic addres

**EC2 instance metadata**
- Data about your instance
- While you are connected to the instance you can view it:
- https://169.254.169.254/latest/meta-data
- Can be used yto configure or manage a running instance
- in the terminal you can view it by running the command:
- curl https://169.254.169.254/latest/meta-data


**Amazon CloudWatch for monitoring**
- Collects and processes raw data from amazon EC2 to near real time metrics
- Maintains 15 months of historical data
- Basic monitoring
- no additional cost and data sent every 5 minutes
- Detailed monitoring
- fixed monthly rate, every 1 minute data delivered


**Amazon EC2 cost optimization**
- Pricing models:
  - On-demand instances: pay for the hour, no long term commitments, elegible for the free tier. (low cost and flexibility)
  - Dedicated hosts: physical server with EC2 instance capacity fully dedicated to your use (licencing restrictions or needs)
  - Dedicated instances: instances that run in a VPC, on hardware that is dedicated to a single user.
  - Reserved instance: full partial or no upfront payment, discount on hourly charge, 1 or 3 year term (predictable or steady state compute needs) 
  - Shecduled reserved instances: purchase a capacity reservation that is always available on a recurring schedule you specify, 1 year term
  - Spot instances: bid on unsued EC2 instances, can lower your costs (large scale at a significantly discounted price)
  - Per second billing: available only for on demand instances, reserved instances and spot instances that run amazon linux or ubuntu
- better explained by chatGPT
  - **1) On-demand — simplest**
    - What it is: You launch an instance and AWS bills you for the time it runs (by hour or — for eligible OSes — per second). No long-term commitment.
    - When to use: short experiments, development, unpredictable traffic, or when you need maximum flexibility.
    - Pros: most flexible; no up-front cost; simple.
    - Cons: highest per-hour price compared to committed options.
  - **2) Reserved Instances (RIs) — commit and save**
    - What it is: You commit to run capacity for 1 or 3 years. In exchange you pay a lower hourly rate. You can choose payment options: No upfront, Partial upfront, or All upfront (more upfront → bigger discount).
    - Types and details:
    - Standard RI: biggest discount but less flexible (best for predictable, steady workloads).
    - Convertible RI: less discount but you can change instance families/OS/size (more flexible).
    - When to use: production servers that run 24/7 (databases, web servers you always need).
    - Pros: predictable costs and big savings (often 30–70% vs on-demand, depending on options).
    - Cons: long commitment; wrong commitment wastes money.
    - How to decide: estimate your steady, always-on baseline usage and buy RIs to cover that baseline.
  - **3) Scheduled Reserved Instances**
    - What it is: Reserve capacity for fixed recurring time windows (for example, every weekday 08:00–18:00) for 1 year.
    - When to use: predictable recurring workloads that only run during specific times (batch jobs, trading hours, etc).
    - Pros/Cons: useful for time-boxed recurring work; less flexible than other RIs.
  - **4) Spot Instances — huge discounts, interruptible**
    - What it is: You run EC2 on spare AWS capacity at deep discounts (often 70–90% off). AWS can reclaim the instance with a short notice (typically 2 minutes).
    - When to use: fault-tolerant, flexible workloads: batch processing, big data jobs, CI/CD jobs, scalable web tiers if you have fallbacks.
    - Pros: very cheap.
    - Cons: can be interrupted — not for single critical server unless you handle interruptions.
  - **5) Dedicated Instances vs Dedicated Hosts — isolation & licensing**
    - Dedicated instance: Your instances run on hardware dedicated to your account, but you don’t control which sockets/CPUs are allocated.
    - Dedicated host: You rent an entire physical server you control. You can place instances on specific sockets — useful for BYOL (bring-your-own-license), compliance, or licensing that must be tied to physical cores.
    - When to use: software licence rules (Windows Server, SUSE, Oracle), strict compliance that requires physical isolation.
    - Pros: meets licence/compliance needs.
    - Cons: far more expensive; more management overhead.
  - **6) Per-second billing (practical note)**
    - What it is: For eligible images (Amazon Linux, Ubuntu, and a few others) AWS charges by the second (with a 60-second minimum). Applies to On-demand, Reserved, and Spot when those OS images are used.
    - Why it matters: saves money for short tasks, since you won’t pay for a full hour if you only used a few minutes.
 - <img width="759" height="313" alt="{FC1BD4D1-03FA-4F70-9A09-D6C65E21737A}" src="https://github.com/user-attachments/assets/9ba1ea45-9d5c-4718-af5a-7286d80d3358" />

**Cost optimization**
1. Right size: provision instances to match the need, use metrics, right size, then reserve
2. Increase elasticity: Stop or hibernate amazon EBS backed EC2 instances that are not actively in use. Automatic scaling to match needs based on usage
3. Optimal pricing model: Leverage the right pricing model for your use case, optimiize and combine puurchase types, consider serverless solutions
4. Optimal storage choices: Reduce costs while maintaining performance, resize EBS volumes, Change volume types, Delete EBS snapshots that are no longer needed, Identify the appropriate destination for different types of data

- Routinely measure and analyze your system so you can continuenly improve and adjust your costs
- Activate cost allocation tags
- Architect for cost
- Define metrics set targeds and review regularly

**Container services**

**Containers**: method of operating system virtualization, enables you to run an app and dependencies in resource-isolated processes
<img width="168" height="212" alt="image" src="https://github.com/user-attachments/assets/11535bf8-9755-4a25-a5d0-d58da59583ef" />

Benefits
- Repeatable
- Self-contained environments
- Software rund the same in different environments
- Faster to launch and stop or terminate than VMs

**Docker**
- Software platform that packages software into containers
- You run containers in docker
- Installed in each server
- Templates called docker images
- Containers like virtual machines
- VMs run directly in a hypervisor
- Containers run on any OS if they have the appropriate features to support docker
<img width="796" height="360" alt="image" src="https://github.com/user-attachments/assets/866662d6-8991-4b5d-b443-f83ae6e92e0b" />

**Amazon ECS (Elastic Container Service)**

- Scalable high performance container management service
- Orcherstrates the running of docker containers
- Removing the complexing of managing the infrastructure yourself
- Familiar set of features as the EC2 services
- **Task definition** to prepare your application to run, specifies things like which containers deploy to run the task
  - Is a text file that describes one or more containers, up to 10 that form your app
  - You define which tasks you want to run in within a cluster, and Amazon is responsible for placing tasks within the cluster
- A task is the instantiation of a task definition within a cluster
- <img width="557" height="248" alt="image" src="https://github.com/user-attachments/assets/57ae8421-f420-49e9-8fe9-b1c23564412c" />

- ECS is managing the running of two different containers (A & B).
- In this example, we deploy 3 copies of Container A and 2 copies of Container B into a cluster with 2 EC2 instances.
- ECS decides how to distribute those copies across the 2 instances based on available resources and rules.
- Together, the EC2 instances form the ECS cluster, and ECS is responsible for orchestrating which containers run where.

**ChatGPT conversation about containers and clusters**
https://chatgpt.com/share/68d56cdb-0dec-800f-9ec3-3056d78bb128

**Cluster options**
- Amazon ECS cluster backed by Amazon EC2:
  - More granular control over infrastructure
  - you can launch and manage the EC2 instances
  - You control how containers get scheduled
 
- Amazon ECS cluster backed by AWS Fargate:
  - You do not manage EC2 instances at all
  - You just tell how many copies of which containers do you want and fargate will manage everything else
  - Easier to maintain but less control


**Kubernetes**
- Open software for container orchestration
- Automates:
  - It automates:
    - Deployment (starting containers).
    - Scaling (more or fewer copies of containers).
    - Networking (how containers talk to each other).
    - Storage (persistent data for containers).
    - Self-healing (restarts failed containers).
   
  - Containers alone solve "packaging apps" but not running them at scale, that's how kubernetes help
 
- **Amazon Elastic kubernetes Service (Amazon EKS)**
  - Enables running kubernetes on AWS
  - Supports linux and windows containers
  - Manage clusters of Amazon EC2 compute instances
  - Run containers that are orchestrated by kubernetes on those instances
 
**Amazon Elastic Container Regitry (ECR)**
- fully managed docker container registry
- Store manage and deploy docker container images
- Integrated with ECS
- You can transfer container images to and from ECS via HTTPS

**AWS Lambda**
<img width="765" height="290" alt="image" src="https://github.com/user-attachments/assets/07051f5d-db7d-4803-befe-6286b03af64e" />

- Serverless compute service
- Run code without managing or provisioning servers
- lambda function: AWs resource that contains the code that you upload
- code only runs when it is triggered
- You pay for the compute time that you use, (you dont pay when your code is not running)
- Supports multiple programming languages
- Completely automated administration
- Built-in fault tolerance
- Supports the orchestration of multiple funcitons

Event sources
- AWs service or developer-created application that produces events that trigger an AWS lambda function to run
- You can also invoke functions directly from the console, SDK or CLI.

Lambda function configuration
- Function name
- Run time environment
- Excecution role, IAM permission to the function to access certain services
- configure the function
  - Adding a trigger
  - Add the function code
  - Specify the memory (MBs) to allocate your function
  - Timeout, VPC, other settings (optional)
- <img width="752" height="334" alt="image" src="https://github.com/user-attachments/assets/5bc7f42a-ad68-4c0c-b9b0-7d84be5d53f2" />

- Schedule/event-based lambda function

AWS Lambda quotas
- Soft limits (relax by submitting a support ticket and a justification) per Region:
  - Concurrent executions: 1000
  - function and layer storage: 75gb
- Hard limits (cannot be relaxed) for individual functions:
  - Maximum function memory allocation
  - Function timeout: 15 mins
  - Deployment package size: 250 MB unzipped, including layers
  - Container image code package size: 10Gb
  
**AWS Elastic Beanstalk**

- Easy way to get web apps up and running
- Managed service that automatically handles:
  - Infrastructure provisioning and configuration
  - Load balncing
  - Automatic scaling
  - Health monitoring
  - Analysis and debugging
  - Logging
- No additional cost for elastic beanstalk, you just pay for the services that you use
- Supports web apps written for common platforms
- You upload your code and elastic beanstalk automatically handles the deployment
- deploys on several servers
- Fast and simple to start using
- Developer productivity (focusing on writing code)
- Difficutl to outgrow 
- Complete resource control 


## Module 7: Storage

**Amazon Elastic Block Store (EBS)**

- CLoud based SSD/HDD that you attach to the virtual machine (EC2 instances)
- Basically is storing data in a SSD or HDD but in the cloud
- You can configure performance types and size
- Provides persistent block storage volumes for use with amazon EC2 instances
- Replicated within availability zone to protect from data lose
- Scale your usage up or down within minutes

- **Block storage**
  - enables you to change one block (piece of the file) that contains certain info
- **Object storage**
  - the entire file must be updated to change even just 1 character on it

- In EBS you can create individual sotorage volumes
- Offers block-level storage
- A backup of an amazon EBS volume is called a snapshot
  - The first snapshot is called the baseline snapshot
  - Every snapshot after the baseline one will only contain what is different from the previous snapshot
 
- Uses:
  - Boot volumes and sotrage for amazon EC2 instances
  - Data storage with a file system
  - Database hosts
  - Enterprise apps
 
<img width="545" height="248" alt="{8D0AF698-0FD3-4C88-B507-AC38D3D302BF}" src="https://github.com/user-attachments/assets/1b51f28c-3b67-457c-8c9b-315c05a5c231" />


Snapshots:
- Point-in-time snapshots
- Recreate a new volume at any time
- Added cost is per GB-month of data stored
Encryption
- No additional costs
- Encrypted amazon EBS volumes
Elasticity
- Increase capacity
- Change to different types
- Dinamically

Volumes: 

- **Persistent storage**: Volume lifetime is independent of any particular Amazon EC2 instance.
- **General purpose**: Amazon EBS volumes are raw, unformatted block devices that can be used from any operating system.
- **High performance**: Amazon EBS volumes are equal to or better than local Amazon EC2 drives.
- **High reliability**: Amazon EBS volumes have built-in redundancy within an Availability Zone.
- **Designed for resiliency**: The AFR (Annual Failure Rate) of Amazon EBS is between 0.1% and 1%.
- **Variable size**: Volume sizes range from 1 GB to 16 TB. 
- **Easy to use: **Amazon EBS volumes can be easily created, attached, backed up, restored, and deleted.


**Amazon Simple Storage Service (S3)**

- An an object-level storage, which means that if you need to make a single change in a file, you need to make tha change and then re upload the entire modified file
- S3 stores data as objects called buckets
- Virtually unlimited storage
- Designed for 11 9s of durability
- Not associated with any particular service
- No need to manage any server
- Objects can be almost any data type
- By default none of the data is shared publicly
- Event notifications when certain events occurs
- Can be sent to you or can trigger other events

Amaozn S3 storage classes
- S3 Standard: high durability, availability and performance, for frequently accessed data, cloud apps, content distribution and big data
- S3 Intelligent-tiering: optimizes costs without performance impact, long lived data with access patterns that are unknown or unpredictable
- S3 Standart-Infrequent Access (standard-IA): data accessed less frequent but requires a rapid access when needed, long term storage and backups
- S3 One-Zone_INfrequent Access (One Zone-IA): data accessesed less frequent but requires a rapid access when needed, but stores in a single availability zone (reduces costs), secondary backup copies storage data that is replicated from another region
- S3 Glacier: secure, durable and low cost storage class for data archiving
- S3 Glacier Deep Archive: lowest cost storage class, long term retention and digital preservation for that that might be accessed once or twice in a year
 
Amazon S3 bucket URLs

To upload your data:
1. Create a bucket in an AWS Region
2. Upload almost any number of objects to the bucket

- Bucket path style URL endpoint:
  - https://s3.<region-code>.amazonaws.com/<bucket-name>
- Bucket virtual-hosted-style URL endpoint:
  - https://<bucket-name>.s3-<region-code>.amazonaws.com

Access the data anywhere:
Console, CLI, SDK

Common scenarios:
- Backup and storage: provide data backup and storage for others
- Provide services that deploy, install and manage web apps
- Media hostingL Build a redundatn, scalable and highly availablee infrastructure that hosts video, photo or music uploads and downloads
- Software delivery: host your software apps that customers can download.

Pricing:
- Gbs per month
- Transfer OUT to other regions
- PUT, COPY, POST LIST and GET requests
Do not pay for:
- Transfers IN to amazon S3
- Transfers OUt from amazon S3 to amazon cloudFont or EC2 in the same region

Sotrage pricing:
1. Storage class type
2. Amount of storage
3. Requests
4. Data transfer

**Amazon Elastic File system**

- provides simple, scalable, elastic file storage for use with AWS services and on premises resources
- Fully managed file system
- You can mount multiple EC2 instances at the same time
- File storage in AWS Cloud
- Wroks well for big data and analytics
- Petabyte scale, low latency, automatically
- thousands of instances can access an EFS file system at any time
- highly durable and highly available
- <img width="913" height="446" alt="{FDDA543C-19E8-4AED-9AFA-510536525BE8}" src="https://github.com/user-attachments/assets/804dc715-9648-4525-af6c-795a5a5f8b2a" />


Set up an EFS
1. Create your amazon EC2 resources and launch your Amazon EC2
2. Create your Amazon EFS file system
3. Create your mount targets in the appropriate subnets
4. Connect your amazon EC2 instances to the mount targets
5. Verify the resources and protection of your AWS account


Resources:
- File system:
  - Mount target
    - Subnet ID
    - Security Groups
    - One or more per file system
    - Create in a VPC subnet
    - One per Availability Zone
    - Must be in the same VPC
  - Tags
    - Key-value pairs

**Amazon S3 Glacier**

- Secure, durable and low cost cloud storage service for data archiving and long term backup
- Terms
  - Archive: Any object that you store in Glacier
  - Vault: container for storing archives
  - Vault access policy: determine who can and cannot access the data that is stored in the vault
- Options for retriving data:
  1. Expedited: typically made available within 1 to 5 minutes (most expensive)
  2. Standard: 3 to 5 hours (less expensive than expedited but more than bulk)
  3. Bulk 5 to 12 hours (least expensive)
- Use cases:
  - Media asset archiving
  - Healthcare information archiving
  - Regulatory and compliance archiving
  - Scientific data archiving
  - Digital preservation
  - Magnetic tape replacement
- You can use the management console, however, the uses are limited
- Better to use REST apis, java or .net SDKs, lifecyles policies

Lifecycle policies
- Enable to delete or move objects based on age
- <img width="611" height="191" alt="image" src="https://github.com/user-attachments/assets/d654a170-3478-4561-9f1c-ea365b4a8435" />

Storage classes
- <img width="969" height="433" alt="image" src="https://github.com/user-attachments/assets/b336d9ce-ca8c-48d3-80c5-eb0d4c61c63d" />

Amazon S3 vs Amazon S3 Glacier\
\
Data volume: No limit | No limit\
Average latency: ms | minutes/hours\
Item size: 5tb max | 40 tb max\
Cost GB/Month: High | Low\
Billed requests: PUT, COPY, POST, LIST and GET | UPLOAD and retrieval\
Retrieval pricing: per request | per request and per GB

<img width="624" height="294" alt="image" src="https://github.com/user-attachments/assets/cf159484-c2c6-4131-868a-336cf7fd4f2d" />

- You can control access with IAM
- Amazon S3 Glacier encrypts your data with AES-256
- Manages your keys for you

## Module 8: Databases

Unmanaged Services: Scaling, fault tolerance and availability are managed by you
Managed services: Scaling fault tolerance and availability are managed by the service

**Challenges on Relational databases**

- Server maintenance and energy footprint
- Software installation and patches
- Database backups and high availability
- Limits on scalability
- OS installation and patches

**Amazon RDS Relational Database Service**
- Managed service that sets up and operates a relational database in the cloud
- Primary focus is the data and optimizing the app
- AWS manages:
  - OS installation and patches
  - Database software installation
  - DB backups
  - High availability
  - Scaling
  - Power and racking stacking servers
  - Server maintenance
 
Amazon RDS instances
- DB instance class
  - CPU
  - Memory
  - Network performance
 
- DB instance storage
  - Magnetic
  - General Purpose
  - Provisioned IOPS
 
- You select which database engine to run


Amazon RDS in a VPC
- <img width="543" height="295" alt="{480DD345-86AC-4D27-AA28-1D92BF94681B}" src="https://github.com/user-attachments/assets/4eadf796-b090-4e4b-90d2-b26801f4712d" />

- There is also an option to deploy a database in multiple Availability zones
- AWS automatically creates a stand by copy which will deploy in the extras AZs

**Read replicas**

- Updates that are made to the source database instance are asynchronously copied to the read replica instance
- Can be promoted to be primary if needed
- Used for read-heavy database workloads
- Offload read queries

Billed on the amount of time that the service is running
No additional charge for backup storage


**Amazon DynamoDB**

Realtional DBs: 
- Structured data
- Organized by tables, records and columns
- RElationships between tables
- SWL
- Difficulties scaling out horizontally or working with semistructured data
- many joins for normalized data

Non relational DBS:
- Any DB that does not follow the relational model
- Designed to overcoe the limitations of relational DBs
- Handle demands of variable structured data
- They can work with unstructured and semistructured data

**DynamoDB**
- Fast and flexible NoSQL database service for all apps that need consistend single digit millisecond latency at any scale
- Amazon manages all the underlying data for these services
- Create tables and then add items to a table
- No practical limit for the amounts of items in a table
- Items in the same table can have tdifferent attributes
- You can make changes without the need to migrate your schema, as you would in a RDB
- Provision the amounts of read write, scalable
- Global tables, enable replicate your choise across regions
- TABLES: Collections of data
- ITEMS: Group of attributes that is uniquely identifiables
- ATTRIBUTES: Fundamental data element in the table
- Primary keys:
  - Simple: Partition key
  - Composite: Partition key + Sort key
 

**Amazon RedShift**

Fast fully managed data warehouse
- Standard SQL
- Existing business intelligence

- Simple and cost effective to set up, use and scale
- Sophiscticated query optimization
- Most results come back in seconds
- An implementatino consist of leader and compute nodes:
  - Leader:
    - Manages communication with client programs ad all communication with compute nodes
    - Parses and develops plans to carry out database operations
    - Series of steps needed to obtain results for complex queries
  - Compute nodes:
    - Run the compiled code and send intermediate results back to the leader node for final aggregation
   
- Only pay for what you use
- Enables to focus on data and business
- Can scale up and down as needed
- Security is high priority (Built in)
- Both at rest and in trnasit
- Compatible with a lot of known tools


**Amazon Aurora**

- MySQL and PostgreSQL compatible relational database that is built for the cloud
- Combines the performance and availability of commercial databases
- Fully managed service
- reduce time consuming tasks like provisioning, patching, backup, recovery, failure detection and repair

- Dont have to do anything to configure high availability
- suport standard SQL
- pay as you go
- With AWS DMS and AWS Schema Conversion tool, you can move your dataset into Amazon Aurora
- High availability, stores multiple copies of your data into multiple AZs

## Module 9: Cloud architecture

**AWS Well-Architected Framework**

Architecture is the art and science of designing and building large structures.
- Cloud architects
- Engage with tdesision makers
- Ensure alignment between tech delverables of a solution and the business goals
- work with delivery teams that are implementing the solution to ensure that the tech features are appropriate

**Well-Architected Framework:**

- Guide designed to help you build the most secure, high-performing, efficent infrastructure for your cloud apps
- Provides a set of foundational questions and best practices that can help evaluate a cloud architecture
- Divided in:
  - Operational excellence:
    - Ability to run and monitor systems to deliver business value
    - Key topics: Automating changes, REsponding to events, defining standards to manage daily operations
    - Design principles
      1. Perform operations as code, (define your entire workload)
      2. Annotate documentation, (automating the creating of documentation after every build)
      3. Make frequen, small, reversible changes, (design workloads to update components regularly)
      4. Anticipate failure, (identify potential sources of failure)
      5. Learn from all operatoinal events and failures, (share what is learn accross teams or the organization)
    - Foundational questions fall under:
      -  Organization
      -  Prepare
      -  Operate and Evolve
  - Security:
    - Focuses on the ability to protect information, systems and assets
    - Key topics: Identifying and managing who can do what, Protecting systems, Establishing controls to detect security events
    - Design principles:
      1. Implementing strong identity foundation, (principle of least privileges, and enforce separation of duties)
      2. Enable traceability, (monitor, alert and audit actions and changes to your environment)
      3. Apply security at all layers, (defense in depth and security controls to all layers in your architecture)
      4. Autoamte security best practices, security mechanisms to improve your ability to secure scale more rapidly and cost effective)
      5. Protect data in transit and at rest, (classify data into sensitivity levels)
      6. Keep people away from data, (reduce the risk of loss or modification due to human error)
      7. Prepare for security events, (incident management process)
    - Foundational questions fall under:
      - Identity and access management
      - Detectivecontrols
      - Infrastructure protection
      - Data protection
      - Incident response
  - Reliability:
    - Ability of a system to recover from failures to meet business and customer demand
    - Key topics: setting up, cross-project requirements, recovery planning, handling change
    - Design principles:
      1. Test recovery pricedures, (test how your system fails, and validate recovery procedures)
      2. Automatically recover from change, (monitore systems and configure them to trigger an automaed recovery when a treshold is breached)
      3. Scale horizontally to increase aggregate workload availability, (replace one large resource with multiple smaller resources)
      4. Stop guessing capacity, (automate the addition or removal or resources)
      5. Manage change in automation, (use automation to make changes to infrastructure and manage changes in automation)
    - Foundational questions fall under:
      - Foundations
      - Failure management
      - Change management
  - Performance efficency:
    - Ability to use It and computing resources efficiently to meet system requirements
    - Key topics: selecting the right resource types and sizes based on workload requirements, monitoring performance, making informed decisions to maintain efficiency as business needs to evolve
    - Design principles:
      1. Democratize advanced technologies, (consume technologies as a service)
      2. Go global in minutes, (deploy systems in multiple regions)
      3. Use serverlessarchitectures, (serverless architectures to remove the opreational burden of running and maintaining servers)
      4. Experiment more often, (perform comparative testing of different types of instances, storages or configurations)
      5. Have mechanical sympathy, (use the technology approach that align best tto what you need)
    - Foundational questions fall under:
      - Selection
      - Review
      - Monitoring
      - Tradeoffs
  - Cost optimization:
    - Avoid unnecessary costs
    - Key topics: Understanding and controlling where money is being spent, selecting te most appropriate and right number of resource types, analyzing spending over time, scaling to meet business needs without overspending.
    - Design principles:
      1. Implement Cloud foundational financial management, (to achieve financial success and accelerate business value realization)
      2. Addopt a consumption model, (pay only for the computing resources that you require)
      3. Measure overall efficency,( measure the business output of the system and the costs associated with delivering it)
      4. Stop spending money on data center operations, (AWS does the heavylifting of racking, stacking and powering servers)
      5. Analyze and attribute expenditure, (the cloud make it easier to accurately idenity system usage and costs)
      6. Use managed and app-level services to reduce cost of ownership, (reduce the operation burden of maintaining servers)
    - Foundational questions fall under:
      - Expenditure awareness
      - Cost-effective resources
      - Matching supply and demand
      - Optimizing over time 
  - Sustainability:
    - Focuses on minimizing the environmental impacts of running cloud workloads
    - key topics: shared responsibility mdel for sustainability, understanding impact, maximizing utilization to minimize required resources and reduce downstream impacts

**Reliability and Availability**
One of the best practices on the well architected framework is to plan for failure or, application/workflow downtime
Reliability: 
- Measure of your system's ability to provide functionality when desired by the user
- You should think of reliability in statistical terms:
  - **Probability that an entire system will function as intended for a period of time**
- Failure of system components impact on the availability of the system
- Statistical measurements:
  - Mean time between failures (MTBF) = total time in service/number of failures
  - Mean Time to Repair (MTTR) = total time bringing back online a system, repairing failures
  - Mean Time Between Failures (MTBF) = MTTF + MTTR
 
Availability:
- Percentage of time that a system is operating normally or correctly performing the operations expected of it.
- Also defined as the percentage of uptime (lenght of time that the system is online between failures)
- Availability is reduced anytime tha app isn't operating normally, including scheduled and unscheduled.
- Common shorthand when referring to availability is the number of 9s: (5 9s = 99.999%)
- Highly available system is the one that can withstand some measure of degradation while still remaining available
- In a highly available system downtime is minimized as much as possible and minimal human intervention is required
- In highly available systems failures are recovered fast (often less than 1 minute)
- <img width="355" height="205" alt="image" src="https://github.com/user-attachments/assets/4104cba9-35f0-4ac0-9b34-f6b267bbb249" />
- Factors that influence availability:
  - Fault tolerance: The built in redundancy of an app component's and it's ability to remain operational
  - Scalability: the ability of your app to accomodate increases in capacity needs without changing design
  - Recoverability: The process, policies and proceures that are related to restoring service after a catastrophic event
 
**AWS Trusted Advisor**

- Online tool that provides real time guidance to help you proovision your resources following AWS best practices
- You can use this tool to design and review your architectures in AWS
- Looks at your entire AWS environment and gives you real time recommendations in five categories:
  - Cost optimization: makes recommendations to optimize cost based on your resource usage, such as eliminating unused resources, or making commits to reserve capacity.
  - Performance: checking your service limits, looking at your provisioned throughput and monitoring overused instances
  - Security: Identifying gaps that you need to close, and examins your permissions
  - Fault tolerance: Increase availability and redundancy of your app, by taking advantage of automatic scaling, health checks, Multi-AZ deployment, and backup capabilities
  - Service limits: Checks for service usage that is more than 80% of the usage limit.


 ## Module 10: Auto Scaling and Monitoring
 
**Elastic Load Balancing** 

AWS Service that distributes incoming app or network traffic across multiple targets.
- In a single AZ or across multiple
- 3 Types of elastic load balancers
- <img width="655" height="262" alt="image" src="https://github.com/user-attachments/assets/86bc7104-4090-419a-b06f-0afd47d71b10" />

How ELastic Load Balancing Works:
- Accepts incomming traffic from clients and routes requests to its registered targets
- Configure it to accept one or more listener:
  - A listener is a process that checks for connection requests
  - A listener is configured with:
    - Protocol
    - Port number for connections from the load balancer to the targets
   
- Also to perform health checks:
  - Monitor the health of registered targets
  - So that the load balancer only sends requests to the healthy instances

**Note:** With application and network load balancers, you register targets in target groups, and route traffic to the target groups\
But with classic load balancers, you register instances with the load balancer\

**Use cases**

- High availability and better fault tolerance
- Containerized apps
- Elasticity and scalability
- VPCs
- Hybrid environment
- Invoke Lambda functions over HTTP(s)

**Load balancer monitoring**

- Amazon CloudWatch metrics: publishes data points, used to verify that the system is performing as expected, and creates an alarm to initiata an action if a metric goes outside an acceptable range
- Access Logs: Capture detailed information about requests sent to your load balancer
- AWS CLoudTrail logs: to capture the who, what, when, and where of API interactions in AWS Services


**Amazon CloudWatch**

Monitoring and observability service used built for devoOps engineers, developers, site reliability and IT managers\
- **Monitors** your AWS resources in real time
- **Collects and tracks**, standard and custom metrics
- Send **Alarms** to an amazon SNS topic, or to perform EC2 autoscaling or EC2 actions
- **Events** to define rules to match changes in AWS environment and rouute these events to one or more target functions or streams for processing


CloudWatch alarms\

- You can create alarms based on:
  - Static threshold: you choose a metric for that threshold and the alarm goes on when the metric breaches the threshold for a specific number of evaluation periods
  - Anomaly detection
  - Metric math expression
 
- Specify:
  - Namespice
  - Metric
  - Statistic
  - Period
  - Conditions
  - Additional configurations
  - Actions

**Amazon EC2 Autoscaling**

- Scaling is the ability to increase or decrease compute capacity of your app
- Useful for workload with varying capacity requirements during a period of time
- Without scaling, your app could under perform, or become unavailable for users
- Or spend a lot of money on unused resources
- Computing power is a programatic resource, this means that you can take a flexible approach to scaling

- EC2 autoscaling is a service that helps your maintain app availability and enables you to automatically add or remove EC2 instances according to conditions you define
- Several ways to adjust scaling to meet the needs of your app
- Dynamic scaling or predictive scaling

**Autoscaling groups**
- Collection of EC2 instances that are treated as logicsl grouping for the purposes of automatic scaling and management
- the size of a group depends on the number of instances you set as the desired capacity
- you can adjust the size to meet demands
- you can specify the minumum/maximum number of instances, amazon will automatically prevent to go over or under that limit
- If you specify the desired capacity, amazon will adjust the size of the group
- <img width="251" height="217" alt="image" src="https://github.com/user-attachments/assets/6028588c-157e-4ba1-ba89-01517a4f764f" />

**Scaling out** is when Amazon EC2 instances are launched\
And **Scaling in** is when amazon EC2 instances are terminated\
**<img width="542" height="234" alt="image" src="https://github.com/user-attachments/assets/9a74f1cd-3c4c-4911-bab1-4766bd09a126" />**

Launch configuration is an instance configuration template with:
- AMI
- Instance type
- IAM role
- Security groups
- EBS volumes

Next, you specify where you want the scale, specifying:
- Minimum and maximum of your instances
- launch it into a subnet with a VPC
- Attach the load balancer

Finally, you specify when to scale your event
- Maintain a specify number of instances runnning at all time
- Manual scalling
- Scheduled scaling
- Dynamic scaling
- Predictive scaling

Implementng dynamic scaling\
<img width="734" height="333" alt="image" src="https://github.com/user-attachments/assets/3fb7fa23-65e7-4d2b-9c42-3e8e7a7b9d80" />

**AWS Auto Scaling**

- Monitors your apps and automatically adjusts capacity to maintain steady, predictable performance at the lowes possible cost
- Provides a simple, powerful user interface that enables you to build scaling plans for resources
