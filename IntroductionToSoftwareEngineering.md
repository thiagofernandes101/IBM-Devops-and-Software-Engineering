# **Overview of Software Engineering**

## **What is Software Engineering?**

### <ins>Software engineering defined</ins>
- Software engineering involves the application of scientific principles to design and create software. It follows a systematic approach to gather and analyze business requirements, enabling the development, construction, and testing of software applications that meet those requirements effectively.

- As computing emerged in the late 1950s, software engineering was a relatively undefined discipline. However, it has progressively evolved into a modernized engineering field.

- During the 1960s, software engineering emerged as a distinct discipline and underwent significant transformation as new technologies were introduced, making it more scientifically oriented. Consequently, the trends in software engineering shifted from ad hoc programming practices to more formal and standardized methods.

### <ins>Software crisis</ins>
- In the early stages, software creation lacked a standardized development process. However, as computers gained widespread adoption, software became increasingly indispensable in various domains. Unfortunately, the inherent inefficiencies of the software development process presented significant challenges in meeting the rapidly growing demand for computing resources and complex software. This led to the emergence of the 'Software Crisis' in the mid-1960s, lasting until the mid-1980s. 

- During this period, software development frequently encountered issues such as exceeding budget limits, falling behind schedule, and dealing with unmanageable, bug-ridden code. Many organizations had to resort to complete system redesigns to address these challenges. Moreover, approaches that proved effective for smaller software systems often proved inadequate when applied to larger, more intricate projects. 

- By the time older software solutions were completed, newer, superior technologies had already been developed, forcing software engineers to refactor or completely redesign their systems. Often, solutions that worked for small software systems failed to scale up to large, complex projects.

- While some of the previously mentioned issues still persist today, their impact has significantly diminished thanks to the consistent application of engineering principles in the software development process. The availability of computing resources has expanded, and standardized methodologies for software development now enable the creation of scalable, large-scale solutions for complex problems

- The resolution to the "Software Crisis" entailed the transformation of ad hoc coding endeavors into a formalized engineering discipline. Additionally, the mid-1980s witnessed the emergence and proliferation of computer-aided software engineering (CASE) tools, which played a significant role in alleviating the challenges posed by the software crisis.

- CASE tools encompass a diverse range of functionalities and can be classified into six distinct categories:
    - Business analysis and modeling: These tools facilitate the analysis and modeling of business processes, enabling a deeper understanding of requirements and aiding in effective software design.

    - Development tools: This category includes tools that assist in software development tasks, such as debugging environments that streamline the process of identifying and rectifying code errors, ensuring the creation of robust and reliable software.

    - Verification and validation tools: These tools are designed to validate and verify the functionality, performance, and quality of the software being developed. They help identify and address potential defects, ensuring that the final product meets the desired specifications.

    - Configuration management: Tools in this category assist in managing and controlling software configurations, including version control, change tracking, and release management. They enable efficient collaboration among team members and ensure proper organization and tracking of software components.

    - Metrics and measurement: These tools provide quantitative insights into various aspects of the software development process, such as code complexity, test coverage, and productivity metrics. They help in evaluating and improving the efficiency and quality of the software being developed.

    - Project management: Tools in this category aid in planning, organizing, and tracking software development projects. They facilitate tasks such as resource allocation, scheduling, task management, and progress monitoring, enhancing overall project efficiency and ensuring timely delivery.

### <ins>Software engineer vs software developer</ins>
- The term "software engineer" is often used interchangeably with software developer, but there are subtle differences.

    - While software engineers are also developers, the term "software developer" typically implies a narrower focus compared to that of a software engineer.

    - Software engineers possess a broader range of knowledge and typically take a systematic, big-picture approach to software development, whereas developers may exhibit more creativity in their approaches.

    - Both software engineers and software developers possess specialized knowledge, but software engineers apply that knowledge to construct entire systems, whereas software developers utilize their knowledge to write code and implement specific functionality within a system.

    - Software engineers are commonly involved in large-scale projects, with their focus centered on designing the overall structure rather than solving immediate problems.

### <ins>Software engineer responsibilities</ins>
- Software engineers are responsible for the design, construction, and maintenance of software systems. Their diverse range of responsibilities includes:

    - Writing and thoroughly testing code to ensure its functionality and reliability.

    - Collaborating with stakeholders, such as clients, third-party software vendors, security specialists, and fellow team members, to gather requirements and address any concerns or challenges.

### <ins>Software development life cycle (SDLC)</ins>
- The adoption of a systematic, scientific approach to software development has profoundly impacted the creation and design of software. In modern times, the development process is commonly guided by the Software Development Lifecycle (SDLC), which outlines the necessary steps to ensure the development of high-quality software.

## **Introduction the the SDLC**

### <ins>Software development life cycle (SDLC)</ins>
- The Software Development Lifecycle (SDLC) is a systematic approach to developing high-quality software within defined timeframes and budgets, with the ultimate goal of meeting a client's specific business requirements.

- The SDLC establishes distinct phases in the software development process, each with its own set of processes and deliverables. It follows a cyclical pattern of planning, design, and development, which can be implemented iteratively to enhance the software development process.

- By adhering to the SDLC, organizations can mitigate risks and control costs associated with the development of deployable, high-quality software. It provides a structured framework that ensures efficient collaboration, thorough testing, and successful delivery of software solutions.

### <ins>History of the SDLC</ins>
- The emergence of the software development life cycle (SDLC) gained momentum in the mid-1960s, driven by the increasing complexity of software development and the need for a more structured approach.

- As large corporations sought to manage intricate business systems that demanded substantial computational resources, the SDLC provided a deliberate and systematic approach to address these challenges.

- Initially, the SDLC relied on the "waterfall method," a linear approach that guided software development through distinct stages. However, in response to evolving customer needs and changing requirements, the SDLC has since been adapted to incorporate more iterative and flexible methodologies.

- This evolution reflects a shift towards more customer-centric development practices, allowing for continuous feedback and adjustment throughout the software development process. The SDLC has embraced iterative methods to enhance responsiveness and better align software solutions with customer expectations.

### <ins>Advantages of the SDLC</ins>
- There are some key advantages for business following the SDLC.

    1. Improved Efficiency and Risk Reduction: The SDLC provides development teams with a structured process to follow, replacing ad hoc approaches. This enhances efficiency, minimizes errors, and reduces risks associated with software development.

    2. Clear and Well-Defined Phases: The SDLC breaks down the development process into distinct phases, ensuring that team members understand their tasks and deadlines. This facilitates effective communication among customers, stakeholders, and the development team, fostering collaboration and alignment throughout the project.

    3. Enhanced Stakeholder Engagement: The SDLC offers an overview of the entire process, enabling stakeholders to understand their role within it. Each phase's clear boundaries help cross-domain teams determine when they have completed their tasks and when development can progress to the next phase, ensuring timely collaboration and coordinated efforts.

    4. Iterative Approach and Adaptability: The SDLC accommodates iterations, allowing for the incorporation of additional requirements and changes as needed. At the end of a cycle, the process can circle back to address new insights or evolving business needs, resulting in more flexible and adaptable software solutions.

    5. Early Problem Solving: The SDLC incorporates problem-solving early in the cycle. This enables issues to be identified and addressed during the design phase rather than during coding, leading to more efficient problem resolution and preventing potential setbacks later in the development process.

    6. Defined Roles and Reduced Conflicts: Each team member has a well-defined role within the SDLC, reducing conflicts and overlapping responsibilities. This clarity fosters a smoother workflow, improved collaboration, and better overall team dynamics.

## **Phases of the SDLC**

