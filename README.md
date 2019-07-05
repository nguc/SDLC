# Software Development Lifecycle

A blurb here about what it is

## Purpose  

- Devs know what they are trying to make
- Managers can track progress
- track if product meets requirements

## Benefits 

- A common vocabulary for each step
- Defined communication channels between development teams and stakeholders
- Clear roles and responsibilities among developers, designers, business analysts, and project managers
- Clearly-defined inputs and outputs from one step to the next
- A deterministic “definition of done” that can be used to confirm whether a step is truly complete

 ## Process 
 
1. **Planning**
    - Resource allocation (both human and materials)
    - Capacity planning
    - Project scheduling
    - Cost estimation
    - Provisioning

    Output: Project plans, schedules, cost estimations, procurement requirements 
    
2. **Design and Prototype**
    - Design patterns
    - architecture frameworks (for code reuse and standardization)
    - rapid prototyping (optional)

3. **Develop**
     (Agile --> Time boxed Sprints)  (Waterfall --> single block of effort)
    - Features
    - Bug fixes
    - engage with stakeholders, ensure expectations being met

     Output: Testable, functional software
    
4. **Testing**
    - code quality
    - Unit Testing
    - Integration testingperformance testing
    - security testing
    - QA testing
    - Can use continuous integration tools to ensure tests are run regularly and never skipped.

     Output: Functional software, ready to deploy to production environment

5. **Deployment**
    - idealiy highly automated
    - Application Release Automation (ARA) systems are usually integrated with Continuous Integration tools. 
    
     Output: Release to Production of working software.

6. **Operations and maintenance**
     - constant monitoring to ensure proper operation
     - error reporting send bugs back
     - improvment requests 

An abbreviated process is necessary to ensure that the fix does not introduce other problems (known as a regression). Regression testing is re-running functional and non-functional tests to ensure that previously developed and tested software still performs after a change. If not, that would be called a regression.
    
## SDLC Models
**Agile**
![Image of Agile method](https://github.com/nguc/SDLC/tree/master/Images/agile.png)

This is the model that we follow here
- more flexible
- emphasizes teamwork, prototyping, and feedback loops that can change the direction of the development effort in response to changing requirements

***Scrum***
- Time is divided into short work cadences - sprints - 1 to 2 weeks
- Product is kept in potentially shippable (properly integrated and tested) state at all times
- End of sprint: Team and stakeholders should meet and see a demo of the product increment and plan its next steps

***Kanban***
- Visualize what you do today (workflow)
- Limit the amount of work in progress (WIP)
- Enhance flow
- Continuous delivery

| Scrum | Kanban |
|---------|-------------------------------------------------------------------------|
| No prescribed roles | Pre-defined roles: Scrum master, Product owner, team member |
| Continuous Delivery | Timeboxed sprints |
| work pulled trough system (single peiece flow) | work pulled through the system in batches (sprint backlog) |
| Changes can be made at any time | No changes allowed mid-sprint |
| Cycle time | Velocity |
| Operational environments with high degree of variablitiliy in priority | Work can be prioritized in batches that can be left alone |


**Waterfall**
![Image of Waterfall model](https://github.com/nguc/SDLC/tree/master/Images/waterfall.png)

We dont do this here

## SDLC Practices

**Source Control**
 - Git
 
**Continuous integration**
 - TFS builds
 
**SDLC Management systems**
 - DevOps, Jira
 - Kanban
 
## Conclusion
All software begins as a concept, and flows through a series of phases until a release is developed and deployed. The Software Development Life Cycle of an application or system continues, with updates and new features, until the day it is decommissioned or replaced. Several methods for software development have evolved over the decades.

Waterfall methods are still common, though Agile is rapidly overtaking it in companies large and small. Whichever method you choose, use the right tools for the job. Software is difficult to delivery reliably without them. There is no perfect method, but it’s far better to use some method than none.
    


