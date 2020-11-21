# Basic concepts of RE

## Requirement concept

### Definitions

* Requirement: Condition that must be fulfilled by a system in order to satisfy a contract, standard, specification or another formal document.
* Requirement engineering: activities of the software development process related to the management and definition of requirement for new and actual systems.
* Software requirement specification (SRS): formal document of system requirements.

A requirement is **not**:

* A design, implementation or testing detail
* Information relative to project planning
* Necessities of the project

### Objective of requirements

* Reach an agreement between clients, developers and user in top of the one we can start producing
* Provide a base for software designing
* Serve as a support for verification and validation of developed products
* Guide potential clients about the definition of our product


### Characteristics of the requirements

Requirements must be:

* Correct
* Consistent: you must be able to satisfy two requirements simultaneously
* Complete: must take into account all possible states, changes, inputs...
* Realistic: can be done
* Needed: must solve the problem of a client
* Verifiable: tests can be prepared in order to check that the requirement is satisfied
* Trackable: you can track each system feature to a requirement

### Common problems

* Inaccuracy: define ambiguous requirements
* Difference between requirement an design: the requirement explain **what** should be done and the design explain **how** it should be done.

## Types of requirements

There's a lot of forms for classifying requirement, depending of its:

* Nature (most used): functional or non-functional
* Level of abstraction: user or system

### Functional / non-functional

* Functional: declaration of the services that the system must provide or descriptions of how this services must be done.
  * Domain: functional requirements that derive of the features of the applications domains
* Non-functional: restrict the system features and specify technical considerations that must be taken into account.
  ![Types of non-functional requirements](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fs-media-cache-ak0.pinimg.com%2Foriginals%2F22%2F99%2F2f%2F22992f0f0e138a49738ae450ccae2b3e.jpg&f=1&nofb=1)

Examples: 

* Functional: The user must be capable of searching between all the products of the web
* Non-functional: All the passwords must be encrypted by an MD5 algorithm

### User / System / Software

* User: user needs expressed in natural language
* System: features that the system must provide
* Software: software requirements