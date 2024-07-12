# Cloud-Computing-Fundamentals


<details>
<summary> Module 1 - Understanding Cloud Concepts </summary>
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

<details>
<summary> Module 1 - 3. Architectural Considerations for the Cloud Environment
 </summary>
<br>
</br>





