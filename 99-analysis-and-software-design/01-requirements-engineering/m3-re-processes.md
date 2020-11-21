# Requirements engineering processes

## RE processes

### What is a RE process?

We can define it as the obtention, analysis, specification and validation of the document of system requirements.

This RE process allow us to take an existing information system + stakeholder needs + standards + regulations/normative and output a document with requirements + system specifications + models of the system.

### Process models

There are different models regarding to RE process.

Comparison between models:

* It's an iterative process
* It's hard to establish the limit between activities
* The products of the process aren't clearly defined

General points:

* Viability study
* Requirements development
  * Education (extraction and capture)
  * Analysis
  * Specification
  * Validation
* Requirements management

#### According to Loucopoulos and Karakostas

Main ideas

* Education: understanding of the problem
* Specification: description of the problem
* Validation: agreement in top of the nature of the problem

#### According to Klaus Pohl

* No specified order
* Iterative process
* Normal steps
  * Capture requirements
  * Negotiate with stakeholders
  * Specify and document the requirement
  * Validate and verify

#### According to Kotonya and Sommerville

* Iterative, can be done thought all the development process
* 4 main activities + 1
  * Education: capture, discovery, acquisition
  * Analysis (and negotiation)
  * Specification (and documentation)
  * Validation
  * Requirements management: manage new changes, maintenance and traceability of requirements

#### According to Kotonya and Sommerville (spiral)

* Iterative model
* Steps
  1. Education
  2. Analysis and negotiation
  3. Specification
  4. Validation
  5. Management (during all the process): manage the incremental obtention and requirement changes

### Common problems

We may have problems during the process if:

* The process is large and expensive
* Lack of time or other resources
* Complex requirement document
* Work lost by a issues with the requirements
* Users doesn't use some features of the system
* Lots of changes once the product is delivered
* Take so much time reach an agreement when changes are proposed

## Development processes

### Involved people

Different stakeholders or people involved in:

* Users: the ones who use the system
* Clients: software owners or the targeted market
* Market analysts: identify what the market demands
* Regulators: ensure the fulfillment of the established laws and norms
* Software engineers

Things to be aware of:

* These involved people may have contradictory interests
* We need to negotiate a balance between requirements, budget and planning
* The software engineers must be able to clarify the needs of the client
* All the roles work together to specify the desires of the client

Products of the process (outputs):

* Viability report
* Agreed requirements
* System specification
* System models
* Prototype

### Activities of the process

#### A0: Viability study

* Objectives:
  * Acknowledge the organization objectives
  * Evaluate if the technology asked is available (can be done with out current stack?)
  * Analyze is can be integrated with another systems of the organization
* Is an optional phase
* Inputs:
  * Preliminar business requirements
  * Brief description of the system
  * Contribution of the system the business process (is worth developing?)
* Output: Viability report. Should we continue with this system?
* Duration: 2-3 weeks max
* Sources of information: department managers, SW engineers, experts in the technology, final users...

#### A1: Capture and requirement analysis

* Requirements:
  * The engineer must learn where the requirements came from and how to collect them
* Objectives:
  * Identify stakeholders (involved people)
  * Establish relations between the development team and the client
  * Detect and solve conflicts between requirements
  * Discover the SW limitations and how it should interact with its environment
* Some requirement analysis techniques: checklists, interaction matrixes...

#### A2: Requirements specification

* Objective: elaborate a SRS (software requirements specification). This document is the base for the agreement between clients, developers or providers about what the product will do.
* Standard: [IEEE Std 830](https://standards.ieee.org/standard/830-1998.html) (recommended practices)

#### A3: Requirements validation

* Objectives:
  * Ensure that the SW understands the requirements.
  * Ensure that the SRS document meets the standards, is comprehensive, consistent and complete.
* Inputs:
  * SRS document
  * Standards
  * Organization knowledge
* Outputs:
  * List of issues
  * List of actions
* Some validation techniques:
  * Reviews
  * Prototyping
  * Models validation
  * Acceptance tests

## Process of managing requirements

The requirements can change because of:

* Changes in the strategy or business priorities
* Technology changes
* Law or regulation changes

Requirement management consist of managing:

* Changes in the agreed requirements
* Relations between requirements
* Dependencies between SRS document and another documents
