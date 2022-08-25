# twpgtwp

The Working Programmer's Guide To Working Programs


## Feasability Study

Scenario: You are given an arbitrary computation device with input and output capabilities. You must boostrap a productive IDE for educational and exploratory programming.

The goal is not to teach contemporary bare metal practices, but to approach any future or past system with proven methodology for bootstrapping a development environment on hardware.

### Prior Work

* Taming the Tarpit https://mikeinnes.io/2017/09/13/brainforth
* Crawling out of the turing tarpit http://rolfwr.net/tarpit
* https://bootstrapping.miraheze.org/wiki/Main_Page
* https://wiki.osdev.org/Main_Page
* https://en.wikipedia.org/wiki/Crt0
* http://stephane.ducasse.free.fr/TopicsVirtual%20Machines.html
* https://www.agner.org/optimize/
* https://github.com/scanlime/metalkit
* https://futhark-lang.org/
* https://theartofmachinery.com/2017/06/04/what_is_the_d_runtime.html
* http://www.ganssle.com/tem-back.htm
* wizard code https://web.archive.org/web/20170712195930/http://vendu.twodots.nl/files/wizardcode4.pdf
* https://belkarx.github.io/posts/finished/Low-levelAtypical%20Technology%20Fundamentals.html
* https://github.com/LowLevelJam/LLJam0001/tree/main/submissions/via_c3_ais_asm
* https://handmade.network/
* https://github.com/area9innovation/wase
* https://terralang.org/
* http://umanovskis.se/files/arm-baremetal-ebook.pdf
* https://www.atarimagazines.com/compute/issue154/60_Where_hardware_meets.php
* https://benhoyt.com/writings/mugo/
* http://wiki.c2.com/?RethinkingCompilerDesign
* http://wiki.c2.com/?SynthesisOs
* https://www.coreboot.org/
* http://menuetos.net/

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

> From the “weird machine” point of view, every input is a program, so long as it causes state changes in the system that consumes it. This view of input is, of course, standard in computation theory: a Turing Machine in of itself merely holds potential computing power until it presented with some input to drive it.

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
Survey of methods for automated code-reuse exploit generation
Poster: Challenges and next steps in binary program analysis with angr
A framework for automated architecture-independent gadget search
Return-oriented programming on a resource constrained device
[m]allotROPism: a metamorphic engine for malicious software variation development
Reliable computing with ultra-reduced instruction set co-processors
Synthesizable-from-C Embedded Processor Based on MIPS-ISA and OISC
An Exploration Platform for Microcoded RISC-V Cores leveraging the One Instruction Set Computer Principle
A Multi-One Instruction Set Computer for Microcontroller Applications
Hybrid Analog Signal-Based Models of Computation
Review on HEROIC Framework: Homomorphically EncRypted One Instruction Computer
Design Space Exploration of Flexible Heterogeneous Dual-Core Processor using MIPS and Extended OISC: A Case Study
Low-complexity Two Instruction Set Computer architecture for sensor network using Skipjack encryption
Reliable Computing with Ultra-Reduced Instruction Set Co-processors
Everybody be cool, this is a roppery!
Overview of software dependability computing techniques from instruction set architecture's viewpoint
One-instruction set computer-based multicore processors for energy-efficient streaming data processing
Simple instruction-set computer for area and energy-sensitive IoT edge devices
Revisiting simple and energy efficient embedded processor designs toward the edge computing
AISC: Approximate Instruction Set Computer
An Analysis of x86 Single-Instruction Compiling as an Obfuscation Technique
Regular Expression Order-Sorted Unification and Matching
BAP: A Binary Analysis Platform
SAIL: Static Analysis Intermediate Language with a Two-level Representation.
Tortoise: Interactive System Configuration Repair
Very simple Chaitin machines for concrete AIT
Computable model discovery and high-level-programming approximations to algorithmic complexity
Algorithmic Information Dynamics of Cellular Automata
MATAR: A Performance Portability and Productivity Implementation of Data-Oriented Design with Kokkos
API as Curriculum: Designing High-Level API Affordances as Instructional Scaffolds
Retroactive data structures
Programming Languages For Interactive Computing
Bootstrap-Based Language Development: Turning an existing VM into a polyglot VM
A Bootstrapping Infrastructure to Build and Extend Pharo-Like Languages
Bridging the Gap between Machine and Language using First-Class Building Blocks
IDE-Independent Program Comprehension Tools via Source File Overwriting
Supporting Source Code Annotations with Metadata-Aware Development Environment
A DSL for Resource Checking Using FSA-Driven Symbolic Execution
The IDE as a Scriptable Information System
Benzo: Reflective Glue for Low-level Programming
Sista: a Metacircular Architecture for Runtime Optimisation Persistence
A Golden Age of Hardware Description Languages
Tydi an open specification for complex data structures over hardware streams
Dataflow Hardware Design for Big Data Acceleration Using Typed Interfaces
fault: A Python Embedded Domain-Specific Language for Metaprogramming Portable Hardware Verification Components
Wire sorts: A language abstraction for safe hardware composition
Programming Language Techniques for Improving ISA and HDL Design
Twine: A Chisel Extension for Component-Level Heterogeneous Design
Reticle: A Virtual Machine for Programming Modern FPGAs
Implicit State Machines
SPIRAL: Extreme performance portability
Stateful dataflow multigraphs: A data-centric model for performance portability on heterogeneous architectures
PALMED: Throughput Characterization for Superscalar Architectures - Extended Version
LEGION: PROGRAMMING DISTRIBUTED HETEROGENEOUS ARCHITECTURES WITH LOGICAL REGIONS
A Bare Machine Tool to Learn System Internals in Computer Science Education
A Bare PC Text Based Browser
An API for Bare Machine Computing Applications
Bit Level Types
An embedded language for programming protocol stacks in embedded systems
the next 700 data description languages
type systems for system types
A Calculus for Describing Ad Hoc Data Formats
Discovering Nontrivial and Functional Behavior in Register Machines
Superoptimizer: A look at the smallest program
Synthesis: An Efficient Implementation of Fundamental Operating System Services
Instruction Selection Principles, Methods, and Applications
Automatic Derivation of Compiler Machine Descriptions
VRASED: A Verified Hardware/Software Co-Design for Remote Attestation
APEX: A Verified Architecture for Proofs of Execution on Remote Devices under Full Software Compromise
How Low Can You Go? Recommendations for Hardware-Supported Minimal TCB Code Execution 

## Binary Analysis

* https://github.com/angr/angr
* https://github.com/BinaryAnalysisPlatform/bap
* https://github.com/binsec/binsec
* https://github.com/google/binnavi
* https://github.com/hotelzululima/insight
* https://github.com/jkinder/jakstab
* https://github.com/cea-sec/miasm
* https://github.com/radareorg/radare2
* https://github.com/revng/revng
* https://github.com/B2R2-org/B2R2
* http://bitblaze.cs.berkeley.edu/


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

### Language
#### Applicative
#### Concatative
#### Lambda Calculus
##### Pointfree
##### Godelization
##### Self-interpreter

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
