# Software architect's handbook

## Chapter 5: Designing Software architecture

### Top-down vs bottom up approach
- ***A top-down approach*** starts with the entire system at the highest level, and then a process of decomposition begins to work downward toward more detail. The starting point is the highest level of abstraction. As decomposition progresses, the design becomes more detailed, until the component level is reached.
- ***The bottom-up approach*** begins with the components that are needed for the solution, and then the design works upward into higher levels of abstraction. Various components can then be used together, like building blocks, to create other components and eventually larger structures. The process continues until all the requirements have been met.

#### when use top-down approach
- The project is large in size
- The project is complex
- Enterprise software is being designed for an organization
- The team is large, or there are multiple teams that will be working on the project
- The domain is well-understood

#### when use bottom-up approach
- The project is small in size
- The project is not very complex
- Enterprise software for an organization is not being designed The team is small, or there is only a single team
- The domain is not well-understood


### Greenfield versus brownfield software systems
- ***A greenfield software system*** is a completely new software application.
- ***A brownfield software system*** is an existing software system.

## Chapter 6: Software development principles and practices

### Designing orthogonal software systems

#### Loose coupling
- Coupling is the degree to which a software module depends on another software module.
- Software modules that are tightly coupled are more complex, which decreases their maintainability.
- It is also easy to engage in parallel development if the code is loosely coupled.
- Types of coupling
  - **Content coupling:** one module directly references the internal or private information in another module.
  - **Common coupling:** share the same global data, such as a global variable.
  - **External coupling:** multiple modules share the same part of an environment that is external to the software.
  - **Control coupling**
  - **Stamp coupling (data-structured coupling)**
  - **Data coupling**
  - **Message coupling**
  - **No coupling**