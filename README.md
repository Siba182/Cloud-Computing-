# Cloud-Computing-Fundamentals


<details>
<summary> Module 1 - 1.Understanding Cloud Concepts </summary>
<br>

**Understanding Cloud Concepts**

**What is the Cloud**
- is a global network of servers around the worls acting as one hard drive.
- Signing onto your gmail account, watching a show on Netflix or opening a file on Dropbox, you are using the cloud
- Before the cloud, you might have been backing up you photos or music on a CDROM or your PC's hard drive
- files are sent to servers and apple's data center around the world. you might lose your phone but that will be available

**Cloud Computing Characteristics**

**On-Demand Self-Service**
- Consumers can provision resources as needed and automatically. Cloud services consumers can provision services on an as-needed basis, without the need to work with the CSP (Cloud service provider) directly.
- The consumer can expand (or reduce) these services without the need for human assistance from the CSP.

**Broad Network Access**
- Services are available across the network from commonly available clients
- Client devices and traditional server deployments are able to access cloud-based resources across the network.
- The network might include the local on-premises network or the Internet, or both.

**Resource Pooling**
- The cloud service provider (CSP) pools resources in a multitenant model and adjusts resource allocation on an on-demand basis, and the specific distribution of hardware resources is abstracted from the consumer
- The CSP manages the resources and maximizes their use.


**Rapid Elasticity**
- Resources are provisioned and released to adjust for changes in demand and consumption
- This process may be automatic or manual
- Server resources in a traditional model are purchased as a capital expenditure, and whether or not those resources are efficiently utilized, their cost and capabilities are fixed.

**Measured Service**
- Metering of resources is monitored, controlled, and billable
- CSPs meter the utilization of their resources
- This metering permits more efficient and dynamic resource allocation
- It also permits the CSPs to bill consumers accurately for exactly the quantity of resources consumed


**Cloud Computing Ecosystem**
It’s important to understand that an ecosystem of participants defines the market. This ecosystem consists of three categories of players:

**Consumers of Services**
These are the everyday end-users (like yourself or your colleagues) that use cloud services in their day-to-day business activities

- **Microsoft OneDrive**: is a file hosting and synchronization service offered by Microsoft. It enables users to store and share files and access them from any device, including PCs, Macs, and mobile devices

- **Google Drive**: is a cloud storage and file backup service provided by Google. It offers free storage space for personal use and allows users to store files, collaborate on documents, and share files with others.

- **iCloud**: is a cloud storage and synchronization service provided by Apple. It allows users to store their photos, videos, documents, and other files and access them across Apple devices.


**Providers of Services**
These cloud providers offer a variety of functions ranging from infrastructure services to applications and tools.

- **Amazon Web Services (AWS)**: AWS is a comprehensive cloud computing platform provided by Amazon. It offers a wide array of services, including computing power, storage, databases, networking, analytics, machine learning, and more.

- **Microsoft Azure**: is a cloud computing platform offered by Microsoft. It provides a range of services for building, deploying, and managing applications and services through Microsoft-managed data centers.

- **Google Cloud Platform (GCP)**: is a suite of cloud computing services offered by Google. It provides infrastructure, storage, AI, machine learning, data analytics, and other services to help businesses scale and innovate.

- **IBM Cloud**: is a collection of cloud computing services provided by IBM. It offers infrastructure, platform, and software as a service (IaaS, PaaS, and SaaS) solutions, along with tools for data analytics, AI, and blockchain.

- **Oracle Cloud Infrastructure**: is an IaaS platform offered by Oracle. It provides a broad range of cloud services, including compute, storage, networking, database, and applications, with a focus on enterprise workloads.

- **Alibaba Cloud**: is the cloud computing arm of Alibaba Group, a Chinese multinational conglomerate. It offers a wide range of cloud services, including computing, storage, networking, database, AI, and security, with a strong presence in the Asia-Pacific region.


**Designer of Services**
These companies build applications and tools. Often services are intended to work within a specific cloud ecosystem or can augment a packaged cloud application.

- **Accenture**: is a global professional services company that offers cloud consulting and implementation services. They help businesses design and deploy cloud solutions, leveraging their expertise in cloud architecture, migration, and management.

- **Deloitte**: is a multinational professional services firm that provides cloud technology consulting and implementation services. They assist organizations in developing cloud strategies, designing architectures, and implementing cloud solutions across various industries

