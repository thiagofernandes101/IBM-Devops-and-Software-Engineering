# **Introduction to Cloud Computing**

## **Definition and Essential Characteristics of Cloud Computing**
### <ins>What is cloud computing?</ins>
- The delivery of on-demand computing resources.

- Everything from application, to datacenters over the internet on a pay-for-use basis.

- NIST defines cloud computing as a model for enabling convenient, on-demand network access to a shared pool of configurable computing resources, that can be rapidly provisioned and released with minimal management effort or service provider interaction.

- Examples of computing resources include networks, servers, storage, applications, and services.

- This cloud model is composed of five essential characteristics, three deployment models, and three service models

### <ins>Five essential characteristics</ins>
- Includes:

1. On-demand self-service: you get access to cloud resources such as the processing power, storage, and netwrok you need, using simple interface, without requiring human interaction with each service provider.

1. Broad network access: cloud computing resources can be accessed via the network through standard mechanisms and platforms such as mobile phones, tablets, laptops and workstations.

1. Resource pooling: what gives cloud provides economies of scale, which they pass on to their customers, making cloud cost-efficient. Resources dynamically assigned based on deman.

1. Rapid elasticity: you can access more resources when you need them, and scale back when you don't.

1. Measured Service: you only pay for what you use or reserve as you go. Resource usage is monitored, measured, and reported transparently base on utilization.

- ### <ins>Cloud Computing as a Service (CaaS):</ins>
- Leverage remote systems on-demand over the open internet, scaling up and scaling back, and paying for what you use making them more cost-efficient while also making organizations more agile in responding to changes in their markets.
![Cloud Computing as a Service](Assets/Cloud%20Computing%20as%20a%20Service.png)

### <ins>Three deployment models</ins>
- There three types of cloud deployment models

1. Public: when you leverage cloud services over the open internet on hardware owned by the cloud provider, but its usage is shared by other companies.

1. Private: the cloud infrastructure is provisioned for exclusive use by a single organization. It could run on-premises or it could be owned, managed, and operated by a service provider.

1. Hybrid: usage a mix of both public and private clouds, working together seamlessly.

### <ins>Three service models</ins>
- The three service models are based on the three layers in a computing stack

- These cloud computing models are aptly reffered to as Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS).

1. Infrastructure (Infrastructure as a Service - IaaS): you get access to infrastructure and physical computing resources such as servers, networking, storage and data center space - without the need to manage or operate them.

1. Platform (Platform as a Service - PaaS): you get access to the platform, that is the hardware and software tools, usually those needed to develop and deploy applications to users over the internet.

1. Applications (Software as a Service - SaaS): is a software licensing and delivery model in which software and applications are centrally hosted and licensed on a subscription basis, and sometimes also referred to as "on-demand software".

## **History and Evolution of Cloud Computing**
### <ins>Cloud computing evolution</ins>
- Dates to the 1950s when large-scale mainframes with high volume processing power bacame available.

- The practice of time sharing, or resource pooling, evolved.

- Multiple users were able to access the same data storage layer and CPU power.

- In the 1970s, with the release of an operating system called Virtual Machine (VM), it bacame possible for mainframes to have multiple virtual systems, or virtual machines, on a single pysical node evolving the 1059s application of shared access of a mainframe by allowing multiple distinct compute environments to exist n the same physical hardware.
![Virtual machine](Assets/Virtual%20machine.png)

- Virtualization thus acame a technology driver and a huge catalyst for some of the biggest evolutions in communications and computing.

- With the internet becomeing more accessible, and the need to make hardware costs more viable, srver were virtualized into shared hosting environments, virtual private servers, and virtual dedicated servers, using the same types of functionality provided by the virtual machine operating system. This is enabled by hypervisors.

- <ins>Hypervisor:</ins> is a small software layer that enables multiple operating systems to run alongside each other, sharing the same physical computing resources. A hypervisor also separates the Virtual Machines logically, assigning each its own slice of the underlying computing power, memory, and storage, preventing the cirtual machines from interfering with each other. So, if one operating system suffers a crash or a security compromise, the others keep working.

- As technologies and hypervisors improved and were able to share and deliver resources reliably, some companies decided to make the cloud’s benefits accessible to users who didn’t have an abundance of physical servers to create their own cloud computing infrastructure. Since the servers were already online, the process of spinning up a new instance was instantaneous. Users could now order cloud resources they needed from a larger pool of available resources and they could pay for them on a per-use basis, also known as Pay-As-You-Go.

- <ins>Pay-As-You-Go</ins>
![Pay-As-You-Go](Assets/Pay%20as%20you%20go.png)

- <ins>Cloud: Switch from CapEx to OpEx</ins>
![Cloud: Switch from CapEx to OpEx](Assets/Cloud%20switch%20from%20capex%20to%20opex.png)

## **Key Considerations for Cloud Computing**
### <ins>Key drivers for moving to cloud</ins>
- Agility, flexibility and competitiveness are key drivers for moving to the cloud, provided it is done without creating business disruption or issues related to security, compliance and performance.

- Considerations that organizations ca use as a guide while working through their cloud strategy:

  - <ins>1. Infrastructure and workloads:</ins> The cost of building and operating data centers can become astronomical. On the other hand, low initial costs and pay-as-you-go attributes of cloud computing can add up to significant cost savings. Another point to consider is that not all workloads may be ready for the cloud, as is.

  - <ins>2. SaaS and development platforms:</ins> Organizations need to consider if paying for application access is a more viable option than purchasing off-the-shelf software and subsenquently investing in upgrades. Organizations also need to consider speed and productivity, what it means for them to get a new application up and running in 'x' hours on the cloud versus a couple of weeks, even months on traditional platforms. And the person-hour cost efficiencies they gain from using cloud dashboards, real-time statistics, and active analytics. Lastly, organizations need to consider the impact of making a wrong decision, their risk exposure. For example, is it riskier for them to invest in the hardware and software or rent by the hour? Is it safer for them to work on a 12-month plan to build, write, test and release the code if they're uncertain about adoption? And is it better fr them to "try" something new paying-as-you-go rather than making long-term decisions based on little or no trial or adoption?

