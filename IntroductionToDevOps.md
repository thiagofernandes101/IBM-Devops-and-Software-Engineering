# **Organiztional impact of DevOps**
1. Identify how organizational structure impacts DevOps
1. Explain Conway's law
1. Describe the optimal organization for DevOps teams

## How does organization affect DevOps?
- Is the culture of your organization agile?
  - Small teams
  - Dedicated teams
  - Cross-functional teams (not working in silos)
  - Self-organizing teams

## Conway's Law
**"Any organization that designs a system (defined broadly) will produce a design whose structure is a copy of the organization's communication structure"** (Melvin Conway, Datamation, 1968)


## Traditional organization around technology
- **Organization structure (each structure has its own roles)**
  - User interface team
  - Application team
  - Database administrator team (DBA)

- **Application structure**
  - Web tier <-> App tier <-> Database

## Organized around business domains
- **Login registration users** (Account team)
- **Personalization** (Personalization team)
- **Shipping Receiving Inventory** (Warehouse team)
> **Important:** Each business domain care for its own organization structure (user interface, application, database) and each team can do its working without depending on another team or tickets opening. They work as a small, dedicated, cross-functional, self-organizing team.

## Align teams with the business
- Each team has its own mission aligned with the business domain.
- Teams have end-to-end responsibility for what they build.
- Teams should have a long term mission usually around a single business domain.

## There is no DevOps Team
- DevOps is often misundertood

## Perspectives on DevOps
- In traditional large enterprises, the development and operation team are separated and DevOps is another team that works with them and "facilitate" communication. However, DevOps is something that both, the development and operation team, do.
> DevOps is a mindset that the hole organization adopt.

## DevOps is not a team
**"The DevOps movement addresses the dysfunction that results from organizations composed of functional silos. Thus, creating another functional silo that sits between Dev and Ops is clearly a poor (and ironic) way to try and solve these problems."**(Jez Humble, The DevOps Handbook)

## DevOps is not a job title
- A cultural transformation on an organizational scale.
- Development and operations engineers working together.
- Following lean and agile principles.
- Cross-functional teams with opennes, tranparency and trust as pillars.

## Bad behavior
**"Bad behavior arises when you abstract people away from the consequences of their actions"**(Jez Humble, Continuous Delivery)
- Functional silos bring bad behavior.
- If people are abstracted from the consequences of their actions, they will become apathetic.

## Acions have consequences
- Make people aware of the consequences of their actions.
- Make people responsible for the consequences of their actions.
- Everyone is Responsible for Success

## DevOps organizational objective
- Share consciouness
- ...with
- distributed (local) control

> # Quis
> - The statement "it is good practice to design systems according to the organization's business domain, that is what they are > producing" is a good illustration of Conway's Law.
> - When working DevOps, it is better to have teams organized around business domains
> - When organizing for DevOps, both Dev (development team) and Ops (operation team) work with the same mindset, goals and > measures
> - In a DevOps environment, the development and operation engineers work together during the entire lifecycle, following Agile > principles.

# **Measuring DevOps**
1. Explain the importance of measuring what you want to improve
1. Identify the value of social and DevOps metrics
1. Recognize that DevOps changes your approach to problem resolution

## **Rewarding for A while hiping for B**
- **<ins>On the folly of rewarding for A, while hoping for B</ins>: "Whether dealing with monkeys, rats, or human beings, it is hardly controversial to state that most organisms seek information concerning what activities are rewarded and then seek to do (or at least pretend to do) those things, often to the virtual exclusion of activities not rewarded. The extent to which this occurs of course will depend on the perceived attractiveness of the rewards offered, but neither operant nor expectancy throrists would quarrel with the essence of this notion"**(Steven Kerr, The Ohio State University)
- You can not measure for A while hoping for B, in other words, you get what you measure so measure what matters.

## Measure what matters
![Measure what matters](Assets/Measure%20what%20matters.png)

## Social metrics
- Who is leveraging the code you are building?
- Whose code are you leveraging?