- **Capgemini**: is a global consulting and technology services company that offers cloud transformation services. They help businesses design and implement cloud architectures, optimize cloud environments, and enable digital transformation through cloud technologies.

- **IBM**: is a leading technology company that provides cloud consulting and design services. They assist organizations in designing hybrid cloud architectures, implementing cloud-based applications, and leveraging emerging technologies like AI and blockchain.

- **PricewaterhouseCoopers (PwC)**: is a multinational professional services firm that offers cloud technology consulting services. They help businesses design and implement cloud strategies, optimize cloud operations, and ensure compliance and security in cloud environments.

- **Cognizant**: is an IT services and consulting company that provides cloud technology services. They help organizations design and implement cloud-based solutions, migrate applications to the cloud, and optimize cloud infrastructure.

- **Wipro**: is a global IT consulting and services company that offers cloud consulting and implementation services. They assist businesses in designing cloud strategies, developing cloud-native applications, and ensuring seamless cloud integration.

- **Tata Consultancy Services (TCS)**: is an IT services and consulting company that provides cloud technology solutions. They assist organizations in cloud strategy development, cloud architecture design, and implementing cloud-based applications and services.

**Infosys**: is a global consulting and IT services company that offers cloud consulting and implementation services. They help businesses design and implement cloud solutions, migrate applications to the cloud, and optimize cloud infrastructure for improved performance.

**DXC Technology**: is an IT services company that provides cloud consulting and implementation services. They assist organizations in designing cloud architectures, migrating applications to the cloud, and managing cloud environments.



**Cloud Concepts**

**Cloud computing**
- is a method of providing shared computing resources, including applications, computing, storage, networking, development, and deployment platforms as well as business processes. Cloud computing makes computing resources easier to use by providing standardization and automation.


**Standardization**
- is the implementation of services using a consistent approach supported by a set of consistent interfaces. Likewise, the cloud generally requires that processes be implemented through the use of automation.


**Automation**
- is a process that’s triggered based on business rules, resource availability, and security demands. Automation is required to support a self-service provisioning model. To promote efficiency, automation can ensure that after a provisioned service is no longer needed, it is returned to the resource pool. This type of rules-based automation can help with capacity planning and overall workload management.


**Understanding Cloud Deployment Models**

**Cloud Components and Clients**
- There are three main components in a cloud services solution.
- The first component is the client platform from which the cloud services are being accessed
- The second is the data center where the cloud services are being hosted
- The final component is the network connection between those two points.

