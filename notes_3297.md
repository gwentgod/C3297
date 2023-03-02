### Software process models


#### Waterfall model

Plan-driven model.
Separate and distinct phases of specification and development.

1. Requirements definition: Define system’s services, constraints, and goals in details.

2. System and software design: Allocates the requirements to hardware or software,
design overall system architecture, describing the fundamental system abstractions and their relationships.

3. Implementation and unit testing: Realize as a set of programs (or program units),
perform unit testing verifying each unit meets its spec

4. Integration and system testing: Units are integrated, and tested as a complete system.
After testing, delivered to the customer.

5. Operation and Maintenance: The system is installed and put into practical use.
Maintenance involves maintenance correcting errors.

###### Usage

- Appropriate when the requirements are well-understood.
- Used for Large Systems engineering projects where a system is developed at several sites.

###### Disadvantages

- Difficulty of accommodating change. A phase has to be completed before moving onto the next phase.

- Bad quality, higher cost and longer elapsed time
due to early freeze of software specification and unit testing.


#### Incremental development

May be plan-driven or agile.
Specification, development and validation are interleaved, with rapid feedback across activities.

###### Advantages

- Less cost for requirements changing.
- Easier to get customer feedback.
- Customers are able to use and gain value from the software earlier.

###### Disadvantages

- Process not visible
- System structure tends to degrade as new increments are added


#### Integration and configuration

The system is assembled based on software reuse

###### Advantages

- Reduced costs and risks
- Faster delivery and deployment of system

###### Disadvantages

- System may not meet real needs of users
- Loss of control over evolution of reused system elements


### Process Activities

#### Specification / Requirements engineering

1. Requirements elicitation and analysis
2. Requirements specification
3. Requirements validation

#### Development / Design and Implementation

- Software design: Design a software structure that realises the specification
- Implementation: Translate this structure into an executable program

#### Validation

Involves checking and review processes, and system testing.
Program/System testing involves executing the system with test cases
that are derived from the specification of the real data to be processed by the system.
Testing is the most commonly used V & V activity.

#### Evolution

Software that supports the business must also evolve and change.


### Coping with change

- Anticipate possible changes before significant rework is required.
- Change tolerance so that changes can be accommodated at relatively low cost.

#### Software prototyping

Demonstrate concepts and try out design options, help with requirements elicitation and validation,
explore options and develop a UI design

1. Establish prototype objectives: Prototyep plan
2. Define prototype functionality: Outline definition
3. Develop prototype: Executable prototype
4. Evaluate prototype: Evaluation report

###### Advantages

- Improved system usability
- A closer match to users' real needs
- Improved design quality
- Improved maintainability
- Reduced development effort


#### Incremental delivery

Break development and delivery into increments.
Freaz the requirements once the development of an increment is started.
requirements for later increments can continue to evolve.

1. Define outline requirements
2. Assign requirements to increments
3. Design system architecture
4. Develop system increment
5. Validate increment
6. Integrate increment
7. Validate system
8. Deploy increment
    > Go back to 4. when system incomplete

###### Advantages

- Customer value can be delivered with each increment so system functionality is available earlier.
- Early increments act as a prototype to help elicit requirements for later increments.
- Lower risk of overall project failure.
- The highest priority system services tend to receive the most testing.

###### Disadvantages

Most systems require a set of basic facilities that are used by different parts of the system.
Specification is developed with the software, which conflicts with many organizations.

### Process improvement

Maturity approach: Focuses on improving process, project management and introducing good software engineering practice,
to improved product quality and process predictability.

Agile approach: Focuses on iterative development and the reduction of overheads in the software process,
for rapid delivery of functionality and responsiveness to changing customer requirements.



- Change: Propose process changes to address some of the identified process weaknesses.
Resume cycle to collect data about the effectiveness of the changes.

- Measure: Measure attributes of the software process or product,
form a baseline that helps you decide if process improvements have been effective.

    - Time taken for process activities to be completed
    - Resources required for processes or activities
    - Number of occurrences of a particular event

- Analyze: Identify process weaknesses and bottlenecks


### Agile Software Development

- Customer involvement: Customers closely involved throughout the development.
They provide/prioritize system requirements, and evaluate system.

- Incremental delivery: Develop software in increments.
Customers specify requirements in each increment.

- People not process: Recognize and exploit development team.
Develop their own ways of working without prescriptive processes

- Embrace change: Expect the system requirements to change
Design the system to accommodate these changes

- Maintain simplicity: Focus on simplicity in both software and process.
Actively work to eliminate complexity from the system


#### Agile development techniques - Extreme programming

1. Incremental planning: Requirements are determined by the time available and relative priority.
2. Small releases: Release system frequently and add functionality incrementally.
3. Simple design: Design enouth to meet the current requirements and no more.
4. Test-first: development: Write tests before implementing the functions
5. Refactoring: Improve code as soon as possible.
6. Pair programming: Developers work in pairs, check each other’s work and provide support
7. Collective ownership: Developers work on all areas on the system together.
8. Continuous integration: Integrate completed task into whole system, pass unit tests.
9. Sustainable pace: Large amounts of overtime are NOT acceptable.
10. On-site customer: A representative of customer in team available full time.

###### Problems with test-first development

- Programmers prefer programming to testing and sometimes they take short cuts when writing tests.
- Some tests can be very difficult to write incrementally.
- It difficult to judge the completeness of a set of tests.

#### Agile project management - Scrum

###### Team

- Development Team
- Scrum Master:  Interface with rest of the company
- Product Owner: Identify and prioritize product features or requirements,
Continuously review product backlog.
Can be customer, PM or stakeholder representative.

###### Scrum Cycle

1. List of to do items must be done on the project. Involves all of the project team.
2. Product Owner prioritize the items in product backlog. Team selects highest priority items.
3. Sprint Backlog
4. Scrum: A daily meeting of the Scrum team. Review progress and prioritizes work to be done that day.
5. Potentially shippable software: Finished state and no further work is needed.
6. Review: All team members share information in a review meeting
7. End: Process improvement, update product backlog, present to stakeholders.


###### Advantages

- The product is broken down into a set of manageable and understandable chunks.
- Unstable requirements do not hold up progress.
- The whole team have visibility of everything and consequently team communication is improved.
- Customers see on-time delivery of increments and gain feedback on how the product works.
- Trust between customers and developers is established.

###### Scaling agile methods

The informality of agile development is incompatible
with the legal approach to contract definition that is commonly used in large companies.
Sol: A contract that pays for developer time rather than functionality is required.
Risk: what has to be delivered cannot be guaranteed

Agile methods are most appropriate for new software development rather than software maintenance. Key problems are:
- Lack of product documentation (Sol: high-quality and readable code)
- Keeping customers involved in the process (Sol: change proposal)
- Maintaining the continuity of the development team (Sol: Properly no)

Agile methods are designed for small co-located teams yet much software development now involves worldwide distributed teams.
