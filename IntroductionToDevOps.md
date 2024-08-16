# **Organizational impact of DevOps**

Understanding the organizational influence on DevOps:

1. Identify how organizational structure impacts DevOps
2. Explain Conway's law
3. Describe the optimal organization for DevOps teams

## How does organization affect DevOps?

The structure and culture of an organization significantly influence the success of DevOps practices. Agile organizations typically feature small, dedicated, and cross-functional teams that do not operate in silos. These teams are self-organizing, which is crucial for fostering the collaborative environment that DevOps requires.

## Conway's Law

Conway's Law states: **"Any organization that designs a system (defined broadly) will produce a design whose structure is a copy of the organization's communication structure"** (Melvin Conway, Datamation, 1968). This law highlights the direct correlation between organizational structure and the systems they produce, underscoring the importance of aligning team structures with desired outcomes in DevOps.

## Traditional organization around technology

In traditional organizations, teams are structured around specific technological functions, such as:

* **User Interface teams**
* **Application team**
* **Database Administrator Team (DBA)**

These teams work on different layers of the application architecture, often leading to a disjointed development process:

* **Web tier <-> App tier <-> Database**

## Organized around business domains

In contrast, an optimal DevOps structure organizes teams around business domains rather than technology layers. For example:

* **Account Team:** Manages login and user registration.
* **Personalization Team:** Focuses on personalizing user experiences.
* **Warehouse Team:** Oversees shipping, receiving, and inventory management.

Each business domain team is responsible for its own user interface, application logic, and database. This structure allows teams to operate independently without relying on other teams or tickets opening, fostering agility and efficiency.

## Align teams with the business

Teams should have missions that are closely aligned with business objectives and each team should take end-to-end responsibility for what they build, ensuring a long-term commitment to their business domain. This alignment ensures that the teams are working towards the same goals as the business.

## The Misconception of a DevOps Team

**"The DevOps movement addresses the dysfunction that results from organizations composed of functional silos. Thus, creating another functional silo that sits between Dev and Ops is clearly a poor (and ironic) way to try and solve these problems."**(Jez Humble, The DevOps Handbook)

DevOps is often misunderstood as a separate team that facilitates communication between development and operations. However, DevOps is not a team or a job title; it is a mindset and a cultural transformation that the entire organization must adopt. Development and operations engineers should work together seamlessly, following lean and agile principles, and operating within cross-functional teams built on openness, transparency, and trust.

## Bad behavior

**"Bad behavior arises when you abstract people away from the consequences of their actions"**(Jez Humble, Continuous Delivery)

Functional silos in an organization can lead to bad behavior, as individuals may become apathetic if they are detached from the outcomes of their work. To counter this, DevOps emphasizes making people aware and responsible for the consequences of their actions, promoting a shared responsibility for success.

## DevOps organizational objective

The primary objective of DevOps within an organization is to foster a shared consciousness with distributed, local control. This approach encourages collaboration and accountability, leading to more effective and resilient systems.

# **Measuring DevOps**

The Importance of Measuring and Improving DevOps Practices:

1. Explain the importance of measuring what you want to improve.
2. Identify the value of social and DevOps metrics.
3. Recognize that DevOps changes your approach to problem resolution.

## **Rewarding for A while hoping for B**

- **On the folly of rewarding for A, while hoping for B:** "Whether dealing with monkeys, rats, or human beings, it is hardly controversial to state that most organisms seek information concerning what activities are rewarded and then seek to do (or at least pretend to do) those things, often to the virtual exclusion of activities not rewarded. The extent to which this occurs of course will depend on the perceived attractiveness of the rewards offered, but neither operant nor expectancy theorists would quarrel with the essence of this notion" (Steven Kerr, The Ohio State University). 

  In DevOps, it is crucial to align your measurements with your goals. You cannot measure for one thing while hoping for another; measure what truly matters.

## Measure what matters

![Measure what matters](Assets/Measure%20what%20matters.png)

In DevOps, you should focus on metrics that provide actionable insights and drive continuous improvement.

## Social metrics

- Identify who is leveraging the code you are building.
- Understand whose code you are leveraging.

## DevOps metrics

- Establishing a baseline provides concrete numbers for comparison as you implement DevOps changes.
- Metric goals help you assess the success of your processes and guide decision-making.

## DevOps changes the objective

Traditionally, organizations focus on Mean Time to Failure (MTTF), aiming to minimize the frequency of failures. However, DevOps shifts the focus to Mean Time to Recovery (MTTR), emphasizing the importance of quickly recovering from failures to maintain system stability and resilience.

# **Vanity metrics versus actionable metrics**

Understanding the Difference Between Vanity Metrics and Actionable Metrics:

1. Identify the limitations of vanity metrics
2. Describe the value of actionable metrics
3. List example of actionable metrics

## Vanity metrics

Vanity metrics, such as "we had 10,000 daily hits on our website," can be misleading. These metrics provide little insight into the effectiveness of your actions or what you should do next. They lack context, making it difficult to derive meaningful conclusions.

## Actionable metrics

Actionable metrics introduce a cause-and-effect relationship, providing valuable insights that guide decision-making. For example, if you add a new feature to your website and use A/B testing, you can measure the impact on revenue. If Group B, which received the new feature, shows a 20% increase in revenue per customer compared to Group A, this data is actionable and can inform future decisions.

![Actionable metrics](Assets/Actionable%20metrics.png)

**Examples of Actionable Metrics**

