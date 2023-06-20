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