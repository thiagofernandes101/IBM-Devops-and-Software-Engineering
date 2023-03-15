# **Introduction to agile philosophy**

## **Agile principles**
### <ins>What is Agile?</ins>
- Agile is an iterative approach to project management that allows teams to be responsive and deliver value to their customers faster.

- Unlike other planning approaches where we plan out an entire year's worth of work, with Agile we plan out small increments and they get feedback from the customer to see if they like what we're doing then making possible to adjust as we go along.

### <ins>Agile defining characteristics</ins>
- Agile emphasizes:
    
    - Adaptive planning which we don't plan out an entire year, but a small iteration to see if we can deliver something of value to the customer, get feedback and see what they like, allowing us to do evolutionary development.

    - Evolutionary development that will evolve over time. We are building... instead of building the whole thing up at once, we are building it in small increments and then evolving and responding as we go. This gives the opportunity to do early delivery.

    - Early delivery is a key component of being agile, in other words, if you are developing iterations and not delivering to the customer, you are not being agile. Putting something in the customers' hands, getting feedback from them to understand and see what they liked, should we pivot, should we persevere? This is a critical defining characteristic of being agile, over just doing iterative development.

    - Countinuous improvement is done as team. We continuously improve the product that we are delivering because we have the opportunity to get feedback from our customer, because we delivered it. This allow us to be responsive to change. So as changes happen (they always do), customers always have changing requirements. We can respond to those changes, because we haven't planned too far in advance, the customer sees the progress we have made and then we can quickly re-plan and be responsive to what a customer needs.

### <ins>Agile manifesto</ins>
- We have come to value:

    - **Individuals and interactions** over processes and tools
    - **Working software** over comprehensive documentation
    - **Customer collaboration** over contract negotiation
    - **Responding to change** over folowing a plan

> While there is value in the items on the right, we value the items on the left more. 
> 
> It does not mean we do not have processing tools, it just means that we value interacting amongst ourselves and with our customers more than the process and tools.
>
> It does not mean we do not document (it is important so that people understand how to use the product), but we can not ship documentation.
>
> Working software is what we are here to deliver. It does not mean that we don't negotiate contracts, we still have contracts, but we want to collaborate with the customer.
>
> As things change, we want to be responsive, which does not mean that we do not have plans, but we value responding to change over simply following the plan.

### <ins>Agile software development</ins>
- Is an interative approach to software development consistent with the Agile Manifesto.

- Emphasizes flexibility, interactivity (with peers and customer) and a high level of transparency, so that everybody knows what everyone else is working on and feels responsible for delivering value to the customers.

- Uses small, co-located, cross-functional, self-organizing teams.

### <ins>Key takeway</ins>
- Build what is needed, not what is planned. If you build what was planned and the customer does not like it, why bother? It is important to make sure that as they need change, you want to build what is needed from the customer regardless of what was planned. We can always replan and be responsive to change.

## **Methodologies overview**

### <ins>Traditional waterfall development</ins>
``` mermaid
flowchart TB
    Requirements --> Design --> Coding --> Integration --> Test --> Deploy
```

- Requirements: people are gathering requirements, seeing what the customer wants, making sure that we are going to deliver something that the customer wants. At least for that point in time. In short, this is a phase where all you are doing is documenting all the requirements of the customer might want in the system.

- Design: happens after getting all the requirements. The architects are designing, figuring out how do we take those requirements, turn them into working software. And so, they design the entire system.

- Coding: this phase is where the developers are coding away.

- Integration: all along, the coding phase was made in isolation and we are not integrating my module with the next person module, but there is a time when all the modules come together and then comes the question: "Do all these pieces of code even work together?". Then comes the testing phase

- Test: with a system that people can test, bugs are found, they go back and open some bugs in the coding phase and do some recoding. However it would be extremely hard to change anything if one of those bugs that they tested turns out to be a change in the design because nothing is interacting well.

- Deploy: Goes to production and is available to the customer.

> In a waterfall development, there is a exit and entrance criteria to move from on phase to the other and once you are in the coding phase, for example, and find out that the design is bad, it is real hard to go back up and redesign thing. In fact, because the software development is treated the same way as a civil engineer project, sometimes some of those designers have moved on to the next project, and you have got to find them. So it is very dificult to go back a phase in a waterfall development.

### <ins>Problems with the waterfall approach</ins>
- No provision for changing requirements. Every phase has entrance and exit criteria and when one ends, the next on begins. Also there is no provision for going back and changin the design or changing the requirements.

- No ideia if it works until the end, there is no intermediate delivery. Nothing is delivered until the last step, where we give to the operations team and say "go deliver this to prodution".

- Each step ends when next begins and each and every phase is an opportunity to lose information, have a mishap happen or to have people get blocked, because they can not accept the work from the previous phase and you are waiting to get the next phase going.

- Mistakes that are found later on are very costly. To find something that is designed wrong and testing and go back and redesign it.

- There is the long lead time, right between getting that sofware delivered. From the time you first want the software and you design, code, test it and, by the time it is delivered, there is a long lead time.

- Teams work separetely, unaware of their impact on each other. The designers, for example, are unaware of the impact of the code, the coders are unaware of their impact to integrating all the code together. In this approach, everybody is working in their little silos for their little phase. With this, people who are furthest away from a code, the operation team, have to run and manage the software in production (they know the lease about the code and are expected to run it).

### <ins>Extreme programming (XP)</ins>
- Kent Beck introduced Extreme Programming in 1996
![Extreme Programming](Assets/ExtremeProgrammingPlanningFeedbackLoops.png)
> The graphic is very iterative and talking about loops. You've got these major release plan on the outer loop, then an iteration plan and so the release maybe months, the iterations maybe weeks, acceptance has maybe days, stand up meetings once a day, pair negotiation in hours, unit test in minutes, pair programming in seconds. It is tighter loops of doing work and getting feedback.

- It is based on iterative approach to software development and the intent is to improve sofware quality, be responsive to change, be responsive to customer requirements, do things in small increments.

- Extreme Programming can also be considered one of the first Agile methods.

### <ins>Extreme programming values</ins>
- Simplicity: keep it simple and do what you need and no more. Do not over-engineer, do not over code, do not deliver more code than the customer asked for.

- Communication: everyone on the team should be communicating to know what everyone else is doing.

- Feedback: the feedback loops are critical to extreme programming, and critical to Agile in general, since you have no idea how you are doing unless you are getting feedback.

- Respect: everyone feels that they are respected on the team, that they can offer advice that they can make suggestions and that their suggestions are just as valuable as anybody else's suggestion on the team. There is no hierarchy, everybody has peers on the team and respected for their ideas.

- Courage: be honest about your thoughts and the amount of work you can do without lying to overestimate yourself.

### <ins>Kanban</ins>
- Means billboard sign and it is all about continuous flow on the manufacturing floor, where these cards or notes would flow with the product from station to station, going down the line. The principle with this is to visualize the workflow

### <ins>Core principles of Kanban</ins>
- Visualize the workflow
- Limit work in progress (wip)
- Manage and enhance the flow
- Make process policies explicit
- Continuously improve

# **Introduction to scrum methodology**

# **Organizing for success**