1. Reduce time to market.
2. Increase overall availability.
3. Reduce the time to deploy.
4. Defects detected before production.
5. More efficient use of infrastructure.
6. Quicker performance feedback.

## Top four actionable metrics

1. **Mean Lead Time:** The time it takes for an idea to go into production.
2. **Release Frequency:** How often new releases are deployed.
3. **Change Failure Rate:** The frequency at which new releases fail.
4. **Mean Time to Recovery (MTTR):** The time it takes to recover from a failure.

# **How to measure your culture?**

* Identify relevant statements for measuring team culture

## Culture measurements

Dr. Nicole Forsgren, during her tenure as the CEO and Chief Scientist at DevOps Research and Assessment (DORA), developed a set of statements to measure team culture. These statements assess team dynamics on a scale of 7 (strongly agree) to 1 (strongly disagree).

![Set of statements developed by Dr. Nicole Forsgren](Assets/Set%20of%20statements%20developed%20by%20Nicole%20Forsgren.png)

**Example Statements for Measuring Team Culture**

- On my team, information is actively sought.
- On my team, failures are learning opportunities and messengers of them are not punished.
- On my team, responsibilities are shared.
- On my team, cross-functional collaboration is encouraged and rewarded.
- On my team, failure causes inquiry.
- On my team, new ideas are welcomed.

> This approach is based on Dr. Nicole Forsgren's research.

# Comparison of DevOps to Site Reliability Engineering (SRE)

Understanding the Differences and Commonalities Between DevOps and SRE.

1. Recognize how site reliability engineering differs from DevOps.
2. Recognize the commonality between site reliability engineering and devops.
3. Explain how site reliability engineering and DevOps can be used together.

## Site reliability engineering

Site Reliability Engineering (SRE) is defined as "...what happens when a software engineer is tasked with what used to be called operations" (Ben Treynor Sloss). The goal of SRE is to automate as much as possible, effectively working towards "automating yourself out of a job."

## Tenets of Site Reliability Engineering (SRE)

1. **Hiring Software Engineers:** The foundation of SRE is rooted in hiring skilled software engineers. SREs are expected to have strong software engineering backgrounds, enabling them to write reliable and maintainable code. Their engineering expertise is critical for building systems that are both scalable and robust.

2. **Focusing on Toil Reduction Through Automation:** A core responsibility of SREs is to minimize repetitive, manual tasks—referred to as "toil"—by developing automated solutions. By automating routine processes, SREs free up time to focus on higher-value engineering work, ultimately enhancing the efficiency and reliability of the system.

3. **Separation from Development Teams:** SRE teams are distinct from development teams, ensuring that they can maintain an unbiased focus on system reliability. While they collaborate closely with developers, the separation allows SREs to prioritize operational concerns, such as availability and performance, without the direct influence of feature-driven development pressures.

4. **Stability Through Error Budgets:** Error budgets are a key mechanism for balancing innovation with reliability. An error budget is the maximum allowable amount of system downtime or failure within a specified period. It provides a quantifiable measure that allows SRE and development teams to assess when to prioritize stability over new features, ensuring a controlled approach to system changes.

5. **Developer Rotation through Operations:** To foster a shared responsibility for reliability, developers periodically rotate through operations roles. This practice not only broadens their understanding of the system's operational challenges but also promotes a culture of collaboration between development and SRE teams. By experiencing the impact of their code in a production environment, developers gain valuable insights into the importance of building resilient systems.

## Team differences

- SRE maintains separate development and operations silos with on staffing pool
- DevOps breaks down the silos into one team with one business objective

## Maintaining stability

| SRE                                                   | DevOps                           |
| ----------------------------------------------------- | -------------------------------- |
| Error budgets based on service-level objectives       | Continuous Delivery pipelines    |
| When error budget is exceeded, there is no deployment | Everyone is responsible for code |

## Commonalities Between SRE and DevOps

Both SRE and DevOps aim to make the work of both development and operations visible to each other, fostering a blameless culture. The shared objective is to deploy software faster while maintaining stability.

## Relationship Between DevOps and SRE

- **SRE Maintains the Infrastructure:** In the collaborative ecosystem of DevOps and SRE, the Site Reliability Engineering (SRE) team is primarily responsible for managing and maintaining the infrastructure. This includes ensuring that the underlying systems, such as servers, networking, and cloud services, are reliable, scalable, and secure. SREs focus on optimizing the infrastructure to support the high availability and performance of the applications running on it.

- **DevOps Uses the Infrastructure to Maintain Applications:** DevOps teams, on the other hand, are primarily concerned with developing, deploying, and maintaining applications. They leverage the infrastructure provided by the SRE teams to build, test, and release software rapidly and efficiently. DevOps practices emphasize continuous integration and continuous delivery (CI/CD), ensuring that applications are consistently updated and deployed with minimal disruption.

- **Platform as a Service (PaaS) Integration:** The collaboration between SRE and DevOps is often facilitated through the use of Platform as a Service (PaaS) solutions. SRE teams create and manage these platforms, providing a stable and standardized environment for DevOps teams to deploy their applications. By abstracting the complexities of the underlying infrastructure, PaaS allows DevOps teams to focus more on application development and less on infrastructure management. This division of responsibilities enables both teams to work efficiently towards their shared goal of delivering reliable, high-quality software.

  - **DevOps Focus:** Application development, deployment, and maintenance.
  - **SRE Focus:** Cloud infrastructure, platform management, and reliability engineering.