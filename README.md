# Dev_journal_csd215_F25

## AWS Cloud foundations course

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

-** Cloud based app**: fully developed in the cloud. apps can either be created on the cloud or migrated to it.
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
\
- <img width="527" height="191" alt="image" src="https://github.com/user-attachments/assets/54823441-7326-4281-a4aa-b52a8e297ccd" />

\
- Invest in reserved instances (RIs)
  - Save up to 75%
  - All Upront Reserved Instance (AURI) + %
  - Partial Upront Reserved Instance (PURI) +/- %
  - No Upront Payments Reserved Instance (NURI) - %
\

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





















 