### <ins>Benefits of cloud adoption</ins>

- <ins>Flexibility:</ins> users can scale back or scale up services to fit their needs, customize applications, and access cloud services from anywhere with an internet connection. Cloud infrastructure scales on demand to support fluctuating workloads. Organizations can determine their level of control with as-a-service options. Users can select from a menu of pre-built tools and features to build a solution that fits their specific needs. And Virtual Private Cloudsm encryption, and API keys help keep data secure.

- <ins>Efficiency:</ins> enterprise users can get applications to market quickly without worring about underlying infrastructure costs or its maintenance. Cloud-based applications and data are accessible from virtually any internet-connected devide. Hardware failures do not result in data loss because of networked backups. Cloud computing uses remote resources, saving organiztions the cost of servers and other equipment, and paying on use-basis.

- <ins>Strategic Value:</ins> Cloud services give enterprises a competitive advantage by providing the most innovative technologies available while managing the underlying infrasctructure, thus enabling organizations to focus on their priorities. While cloud brings great opportunity, it also introduces challenges for business leaders and IT departments. Some of these perceived risks include:
  
  - Data security, associated with loss or unavailability of data causing business disruption;

  - Governance and sovereignty issues;

  - Legal, regulatory and compliance issues;
  
  - Lack of standardization in how the contantly evolving technologies integrate and interoperate;

  - Choosing the right deployment and service models to serve specific needs;

  - Partnering with the right cloud service providers;

  - Concerns related to business continuity and disaster recovery.

> Organizations can no longer think of cloud adoption as something that is to be looked at in the future. With the right cloud adoption strategies, technologies, services and service providers, these risks can be mitigated.

## **Key Cloud Service Providers**
### <ins>Future of cloud computing</ins>
![Future of cloud computing](Assets/Future%20of%20cloud%20computing.png)

### <ins>Cloud service providers</ins>
![Cloud service providers](Assets/Cloud%20service%20providers.png)

- <ins>Alibaba Cloud (Aliyun):</ins> while relatively new, is the largest Chinese cloud computing service provider. Aliyun provides a comprehensive suite of global cloud computing services to power not just their customer's online business but also the Alibaba Group's own e-commerce ecosystem. It offers a host of products and service such as compute, network, storage, security, monitoring and managing, communication, analytics, IoT, application development, data migration and web hosting.

- <ins>Amazon Web Services (AWS):</ins> was one of the first to enter the cloud computing space and offers an extensive range of Infrastructure and Platform services to individuals, companies, and governments on a metered pay-as-you-go basis. AWS provides a wide range of products, services and solutions raging from Compute, DevOps, Data, Analytics, IoT, Machine Learning, Networking, Content Delivery, Robotics and Serverless Computing.

- <ins>Google Cloud Platform (GCP):</ins> is a suite of cloud computing services, providing Infrastructure, Platform, and Serverless Computing environments. Google also uses GCP internally for their end-user products such as Google Search and YouTube. Google Cloud includes G Suite with products for communication, productivity, collaboration, storage, and more. The Google App Engine is a platform for developing and hosting web applications in Google-managed data centers, automatically allocating and de-allocating resources to handle demand.

- <ins>IBM Cloud:</ins>  is a full stack cloud platform that spans public, private, and hybrid environments with products and services covering compute, network, storage, management, security, DevOps, and databases. Some of their prominent offerings include their Bare Metal Servers, VMWare, Cloud Paks for Application Modernization, Virtual Private Cloud, and the suite of emerging technologies such as AI, IoT, Blockchain, Data and Analytics. With the acquisition of Red Hat, IBM is also positioning itself as the leading hybrid cloud provider.

- <ins>Microsoft Azure:</ins> is a flexible cloud platform for building, testing, deploying, and managing applications and services through Microsoft managed data centers. With its data centers spread out in many regions, Azure provides a global reach with a local presence. It provides Software, Platform, and Infrastructure services supporting Microsoft-specific and third-party languages, tools, and frameworks.

- <ins>Oracle Cloud:</ins>  is primarily known for Software as a Service and Database as a Service (also known as the Oracle Data Cloud). Oracle’s SaaS offering includes wide-ranging applications such as ERP, SCM, HCM, Marketing, Sales, and CX running in the cloud. And the Oracle Data Cloud provides one of the largest cloud-based data management platforms helping customers personalize their online, offline, and mobile marketing campaigns, for targeted audiences. Oracle Cloud also provides some cloud Infrastructure and Platform services.

- <ins>Salesforce:</ins> specializes in their Software as a Service offering that focuses on customer relationship management, supporting businesses to better connect with their customers, partners, and potential customers. Salesforce offers multiple cloud services such as Sales Cloud, Service Cloud, and Marketing Cloud, helping customers track analytics in real-time, customer success and support, customer complaints, even listening in to customers across social platforms to automatically route them to appropriate agents for resolution.

>  SAP is known for Enterprise software and applications such as ERP, CRM, HR, and Finance, running in the cloud. There is also an SAP Cloud Platform for building and extending business applications with rapid innovation cycles in a secure cloud computing environment managed by SAP.

# Business case for Cloud Computing

## **Cloud adoption - no longer a choice**
- Goes from a single individual from a glova multi-billion dollar enterprise.

- Anybody can access the computing capacity they need on the cloud.

- The lag time from decision to value is no longer a journey of years with high upfront capital, since cloud makes it possible for business to experiment, fail, and learn much faster, with low risk exposure.

- Business have greater freedom to change course than to live with the consquences of expensive decisions taken in the past.

