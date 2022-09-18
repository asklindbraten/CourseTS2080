## Use Case Diagrams

- High level function. 
- User point. 
- Set of action.
- Helps visualise functional requirements.
- nonfunctional requirements - aesthetics, parts of the frontend, background colors, etc. Functions that does not affect thefunctionality of   the program. 

**Summarize:

- The purpose of a use case is to define a piece of coherent behavior without revealing the internal structure of the subject. 
- Help visualize the functional reuirements of a system, including the relationship of "actors" to the essential processes, as well as the relationships among different use cases.  
- Further interactions can be defined as statechart diagrams, sequence diagrams, communication diagrams, or informal text descriptions. Dont crowd this diagram. 

**Facts:

- System boundary: A system boundary defines the scope and limits of the system. It is shown as a rectangle that spans all use cases of the system. 

- An actor is an idealization of a role played by an external person, process, or thing interacting with a system, subsystem or class.
- Use Case: Every business functionality is a potential use case. The use case should list the discrete business functionality specified in the problem statement.

- Generalization: Generalization of an actor means that one actor can inherit the role of the other actor. The descendant has one or more use cases that are specific to that role.

- Associations: A - line between actors and use cases. In complex diagram, it is important to know which actors are associated with which use cases.

- Include: Include relationship represents an invocation of one use case by another use case. From a coding perspective, it is like one function being called by another function. The base use case is incomplete without the included use case. The included use case is mandatory and not optional. 

- Extend: This relationship signifies that the extended use case will work exactly like the base use case, except that some new steps will be inserted in the extended use case.The extending use case is usually optional and can be triggered conditionally. The extended (base) use case must be meaningful on its own. This means it should be independent and must not rely on the behavior of the extending use case.

- Include is for "need for" whereas extend is for "may".



