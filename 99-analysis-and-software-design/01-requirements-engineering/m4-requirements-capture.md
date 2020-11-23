# Requirements capture and analysis

## Requirements capture

The objective of this activity is to understand:

* The problem we are trying to solve
* The business, how the systems interact with each other, how this system contributes to the business objectives
* Specific needs for the users of the system

The source of this objectives can be: business objectives, improvements of existing systems, stakeholders...

Common problems when capturing requirements:

* The users don't know hot to express their ideas accurately
* This process must be cooperative not passive
* Viewpoints, each role has a segmented vision on the system and our challenge is to express what the client needs in a very precise way for all the roles to understand it

## Requirements capture techniques

The decided technique will depend on the situation, clients and resources.

### Traditional

Here the main method is doing interviews.

1. Planning
   * What data we want to obtain?
   * Who is interviewed?
   * When?
   * Where?
2. Preparation
   * Collect external info about the problem
   * Prepare questions
   * Research about the interviewed person (job title, personality...)
   * Send event details (date, time, location)
3. Realization
   1. Opening
      * General interview details (duration, objectives)
      * Why this interview is important?
      * Set an informal tone
      * Ask for permission to take notes
   2. Development
      * Better to go 2 people to interview
      * Listen to the interviewed
      * Make sure you understand everything that the interviewed is telling
      * Take detailed notes
      * Don't be passive, ask and encourage
   3. Closing
      * Summary of the notes taken
      * Verify obtained data
      * Thank you for the interview
4. Analysis / Conclusions
   * Review and elaborate conclusions
   * Search for improvement areas for future interviews

### Grupal

Very helpful for obtaining more viewpoints that in individual interviews and for generating discussion. Must be well mediated in order to avoid conflict.

#### Brainstorming

* Objective: obtain creative ideas for solving our problem
* Phases:
  1. Prepare session
     * Select a group of different people
     * Select an objective for the session
  2. Brainstorming
     * Expose the objective of the session
     * Write all ideas with no order
     * Better quantity than quality
     * Associate or modify ideas
     * Make sure all ideas are visible
     * Stop when no more ideas
  3. Evaluate ideas (following day)
     * Same group of people, use the ideas taken in the previous session
     * Evaluate each idea and dig deeper (refine)
     * Associate or merge ideas
     * Select a winning idea

#### JAD

* Objective: establish workgroups and try to reach a consensus between user needs and the services to produce
* Procedure: few well-prepared long meeting
* In each session we elaborate easy to understand models with diagrams and at the end of the sessions the participants must approve their model
* Roles:
  * Moderator: wide knowledge of the methodology, must guide the meeting
  * Promotor: the person that wants the development to be done
  * Project chief: responsible for the implantation of the project
  * Modeling specialist: responsible for making the models during the session
  * Developers: ensure that the models are accurate and meet the requirements
  * Users: responsible for defining the requirements of the system and validate them
* Phases:
  1. Opening: prepare material, select participants, place and time
  2. Development: identify project outputs and agreeing on models
  3. Closing: validate and generate products

### Cognitive

Set of techniques originally developed fo the acquisition of knowledge destined to knowledge-based systems.

#### Protocol analysis

* Procedure: Analyse an expert while he explains how he do his job.
* Pros: good to reveal problems with existing system
* Cons: centers only in the execution of the job and leaves out the social aspects. Based on what he said not what he do
  
#### Card sorting

* Procedure: ask stake holders to group cards, each card has a name of a domain entity. After that ask them to explain why they choose this groups
* Useful for knowledge classification but requires a knowledge of the different domain entities

#### Laddering

Try to create a tree of concepts from a main concept. The activity is guided by questions.

### Contextual

* Ethnographic methods (observe participants): analyse how the participants works watching a video and extract a list of improvements


### Model driven

This techniques uses a specific model of the type of information that we want to capture and use this model to guide the capture process.

#### Scenes

Examples of interaction scenes. The most common type of scene are the use cases.

* Must include
  * Description of the starting point
  * Description of a normal flow
  * Description of what can go wrong
  * Inform about any other parallel activity
  * Description of the end of the scene

Example:

* System: ask a client his password
* Client: introduces the password using the keyboard
* System: checks if the password is valid
* System: accepts the operation

### Prototyping

Tool for clarifying poor-defined requirements. Works for capturing and validating requirements.

> I don't know exactly what I want but I will know when I see it.

* Useful scenarios
  * Areas of an application poor-defined
  * Complex apps
  * Need for evaluating the impact of a system
* When to use it
  * How the UI will look like
  * Performance models (what model performs better)
  * Evolutive prototyping (can change things fast)
* Main advantage: being built faster than an app
* Types:
  * Disposable (quick)
    * Starts with poor-defined parts and try to obtain more info about them or to simplify
    * Once verified you throw it away
    * Quick construction, without unneeded details
    * Useful for isolated parts and small bad-understood parts
    * Optimizes development time
  * Evolutive
    * Useful when requirements are well-stablish
    * Quick construction with more detail and quality
    * The latest prototype is preserved for doing future modifications
    * Serves for obtaining a solid base of the final product
    * Easy to change during the development process
    * Cons: the iterative model favors poor design and architecture (complex systems less scalable and hard to maintain)
  * Operational
    * Only for well-stablish requirements
    * Outputs a product that the user can test
    * The user can propose changes or unneeded features
    * Useful for obtaining real feedback of the product and how the user will use it

### Other

#### Reverse engineer

* Requires an existing system with or without documentation.
* Cons: doesn't reflect the information update, information overdetailed (low level)

#### Reuse

* Requires an existing system
* We must define what should be reused
* Favors quality and productivity but isn't always easy to achieve that reuse

## Requirements analysis

Objectives of this activity:

* Detect and solve conflicts between requirements
* Discover the limits of the software and how it should interact with his environment
* Elaborate the requirements of the system for the future obtention of the software requirements

### Requirement analysis tasks

#### Classification

Depending on the nature of the project its requirements can be classified by different criteria:

* Funcional vs non-functional
* Origin: high level vs low level
* Product vs process
* Priority
* Scope
  * Components or pieced affected
  * Some non-functional requirements have a global scope
* Volatile vs stable

#### Conceptual modeling

Looks for the understanding of the problem before initializing the solutions design

Main modeling techniques:

* Use cases
* Data flow diagrams (DFD)
* State machines
* Event diagrams
* User interaction diagrams
* Object and data modeling

#### Localization

Consists of assigning the responsibility of fulfilling a requirement to a component. Requires a architectural design of the software (for the components).

Once assigned to components is possible to realize a more detailed analysis of each of them to discover new requirements of his interaction among them.

#### Negotiation

AKA conflict resolution.

* Solve problems:
  * When 2 participants require incompatible features among them
  * Between requirements and resources
  * Between funcional and non-functional requirements
* All decisions must be consensus based
* Have to be done also in the validation phase of the process
* Steps to solve a conflict
  1. Information: explain the nature of the problem
  2. Debate: each participant exposes how the problem can be solved
  3. Resolution: agreement in top of the actions that affect each requirement

### Conceptual modeling