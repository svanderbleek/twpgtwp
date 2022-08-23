# twpgtwp

The Working Programmer's Guide To Working Programs


## Soup

Nail: A Practical Interface Generator for Data Formats
Sections are Types, Linking is Policy: Using the Loader Format for Expressing Programmer Intent
Work-in-Progress: Towards a Platform to Compare Binary Parser Generators
PROTECTING SYSTEMS FROM EXPLOITS USING LANGUAGE-THEORETIC SECURITY
‘Weird Machine’ Patterns
Automated Attacker Synthesis for Distributed Protocols
“Weird Machines” in ELF: A Spotlight on the Underappreciated Metadata
How the ELF Ruined Christmas
Bootstrapping Trust in a “Trusted” Virtualized Platform
A Logic for Secure Stratified Systems and its Application to Containerized Systems
Automatic extraction of x86 formal semantics from its natural language description
DSV: Disassembly Soundness Validation withoutAssuming a Ground Truth
TYPES FOR THE CHAIN OF TRUST: NO (LOADER) WRITE LEFT BEHIND
BARF: A multiplatform open source Binary Analysis and Reverse engineering Framework
Evaluation of the Executional Power in Windows using Return Oriented Programming
An Optimized Intermediate Representation for Binary Rewriting at Runtime

## Feasability Study

Scenario: You are given an arbitrary computation device with input and output capabilities. You must boostrap a productive IDE for educational and exploratory programming.

## Methodology
### Stages

## Tools

What is given by the system we intend to develop on? How can we organize and utilize what we have as a starting point?

* https://github.com/jart/bestline

### Read
### Print
### Loop
### Eval
### Instructions
### Metrics

## Intro

Change your thinking, change your soul.

We never got mind bicycles. So let's learn to build them!

The title means more than just making programs that work, it also means working out programs, by whatever means available.

The goal is to create a verified software stack that is well-motivated and explorable. We want to not abstract from system details but to represent them in a logic where we can reason about them. This means being able to speak about things as diverse as device drivers, memory layouts, processing units and registers. We will scaffold our system in a way that it can be built on any computational substrate as a self describing operating system that provides facilities for extension.

Rather than concerning ourselves with what is the ideal theory for this work we will build things in a way that let us parametize the theory, like Dedukti's notion of "calculus modulo in which many theories and logics can be expressed".

Here is an example. Let us try and write a basic applicative language, just function applications, of single arguments with no environments. Then we observe generated code and see how the machine is doing function application. Then we optimize with abstract machines mapped to our computing environment and observe the wins and losses along the way. We prove meta theorems about our system and build tooling to allow us to do this from within our system thus creating a verified stack and sound meta theory.

Think of yourself as given some arbitrary computing device with whatever capabilities. You want to bootstrap a computing environment on top of this to learn and optimize. A concrete goal is being able to self study mathematics and computer science using the system you will construct.

So let's get started.

## Building a SLED

So you can go places.

If you're willing to be crazy you can get a lot done.

## Snippets

> parser generators have become standard compiler technology (AHO et al., 2006, p. 287) and table-driven back end descriptors are not unusual in modern compiler infrastructures (GOLDBERG, 2017, p. 28)

>  It is now common practice to develop portable software for abstract (as opposed to real) machines, which are usually defined in a written specification and may exist only as Virtual Machines (VMs) – machine emulation programs implemented on top of the actual computer (CALVERT, 2015, p. 11)

> Hennessy & Patterson (2019) predict a “Cambrian explosion” of domainspecific computer architectures in the next decade. They point out the need for domain-specific programming languages and related compiler technology. This was also evident to Lattner et al. (2021), who developed MLIR as a compiler infrastructure better suited to build domain-specific compilers in the upcoming “golden age” of computer architecture, hardware accelerators, programming languages and optimizing compilers 

## Topics

### Binary
#### Bincodes
#### Logicodes
#### Interpolation based bintree

### Hacks
#### Mismorphisms
#### Gadgets
#### Blocks
#### Discovery
#### Analysis
#### Micro-gadgets

### Text
#### Poplar
#### Editing by Example
#### Sequitur
#### Grammar-based compression

#### CollapseOS
#### Boostrapping Hex
#### Unary languages recognized by two-way one-counter automata
#### Gadgets for Return Oriented Programming
#### Analyzing Binary Memory In Executables
#### Grammar-Based Codes: A New Class of Universal Lossless Source Codes

### ISA
#### SLED
### URISC
### Subleq
#### SSL
#### Sail
#### Lem

### OS
#### TEE
#### Memory
##### Registers
##### RAM
##### Pointers
#### Capabilities
#### Singularity OS
#### Oxide (https://hubris.oxide.computer/reference/)

### Lambda Calculus
#### Pointfree
#### Godelization
#### Self-interpreter

### Abstract Machines
#### Complexity
#### SECD
#### CAM
#### WAM
#### MAM
#### KAM
#### CHAM
#### SMC

### Compilers

### Logics and Types
#### FOL
#### HOL
#### Hoare 
#### Separation 
#### Linear
#### Modal
#### Comonad
#### Graded
#### Uniqueness
#### Session 
#### Indexed
#### Bunched 
#### Dependent