- According to an IBM Institute for Business Value study, more than three-quarters of enterprises today are using cloud computing to expand into new industries. 74% have adopted cloud to improve customer experience, and 71% use cloud to create enhanced products and services while simultaneously downsizing legacy systems and reducing costs. To remain competitive, businesses need to be able to respond quickly to marketplace changes, use analytics to understand customer experience, and apply that understanding to adapt their products and services based on what they learn.

- Product lifecycles have shortened, and barriers to entry have become lower. Cognitively-enabled workflows, Applied exponential technologies such as AI, Automation, IoT, and Blockchain, applications that span new and legacy solutions, and open hybrid and secure Multicloud infrastructures, are today's enablers for growth, agility and innovation.

- The power, scalability, flexibility, and pay-as-you-go economics of cloud has made it the underpinning foundation for digital transformation.

- Businesses that haven’t already, or are not currently, integrating cloud into their business strategy, run the risk of lacking the speed, agility, innovation, and decision-making capacities needed to be competitive, as also their ability to respond to digital disruption.

## **Cloud adoption - some case studies**

1. To become more responsive to customer needs, American Airlines needed a new technology platform and a new approach to development that would help it deliver digital self-service tools and customer value more rapidly across its enterprise. The airline recognized the opportunity to remove the constraints of their existing customer-facing applications, based on monolithic code into cloud-native based microservices architecture on the cloud. The results: Faster development and release of new apps. Improved operational reliability, productivity, and end customer response times. Cost savings by avoiding existing upgrade costs via migration to the IBM Cloud.

1. REMOVING BARRIERS TO INNOVATION: UBank excels at finding innovative ways to meet demands. Continually challenged to find more efficient ways to operate, UBank’s IT team explored a Platform as a Service (PaaS) cloud development model. Their need was to give more control to their developers, reduce the need for additional resources, faster speed to market, and removing barriers in going from an idea to production. UBank launched new initiatives in an IBM Cloud Platform environment, including a virtual assistant that incorporates IBM Watson technology to support the bank’s online home loan application. The results: Faster time to market made possible through the Cloud Platform framework, that streamlines development and empowers product teams. Foster greater innovation with cloud-based development resources that are quick, easy, and cost-effective to deploy more efficient operations.

1. DEMAND FOR ENTERPRISE SCALE: Since its inception in 2008, Bitly has journeyed from a startup that offered intelligent link-shortening technology adopted by users to compress lengthy URLs for social media posts, to an enterprise product. Seeking an agile, cost-effective IT infrastructure to support this transition, Bitly started planning for cloud migration. Their need was to have a cloud-based model with pay-as-you-go pricing, the ability to scale up and down, a more global presence, and the ability to geodistribute into more POPs. And they wanted it to be low-risk. Bitly migrated to an IBM Cloud environment, establishing a scalable hosting platform for low-latency delivery to enterprise customers around the world. The results: 25 billion data-infused links migrated from one hosting site to Cloud infrastructure with data center locations worldwide. 1 billion user interaction data set stored and managed in a flexible, cost-effective Cloud Object Storage environment. Transformed IT operations to scale for growth, control costs and focus valuable resources on new product development.

1. ACCELERATING GROWTH: Financial traders demand extreme speed and availability from trading systems. Profitability depends on split-second decisions. As a leading online broker in forex, commodities, equities, cryptocurrencies, indices, and other financial instruments, ActivTrades enables investors to buy and sell on numerous financial markets. Investors need reliable access to accurate market information, combined with the ability to move rapidly to execute trades. As its client base grew, Active Trades wanted to cut latency, accelerate execution, and streamline the delivery of new functions. ActivTrades migrated three major trading systems from on-premises infrastructure to IBM Cloud for VMware solutions, backed by data storage, networking, and security offerings on the IBM Cloud. The results: Up to 3X performance boost, helping clients seize fleeting opportunities for profit. Security-rich cloud platform with ultra-high availability protects client investments. Hours, not days to fire up new resources, for faster response to emerging requirements.

# Emerging Technologies Accelerated by Cloud
- In this new era, technologies such as Internet of Things, Big Data, artificial intelligence, and blockchain are disrupting existing business models and industries while creating unprecedented opportunities for businesses to differentiate themselves and create value for their clients.

- The power, scale, dynamic nature, and economics of the cloud resources make cloud computing a key enabler for adoption and evolution of these emerging technologies.

## **Internet of things in the cloud**
- The Internet of Things, or IoT, is a giant network of connected things and people that have changed much of how we live our daily lives - from the way we drive, to how we make purchases, monitoring our personal health, and even how we get energy for our homes.

- Smart devices and sensors are continuously tracking and collecting data. For example, a smart building could have thousands of sensors measuring all kinds of data related to thermal, optical, structural, and environmental stimuli.

- An unprecedented amount of data is being generated, putting a tremendous strain on the Internet. That is where the cloud comes in, by connecting the IoT device user to the cloud - be it for device registration, device identity, storing data, or accessing enterprise data. 

- Data collected through IoT devices is stored and processed on the cloud since IoT devices can be in a state of motion, the cloud serves as a collection point in closest proximity, minimizing the latency in reporting up the data points and providing a response back to the IoT application. So, from IOT platforms running entirely on the cloud to the interfaces used by customers to interact these devices, to the backend analytics platforms - cloud computing supports and enables IoT. 

- Cloud service providers also offer specialized IoT services designed to help speed up the development of IoT solutions.

## **Artificial inteligence on the cloud**

- Making sense of the endless streams of data is where Artificial Intelligence, or AI, comes in. Many of the applications where we apply AI today simply wouldn't have been possible without the scalable, -on-demand computing offered by the cloud.