### <ins>SDLC phases</ins>
- The Software Development Lifecycle (SDLC) typically consists of six phases, providing a structured approach to software development:

    1. Planning: This phase involves gathering requirements, defining project goals, establishing timelines, and allocating resources. It sets the foundation for the entire development process.

    2. Design: In this phase, the software's architecture, components, and user interface are designed. It includes creating system specifications, wireframes, and prototypes to visualize the software's structure and functionality.

    3. Development: The development phase involves writing code based on the design specifications. Programmers implement the software's features and functionality, following coding standards and best practices.

    4. Testing: During the testing phase, the software is rigorously tested to identify and rectify any bugs, errors, or inconsistencies. Various testing methods, such as unit testing, integration testing, and user acceptance testing, are employed to ensure the software meets quality standards.

    5. Deployment: Once the software passes the testing phase, it is deployed or released to the production environment. This includes installation, configuration, and making the software available to end-users.

    6. Maintenance: The maintenance phase involves ongoing support, bug fixes, updates, and enhancements throughout the software's lifecycle. It ensures the software remains reliable, secure, and compatible with evolving technologies and user needs.

- Each phase is discrete. This means that tasks from a previous phase do not overlap with tasks in the next phase.

- While the original SDLC followed a linear waterfall method, the approach has evolved to introduce iterations. This allows for the accommodation of shifting requirements and promotes a more flexible and adaptable development process.

- It's worth noting that different organizations may use alternative names for each stage. For example, "planning" may be referred to as "requirements gathering," "strategy," or "analysis." Additionally, organizations may have additional or fewer stages depending on their specific development processes and methodologies.

### <ins>Phase 1: Planning</ins>
- The planning phase of the SDLC is crucial for gathering, analyzing, documenting, and prioritizing requirements.

- During this phase, several factors need to be considered to ensure a successful software solution:

    - Users of the solution: Understanding the target audience and their specific needs and preferences.

    - The overall purpose of the solution: Defining the primary objectives and goals of the software solution.

    - Data inputs and outputs: Identifying the data sources and desired outputs of the software.

    - Legal and regulatory compliance: Ensuring the software adheres to relevant laws and regulations.

    - Risk identification: Identifying potential risks and developing strategies to mitigate them.

    - Quality assurance requirements: Establishing the desired quality standards and testing procedures.

    - Allocation of human and financial resources: Determining the necessary personnel and budget for the project.

    - Project scheduling: Developing a timeline and milestones for the project.

- In addition to planning the above factors, the planning phase involves estimating labor and material costs, considering time constraints, and identifying project teams and their respective roles.

- Prototyping is often employed during the planning stage to help stakeholders define requirements.

> NOTE: A prototype is a small-scale replica of the end product used to get stakeholder feedback and establish requirements and is used to test basic design ideas. Though prototyping usually occurs during the planning stage, prototyping can occur at various phases of the SDLC whenever requirements need to be reconsidered or clarified as the project develops.

- Once the requirements have been gathered, they are consolidated into a comprehensive document known as the "Software Requirements Specification" (SRS). This document serves as a clear and approved understanding of the requirements for all stakeholders. Developers are actively involved at this stage to gain a thorough understanding of the requirements and align their development approach accordingly.

### <ins>Phase 2: Design</ins>
- During the design phase, the requirements gathered from the Software Requirements Specification (SRS) are utilized to develop the software architecture. In this stage, a collaborative effort among team members takes place to design the architecture, which is subsequently reviewed by both stakeholders and the team.

- Prototypes can be created in this phase to serve as demonstrations, and a design document is generated. This document, known as the design document, serves as a reference for developers throughout the development phase.

### <ins>Phase 3: Development</ins>
- The development phase, also known as the "building" or "implementation" phase, marks the commencement of the coding process once the design document has been finalized. During this phase, the project planner refers to the design document to allocate and assign coding tasks, which often involve the utilization of programming tools, various programming languages, and software stacks. It is common for organizations to have specific standards or guidelines that developers must adhere to.

### <ins>Phase 4: Testing</ins>
- The testing phase follows the completion of coding and can take the form of manual testing, automated testing, or a combination of both. During this phase, product bugs are identified, logged, tracked, and subsequently resolved. This iterative process continues until the software achieves stability.

- For larger projects, dedicated testing teams are often employed to conduct comprehensive testing. This is crucial to ensure that the code is thoroughly tested for stability, security, and compliance with the requirements specified in the Software Requirements Specification (SRS).

- Several levels of testing are commonly employed, including unit testing, integration testing, system testing, and acceptance testing. Each level serves its specific purpose in ensuring the quality and reliability of the software.

### <ins>Phase 5: Deployment</ins>
- The deployment phase marks the release of the application into the production environment, making it accessible to users.

- The deployment process may occur in stages. Initially, the application is deployed onto a user acceptance testing (UAT) platform, where the functionality is thoroughly evaluated. Once the customer approves the functionality, the application is then released to the production environment. This approach is commonly employed for making software available on websites, mobile app stores, or software distribution servers within corporate networks.

- By following this staged deployment approach, organizations can ensure a smooth and controlled transition of the software into the hands of users while minimizing potential disruptions or issues

### <ins>Phase 6: Maintenance</ins>
- The maintenance phase occurs after the code has been deployed to the production environment.

- During this phase, the primary objective is to identify and address any remaining bugs or issues that may have been overlooked during testing. It also involves evaluating user interface (UI) issues and identifying additional requirements that were not initially specified in the Software Requirements Specification (SRS). Furthermore, code enhancements may be implemented to improve the software's functionality and performance.

- If any bugs are discovered during the maintenance phase, they are typically addressed based on their priority. High-priority issues may require immediate fixing, while lower-priority issues may be incorporated into future software releases or considered for future development cycles.

- The maintenance phase is an ongoing process that ensures the software remains in good working order, meets user expectations, and evolves to meet changing needs over time.

## **Building Quality Software**

### <ins>Common software engineering process</ins>
- Software engineering projects typically involve a set of common processes that contribute to their success. Some of these processes include:
    - Requirements Gathering: This initial phase involves gathering and documenting the requirements for the software project, which outlines the desired functionality, features, and constraints.

    - Design: In the design phase, the gathered requirements are translated into a comprehensive software architecture. This involves making decisions about the system's structure, components, and interfaces.

    - Coding for Quality: Once the design phase is complete, the development team begins coding the software, focusing on writing high-quality code that is efficient, maintainable, and adheres to coding standards and best practices.

    - Testing: The testing phase involves verifying and validating the software to ensure that it meets the specified requirements and performs as expected. Testing can be performed at different levels, such as unit testing, integration testing, system testing, and acceptance testing.

    - Releases: After successful testing and bug fixing, the software is released into the production environment, making it available to users. The deployment process may involve multiple stages, including user acceptance testing and production releases.

    - Documenting: Throughout the software engineering process, it is crucial to document important information such as requirements, design decisions, code documentation, and user manuals. Documentation helps in understanding the software, maintaining it, and supporting future development and enhancement efforts.

### <ins>Requirements gathering</ins>
- The process of requirements gathering involves collecting and documenting the set of specifications that the software needs to meet. This is typically done through the creation of a Software Requirements Specification (SRS). The SRS captures the essential details of what the software should do and how it should behave.