![image](https://github.com/Siba182/Cloud-Computing-/assets/60964130/d44bbb91-f152-4115-a07f-0e23a728ac7d)


**Types of Cloud Computing**

**Deployment Models**
**Public cloud**:
- A CSP owns the cloud deployment and allocates its resources to external, unaffiliated customers. Those customers share the public cloud’s resources without knowing precisely where their data is in relation to that of any other organization

**Private cloud**:  
- Services are provided to only a single organization.

**Hybrid cloud:** 
- There is a combination of two or more private, public, or community deployments where the two cloud environments work together to solve business problems
- The goal is to create a hybrid cloud environment that can combine services and data from a variety of cloud models to create a unified, automated, and well-managed computing environment



![image](https://github.com/Siba182/Cloud-Computing-/assets/60964130/3447afe8-e68a-49b4-9b14-8bd3356c9c1a)


**Multicloud**
- is when two or more public clouds are being used within an organization.
- Many businesses initially found that they had a multicloud environment because different development teams or business units were choosing to use varying public clouds


**Cloud Within a Cloud (Virtual Private Cloud)**
- the concept of cloud within a cloud means a public CSP hosts your organization’s cloud services in an isolated segment, separated from any resources shared with other companies


**Differences betweeb VPC and Private Cloud deployments**
- VPC–logical isolation of the cloud deployment that resides on a CSP's infrastructure (and is therefore scalable).

- Private cloud–physical isolation of the cloud deployment in a private data center, a community data center, or CSP's infrastructure. It is limited by the available hardware and therefore less scalable.


**Multitenancy**
- This is the concept behind public cloud deployments. Multiple consumers, known as tenants, share computing resources owned and managed by the CSP. This is the opposite idea from a VPC deployment. It is multitenancy that provides the cost benefits behind shared resource utilization.


**Multi-cloud**
- There are many multi-cloud variations, but some of the most common are combinations of cloud services spread among two or more public CSPs (such as AWS and Azure) as well as on a private cloud infrastructure. Multi-cloud deployments reduce reliance on a single vendor, provide greater service flexibility and choice, permit improved geographic control of data, and help manage disaster mitigation



**Cloud Computing Elements: Resource Pools/Cloud Models and Services**

Below  illustrates the related elements that come together to create clouds. On the bottom of the diagram is a set of resource pools that feed a set of cloud delivery services. On the top of the diagram are the common service elements needed to support these delivery models.

![image](https://github.com/Siba182/Cloud-Computing-/assets/60964130/cba6fc29-c509-490c-b9cf-38781fb4ade4)


**Cloud Delivery Models**

**Infrastructure as a Service**
- is the delivery of services, including an operating system, storage, networking, and various utility software elements, on a request basis
- The easiest way to think of IaaS is that it provides a virtual server that is equivalent to a physical server

- IaaS has both public and private versions.

- In the public IaaS, the public cloud provider creates the infrastructure and resources that consumer can use. The user simply needs a credit card to acquire these resources. When that user stops paying, the resource may disappear

- In a private IaaS service, it is usually the IT organization or an integrator who creates an infrastructure and resources that internal users and sometimes business partners can use on demand. Whereas criteria for a public cloud are based primarily on the ability to pay for a service, a private service applies company policy to a service request


**IaaS examples:**
- AWS EC2
- Microsoft Azure
- Rackspace
- Digital Ocean

Target audience: IT administrators


**Platform as a Service**
- is a mechanism for combining IaaS with an abstracted set of middleware services, software development, and deployment tools that allow the organization to have a consistent way to create and deploy applications on a cloud or on-premises environment

- The easiest way to think about PaaS is that it’s an IaaS, but the operating system and development tools are already in place. Because a PaaS environment is ready for development, productivity and time to value are greatly increased.


**PaaS examples:**
- Google App Engine
- Heroku
- AWS ElasticBeanstalk
- Salesforce

Target audience: Developers and DBAs


**Software as a Service**
- is a business application created and hosted by a provider in a multi-tenant model
- Customers typically pay for the SaaS service per user on a monthly or yearly contract model
- The SaaS application sits on top of both a Platform as a Service and foundational Infrastructure services.


**SaaS examples:**
- Microsoft Office 365
- Google Apps
- WebEx
- Dropbox
- Netflix

Target audience: End users


**The Computing Resources Life Cycle**
- A basic concept of both public and private cloud computing is that users only employ computing resources when needed and pay only for the resources they actually utilize during the time they use them.


**Understanding Self-Service Provisioning and Elasticity**
- Self-service provisioning is one of the most important capabilities of cloud computing.
-  With self-service, cloud consumers can use a website in the cloud to select and purchase cloud services, configure them, launch them into the cloud environment, and start using them within minutes or perhaps even seconds


**Establishing a Dynamic Life Cycle across Workloads and Data**
- A cloud isn’t a single unified environment; rather, it’s a combination of resources that may be spread across systems and geographies
- The cloud is a federated environment that brings together resources so that they can work together.
- To make this happen in an organized manner requires an organization of workloads. A workload is an independent service or collection of code that can be executed


**Management Services**
- Management services are mandatory for ensuring that the operation of your cloud workloads and resources meets constituent needs (whether they are customer, employee, or partner) needs
- This is the case regardless of the cloud deployment and delivery model


**The Changing Role of the Data Center**
- What happens to the data center when companies begin to implement hybrid clouds? First, the data center does not go away. After all, almost all medium-size and large companies run their own data center — which is how many companies operate their systems of record, including accounting systems, inventory records, and line of business applications, to name a few.


**Evolution of the Data Centre into a Private Cloud**
- IT organizations have discovered that it’s much more efficient and effective to create private cloud services for developers to create new applications and services.
- Therefore, companies are setting up a highly automated computing environment enabled with a self-service portal
- This portal is often designed with business process rules that dictate what services a developer or an authorized partner can use.


**Seeing how the Public Cloud Fits**
- Your company selected its cloud provider partly because they run worldwide cloud environments. The cloud provider makes it easy to replicate applications and data to different regions, so it was simple to set up the SaaS application


**Knowing When the Private Cloud Shines**
- An architected private cloud that maintains sensitive financial data is ideal for the financial services company
- The private cloud provides the scalability required for the quantity of data being managed, as well as meeting the legal obligations to store the regulated data in the country where the business is conducted.
</br>
</details>

<details>
<summary> Module 1 - 2. Embracing the Business Imperative
 </summary>
<br>

 **Understanding IT Transformation**
 - With the rise of commercial cloud computing vendors and services, the role of IT is changing dramatically
 - While the IT organization in the past had total control of computing resources, now IT is tasked with providing oversight, management, and vetting of options
 - IT now has to provide oversight and management of both cloud and on-premises computing services
 - This means that IT needs to provide a transition plan for applications that no longer have the modularity to support business requirements.

**Escaping the IT Legacy Trap**
- Ironically, legacy applications are often core to managing core business processes, such as payment services, customer information systems, and customer management. But the architectural foundation of these applications means that they’re unable to be easily updated as business processes change.

- Assuming that these applications can simply be lifted into a cloud platform is tempting. In reality, this approach is one of the most expensive and least productive ways of gaining productivity.

- First, not only does the application itself need to be moved, but also all the related dependent applications. In addition, these applications were not efficiently developed because of the technical constraints of an older computing model

**Preparing for the Cloud**
- The adoption of cloud as a strategy and plan calls for new practices, skills, and roles
- How do you go about modernizing existing applications?
- Are there Software as a Service (SaaS) applications that live in the cloud that are a better fit for the way business is being conducted today?
- If a SaaS application is the answer, you need to determine how and where it will be used. There may be a need for adding new business processes for that SaaS application.
- After all that preparation, cloud technologies are ready to be deployed, in either a private, hybrid, public, or multicloud context.



**Building for Innovation**
- As IT transforms itself to help guide the cloud strategy, the organization can become an agent of change.
- With the use of well-defined cloud services supported by standard Application Programming Interfaces (APIs), it is possible to more quickly establish new innovative applications and services to support partners and suppliers
-  With the use of either public or private cloud services, a business can pilot new services with selected partners and iterate based on feedback.


**The Business Imperatives**
- By establishing a well-defined cloud strategy that is a collaboration between key constituents across a business, you will be in a good position to get started
-  We can begin the process of streamlining the IT in an organization by modernizing critical business applications and moving key workloads to the cloud
-  You’ll be able to make well-informed decisions about which workloads should remain on-premises and which services should reside in the cloud. 


**Optimizing Your Existing Business**
- You want to be able to demonstrate that you can react to their needs for change without delay.
- Today’s customers expect your applications and services to be able to transform in near real-time.
-  If you can’t meet their expectations for rapid change, they’ll find providers that are more responsive to their needs


**Modern Development and Deployment Strategies**
- DevOps — a combination of modern application development and deployment techniques — is the requirement for building cloud-based innovation
-  With DevOps, developers employ an agile development approach that assumes an iterative development process
-  The focus of DevOps and agile development is to focus on customer needs and metrics that can predict success.
-   DevOps streamlines development and deployment processes so products can be deployed at any time, not just when a new “release” has been created

**Revisiting Your Business Model**
- One of the benefits of the cloud is that it makes it easier to adapt your business model or to experiment with new ideas that could transform your business.


**Transforming the Business Model**
- Smart businesses aren’t afraid to break their business model and experiment with new approaches to satisfying customers
-  In fact, the cloud is also the perfect place to experiment with new ideas
-  Offering compelling offerings that solve customer problems encourages them to buy once they get a taste of success
- Being able to leverage the cloud to both offer and manage customer interaction transforms your ability to move quickly to increase your business.  

</br>
</details>


<details>
<summary> Module 1 - 3. Architectural Considerations for the Cloud Environment
 </summary>
<br>

 **Rethinking the Type of Constituents Your Cloud Serves**
 Two constituents that are part of the cloud ecosystem determine how you view the cloud architecture:

 - **Cloud consumers:**  The individuals and groups within your business unit that use different types of cloud services to get a task accomplished. A cloud consumer could be a developer using computing services from a public cloud.

- **Direct customers:**  Users who often take advantage of services that your business has created within a cloud environment. End users of your service have no idea that you are using a public or private cloud. As far as the users are concerned, they are interacting directly with your services and value.

- **Cloud service provider:**  Commercial vendors or companies that create their own capabilities. Commercial vendors sell their services to cloud consumers. In contrast, a company might decide to become an internal cloud service provider to its own employees, partners, and customers — either as an internal service or as a profit center. These providers also create applications or services for these environments.


**Planning for Deployment**
-  from an architectural perspective, it is important to look at the relationship among the services that are used together
-  One of the best practices needed is to be able to keep track of what task a specific service executes, the rules for how it can be used, as well as definitions and dependencies

hybrid models have four primary architectural considerations:

**1. Latency and Performance**
- Latency, or slow response or performance, is a constant concern for customers
- For example, say that a critical issue for your business is the speed at which customers’ orders are confirmed. If you do not handle this issue efficiently, customers won’t be happy and may move to another supplier
- In a service-based approach to computing, you can tightly couple a set of services that must execute with low latency

**2. Security: Planning in Context**
- When planning your hybrid environment, at the outset, you need to think about the security requirements for customers. 


**3. Governance: Getting the right balance**
- Like security, governance requirements will determine how you plan and architect your hybrid cloud environment
- These types of governance requirements demand that IT organizations plan their platform with this in mind.
- This means including process management services that determine where data must be stored 


**4. Reliability in the Context of Change**
- Within an architectural framework, determining business, performance, and customer goals is important, and to do so, you must consider all aspects of computing.
- You need to consider the issue of latency of overall performance and latency of managing data.

- If applications and services being offered to customers are based on a tightly coupled set of services with many dependencies, a public cloud service will cause serious problems with performance

- However, if the organization is creating and leveraging a platform of well-defined and loosely coupled services that are designed to be easily linked together at run time, a public cloud service is ideal

**Setting the Right Policies and Business Rules**
- Companies generally think about policy and business rules from an overall governance perspective

- On the contrary, making policies and rules operational in a hybrid cloud environment means that these dictates must be integrated from an architectural perspective.

- Building a policy or rule into the actual application may be straightforward in an on-premises environment. In a hybrid environment, however, you must make sure those policy requirements can be applied across components.


**Navigating the Choices in a Hybrid World**
- The great thing about a hybrid cloud is that the environment allows you to select the right service for the right tas

- Think about the collection of requirements from a business perspective and match that perspective to an architectural approach

- In general, you want the platforms you select to be appropriate for the service level requirements of the business

- In the end, you want to end up with a highly optimized environment that matches the needs of the customers that you need to support.


**Optimizing for Workloads**
- Being able to optimize workloads across environments is one of the fundamental architectural principles of hybrid cloud computing

- Unless workload optimization and balancing are one of the starting points, satisfying customer requirements will be difficul


**Supporting a Dynamic Life Cycle**
- The life cycle of cloud computing is different in many ways from the life cycle of a traditional computing environment

- The architecture of the cloud environment is predicated on the ability to abstract the details away from users based on a services-oriented architecture

As you start thinking about supporting a dynamic life cycle to support a hybrid cloud environment, consider the following:

- Think about an overall services-based model that breaks down traditional disconnected silos of applications, processes, and services.

- Think about creating an environment with fewer dependencies so that when you add new cloud services, you will have the flexibility to advance as the industry advances

- Think about the performance requirements that will give your customers excellent experiences.

- Think about creating a predictable, safe, and well-governed environment that will support business operations in the long run 
</br>
</details>


<details>
<summary> Module 1 - 4. Managing a Hybrid and Multicloud Environment
 </summary>
<br>

**Managing SaaS Applications**
- Increasingly businesses are turning to SaaS applications that are owned and operated by third-party vendors

- However, businesses are beginning to bring some level of control to the use of SaaS applications. IT management must contend with several key problems in managing SaaS applications.


**Optimizing SaaS Management**
- Once a business has set the ground rules for using SaaS within the organization and educated users on the best practices of using public SaaS applications, it can take additional steps to improve costs, productivity, and security

- Security should examine actual use to understand whether any practices are risking loss of the business’s intellectual property (IP), opening up connections that hackers can exploit or where other insecure activities can occur.


**A SaaS Cautionary Tale**


**Managing External Cloud Resources**
- Businesses use many types of external or public cloud resources that require management. Resources may be virtual machines that developers use, storage for backups or disaster recovery

- Cloud resources are the building blocks used to create applications. These infrastructure services are designed as a layer below SaaS applications and therefore are the responsibility of software developers.

**Visibility and Control of External Resources**
- To be successful, you need to have the ability to apply controls so that you can gain visibility into the cloud applications and services.

- The biggest management challenges of external cloud resources are identifying the most appropriate services to use, verifying their characteristics (performance, security, cost, and so on), and making sure that these services are used exclusively

- The rationale for using these resources to the exclusion of other resources is that after a service has been selected, investments in training, testing, and building infrastructure software will occur to make the service work effectively. 


**The Importance of Self-Service**
- Cloud providers make it as easy as possible for consumers to find and use their services. At the low pay-as-you-go prices of most cloud resources, it is a very compelling bargain. However, the company should limit employee choices of computing resources to approved resources.


**Service Level Agreements (SLAs)**
- Every cloud resource comes with a contractual agreement, known as a service level agreement (SLA), that outlines what the provider is delivering, along with the customer’s responsibilities

- The agreement should outline characteristics like availability, accuracy, response time, throughput, and security.

- These important traits are critical for selecting resources that will meet the performance requirements of the services or applications that will use them.



**Addressing Poor Cloud and Computing Behaviors**
- Cloud providers routinely seek to make their computing environments secure and robust, but users of those environments can still engage in risky behaviors.

- We’ve all heard about people choosing passwords that are easy to guess, possibly leading to unauthorized theft of information or damage to software and systems. That is just one example of a dangerous behavior that companies work hard to prevent.

- One more example of a security risk that is particularly relevant to today’s employees is the use of social media

- However, a new generation has grown up with social media and uses it to share information, answer questions, and generally extend the user’s community outside the company’s boundaries.



**Managing Internal Cloud Resources**
- Because the business is serving cloud resources to its own employees and perhaps its business partners, it is not a public cloud provider but will deliver cloud resources via private or hybrid clouds

- If it is using a hybrid cloud, the business may well pass public cloud resources to its internal customers, making the business both a public cloud consumer as well as a private cloud provider.

- Regardless of the scope of offerings, issues like self-service, SLAs, and approved resources are just as critical, if not more so, to consumers of private and hybrid clouds.


**Managing a hybrid cloud environment**
- The combination of these resources (private and public clouds) provides the benefits of scalability, flexibility, and performance to their internal computing consumers. 


**Understanding the Role of Internal SLAs**
- When a company is a private or hybrid cloud provider to its internal consumers, the company should define SLAs for the resources and services provided

- Doing so will formalize the operational requirements for those services and increase the chances that consumers will be pleased with the internal services.

- SLAs provide objective targets for performance and other operational characteristics, such as mean time between failures, and therefore are important for determining whether performance problems with applications are due to problems with the application or problems with the resources and services that the application uses

- In the public cloud, management of resources and services is the responsibility of the public cloud vendor or the third party who provides the software

- In the private cloud environment, it is usually the responsibility of IT operations to monitor the software for deviations from SLA commitments.


**Managing Internal Services**
- As more businesses rely on cloud computing, they are creating internal services that are delivered to consumers within a company via a private or public cloud or a hybrid of both

- But regardless of where applications are served from, internal consumers of cloud services expect professional applications to be operating with reliability and security and be backed by professional support

- Support for internal applications may come from IT or from a call center — both managed within the company providing the private or hybrid cloud


**Supporting Cloud Customers**
- When customers run into problems with an application, they expect quick help. For third-party applications, comprehensive support will usually come from those third parties although internal support should be aware of the common issues consumers may encounter.

-  But if applications are developed or maintained in-house by internal development teams or by IT acting as a development organization, then development has a role to play with support.

-  For their part, support organizations pride and measure themselves on delivering quality and timely support. In fact, support organizations increasingly see a reduction of support calls as a goal


**Monitoring Resources Imported From the Public Cloud**
To verify that those resources are operating with sufficient performance and meeting SLAs, you have a few choices:

- Set up test software in the public cloud to sample the performance of the resources. On the positive side, by testing the resource outside of your computing stack, you will avoid affecting your application’s performance. On the negative side, you may be testing resources that are so independent of your application that the testing results are not applicable to your application’s performance.

- Set up that same test software in the hybrid cloud. The results are more likely to be consistent with what your application is experiencing, but the downside is that the testing will have a greater impact on the performance of your infrastructure because that is where the testing is operating.

- Look to see whether the resources you are testing have a dashboard or other operational information available to you. If so, it may provide the performance information you are looking for.

- Instrument the application running in the hybrid environment to log the actual performance of the resources as delivered to the application. If done carefully, it will have little impact on the application’s performance. This approach, which is perhaps the best solution, is desirable as it will be the most accurate way to monitor the resources’ behavior, and the results can be integrated with all the other issues being monitored by the application.


**Monitoring the Cloud Infrastructure**
- Public cloud vendors provide information about the operational status of major subsystems and services within their cloud environments.

- The same type of information should be maintained for private and hybrid clouds.

- Although this information is usually high level, ensuring that basic services are working properly should be the first thing that support people look to verify.


**Monitoring Applications and Services**
- User experience experts can look at how users work with the application to see problems in the user interface, opportunities for streamlining the user’s experience, and bugs in the application

-  Product managers use the information to verify that features are being used as intended and to explore how new features can improve the application.

-  Applications routinely generate logs, or records of exactly what the application has done. Developers examine logs after applications crash to help figure out why the crash occurred.

-  Applications can also be instrumented to provide other useful information to the business, including Key Performance Indicators (KPIs) that, when designed properly, can disclose whether applications are meeting the goals they were designed to achieve.


**Constructing Dashboards**
- A wealth of data and information comes from a busy cloud environment, and many employees can use that information to solve their daily challenges

Harnessing this information into a form that is useful requires at least two parts:
- Analysis software that processes and reduces the data to a manageable form.
- A visualization technique that makes the information easy for people to recognize.


- Dashboards are often the best tool for presenting operational information to various audiences. With flexibility in how dashboards are constructed, different views with different focuses can be designed for different audiences.



**Managing External Services**
- One characteristic of a hybrid cloud environment is that an organization will have a variety of services that need to be managed.

- To be successful, visibility and control over external and internal resources is critical.


**DevOps and Deployment to Public Clouds**
- DevOps combines Development with Operations and enables continuous development and deployment of software.

-  DevOps streamlines the management of application and service life cycles by eliminating handoffs between development and operations and makes the software more robust because developers are now paying more attention to operational issues


**External System Monitoring**
- With applications and services used by customers in other companies, it is even more important that system monitoring gathers application and service usage than it was within a single company

**Application and Service Life Cycles**
Consider these issues for making applications and services fit the “always on and always available” expectations of the public cloud


- DevOps’s goal for continuous development and deployment is to release new features as soon as they are ready. But while it was once okay to take the application down while it was being upgraded, it is not acceptable in the cloud. Applications and services must be able to be upgraded without disturbing customers who are using the application

- Application and server failures are always bad, but they are probably worse in the cloud (if only because there may be many more users). Designing in failover capabilities so that a failure causes only a momentary pause is much more desirable than having the application be completely unavailable, or perhaps worse, cause user data loss.



**The Future of Multicloud Management**
Many different services and deployment models are emerging as part of the hybrid cloud fabric.

You should begin asking some key questions:

- What are all the services being used, and which ones do you anticipate adding?
- Why is a service being used? Does it fulfil the business requirement?
- Do the services provide the level of security and governance demanded by management?
- Is the data that the application generates stored in the appropriate geography?
- Is the latency of the overall environment acceptable to all service consumers?

</br>
</details>

<details>
<summary> Module 1 - 5. Standards in a Multicloud World 
 </summary>
<br>
 
**What are Standards?**
- Standards are established common and repeatable practices that have been agreed to by a business or group

-  An open standard is one that is publicly and freely available, one that has been developed in a public context where anyone who is affected by the standard can contribute

**Evolution of Standards**
- **Multinational bodies:**  Treaties or other similar international legal agreements typically govern these bodies. These groups generally have long procedures and red tape before an agreement is reached. Members may be diplomats instead of technical experts. The International Organization for Standards (ISO) is one such group and is comprised of representatives from countries all over the world.

- **Industry consortiums:**  A consortium is typically an organized group dedicated to developing standards for a specific industry requirement. Even though the members may be competitors, they know that coming together will help everyone. These groups are often more streamlined and agile than international bodies and often directly engage technical experts in the process

- **An ad hoc group:**  Ad hoc groups are self-organized and governed. These groups are often built around open-source initiatives. They can be a loose body that discusses their matters through an Internet message board, or they may be more formally organized. These groups have even fewer processes than industry consortiums and are therefore able to quickly adapt and change as technology moves

- **De facto standards:**  A de facto standard emerges when an approach or product is used so extensively used that it becomes a standard. The important distinction is that a de facto standard is not created by a specific body or organization, but instead develops through practice. Often, de facto standards emerge when industry best practices converge.


standards can be categorized based on their level of maturity:
- None
- Under development
- Approved
- A reference
- Market accepted (in widespread use)
- Retired


**Categories of Cloud-Related Standards**
- SDOS vs SSOS
- Interoperability
- Portability
- Security
- Organizations Building Momentum Around Standards
- Distributed Management Task Force (DMTF)
- National Institute of Standards and Technology (NIST)
- Cloud Standards Customer Council (CSCC)
- Open Commons Consortium (OCC)
- The Open Group
- Storage Networking Industry Association (SNIA)
- Vertical Groups


**The Impact of Standards on the Multicloud**
- In a multicloud world, many interfaces are between those that exist at your cloud provider and your applications, data, servers, and so on.
- This state of affairs means that security is a risk in many places.

Standards let you do the following:
- In a multicloud world, where you may have part of the resources associated with an application on your own premises and part with a cloud provider, this capability is important because it enables your organization to be more flexible about where your resources may be located.

- Prevent vendor lock-in. Lock-in occurs when you are so entrenched with a particular provider and its interfaces that moving to another provider is too costly. Removing barriers to lock-in increases your choices.

- Integrate applications more easily between your on-premises data center and private and public cloud environments. Face it; integrating your assets across multiple environments can be time-consuming and costly if every cloud provider has a proprietary model. Standards help to make integration easier and eliminate many common barriers.

</br>
</details>

<details>
<summary> Module 1 - 6. A Closer Look at Cloud Services 
 </summary>
<br>

**The Importance of Modularity**
- Each service can be developed and deployed by small independent teams. This flexibility provides greater benefits in terms of performance, cost and scalability.

- This approach of building services, packaging them together, and managing them consistently and predictably, demands a new approach to software development and deployment.

- Application containerization has brought about new management frameworks that simplify and streamline service and other workloads.


**Discovering Why Services Matter in the Cloud**
-  In the early days of software development, subroutine libraries provided a shortcut for developers to execute a task quickly.

-  Today services have been reimagined so that they are the actual building blocks of reusable services.

- In many instances, today’s development teams are assembling applications from prebuilt services rather than coding applications from scratch. 


**Explaining Microservices**
- Microservices is a process of developing applications that consist of code that is independent of each other and of the underlying developing platformy

- These services are defined in a catalogue so that developers can more easily locate the right service and understand the governance rules for usage.

- Cloud native applications are built as a collection of multiple, independent microservices

Why are microservices so important for a true cloud environment? Consider these four key benefits:


- Application development is simplified because each microservice is built to serve a specific and limited purpose. Small development teams can focus on writing code for narrowly defined and more easily understood functions.
  
- Code changes will be smaller and less complex than with a complex integrated application, making it easier and faster to make changes, whether to fix a problem or to upgrade a service with new requirements.
  
- Scalability — both up and down — makes it simpler to deploy an additional instance of a service or change that service as needs evolve.
  
- Microservices are fully tested and validated. When new applications leverage existing microservices, developers can assume the integrity of the new application without the need for continual testing.


**The Imperative to Manage Microservices**
- Microservices are designed to be packaged within containers.
- Containers provide a technique for packaging applications so that they are abstracted from their runtime environments
- Containers are then managed through orchestration services. These orchestration services are needed to manage both process and logic as well as data services.


**Containers**
- Docker, CRI-O, Containerd, and frakti are four of the most common container run times.
- You can think of a container as packaged up software code along with all of its dependencies so that it can run consistently across clouds and on premises

- This packaging up of code is often call encapsulation. Encapsulating code is significant for developers because they do not have to develop code based on each individual environment. 


**Containers Bring Virtualization Abstraction to the Next Level**
-
</br>
</details>