- There is a three-way relationship between AI, IoT, and Cloud. Just as AI consumes the data produced by IoT devices, the IoT devices’ behavior can be dictated based on responses from AI. For example, Smart Assistants, a common type of IoT device, continues to learn about the user’s preferences as usage grows, such as the songs they like, their home temperature settings, preferred meal times, and over time they anticipate their actions based on the user’s past history.

- What we see is a symbiotic relationship between IoT, AI, and Cloud. IoT delivers the data, AI powers the insights, and both these emerging technologies leverage cloud’s scalability and processing power to provide value to individuals and businesses alike.

## **Blockchain and analytics in the cloud**

### <ins>Blockchain in the cloud</ins>
- Blockchain is a secure, distributed, open technology that can help speed up processes, lower costs, and build transparency and traceability in transactional applications. It is an immutable Network allowing members to view only those transactions that are relevant to them. The more open, diverse, and distributed the network, the stronger the trust and transparency in the data and transactions.

- 85% of businesses today rely on multiple clouds to meet their IT needs, with more than 70% using more than three. These businesses need to be able to move applications and data across multiple clouds easily and securely, leading to the emerging demand to build and manage business applications such as blockchain for the multi cloud environment.

- Blockchain and AI, much like IoT and AI, powered by the cloud, also have a three-way relationship. Where blockchain technology provides the trusted, decentralized source of truth, AI powers the analytics and decision-making from the data collected, and cloud provides globally distributed, scalable, and cost-efficient computing resources to support both the unprecedented amounts of data being collected and the processing power required to draw insights from this data.

- Blockchain serves to make AI more understandable by recording the data and variables that go into a decision made in an AI algorithm, leading to greater trust and transparency in the conclusions and decisions made by these algorithms.

### <ins>Analytics in the cloud</ins>
- Analytics technologies on the cloud leverage the flexibility, scalability, and computing resources available on the cloud. From tracking trends on social media to predict future events, to analyzing data to build machine learning models that can be deployed in cognitive applications, cloud provides the integrated environment that is required to leverage data for continuous improvement and accelerated business growth.

# **Service models**

## **Overview of Cloud Service Models**
- IaaS, the cloud provider manages the physical resources, data centers, cooling power, Network and security, as well as computing resources that include servers and storage. 

- PaaS, the provider, in addition to the computing resources, also manages the platform infrastructure which includes the operating systems, development tools, databases, and business analytics. 

- SaaS model, in addition to the infrastructure and the platform resources, the provider also hosts and manages the applications and data.

## **IaaS - Infrastructure as a Service**
- Infrastructure-as-a-Service, commonly referred to as “IaaS,” – or simply “eye-es” -is a form of cloud computing that delivers fundamental compute, network, and storage resources to consumers on-demand, over the internet, on a pay-as-you-go basis.

- The cloud provider hosts the infrastructure components traditionally present in an on-premises data center as well as the virtualization or hypervisor layer.

- In an IaaS Cloud environment, customers can create or provision virtual machines (or VMs) in their choice of Region and Zone available from the Cloud Provider. These VMs typically come pre-installed the customer’s choice of operating system. The customers can then deploy middleware, install applications, and run workloads on these VMs. They can also and create storage for their workloads and backups.

- Cloud providers often provide customers the ability to track and monitor the performance and usage of their cloud services and manage disaster recovery.

- <ins>Components of cloud infrastructure:</ins>
  - Physical data centers: IaaS providers manage large data centers that contain the physical machines required to power the various layers of abstraction on top of them. In most IaaS models, end users do not interact directly with the physical infrastructure but experience it as a service provided to them.

  - Compute: IaaS providers manage the hypervisors and end-users programmatically provision virtual instances with desired amounts of compute, memory, and storage resources. Cloud compute typically comes with supporting services like auto scaling and load balancing that provide scalability and high performance.

  - Network: Users get access to networking resources on the cloud through virtualization or programmatically, through APIs.

  - Storage: There are three types of cloud data storage: object, file, and block storage. Object storage is the most common mode of storage in the cloud, given that it is highly distributed and resilient.

- <ins>IaaS supports a wide array of use cases:</ins>

  - Organizations today are using cloud infrastructure services to enable their teams to set up test and development environments faster, helping create new applications more quickly. By abstracting the low-level components, cloud infrastructure is helping developers focus more on business logic than infrastructure management.

  - Business continuity and disaster recovery require a significant amount of technology and staff investments. IaaS is helping organizations reduce this cost and make applications and data accessible as usual during a disaster or outage.

  - Organizations are using cloud infrastructure to deploy their web applications faster and also scale infrastructure up and down as demand fluctuates.

  - Organizations are leveraging the high-performance computing capabilities of cloud infrastructure to solve complex problems involving millions of variables and calculations such as climate and weather predictions and financial modeling.

  - Mining massive data sets to locate valuable patterns, trends, and associations requires a huge amount of processing power. Cloud infrastructure not only provides the required high-performance computing but also makes it economically viable.

> While there are some concerns regarding the lack of transparency in the cloud infrastructure’s configuration and management and dependency on a third-party for workload availability and performance, Infrastructure-as-a-Service is the fastest growing cloud model today.

## **PaaS - Platform as a Service**
- Platform-as-a-Service, commonly referred to as “PaaS” or simply "pass", is a a cloud computing model that provides customers a complete platform to develop, deploy manage, and run applications created by them or acquired from a third-party.

- The PaaS provider hosts everything—servers, networks, storage, operating system, application runtimes, APIs, middleware, databases, and other tools at their data center.

- The provider also takes responsibility for the installation, configuration, and operation of the application infrastructure, leaving the user responsible for only the application code and its maintenance. Customers pay for this service on a usage basis and purchase resources on-demand.

- With IaaS, the cloud provider offers access to ‘raw’ computing resources, such as servers, storage, and networking, while the user is responsible for the platform and application software. With PaaS, the cloud service provider delivers and manages the entire platform infrastructure, abstracting users from the lower-level details of the environment.