- The SRS includes various types of requirements, which can be classified into four broad categories:
    1. Functional Requirements: These requirements define the specific functionalities and features that the software should possess. They describe the tasks, actions, and operations that the software must be able to perform.

    2. External and User Interface (UI) Requirements: These requirements focus on the software's interaction with external systems, devices, or users. They encompass aspects such as the user interface design, user experience, and integration with external components or APIs.

    3. System Features: System features refer to the overall capabilities and characteristics that the software should possess. This includes performance, scalability, security, reliability, and any other system-level attributes that are necessary for the software's successful operation.

    4. Non-functional Requirements: Non-functional requirements define qualities and constraints that the software must adhere to, but are not directly related to its specific functionalities. These requirements can include factors such as usability, accessibility, legal and regulatory compliance, maintainability, and documentation.

### <ins>Design</ins>
- Software design is a crucial phase in the software development process. It involves transforming the requirements into a structured and implementable solution using code. The goal of software design is to create a blueprint that developers can use to write the code and build the software system.

- During the design process, the technical lead or design team breaks down the requirements into sets of related components. These components have clearly defined behaviors, boundaries, and interactions, forming the foundation of the system architecture.

- The system design encompasses various aspects, including:

    - System Functions: Defining the specific functions and features that the software system will provide to meet the requirements.

    - Performance: Considering the performance requirements and designing the system to ensure it can handle the expected workload efficiently.

    - Security: Incorporating security measures and safeguards to protect the system and its data from unauthorized access and vulnerabilities.

    - Platform Characteristics: Identifying the target platform(s) and designing the system to leverage the platform's capabilities and optimize performance.

    - Business Rules and Application Logic: Defining the business rules and the underlying application logic that governs the behavior and operations of the software.

    - Application Programming Interface (API) Design: Designing the interfaces and protocols that enable communication and data exchange between different components or external systems.

    - User Interfaces: Designing the user interfaces (UI) that allow users to interact with the software, ensuring usability, intuitiveness, and a positive user experience.

    - Database Design: Designing the database structure, schema, and relationships to efficiently store and retrieve data according to the requirements.

- The system design incorporates guidance on system functions, performance, security and platform characteristics communicating business rules and application logic, application programming interface design, which is how apps talk to each other or communicate with the database, user interfaces and database design.

### <ins>Code for quality</ins>

- Code quality is a crucial aspect of software development, encompassing various attributes such as maintainability, readability, testability, and security. High-quality code is essential for creating reliable, efficient, and maintainable software systems.

- When coding for quality, developers strive to meet the intended requirements of the software while ensuring that the code is free from defects. Some key characteristics of quality code include:

    - Maintainability: Quality code is designed and organized in a way that makes it easy to understand, modify, and maintain. It follows coding best practices and principles, such as modularization, encapsulation, and separation of concerns.

    - Readability: Code should be written in a clear, expressive, and easily understandable manner. This involves using meaningful variable and function names, writing concise and well-structured code, and providing proper indentation and formatting.

    - Testability: Quality code is designed to be easily testable, allowing for comprehensive testing of different functionalities and scenarios. It involves writing code that can be isolated and unit tested, as well as using techniques like dependency injection to facilitate testing.

    - Security: Code should be written with security considerations in mind, implementing secure coding practices to protect against common vulnerabilities and threats. This includes input validation, proper handling of sensitive data, and protection against common attack vectors.

- To achieve code quality, developers follow a set of coding practices and conventions during development. This includes adhering to common code standards, conventions, patterns, and styles that are recognized and accepted within the development community. Consistency in coding style and practices enhances code readability and maintainability.

- Automated tools, such as linters, can be utilized to detect programmatic and stylistic errors in the code. These tools help identify potential issues and enforce coding standards, ensuring that the code meets quality criteria.

- Additionally, developers can enhance code quality by including meaningful comments within the code. These comments serve as documentation, making it easier for other developers to understand and modify the code.

- By focusing on coding for quality, software developers can produce code that is clean, consistent, maintainable, and efficient, contributing to the overall success and reliability of the software system.

### <ins>Testing</ins>
- Software testing is a critical phase in the software development process, aimed at verifying that the software meets established requirements and is free from bugs and errors. The primary purpose of testing is to identify any discrepancies, gaps, or missing requirements compared to the stated specifications.

- Properly tested software ensures reliability, security, performance, and efficiency, thereby enhancing the overall quality of the software system.

- Software testing can be performed either manually or through automated means. Different levels of testing are conducted to ensure comprehensive coverage, including:

    - Unit Testing: This level of testing is typically carried out by developers and focuses on testing the smallest individual components of code in isolation. Unit tests validate the behavior and functionality of these components.

    - Integration Testing: Integration testing follows unit testing and focuses on testing the interactions and integration between different components of the software system. It ensures that the components work together as intended and that data flows correctly between them.

    - System Testing: System testing involves testing the entire software system as a whole, once all the components have been integrated. This testing phase evaluates the system's compliance with the specified requirements and verifies its overall functionality, performance, and behavior.

    - User Acceptance Testing (UAT): UAT is performed by the intended end users of the software. It aims to validate the software against real-world scenarios and user expectations. UAT ensures that the software meets the users' needs and operates as intended in their specific environment.

- Testing can also be categorized into three main types:

    - Functional Testing: This type of testing focuses on verifying the functional requirements of the software system. It involves testing the various features, functions, and interactions to ensure they work correctly and meet the specified requirements.

    - Non-functional Testing: Non-functional testing is concerned with validating the non-functional aspects of the software, such as performance, scalability, security, usability, and compatibility. It ensures that the software meets the desired standards and performs well under different conditions.

    - Regression Testing: Regression testing involves retesting the software after modifications or bug fixes to ensure that the changes did not introduce new issues or break existing functionalities. It helps ensure that the software continues to function correctly and as expected throughout the development cycle.

- By conducting thorough and comprehensive testing at each level and type, software developers can identify and resolve issues early in the development process, leading to more robust and reliable software.

### <ins>Releases</ins>
- The release phase involves making the newest version of the software available to users. Different types of releases are typically used to target different audiences and ensure the software meets the desired quality standards. These types often include alpha, beta, and general availability (GA) releases.

    - Alpha Release: Is the initial functioning version of the software that is made available to a select group of stakeholders. This release is typically limited in scope and may not include the full feature set or finalized design. It is common for an alpha release to have known errors or issues, and design changes may still occur. However, it does contain most of the desired functionality and serves as an opportunity for early feedback and testing.

    - Beta Release: Is a more advanced stage of the software, where it meets all the specified requirements and is made available to stakeholders outside of the development organization. The purpose of a beta release is to gather feedback, test the software under real conditions, and identify any remaining bugs or errors. It allows a wider audience to use and evaluate the software, providing valuable insights for further improvements.

    - General Availability (GA) Release: The GA release, also known as the stable release or the production-ready release, is the version of the software that is considered to be stable and reliable. It is made available to all users after the necessary changes and improvements from the beta release have been agreed upon, implemented, and thoroughly tested. The GA release indicates that the software is ready for general use and is typically the version that is recommended for production environments.

- By following a staged release process, starting from alpha, progressing to beta, and finally reaching the GA release, software development teams can incrementally improve the software based on user feedback and ensure a higher level of quality and reliability before making it widely available.

### <ins>Documentation</ins>
- Documentation plays a vital role in software development by providing valuable information to both non-technical end-users and technical users. It serves as a reference and guide for understanding the software's operation, usage, and maintenance.

- System Documentation: Is primarily intended for technical users, such as engineers, developers, and architects. It provides in-depth information about the software system's architecture, design, and internal workings. Some common components of system documentation include:

    - README files: These files provide an overview of the software, installation instructions, and any essential information for getting started.

    - Inline comments: Comments within the source code that explain the purpose, functionality, and implementation details of specific sections or modules.

    - Architecture and design documents: Detailed documentation that outlines the system's overall architecture, including components, modules, and their interactions. It describes the high-level design decisions and the rationale behind them.

    - Verification information: Documentation related to testing, including test plans, test cases, and test results. It helps ensure the software meets the specified requirements and passes the necessary quality checks.

    - Maintenance guides: Documentation that provides guidance on maintaining and troubleshooting the software, including instructions for resolving common issues, applying updates, and handling potential challenges.