## DevOps metrics
- A baseline provides a concrete number for comparison as you implement your DevOps changes.
- Metric goals allow you to reason about these numbers and judge the success of your process.

## DevOps changes the objective
- Old school is focused on mean time to failure (MTTF)
- DevOps is focused on mean time to recovery (MTTR)

# **Vanity metrics versus actionable metrics**
1. Identify the limitations of vanitymetrics
1. Describe the value of actionable metrics
1. List example of actionalbe metrics

## Vanity metrics
- Example: we had 10.000 daily hits to our website!
- Now what? (What does a hit represent?)
- What actions deove those visitors to you?
- Which actions to take next?


## Actionable metrics
- A cause and effect is introduced.

- Example case: Imaginge you add a new feature your webside, and you initially introduce it using A/B split testing in which 50% of the customers in group B see the new feature and the other 50% in group A don't. A few days later, you compare the revenue you have earned from each customer group, noticing that group B has 20% higher revenue per customer.
![Actionable metrics](Assets/Actionable%20metrics.png)

- Examples
  1. Reduce time to market
  1. Increase overall availability
  1. Reduce the time to deploy
  1. Defects detected before production
  1. More efficient use of infrastructure
  1. Quicker performance feedback

## Top four actionable metrics
1. Mean lead time (how long it takes for an idea goes to production)
1. Release frequency
1. Change failure rate (how often changes, such as new releases, fail)
1. Mean time to recovery (MTTR) (how long it takes to recover when something fails)

# **How to measure your culture?**
1. Identify relevant statements for measuring team culture

## Culture measurements
- Set of statements developed by Dr. Nicole Forsgren when she was the CEO and Chief Scientist at DevOps Research and Assessment (DORA)
![Set of statements developed by Dr. Nicole Forsgren](Assets/Set%20of%20statements%20developed%20by%20Nicole%20Forsgren.png)

- These are culture statements for measuring the teams on a scale of 7, strongly agree, to 1, strongly desagree.

## Strongly agree or disagree?
- On my team, information is actively sought
- On my team, failures are learning opportunities and messengers of them are not punished
- On my team, responsibilities are shared
- On my team, cross-functional collaboration is encouraged and rewarded
- On my team, failure causes inquiry
- On my team, new ideas are welcomed
> This is Dr. Nicoles approach

# Comparison of DevOps to site reliability engineering (SRE)
1. Recognize how site reliability engineering differs from DevOps
1. Recognize the commonality between site reliability engineering and devops
1. Explain how site reliability engineering and DevOps can be used together

## Site reliability engineering
- What is Site Reliability Engineering (SRE)?
  - "...what happens when a software engineer is tasked with what used to be called operations" (Ben Treynor Sloss)
  - Goal: Automate yourself out of a job
- How does it differ from DevOps?
- How can you leverage SRE in a DevOps environment?

## Tenets of SRE
- Hire only software engineers
- Sire reliability engineers work on reducing toil through automation
- SRE teams are separate from development teams
- Stability is controlled through error budgets
- Developers rotate through operations

## Team differences
- SRE maintains separate development and operations silos with on staffing pool
- DevOps breaks down the silos into one team with one business objective

## Maintaining stability
| SRE    	| DevOps                                                        	|
|--------------------------	|--------------------------------------------------------------------------	|
| Error budgets based on service-level objectives       	| Continuous Delivery pipelines                                      	|
| When error budget is exceeded, there is no deployment 	| Everyone is responsible for code                                   	|
|                   	| You build it, you run it 	|

## Commonality
- Both seek to make both Dev and Ops work visible to each other
- Both require a blameless culture
- The objective of both is to deploy software faster with stability

## DevOps + SRE
- SRE maintains the infrastructure
- DevOps uses the infrastructure to maintain their applications
> DevOps -> Application
>
> SRE -> Cloud
>
> Using things like platform as a service is important to DevOps. The SRE teams provide a platform. The DevOps teams utilize the platform to deploy their applications.