### <ins>Essential characteristics of PaaS</ins>
- PaaS clouds are distinguished by the high level of abstraction they provide to the users, eliminating the complexity of deploying applications, configuring infrastructure, and provisioning and configuring supporting technologies like load balancers and databases.

- PaaS clouds provide services and APIs that help simplify the job of developers in delivering elastically scalable and highly available cloud applications. These services typically include a variety of capabilities such as APIs for distributed caching, queuing and messaging, file and data storage, workload management, user identity, and analytics, thus eliminating the need to integrate disparate components.

- The PaaS runtime environment executes end-user code according to policies set by the application owner and cloud provider. Many of the PaaS offerings provide developers with rapid deployment mechanisms, or “push and run” mechanism, for deploying and running applications.

- PaaS offerings support a range of application infrastructure or middleware capabilities, such as application servers, database management systems, business analytics servers, mobile back-end services, integration services, business process management systems, rules engines, and complex event processing systems. Such an application infrastructure assists developers by reducing the amount of code that must be written while expanding the application’s functional capabilities.

- The most important use case for PaaS is strategic—build, test, deploy, enhance, and scale applications rapidly and cost-effectively.

### <ins>Use cases for PaaS</ins>
- API development and management: Organizations are using PaaS to develop, run, manage, and secure APIs and microservices, which are loosely coupled, independently deployable components and services.

- Internet of Things, or IoT: PaaS clouds support a broad range of application environments, programming languages, and tools used for IoT deployments.

- Business analytics/intelligence: PaaS tools allow organizations to analyze their data to find business insights that enable more informed business decisions and predictions.

- Business Process Management, or BPM: Organizations are using the PaaS cloud to access BPM platform delivered as a service.

- Master data management, or MDM: Organizations are leveraging the PaaS cloud to provide a single point of reference for critical business data such as information about customer transactions and analytical data to support decision making.

### <ins>Advantages of using PaaS</ins>
- Scalability, made possible because of the rapid allocation and deallocation of resources with a pay-as-you-use model offered by PaaS. The APIs, support services, and middleware capabilities that PaaS clouds provide assist developers in focusing their efforts on application development and testing, resulting in faster time to market for their products and services. Middleware capabilities also reduce the amount of code that needs to be written while expanding the application’s functional capabilities.

- Greater agility and innovation because using PaaS platforms means that you can experiment with multiple operating systems, languages, and tools without having to invest in these resources. You can evaluate and prototype ideas with very low risk exposure resulting in faster, easier, less-risky adoption of a wider range of resources.

### <ins>PaaS available offerings</ins>

- Some of the key PaaS offerings available in the market today include AWS Elastic Beanstalk, Cloud Foundry, IBM Cloud Paks, Windows Azure, RedHat OpenShift, Magento Commerce Cloud, Force.com, and Apache Stratos. PaaS clouds do come with some risks—risks that all cloud offerings have in general, such as information security threats and dependency on the service provider’s infrastructure.

### <ins>Risks of PaaS</ins>

- Services can get impacted when a service provider’s infrastructure experiences downtime. 

- Customers also don’t have any direct control over the changes that may take place when a provider makes changes in its strategy, service offerings, or tools. 

- But the benefits can far outweigh these risks.

## **SaaS - Software as a Service**
- Software-as-a-Service, “SaaS”, is a cloud offering that provides users with access to a service provider’s cloud-based software.

- SaaS providers maintain the servers, databases, and code that constitute an application.

- They also manage access to the application, including security, availability, and performance.

- Applications reside on a remote cloud network, and users use these applications without having to maintain and update the infrastructure.

### <ins>SaaS supports</ins>
- Core business processes supported by SaaS today include email and collaboration via offerings such as Microsoft's Office 365 and Google's Gmail

- Customer Relationship Management via services such as NetSuite CRM and Salesforce

- Human Resource Management via services from Workday and SAP SuccessFactors, financial management, billing and collaboration, and many more.

> According to Forrester Research, SaaS has overtaken on-premises solutions in categories such as human capital management (HCM), customer relationship management (CRM), and collaboration. Solutions once available with several different deployment options are now SaaS-only.

### <ins>Key characteristics</ins>
- SaaS clouds have a multitenant architecture. Infrastructure and code are maintained centrally and accessed by all users.

-  SaaS makes it easy for users to manage privileges, monitor data use, and ensure everyone sees the same information at the same time.

- Security, compliance, and maintenance are all part of the offering.

- Users can customize applications to fit their business processes with point-and-click ease; can customize the UI to work with their branding guidelines; they can modify data fields and enable or disable features within the business process. These customizations are preserved through upgrades; pay for the use of the services via a subscription model. The use of resources can be scaled easily, depending on service needs.

### <ins>Key benefits</ins>

- Businesses can directly procure solutions without upfront capital and assistance from IT, greatly reducing the time from decision to value from months to days.

- Greatly increases workforce productivity and efficiency.
  - Users can access core business apps from wherever they are. 
  - Users can also buy and deploy apps in minutes, reducing the typical obstacles enterprises have to test the products they they might use.

### <ins>Use cases</ins>
- Organizations are moving to SaaS for their core business needs as part of their strategic transformation to reduce on-premises IT infrastructure and reduce capital expenditure.

- Oragnzaitions are leveraging SaaS to avoid the need for ongoing upgrades, maintenance, and patching, done traditionally by internal IT resources; applications run reliably with minimal input, for example, email servers and office collaboration and productivity tools.

- Organizations are increasingly opting for SaaS eCommerce Platforms to manage their websites, marketing, sales, and operations. With SaaS, organizations are able to take advantage of the resilience and business continuity of the cloud provider.

- Enterprises are now developing SaaS integration platforms (or SIPs) for building additional SaaS applications, moving SaaS beyond standalone software functionality to a platform for mission-critical applications.