- User Documentation: Is designed for non-technical end-users to assist them in effectively using the software. It aims to provide clear instructions and explanations to ensure a positive user experience. Common forms of user documentation include:

    - User guides: Comprehensive guides that provide step-by-step instructions on how to use the software, including its features, functionalities, and settings.

    - Instructional videos and manuals: Visual and interactive resources that demonstrate various tasks and workflows within the software.

    - Online help: Contextual help provided within the software interface, allowing users to access relevant information and instructions as they navigate through the application.

    - Inline help: Inline tooltips, prompts, or explanations within the user interface that provide quick assistance and guidance on specific elements or actions.

- By providing comprehensive and well-structured documentation, software developers enable both technical and non-technical users to understand and utilize the software effectively. Documentation serves as a valuable resource for onboarding new users, troubleshooting issues, and maximizing the software's capabilities.

## **Requirements**

### <ins>Steps to gathering requirements</ins>
- Requirement gathering is a crucial phase in software development, involving the process of defining a problem and documenting the necessary steps to solve it. This process typically consists of the following six steps:

    - Identifying Stakeholders: The first step is to identify all the relevant stakeholders who will be affected by or have an interest in the software solution. Stakeholders can include end-users, clients, customers, managers, subject matter experts, and other individuals or groups with a vested interest in the project.

    - Establishing Goals and Objectives: Once the stakeholders are identified, the next step is to establish the goals and objectives of the software project. This involves clearly defining what the software should achieve, the problems it should solve, and the expected outcomes.

    - Eliciting Requirements from Stakeholders: In this step, the requirements are gathered from the stakeholders through various techniques such as interviews, workshops, surveys, and observations. The goal is to understand the stakeholders' needs, expectations, and desired functionalities of the software system.

    - Documenting the Requirements: Once the requirements are elicited, they need to be documented in a structured and organized manner. This involves creating a requirements document or specification that captures the functional and non-functional requirements of the software. The document serves as a reference for all stakeholders involved in the development process.

    - Analyzing and Confirming the Requirements: After documenting the requirements, they need to be analyzed to ensure they are complete, consistent, and feasible. This step involves reviewing the requirements, resolving any conflicts or ambiguities, and validating them with the stakeholders to ensure accuracy and understanding.

    - Prioritizing the Requirements: In this final step, the requirements are prioritized based on their importance and criticality. This helps in managing resources effectively and ensures that the most essential features and functionalities are addressed first. Prioritization can be based on factors such as business value, stakeholder needs, technical feasibility, and project constraints.

- By following these steps, software development teams can gather comprehensive and well-defined requirements that serve as a foundation for designing and developing the software solution. Effective requirement gathering sets the stage for successful project execution and ensures alignment with stakeholder expectations.

### <ins>Identifying the stakeholders</ins>
- Identifying stakeholders is a crucial step in the requirement gathering process as it ensures that all relevant individuals or groups are involved in shaping the software product. The stakeholders typically represent various roles and departments within the organization that requests the development of the software. Here are some key stakeholders commonly involved:

    - Decision-makers: These individuals hold decision-making authority and have the power to approve the software project, allocate resources, and set project objectives. They provide strategic direction and have a vested interest in the successful outcome of the software.

    - End-users: End-users are the individuals who will directly interact with the software once it is developed and deployed. Understanding their needs, preferences, and workflows is crucial to designing a user-friendly and effective solution.

    - System Administrators: System administrators are responsible for managing the software infrastructure, including installation, configuration, security, and maintenance. Involving system administrators ensures that their technical requirements and constraints are considered during the development process.

    - Engineering: Engineers play a vital role in software development. They possess technical expertise and contribute to the design, development, and implementation of the software. Involving engineering stakeholders helps ensure that the software meets technical standards and aligns with the organization's technological capabilities.

    - Marketing: Marketing stakeholders can provide valuable insights into the target market, customer expectations, and competitive landscape. They may have requirements related to branding, positioning, or integration with marketing tools and platforms.

    - Sales: Sales stakeholders can contribute their knowledge of customer needs, pain points, and sales processes. They may have requirements related to CRM integration, lead management, or reporting features to support the sales team's activities.

    - Customer Support: Customer support stakeholders can provide insights into common customer issues, feature requests, and user feedback. Their involvement helps ensure that the software addresses customer needs and provides effective support mechanisms.

- In addition to these roles, stakeholders can vary depending on the specific organization and the nature of the software product. It is important to identify and involve representatives from all relevant departments and groups that will be impacted by or have an interest in the software. This ensures that the requirements gathered are comprehensive, well-rounded, and reflect the diverse needs of the organization and its stakeholders.

### <ins>Establishing goals and objectives</ins>
- When gathering requirements for a software project, it is essential to establish clear goals and objectives that align with the organization's overall vision and strategy. Here's how goals and objectives can be defined:

    - Goals: Goals are broad, long-term outcomes that the software product aims to achieve. They provide a clear direction for the development process and help ensure that the software aligns with the organization's overarching vision. Some examples of goals in software development include:
        - Improving customer satisfaction and user experience
        - Increasing operational efficiency and productivity
        - Enhancing data security and privacy
        - Expanding market reach and customer base
        - Streamlining business processes and workflows

    - Objectives: Objectives are specific, measurable, and actionable steps that contribute to achieving the established goals. They provide clarity and focus, guiding the development team in defining the functionalities and features of the software. Objectives should be SMART (Specific, Measurable, Achievable, Relevant, Time-bound). Examples of objectives related to the goals mentioned above could be:

        - Goal: Improving customer satisfaction and user experience
            - Objective: Reduce average response time of customer support inquiries by 20% within six months.
            - Objective: Increase user engagement by implementing intuitive and user-friendly interface design principles.

        - Goal: Increasing operational efficiency and productivity
            - Objective: Automate manual data entry processes, reducing data entry errors by 50% within three months.
            - Objective: Implement workflow automation to reduce processing time for routine tasks by 30%.

        - Goal: Enhancing data security and privacy

            - Objective: Implement multi-factor authentication for user logins to enhance account security by the end of the quarter.
            - Objective: Conduct a comprehensive security audit and address all identified vulnerabilities within six months.

- By establishing clear goals and defining specific objectives, the software development team can focus their efforts and ensure that the software solution addresses the desired outcomes. Goals and objectives provide a framework for decision-making, prioritization, and evaluation throughout the development process, helping to drive the project towards successful completion.

### <ins>Eliciting, documenting, confirming</ins>
- The process of gathering requirements involves eliciting, documenting, and confirming the requirements to ensure that they align with the project's goals and objectives. These steps are typically performed iteratively throughout the requirement gathering process. Here's a breakdown of each step:

    - Eliciting Requirements: Eliciting requirements involves gathering information from stakeholders to identify their needs, preferences, and expectations. This can be achieved through various techniques, such as surveys, questionnaires, interviews, and workshops. The goal is to extract relevant information and capture the requirements in a comprehensive manner.

    -  Documenting Requirements: Once the requirements are elicited, it is important to document them in a clear and understandable manner. The requirements documentation should provide a detailed description of the functionality, features, and constraints of the software. It should be organized, structured, and accessible to stakeholders and the project team. Various documentation formats can be used, such as textual requirements, use cases, user stories, diagrams, and prototypes, depending on the project's needs.

    - Confirming Requirements: Confirming the requirements involves analyzing and evaluating them to ensure consistency, clarity, and completeness. This step helps identify any gaps, conflicts, or ambiguities in the requirements. Requirements should be reviewed and validated by stakeholders and subject matter experts to verify their accuracy and relevance. This confirmation process helps minimize misunderstandings and ensures that the documented requirements accurately represent the stakeholders' needs and expectations.

    - Sharing with Approved Stakeholders: Once the requirements have been confirmed, they should be shared with the approved stakeholders for their review and approval. This step ensures that all relevant parties have visibility into the requirements and can provide feedback or make necessary revisions. Effective communication and collaboration with stakeholders are key to ensuring that the requirements are well-understood and aligned with the project's goals.

