# Software Component Canvas

![image](https://user-images.githubusercontent.com/1470822/187955517-b88158c8-9587-49a3-afba-b7dbd3639a17.png)


## Background

I've created the Software Component Canvas to get a quick overlook of a broader software system landscape. It helped me to create kind of an inventory of almost all the software systems within a company.

## Current state

This is a slightly polished version of the original. It's not documented in detail yet, but even so, I think the canvas will have more value to you this way than if it's just laying around on my hard drive.

## How does it work?

1. Fill out all the canvas areas while interviewing people who know something about the system or its creation. Alternative: research existing documents and artifacts
2. Connect all the systems based on the information of the individual systems (e.g., by using the context diagram or collaboration information).
3. Get a kind of inventory, including relationships between the systems.
4. Be happy because now you know what systems there are!

And then? You have a good starting point to dig deeper! E.g. start thinking about which systems to improve or get rid of, align the team organization or begin to document the software architecture. Those steps depend heavily on your specific context and problem situation.

## Sections in detail
_unfinished for now, but better than nothing_

### Component name
Write down the official name of the component. Write also down possible abbreviations or nicknames of the component. This is important because later on, you'll talk to different people and see different artifacts that may mention this very same component under different names.

### Short description
Write down in 1-2 sentences what this component is roughly. It should be enough to remind yourself later on if you want to get more details about it.
Also, make sure you add a hint what this component is (system, module, batch process etc.)

## References
Here I list where all the ideas from the sections come from (roughly in order of appearance)

### arc42
https://arc42.org/
- Component name
- Short description
- Main stakeholders
- Responsibility / accountability
- Top 3 quality goals
- Context diagram

### aim42
http://aim42.github.io/
- Top 3 challenges

### Bounded Context Canvas
https://github.com/ddd-crew/bounded-context-canvas
- Strategic classification -> Importance for the business
- Provided capability
- Collaboration with other compoments

### Gregor Hohpe
https://files.gotocon.com/uploads/slides/conference_7/282/original/Enterprise%20Architecture%20Architecting%20the%20Enterprise.pdf, slide 8
- Visibility on C-level

### Wardley Maps
https://medium.com/wardleymaps
- Visibility for customers (adopted value chain)
- Evolution of the component
- Development process, teams and activities -> Personalities

### Cloud Native Transformation Patterns
https://www.cnpatterns.org/
-  Development process, teams and activities -> Process, Drive Mode, Organization

### Team Topologies
https://teamtopologies.com/
- Development process, teams and activities -> Types

### Own work
- Technical key facts
- Development process, teams and activities -> Teams key facts

### DORA report
https://www.devops-research.com/research.html
- Development process, teams and activities -> Teams key facts
- Technical key facts

### cards42* 
https://cards42.org/
- Development process, teams and activities -> Best Pracitices  

\* actually kind of, because cards42 is partly my own work, too

## FAQ

### Isn't there a mismatch between a software component and teams?
Probably! Depending on the abstraction level of the component, one team can be responsible for multiple components or a component can have multiple teams that are responsible for it. You can use the canvas then by referencing the sections regarding the teams for multiple components or vice versa.