### <ins>Concerns</ins>
- Primary among them being data ownership and data safety. Security is an important consideration when you’re allowing a third-party to maintain business-critical data.

- Application access relies on a good internet connection. If you’re not connected, you cannot access the apps.

# **Deployment models**
- Deployment models indicate where the infrastructure resides, who owns and manages it, and how cloud resources and services are made available to users. The three cloud deployment models include—Public Cloud, Private Cloud, and Hybrid Cloud.

## **Public Cloud**
- In a public cloud model, users get access to servers, storage, network, security, and applications as services delivered by cloud service providers over the internet.

- Using web consoles and APIs, users can provision the resources and services they need.

- The cloud provider owns, manages, provisions, and maintains the infrastructure, renting it out to customers either for a subscription charge or usage-based fee. Users don’t own the servers their applications run on or storage their data consumes, or manage the operations of the servers, or even determine how the platforms are maintained.

- In very much the same way that we consume and pay for utilities such as water, electricity, or gas in our everyday lives, we don’t own any of these cloud resources—we make an agreement with the service provider, use the resources, and pay for what we use within a certain period.

- Public clouds offer significant cost savings as the provider bears all the capital, operational, and maintenance expenses for the infrastructure and the facilities they are hosted in. It makes scalability as easy as requesting more capacity. However, with a public cloud, the user does not have any control over the computing environment and is subject to the performance and security of the cloud provider’s infrastructure.

- There are several public cloud providers in the market today, such as Amazon Web Services, Microsoft Azure, IBM Cloud, Google Cloud Platform, and Alibaba Cloud.

- While all providers include a common set of core services, such as servers, storage, network, security, and databases, they also offer a wide spectrum of niche services with varied payment options.
![Public cloud providers in the market today](Assets/Public%20cloud%20providers%20in%20the%20market%20today.png)

### <ins>Public cloud characteristics</ins>
- A public cloud is a virtualized multi-tenant architecture enabling tenants or users to share computing resources, residing outside their firewalls.

- The cloud providers pool of resources, including infrastructure, platforms, and software, are not dedicated for use by a single tenant or organization.

- Resources are distributed on an as-needed basis offered through a variety of subscription and pay-as-you-go models.

### <ins>Public cloud benefits</ins>
- Vast on-demand resources are available, allowing applications to respond seamlessly to fluctuations in demand.

- Considering the large number of users that share the centralized cloud resources on-demand, the public cloud offers the most significant economies of scale.

- The sheer number of server and network resources available on the public cloud means that a public cloud is highly reliable. If one physical component fails, the service still runs unaffected on the remaining available components.

### <ins>Public cloud concerns</ins>
- Security and data sovereignty compliance.

- Security issues such as data breaches, data loss, account hijacking, insufficient due diligence, and system and application vulnerability seem to be some of the fears users continue to have concerning security in the public cloud.

- With data being stored in different locations and accessed across national borders, it has also become increasingly critical for companies to be compliant with data sovereignty regulations governing the storage, transfer, and security of data.

### <ins>Public cloud use cases</ins>
- Organizations are increasingly opting to access cloud-based applications and platforms so their teams can focus on building and testing applications, and reducing time-to-market for their products and services.

- Businesses with fluctuating capacity and resourcing needs are opting for the public cloud.

- Organizations are using public cloud computing resources to build secondary infrastructures for disaster recovery, data protection, and business continuity.

- More and more organizations are using cloud storage and data management services for greater accessibility, easy distribution, and backing up their data.

- IT departments are outsourcing the management of less critical and standardized business platforms and applications to pubic cloud providers.

## **Private Cloud**
- The National Institute of Standards and Technology defines Private Cloud as cloud infrastructure provisioned for exclusive use by a single organization comprising multiple consumers, such as the business units within the organization. It may be owned, managed, and operated by the organization, a third party, or some combination of them, and it may exist on or off premises.

### <ins>Internal or external</ins>
- Internal infrastructure: when the platform is provisioned over an organization’s internal infrastructure, it runs on-premises and is owned, managed, and operated by the organization.

- External infrastructure: When it is provisioned over a cloud provider’s infrastructure, it is owned, managed, and operated by the service provider.

### <ins>Virtual Private Cloud (VPC)</ins>
- This external private cloud offering that resides on a cloud service provider’s infrastructure is called a Virtual Private Cloud, or VPC.

- A VPC is a public cloud offering that lets an organization establish its own private and secure cloud-like computing environment in a logically isolated part of a shared public cloud.

- Using a VPC, organizations can leverage the dynamic scalability, high availability, and lower cost of ownership of a public cloud, while having the infrastructure and security tailored to the organization’s unique needs.

- Virtual Private Clouds are offered by most Public Cloud providers such as IBM and Amazon.

### <ins>Best of both worlds</ins> 
- A private cloud is a virtualized environment modeled to bring in the benefits of a public cloud platform without the perceived disadvantages of an open and shared public platform.

- Users of a private cloud, such as Developers and Business Units in an organization, still get to leverage benefits such as economies of scale, granular scale, operational efficiencies, and user self-service, while exercising full control over access, security, and compliances specific to their organization and business.

### <ins>Benefits of private clouds</ins> 
1. The ability to leverage the value of cloud computing using systems that are directly managed or under perceived control of the organization’s internal IT.

1. The ability to better utilize internal computing resources, such as the organization’s existing investments in hardware and software, thereby reducing costs.

1. Better scalability through virtualization and “cloud bursting,” i.e., leveraging public cloud instances for a period of time but returning to the private cloud when the surge is met.

1. Controlled access and greater security measures customized to specific organizational needs.

1. The ability to expand and provision things in a relatively short amount of time, providing greater agility.

> Organizations may choose to opt for private cloud because of various reasons—because their applications provide a unique competitive advantage, there are security and regulatory concerns, or because the data is highly sensitive and subject to strict industry or governmental regulations.