- It is important to note that the requirement gathering process is iterative, meaning that these steps may be repeated multiple times throughout the project lifecycle. As the project progresses and stakeholders gain a deeper understanding of the requirements, new insights may emerge, requiring adjustments to the elicited, documented, and confirmed requirements.

### <ins>Prioritizing</ins>
- Once the requirements have been confirmed, it is important to prioritize them to ensure that the most critical and valuable features are addressed first. Prioritization helps in resource allocation, decision-making, and determining the order in which the requirements should be implemented. Here are some key steps in prioritizing requirements:

    - Categorize the Requirements: Start by categorizing the requirements into different groups based on their importance and urgency. Common labels used for categorization include "must-have," "high-priority," "medium-priority," and "nice-to-have." These labels provide a clear understanding of the relative importance of each requirement.

    - Consider Business Value: Assess the business value of each requirement by considering its impact on achieving the project's goals and objectives. Identify requirements that directly contribute to the project's success, such as those that address critical user needs, improve efficiency, or provide a competitive advantage.

    - Evaluate Dependencies: Consider dependencies between requirements and determine whether certain requirements need to be addressed before others. Some requirements may rely on the completion of specific prerequisites or the availability of certain resources. Prioritizing requirements with dependencies in mind helps ensure a logical and efficient development process.

    -  Engage Stakeholders: Involve stakeholders in the prioritization process to gather their input and perspectives. This can be done through meetings, workshops, or surveys. Seek feedback from stakeholders to understand their priorities, expectations, and any potential trade-offs that need to be considered.

    - Apply Agile Principles: If following an Agile development approach, consider using techniques such as MoSCoW (Must-have, Should-have, Could-have, Won't-have) or relative prioritization methods like the Weighted Shortest Job First (WSJF) technique. These methods assign a priority value or weight to each requirement, enabling a more precise prioritization process.

    -  Regularly Review and Adjust: Prioritization is not a one-time activity. It should be an ongoing process throughout the project lifecycle. As the project progresses and new information becomes available, regularly review and adjust the prioritization of requirements to ensure alignment with changing project needs and stakeholder expectations.

### <ins>Requirements documentation</ins>
- During the requirements gathering process, it is common to create multiple documents to capture and communicate the gathered requirements. These documents help provide a clear understanding of the software requirements and serve as a reference for the development team. While the specific document names and formats may vary, three commonly used types of requirements documents are:

    1. Software Requirements Specification (SRS): The SRS is a comprehensive document that describes the functional and non-functional requirements of the software. It provides an overview of the software system, its features, and the interactions with users and external systems. The SRS serves as a contract between the development team and stakeholders, ensuring a shared understanding of what the software should accomplish.

    2. User Requirements Specification (URS): The URS focuses on capturing the needs and expectations of the end-users. It describes the software requirements from the perspective of the users, highlighting their goals, tasks, and desired functionalities. The URS helps ensure that the software addresses the user's requirements and provides a satisfying user experience.

    3. System Requirements Specification (SysRS): The SysRS, also known as the System Specification or Technical Requirements Document, provides detailed technical specifications and requirements for the software system. It includes information about the system architecture, hardware and software components, performance requirements, security considerations, and integration requirements. The SysRS is primarily targeted at the development team and technical stakeholders involved in the implementation of the software.

- While the System Requirements Specification (SysRS) is commonly used and focuses on technical aspects, it's important to note that the specific naming and categorization of these documents can vary between organizations and projects. Some projects may combine elements from the SRS and URS into a single document or use different terminology.

- The purpose of these documents is to document and communicate the requirements effectively, ensuring that all stakeholders have a shared understanding of what needs to be developed. They provide a basis for design, development, and testing activities throughout the software development lifecycle. Regular updates and revisions to these documents may be necessary as requirements evolve or change over time.

### <ins>Software Requirements Specification</ins>
- The Software Requirements Specification (SRS) is a crucial document that defines the functionalities and performance expectations of the software being developed. It serves as a reference for all stakeholders involved in the project, including the development team, clients, and other relevant parties. The SRS outlines various aspects of the software, ensuring a common understanding of its purpose and requirements. Here are the key components typically included in an SRS:

    - Purpose Statement: This section describes the intended use of the SRS document, including its audience and how it should be utilized throughout the software development process.

    - Scope: The scope outlines the boundaries of the software, specifying its objectives, functionalities, and any constraints that may impact the design or implementation.

    - Assumptions: Assumptions document any underlying assumptions made during the requirements gathering process. This may include assumptions about the user's hardware, operating system, or other software components required for the software to function as intended.

    - Constraints: Constraints define the limitations or conditions under which the software must operate. These can include factors such as compatibility requirements, adherence to industry standards, hardware or software dependencies, or any specific environmental considerations.

    - Dependencies: If the software relies on other software components, systems, or external interfaces, these dependencies are documented in this section. It ensures that the development team is aware of any external dependencies that need to be considered during implementation.

    - Dependencies: defines if there are dependencies on other software products.

    - Requirements: The requirements section forms the core of the SRS and can be categorized into different types:

        - Functional Requirements: These define the specific functionalities and operations that the software should perform. They describe how the software should behave and the tasks it should be able to accomplish.

        - External Interface Requirements: These requirements cover the interactions between the software and external entities, such as users, other hardware systems, or third-party software. They detail the input and output formats, communication protocols, and any data exchange requirements.

        - System Features: System features are a subset of functional requirements and highlight the essential features or capabilities that the software must possess for it to function effectively.

        - Non-functional Requirements: Non-functional requirements encompass qualities of the software that are not directly related to its functionality. They include aspects such as performance, reliability, security, usability, scalability, and other quality standards that the software should meet.

- The Software Requirements Specification serves as a contract between the stakeholders and the development team, ensuring a shared understanding of the software's requirements and objectives. It provides a foundation for subsequent phases of the software development lifecycle, including design, coding, and testing. Regular updates and revisions may be required as the project progresses and new requirements emerge or existing ones change.

### <ins>User Requirements Specification (URS)</ins>
- The User Requirements Specification (URS) is a document that focuses on capturing the business needs and expectations of the end-users from the software system. It aims to define the functional requirements from the perspective of the users and describes the desired behavior and functionalities of the software. While the URS is sometimes created as a separate document, it is common for user requirements to be included within the Software Requirements Specification (SRS) document.

- Key points about the User Requirements Specification are as follows:

    - Business Needs and Expectations: The URS identifies the specific business needs that the software should address and the expectations of the end-users. It provides a clear understanding of why the software is being developed and the value it is expected to deliver.

    - User Stories or Use Cases: User requirements are often written in the form of user stories or use cases. These narratives or scenarios describe the interactions between the users and the software system, answering questions such as who the user is, what function they need to perform, and why they require that particular functionality. User stories or use cases help capture the user's perspective and define the desired behavior of the software.

    - User Acceptance Testing: User acceptance testing is a critical step in determining whether the software meets the user requirements. It involves testing the software with real end-users to ensure that it satisfies their needs, performs the expected functions, and meets their acceptance criteria. User acceptance testing validates that the software aligns with the user's expectations and is suitable for its intended purpose.

    - Integration with Software Requirements: In some cases, the user requirements and the software requirements are combined into a single Software Requirements Specification (SRS) document. This integrated approach ensures that both the business needs and the technical aspects of the software are captured and addressed in a comprehensive manner. The SRS provides a consolidated view of the expectations from both the users and the development team.

-  The URS helps establish a common understanding between the users, stakeholders, and the development team. It serves as a guide for the software development process, ensuring that the final product meets the needs and expectations of the end-users.

### <ins>System Requirements Specification (SysRS)</ins>
- The System Requirements Specification (SysRS) is a document that outlines the broader set of requirements for a software system. It provides a detailed description of the system's capabilities, interfaces, user characteristics, and other key aspects that are essential for its successful implementation and operation. While the Software Requirements Specification (SRS) focuses primarily on the functional requirements of the software, the SysRS encompasses a wider range of requirements, including hardware, performance, security, regulations, and policies.

- Key points about the System Requirements Specification are as follows:

    - System Capabilities: The SysRS defines the capabilities and functionalities of the entire system, including both the software and hardware components. It describes the expected behavior and features of the system as a whole, addressing the interactions between various subsystems and components.

    - Interfaces: The SysRS specifies the interfaces that the software system must have with external entities, such as users, other systems, databases, and hardware devices. It outlines the protocols, formats, and communication mechanisms required for seamless integration with these external interfaces.

    - User Characteristics: The SysRS identifies the characteristics and expectations of the system's users. It takes into account factors such as user roles, skill levels, accessibility requirements, and preferences to ensure that the system is designed and developed to meet their specific needs.

    - Non-functional Requirements: The SysRS includes non-functional requirements that define the quality attributes and constraints of the system. This can encompass performance requirements, security requirements, scalability, reliability, maintainability, and usability aspects. It also addresses any regulatory or policy requirements that the system must comply with.

    - Hardware Requirements: Unlike the SRS, the SysRS includes hardware requirements in addition to software requirements. It outlines the specifications and configurations of the hardware components needed to support the software system effectively. This may include details such as processing power, memory, storage, network connectivity, and other hardware dependencies.

- While the SRS focuses on the specific functionalities of the software, the SysRS provides a broader perspective, considering the system as a whole. Depending on the nature of the project, some software projects may develop an SRS instead of a separate SysRS. However, in cases where hardware components, performance, security, and other system-level factors are crucial, a dedicated SysRS helps ensure a comprehensive understanding of the system requirements.

# **Software building process and associated roles**

## **Software development methodologies**

### <ins>Common development methodologies</ins>
- A process is needed to clarify communication and facilitate information sharing among team members and a few of them are:

    - Waterfall: A linear, sequential approach to software development. It follows a structured progression of phases, where each phase is completed before moving on to the next one. The phases typically include requirements gathering, design, implementation, testing, deployment, and maintenance. This methodology emphasizes thorough planning and documentation, with little room for changes once a phase is completed.

    - V-shape model: An extension of the Waterfall methodology that emphasizes the testing phase. It follows a similar sequential structure, but with testing activities mirrored at each phase. The V-Shape model places significant emphasis on verification and validation, aiming to catch defects and issues early in the development process. It emphasizes a strong focus on testing and quality assurance.

    - Agile: An iterative and incremental approach to software development. It promotes flexibility, collaboration, and adaptive planning. Agile methodologies, such as Scrum or Kanban, involve breaking the development process into small increments called sprints or iterations. Each iteration typically includes requirements gathering, design, development, testing, and review. Agile methodologies prioritize frequent communication, customer collaboration, and the ability to adapt to changing requirements throughout the development process.

### <ins>Waterfall methodology</ins>
- The Waterfall method is a sequential software development approach that follows a linear progression from one phase to another. Here are some key characteristics of the Waterfall method:

    - Sequential Phases: The development process is divided into distinct phases, such as requirements gathering, design, implementation, testing, deployment, and maintenance. Each phase is completed before moving on to the next.

    - Rigid and Linear: The Waterfall method follows a rigid and linear flow, where one phase must be completed entirely before the next phase begins. There is little to no overlap or iteration between phases.

    - Early Planning: The emphasis is placed on extensive upfront planning, where all requirements are defined and documented at the beginning of the project. Changes to requirements are not easily accommodated once a phase is completed.

    - Minimal Customer Involvement: The customer's involvement is typically limited to the initial requirements gathering phase and the final acceptance testing phase. The customer may not see the product until it is fully developed, leading to potential risks if the customer's expectations are not met.

    - Long Development Cycles: Due to its sequential nature and emphasis on completing one phase before starting the next, the Waterfall method often results in long development cycles. This can lead to delays in delivering a working product to the customer.

    - Limited Flexibility: The Waterfall method offers limited flexibility to accommodate changes or adjustments during the development process. Changes in requirements or design typically require revisiting previous phases, which can be time-consuming and costly.

### <ins>V-shape methodology</ins>
- The V-Shape methodology is a variation of the Waterfall method that emphasizes the relationship between verification and validation activities. Here are the key characteristics of the V-Shape methodology:

    - Sequential Phases: Similar to the Waterfall method, the V-Shape methodology follows a sequential approach with distinct phases. The phases on the left side of the "V" focus on verification activities, while the phases on the right side focus on validation activities.

    - Corresponding Verification and Validation: Each phase of verification (going down the left side of the "V") corresponds to a phase of validation (going up the right side of the "V"). For example, the planning phase on the left side is followed by the unit testing phase on the right side.

    - Planning and Design Phases: The initial phases of the V-Shape methodology involve planning, system design, architecture design, and module design. These phases focus on defining the requirements and creating the design specifications.

    - Testing Phases: The testing phases are integral to the V-Shape methodology. Testing activities, such as unit testing, integration testing, system testing, and acceptance testing, are defined during the verification phases and executed during the corresponding validation phases.

    - Coding Phase: The coding phase is located at the bottom of the "V" and is typically preceded by the design phases. Once the design is completed, the coding phase begins, where the software is implemented based on the design specifications.

    - Emphasis on Testing and Validation: The V-Shape methodology places significant emphasis on testing and validation activities. Testing is performed at each level of the software development process to ensure that the software meets the specified requirements and functions as intended.

        ![V-Shape model](Assets/vshape%20model.png)

- The V-Shape methodology aims to address some of the limitations of the traditional Waterfall method by integrating testing and validation activities into the development process. By emphasizing verification and validation in a sequential manner, it helps ensure that the software is thoroughly tested and validated before final release. However, like the Waterfall method, it still follows a relatively rigid and sequential approach, which may make it less adaptable to changes during the development process.

### <ins>Agile methodology</ins>
- The Agile methodology is an iterative and collaborative approach to software development that emphasizes flexibility, adaptability, and continuous feedback. Here are the key characteristics of the Agile methodology:

    - Iterative Development: Agile follows an iterative development approach, where the development process is divided into short cycles called sprints. Each sprint typically lasts two to four weeks and involves the completion of a set of prioritized tasks or user stories.

    - Collaborative Approach: Agile emphasizes collaboration and frequent communication among team members, stakeholders, and customers. Cross-functional teams work closely together throughout the development process, promoting effective collaboration and knowledge sharing.

    - Continuous Feedback: Feedback is a crucial aspect of Agile. At the end of each sprint, there is a sprint review or demo where stakeholders and customers can provide feedback on the working software. This feedback is used to make adjustments, refine requirements, and plan the next sprint.

    - Customer Involvement: Agile encourages active customer involvement throughout the development process. Customers or product owners collaborate with the development team to prioritize requirements, provide clarifications, and validate the software at regular intervals.

    - Adaptive Planning: Agile embraces change and recognizes that requirements can evolve over time. The development team is flexible and can respond to changing customer needs or market conditions. Planning is done incrementally, with detailed plans created for the upcoming sprint while leaving room for adjustments in subsequent sprints.

    - Agile Manifesto: The Agile methodology is guided by the principles outlined in the Agile Manifesto, which emphasizes values such as individuals and interactions, working software, customer collaboration, and responding to change. These values prioritize people and effective communication over rigid processes and documentation.

    - Emphasis on Working Software: Agile places a strong emphasis on delivering working software in each sprint. Rather than focusing on extensive documentation, Agile values functional and tested software that meets the customer's needs.

- The Agile methodology provides a more flexible and adaptive approach compared to traditional sequential models like the Waterfall or V-Shape. By working in iterative cycles, Agile enables teams to respond to feedback, accommodate changes, and deliver value to customers more frequently. It promotes collaboration, transparency, and continuous improvement throughout the software development lifecycle.

- It still aligns with the SDLC, but each phase is short since teams work in cycles/sprints which are usually two to four weeks long. Unit testing happens in each sprint to minimize the risk of failure and, rather than the "maintenance" stage of the SDLC, the final stage of the sprint is a feedback stage.

### <ins>Sequential vs iterative</ins>
- One fundamental distinction between traditional SDLC methods like waterfall and the V-shape model, and Agile methodology lies in their approach. Traditional methods such as waterfall and V-shape follow a sequential process, whereas Agile methodology takes an iterative approach.

- Traditional SDLC methods, such as waterfall and V-shape, follow a sequential process where the entire product is developed before seeking customer feedback. In contrast, Agile methodology emphasizes rapid, incremental development cycles.

- Each approach has its advantages and disadvantages, but Agile has gained widespread popularity as the preferred method in modern software development.

### <ins>Waterfall pros and cons</ins>
- Pros:
    - Clear and well-defined stages: The waterfall methodology is easy to understand and follow as each stage is discrete and well-defined. This clarity allows team members to understand their roles and responsibilities clearly throughout the development process.

    - Budget and resource allocation: Since planning is done upfront in the waterfall approach, it is generally easier to estimate the budget and allocate resources. This can be beneficial for organizations that require detailed planning and budgeting before initiating a project.

- Cons:
    - Lack of flexibility: One of the main drawbacks of the waterfall methodology is its lack of flexibility. Once the planning stage is completed, it can be challenging to incorporate changes or new requirements at a later stage. This inflexibility can lead to complications if unforeseen issues arise or if the agreed-upon functionality shifts from the initial vision.

    - Difficulty in accommodating change: Due to the sequential nature of the waterfall approach, accommodating changes can be time-consuming and costly. Any changes or modifications typically require going back to previous stages, which can disrupt the entire project timeline.

> Overall, while the waterfall methodology has its strengths in terms of clear stages and upfront planning, its rigidity and limited adaptability to change can pose challenges in dynamic and evolving projects.

### <ins>V-shape model pros and cons</ins>
- Pros:
    - Simplicity and ease of use: The V-shape model shares the simplicity and ease of use of the waterfall methodology. Its sequential nature allows for a clear understanding of project stages and facilitates effective team coordination.

    - Efficient test planning: One advantage of the V-shape model is that test planning is done during the verification phase. This approach saves significant time during coding and validation phases since the test plans are designed in parallel. It promotes early detection of defects and reduces the likelihood of issues surfacing later in the development process.

- Cons:
    - Limited flexibility with changing requirements: Similar to the waterfall methodology, the V-shape model faces challenges in accommodating changing requirements. Once the application enters the testing phase, it becomes difficult to introduce changes or modify functionality. This rigidity can be a disadvantage in projects that require frequent adjustments or have evolving requirements.

    - Difficulty in adapting to unforeseen issues: The sequential nature of the V-shape model can make it challenging to address unforeseen issues effectively. If unexpected problems arise during the development process, going back to previous stages for modifications or refinements can disrupt the overall timeline and project progress.

### <ins>Agile pros and cons</ins>
- Pros:
    - Iterative and adaptive approach: Agile development incorporates ongoing research, planning, and testing throughout the product development cycle. It allows for the addition of new features while still following the key phases of traditional SDLC. Agile methodology enables quick and easy handling of changing requirements since planning is initiated at the beginning of each sprint cycle.

    - Focus on building: In Agile, a significant portion of resources is allocated to the building phase. This ensures that development efforts are primarily concentrated on creating and refining the product, maximizing productivity and delivering value to customers.

    - Continuous feedback and testing: At the end of each iteration or sprint, Agile encourages collaboration among the QA team, stakeholders, and the customer. They have the opportunity to test the working code against requirements and provide feedback. This iterative feedback loop enables continuous improvement and ensures that the product aligns with stakeholder expectations.

    - Modular coding and MVP releases: Agile promotes the use of modular coding, which allows small chunks of functionality to be integrated into a larger product. This modular approach enables the creation of Minimum Viable Products (MVPs) that can be released to users early, providing tangible value and gathering valuable feedback
- Cons:
    - Challenges in upfront planning: One of the challenges of Agile methodology is that upfront planning, such as budgeting and scheduling, can be more complex. The overall scope of the product may not be clearly defined at the beginning, making it difficult to estimate project timelines and allocate resources accurately.

> While Agile methodology offers advantages such as adaptability, continuous feedback, and modular development, the need for flexible planning and the potential ambiguity in scope should be considered when implementing Agile in projects.

## **Software versions**

### <ins>Software versions</ins>
- Software versions provide valuable information about programs and applications, benefiting both users and developers.

- For users, software versions help determine the specific version they are using, while developers can convey important details through version numbers.

- Software version numbers can vary in length and meaning, but they generally follow a similar format and convey similar information.

- Version numbers typically indicate:
    - Release date: The software version reveals when it was initially released to the public.
    - Updates: The version number may reflect subsequent updates or enhancements made to the software after the initial release.
    - Patches or minor changes: Version numbers can indicate if any patches or minor modifications have been applied to address issues or introduce small improvements.

- Software versioning is the system employed by developers to keep track of new software releases, updates, and patches for programs and applications.

### <ins>Version numbers</ins>
- Version numbers can be represented in various formats and lengths, depending on the software and developer's preference. They typically consist of two, three, or four number sets separated by periods.

- The initial release of an application or program often starts with a version number of 1.0. This number indicates that there have been no previous updates, patches, or fixes for the software.

- For programs with numerous releases and updates, version numbers can become longer, incorporating multiple number sets. These extended version numbers provide a more detailed indication of the software's evolution and history.

- Some software developers may adopt a versioning system based on dates. For example, Ubuntu version 18.04.2 was released in April 2018. In this case, the third number set (point-2) represents an additional change or update within the overall release.

> <strong>It's worth mentioning that software versions still in the beta or testing phase may have a version number lower than 1, such as 0.9. This indicates that the software is still undergoing development and refinement before reaching a stable release.</strong>

### <ins>What do version numbers mean?</ins>
- Version numbers can vary depending on the numbering system adopted by software developers. While not all numbering systems follow the same format, many use a semantic numbering approach with multiple parts separated by periods. Here is a general explanation of version number components in the semantic numbering system:

    - First Number: The first number represents major changes in the software. It typically indicates a significant release or a major update that introduces substantial new features, functionality, or architectural changes. Incrementing this number signifies a substantial change that may have compatibility implications.

    - Second Number: The second number in the version indicates minor changes. It usually represents smaller updates, improvements, or additions that are not as significant as a major release but still bring meaningful enhancements or modifications to the software. These changes often preserve backward compatibility.

    - Third Number: The third number represents patches or minor bug fixes. It indicates updates or corrections made to address software issues, bugs, or vulnerabilities. These patches are typically aimed at improving the stability, performance, or security of the software without introducing significant new features.

    - Fourth Number: The fourth number, if present, can indicate a build number or a build date. It represents less significant changes, such as additional builds or revisions within a specific version. This number is often optional and not present in all version numbers.

### <ins>Version compatibility</ins>
- Compatibility issues between different versions of software are a common challenge that users may encounter. It is important to be aware of the software version you are using, as it can help troubleshoot compatibility problems. Here are some key points to consider:

    - Identifying outdated versions: Checking the software version can help determine if you are using an older or outdated version. Outdated versions may lack compatibility with newer software, systems, or file formats, potentially causing issues or errors.

    - Updating to newer versions: Updating the software to a more recent version can often resolve compatibility problems. Software developers frequently release updates to improve compatibility, address bugs, and introduce new features. By upgrading to the latest version, you can ensure that your software is compatible with current technologies and systems.

    - Backward compatibility: Some software is designed to be backward compatible, which means that newer versions of the software can work with files, programs, and systems from older versions. This allows for a smooth transition and ensures that older components remain functional even with the introduction of newer software versions.

- However, it's important to note that backward compatibility is not guaranteed for all software. Some updates may introduce changes or features that are not compatible with previous versions. In such cases, it is recommended to refer to the software documentation or consult with the software developer for specific compatibility information.

- Being mindful of version compatibility and keeping software up to date can help minimize compatibility issues and ensure smooth operation between different software components and systems.

## **Software testing**

### <ins>What is software testing</ins>
- Software testing is an essential practice that involves the integration of quality checks at various stages of the software development cycle.

- The primary objective of testing is to evaluate the software against predetermined requirements and ensure the delivery of error-free software. This is achieved by meticulously designing and executing "test cases" that verify the software's functionality, performance, and reliability.

### <ins>Test cases</ins>
- Test cases play a crucial role in verifying the functionality of a software application and ensuring that all requirements are met. They can be written at different stages of the Software Development Life Cycle (SDLC) and may vary based on the chosen development approach, such as Agile or waterfall.

- Typically, a test case comprises the following elements:
    - Steps: Clear and concise instructions outlining the actions to be performed during the test.
    - Inputs: The specific inputs or data that need to be provided to the software.
    - Data: Any additional data or context required for the test case execution.
    - Expected corresponding outputs: The anticipated outcomes or results that the software should produce.

- It is important to note that regardless of the test type or development method, test cases should always be written after the requirements have been finalized. This ensures that the test cases align accurately with the intended functionality and serve as a reliable means of validating the software's performance.

### <ins>Three types of testing</ins>
- Software testing plays a vital role in assessing software products to determine if they meet the specified requirements and are free from errors.

- Testing can be broadly classified into three categories:

    - Functional testing: This type of testing focuses on validating the functional aspects of the software. It aims to ensure that the software performs its intended tasks correctly and meets the defined functional requirements. Functional testing involves testing individual functions, features, and their interactions to verify if they produce the expected outputs.

    - Non-functional testing: Non-functional testing evaluates the non-functional aspects of the software, such as performance, reliability, scalability, usability, and security. It aims to assess the software's behavior under various conditions and to identify any performance bottlenecks or usability issues that may impact its overall quality.

    - Regression testing: Regression testing is performed to verify that recent changes or enhancements in the software have not introduced new defects or caused any regression in existing functionality. It involves retesting previously tested components to ensure that they still function correctly after modifications have been made to the software.

### <ins>Functional testing</ins>
- Functional testing is a critical aspect of software testing that primarily focuses on verifying the functionality of an application. It typically involves black box testing, which means testing without examining the source code or internal structure of the system under test. Instead, the focus is on inputs and corresponding outputs, ensuring that the application behaves as expected.

- Key points about functional testing:

    - Functional testing is based on testing the function requirements of the application, ensuring that it operates correctly and meets the specified functional criteria.

    - It can be performed manually or using automated testing tools.

    - The primary goal of functional testing is to validate the usability and accessibility of the application.

    - By conducting functional tests, software teams ensure that the application can handle user errors or input edge cases effectively, displaying appropriate error messages when necessary.

- Functional testing plays a crucial role in ensuring that the application's functionality aligns with the intended requirements, providing a seamless and error-free user experience.

### <ins>Non-functional testing</ins>
- Non-functional testing focuses on evaluating the attributes and characteristics of an application beyond its functional aspects. It involves testing the application's behavior in terms of performance, security, scalability, availability, and other non-functional requirements. This type of testing aims to ensure that the software meets the desired quality standards and performs optimally under different conditions.

- Key points about non-functional testing:

    - Non-functional testing examines the non-functional behavior of the system under test, including its performance, security, scalability, and availability.

    - It addresses questions such as:

        - How does the application perform under stress or high load conditions?
        
        - What is the application's behavior when multiple users log in simultaneously?
        
        - Are the instructions in the documentation and user manuals consistent with the application's actual behavior?
        
        - Does the application behave consistently across different operating systems?
        
        - How does the application handle disaster recovery scenarios?
        
        - What are the security measures in place to protect the application from vulnerabilities?

### <ins>Regression testing</ins>
- Regression testing, also known as maintenance testing, is performed to ensure that recent changes made to the application, such as bug fixes or updates, do not negatively impact the existing functionality.

- Key points about regression testing:

    - Regression testing is necessary when there are changes in requirements or when defects have been fixed.
    
    - The purpose of regression testing is to verify that previously tested functionalities are still working as intended after modifications.
    
    - To conduct regression testing, a selection of test cases is chosen to be executed against the application. However, the process of test case selection and prioritization can be challenging and depends on various factors.
    
    - Common reasons for selecting regression test cases include:
        - Test cases that have previously identified defects.
        - Test cases that cover frequently used functionality.
        - Test cases that cover features with recent changes or complex scenarios.
        - Test cases that cover edge cases or have shown random success or failure in the past.

### <ins>Testing levels</ins>
- Software testing is typically divided into different levels, which are carried out at various stages of the Software Development Life Cycle (SDLC). These testing levels help ensure effective testing while minimizing overlap and optimizing time spent on testing activities.

- The four commonly recognized testing levels are:

    1. Unit testing: This level focuses on testing individual components or units of the software in isolation. It aims to verify that each unit functions correctly according to its design and meets the specified requirements. Unit testing is typically performed by developers using techniques like white box testing.

    2. Integration testing: Integration testing involves testing the interaction between different units or modules of the software. It ensures that the integrated components work together seamlessly and perform as expected. Integration testing can be conducted in various ways, such as top-down, bottom-up, or sandwich testing approaches.

    3. System testing: System testing evaluates the entire system as a whole. It involves testing the integrated software system against the specified requirements to ensure that it functions as intended. This level of testing focuses on validating system behavior, performance, security, and other system-level characteristics.

    4. Acceptance testing: Acceptance testing is the final level of testing and is conducted to determine if the software meets the user's expectations and requirements. It involves testing the software in a realistic environment to validate its readiness for deployment. Acceptance testing is usually performed by end-users, business stakeholders, or a designated testing team.