### <ins>Common use cases</ins>
1. Is an opportunity for organizations to modernize and unify their in-house and legacy applications. Moving these applications from their dedicated hardware to the cloud also allows them to leverage the power of the compute resources and multiple services available on the cloud.

1. Using the private cloud, organizations are integrating data and application services from their existing applications with public cloud services. This allows them to leverage their private cloud’s compute capability for the larger jobs while pulling data into an application on a private cloud to leverage public cloud services — essentially opening their data centers to work with cloud services.

1. Application portability is a key feature of cloud platforms. Using the private cloud gives organizations the ability to build applications anywhere, and move them anywhere, without having to compromise security and compliance in the process.

1. Some of the key reasons that may prevent an organization from moving to a public cloud include security and regulatory concerns, and data sensitivity. A private cloud offers these organizations the benefits of on-demand enterprise resources while exercising full control over critical security and compliance issues from within the environment of their dedicated cloud.

## **Hybrid Cloud**
- Hybrid Cloud is a computing environment that connects an organization's on-premise private cloud and third-party public cloud into a single flexible infrastructure for running the organization's applications and workloads.

- The mix of public and private cloud resources gives organizations the flexibility to choose the optimal cloud for each application or workload, workloads move freely between the two clouds as needs change.

- Organizations can choose to run the sensitive highly regulated and mission-critical applications or workloads with reasonably constant performance and capacity requirements on private Cloud infrastructure. While deploying the less sensitive and more dynamic workloads on the public cloud.

- With proper integration and orchestration between the public and private clouds, you can leverage both clouds for the same workload. For example, you can leverage additional public cloud capacity to accommodate a spike in demand for a private cloud application also known as cloud bursting.

### <ins>The Three Tenets</ins>
- The key tenants of a hybrid cloud are interoperability, scalability and portability.

- Interoperability: The public and private cloud services can understand each other's APIs, configuration, data formats, and forms of authentication and authorization.

- Scalability: When there is a spike in demand a workload running on the private cloud can leverage the additional public cloud capacity making it scalable.

- Portability: A hybrid cloud is also portable, since you're no longer locked in with a specific vendor, you can move applications and data not just between on-premise and cloud systems, but also between cloud service providers.

### <ins>Types of Hybrid Clouds</ins>
- There are two common types of hybrid clouds, hybrid monocloud and hybrid multi-cloud.

  - Hybrid clouds: is a hybrid cloud with one cloud provider

  - Hybrid multi-cloud: is an open standards-based stack that can be deployed on any public cloud infrastructure.

> The difference lies in the flexibility that the hybrid multicloud offers organizations to move workloads and environments from one vendor to another. There is also a and of hybrid multicloud called the, Composite Multicloud, which makes this flexibility even more granular as it distributes single applications across multiple providers, allowing you to move application components across cloud services and vendors as needed.

### <ins>Benefits</ins>
1. Security and compliance

1. Scalability and resilience

1. Resource optimization

1. Cost-saving

- A hybrid cloud lets organizations deploy highly regulated or sensitive workloads in a private cloud while running the less-sensitive workloads on a public cloud.

- Using a hybrid cloud you can scale up quickly, inexpensively, and even automatically using the public cloud infrastructure, all without impacting the other workloads running on your private cloud.

- Because you're not locked-in with a specific vendor and also don't have to make either-or decisions between the different cloud models, you can make the most cost-efficient use of your infrastructure budget. You can maintain workloads where they are most efficient, spin-up environments using pay-as-you-go in public cloud, and rapidly adopt new tools as you need them.

### <ins>Use cases</ins>

- A typical organization will have a range of applications and workloads spread across private public and traditional IT environments. This represents a range of opportunities for optimization via a hybrid cloud approach.

- Some increasingly common hybrid cloud use cases:

  - Software-as-a-Service integration, through hybrid integration organizations are connecting software-as-a-service applications available in the public cloud to their existing public cloud, private cloud, and traditional IT applications to deliver new solutions.

  - Data and AI integration, organizations today are creating richer and more personal experiences by combining new data sources on the public cloud. Such as weather, social, the Internet of things, CRM, and ERP, with existing data in analytics, machine learning, and AI capabilities.

  - Enhancing legacy apps, an increasing number of organizations are using public cloud services to upgrade their user experience of their on-premises applications and deploy them globally to new devices, while incrementally modernizing their Core Business Systems.

  - VM ware migration, more and more organizations are lifting and shifting their on-premises virtualized workloads to a public cloud without conversion or modification to reduce their on-premises data center footprint and position themselves to scale without added capital expense.

> Hybrid cloud is a concept that's been around for quite some time, but we're finding that it's becoming increasingly used to architect and modernize existing or legacy applications. According to research we found that 75% of non-cloud applications will be moving to the cloud in the next three years. This goes to say that if you're not already thinking about your hybrid cloud strategy, you may be falling behind.

# **Cloud infrastructure**

## **Overview of cloud infrastructure**
- The infrastructure layer is the foundation of the cloud. This layer consists of physical resources that are housed in Regions, Zones and Data Centers.

- A Cloud provider’s IT environment is typically distributed across many regions around the world. A cloud region, is a geographic area or location where a cloud provider’s infrastructure is clustered, and may have names like NA South or US East. The cloud regions are isolated from each other so that if one region was impacted by a natural disaster like an earthquake, the cloud operations in other regions would keep running.

- Each Cloud Region can have multiple Zones (or Availability Zones or AZ for short), which are typically distinct Data Centers with their own power, cooling and networking resources. These Zones can have names like DAL-09 or us-east-1. The isolation of zones improves the cloud’s overall fault tolerance, decreases latency, and avoids creating a single shared point of failure. 

- The Availability Zones (and DataCenters within them) are connected to other AZs and regions, private datacenters and the Internet using very high bandwidth network connectivity.

- A cloud data center is a huge room or a warehouse containing cloud infrastructure. These data centers contain pods and racks or standardized containers of computing resources such as servers, as well as storage, and networking equipment - virtually everything that a physical IT environment has.

### <ins>Computing resources</ins>
- Cloud providers offer several compute options – Virtual Servers, Bare Metal Servers, and “Serverless” computing resources.

- Most of the servers in a cloud datacenter run hypervisors to create virtual servers or virtual machines (also called VMs for short), that are software-based computers, based on virtualization technologies.

- Other servers in the racks are bare metal servers that are physical servers that aren’t virtualized. Customers can provision VMs and Bare Metals servers as and when they need them and run their workloads on them.

- loud users can also run their workloads on serverless computing resources, which are an abstraction layer on top of virtual machines.

### <ins>Storage</ins>
- Information and data can consist of files, code, documents, images, videos, backups, snapshots, and databases and can be stored in many different types of storage options on the Cloud.

- Bare Metal Servers and Virtual Servers are provisioned with default storage in local drives. Since these cloud servers can be provisioned and decommissioned by customers on demand and freed up for use by other users, any information stored in a local drive can be lost when you delete or decommission a cloud server. However there are other storage options available on the cloud to persist data that you can choose depending on factors like how important your data is, how quickly you want to be able to access it, how often you access it, and how secure you need it to be. These additional storage options include Block storage, File storage, and Object storage.

- Block and file storage modes are commonly used in traditional data centers, but often struggle with scale, performance and distributed characteristics of cloud.

- Object storage is the most common mode of storage in the cloud as it’s both highly distributed and resilient.

### <ins>Networking</ins>
- Networking infrastructure in a cloud data center includes traditional networking hardware like routers and switches, but more importantly for users of the Cloud, the Cloud providers have Software Defined Networking (or SDN) options where certain networking resources are virtualized or made available programmatically, through APIs. This allows for easier network provisioning, configuration, and management in the cloud.

- When servers in the cloud are provisioned, you need to setup their public and private network interfaces.

- The public network interfaces, as the name suggests, connect the servers to the public internet, whereas the private ones provide connectivity to your other cloud resources and help keep them secure. As in the physical IT world, network interfaces in the cloud need to have IP addresses and subnets either assigned automatically or configured. In a cloud environment it is even more important to configure which network traffic and users can access your resources, which can be done by setting up Security Groups and Access Control Lists (or ACLs). For further security and isolation of your resources in the cloud, most Cloud providers provide Virtual Local Area Networks (VLANs), Virtual Private Clouds (VPCs), and Virtual Private Networks (VPNs). Some of the traditional hardware appliances such as firewalls, load balancers, gateways and traffic analyzers can also be virtualized and made available as services in the cloud.

- Another networking capability provided by the Cloud Providers is Content Delivery Networks or CDNs, that distribute content to multiple points throughout the world so users accessing the content can access it more quickly by getting it from a point nearest to them. We will learn more about some of these cloud networking options and terminology in subsequent videos.

> Cloud infrastructure is constantly advancing and improving.

## **Virtualization and virtual machines explained**
- Virtualization is a fairly old technology, but it's still super relevant to building our cloud computing strategy today.

- Virtualization is the process of creating a software based, or virtual, version of something, whether that be compute, storage, networking, servers, or applications and what makes virtualization feasible, is something called the hypervisor.

- Hypervisor it's simply a piece of software that runs above the physical server, or host. What they do is essentially pull the resources from the physical server and allocate them to your virtual environments. 

- There are two main types of hypervisors: Type 1 and Type 2.

  -  A Type 1 hypervisor is a hypervisor that is installed directly on top of the physical server. They're also called bare-metal hypervisors and are the most frequently typed of use hypervisors since they are the most secure, has lower latency, and these are the ones that you'll see in the market the most. Some examples would be VMware, ESXi, or Microsoft Hyper-v, or even open-source KVM.

  - A Type 2 hypervisor, also called Hosted, are differs from a Type 1 hypervisor for having a layer of host OS that sits between the physical server and the hypervisor. These are a lot less frequent and are mostly used for end-user virtualization. Some examples in the market are Oracle VirtualBox or VMWare workstation. They have high latency than a Type 1 hypervisor so, once you have a hypervisor installed, you can build virtual environments, or virtual machines, or simple put, VMs,

- What makes a VM? A VM is simply a software based computer. They run like a physical computer, have an operating system and applications and are completely independent of one another, but you can run multiple of them on a hypervisor and the hypervisor manages the resources that are allocated to these virtual environments from the physical server.

- Because they are independent, they can run different opperating systems on different virtual machines. For example, Windows, Linux or Unix.

- Because they're independent they're also extremely portable. You can move a virtual machine from one hypervisor to another hypervisor on a completely different machine almost instantaneously, which gives you a lot of flexibility and a lot of portability within your environment.

### <ins>Benefits</ins>

1. Cost savings. When you think about this and the fact that you can run multiple virtual environments from one piece of infrastructure, means that you can drastically reduce your physical infrastructure footprint. This is consolidation at its core. And the fact that you don't have to maintain nearly as many servers, run as much electricity, save on maintenance costs, means that you save on your bottom line at the end of the day.

1. Agility and speed. Spinning up a virtual machine is relatively easy and quick - a lot more simple than provisioning an entire new environment for your developers if they say they want to spin up a new environment so that they can run a test scenario. Whatever it might be, virtualization makes that process a lot simpler and quicker.

1. Lowers your downtime. So, let's say that this host goes out unexpectedly. The fact that you can move virtual machines from one hypervisor to another, on a different physical server, means that you have a great backup plan in place right? So, if this host goes down you can simply move your VMs very quickly to another hypervisor on a machine that is working. Virtualization and VMs are at the center of cloud computing and provide many benefits.

## **Types of virtual machines**

## **Bare metal server**