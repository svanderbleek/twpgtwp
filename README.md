# twpgtwp

The Working Programmer's Guide To Working Programs

## Standing on Shoulders

I found some good ones. As a synthesizer I combine formal methods, algorithmic information theory, systems programming, hobbyist computing, etc. Kill me please.

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
* https://www.usenix.org/legacy/event/wiov08/tech/full_papers/xia/xia_html/
* https://sqlite.org/src/doc/trunk/doc/lemon.html
* https://github.com/udem-dlteam/ribbit
* https://github.com/cksystemsteaching/selfie
* https://emeryberger.com/teaching/grad-systems/
* https://homepage.cs.uiowa.edu/~dwjones/syssoft/notes/
* http://cap-lore.com/Languages/lambda/new.html#claim
* http://tinlizzie.org/ometa/
* https://github.com/robertpfeiffer/cola
* http://canonical.org/~kragen/binary-relations
* https://github.com/michaelchisari/scrwl
* https://benhoyt.com/writings/hash-table-in-c/
* https://pages.cs.wisc.edu/~remzi/OSTEP/
* https://www.inkandswitch.com/
* https://2020.programming-conference.org/home/salon-2020
* https://www.programmer-books.com/wp-content/uploads/2019/04/Low-Level-Programming.pdf
* http://twofishergourmetseafood.com/
* https://github.com/akkartik/mu
* https://feenk.com/
* https://instadeq.com/blog/posts/no-code-history-sketchpad-a-man-machine-graphical-communication-system-1963/
* https://www.drmaciver.com/2016/05/the-derivative-as-an-alternative-minimal-deterministic-automaton/
* http://arclanguage.org/
* https://100r.co/site/nasu.html
* https://hundredrabbits.itch.io/left
* https://100r.co/site/uxn.html
* https://wiki.xxiivv.com/site/potato.html
* https://permacomputing.net/
* https://sr.ht/~bctnry/chifir/
* http://sw.ccs.bcs.org/CAMiLEON/dh/ep5.html
* https://rosettaproject.org/disk/technology/
* https://github.com/civboot/civboot
* https://esoteric.codes/blog/a-programming-language-with-only-one-command-and
* https://cs.stanford.edu/people/eroberts/courses/soco/projects/risc/risccisc/
* https://os-projects.eu/dawn-os
* http://solarprotocol.net/
* https://web.archive.org/web/20010625015518/http://www.nla.gov.au/padi/topics/19.html
* https://en.wikipedia.org/wiki/CARDboard_Illustrative_Aid_to_Computation
* https://en.wikipedia.org/wiki/Little_man_computer
* http://www.yorku.ca/sychen/research/LMC/index.html
* http://elearning.algonquincollege.com/coursemat/dat2343/lectures.f03/12-LMC.htm
* https://www.cs.drexel.edu/~bls96/museum/cardiac.html
* http://www.kaleberg.com/software/cardiac/
* https://wimvanderbauwhede.github.io/articles/frugal-computing/
* https://damaged.bleu255.com/Salvage_Computing/
* https://openresearch.lsbu.ac.uk/item/8xwq2
* https://computingwithinlimits.org/2022/
* https://damaged.bleu255.com/Collapse_Informatics/
* https://damaged.bleu255.com/Convivial_Computing/
* https://damaged.bleu255.com/Low-Tech/
* https://damaged.bleu255.com/Small_Technology/
* https://damaged.bleu255.com/Liberatory_Technology/
* https://suckless.org/
* https://2022.programming-conference.org/home/MoreVMs-2022
* https://2022.programming-conference.org/home/salon-2022
* https://boxer-project.github.io/
* http://homepage.cs.uiowa.edu/~dwjones/syssoft/notes/01intro.html
* https://webkit.org/docs/b3/
* https://www.crashonline.org.uk/38/beginner.htm
* http://www.chaos.org.uk/~pdh/homilies/linux.htm
* http://www.searle.wales/
* https://github.com/xinu-os/xinu
* http://rbjones.com/rbjpub/rbjcv/papers/wp32.htm
* https://wiki.xxiivv.com/site/paper_computing.html
* https://highlowtech.org/
* https://esolangs.org/wiki/Dependently_Typed_Binary_Lambda_Calculus
* https://github.com/AHartNtkn/Dependent-Binary-Lambda-Calculus
* https://csvoss.com/circuit-notation-lambda-calculus
* http://www.golfscript.com/lam/
* https://tanami.org/archive/Most%20functional%20ioccc%20binary%20lambda%20calculus.html
* https://www.fstar-lang.org/tutorial/book/part2/part2.html
* http://www.willdonnelly.net/blog/2020-10-25-compact-church-data/
* http://unikernel.org/projects/
* https://github.com/rumpkernel/rumprun
* https://genode.org/documentation/genode-foundations/19.05/introduction/index.html
* https://wiki.xxiivv.com/site/devlog.html
* https://dirk-kutscher.info/publications/iceflow/
* https://github.com/chessai/theseus
* https://suif.stanford.edu/dragonbook/lecture-notes/Stanford-CS143/15-Runtime-Environments.pdf
* http://the-knowledge.org/en-gb/
* https://thesurvivalmom.com/wp-content/uploads/2015/03/Beyond-Collapse.pdf
* https://frida.re/
* https://github.com/NationalSecurityAgency/ghidra
* http://lock.cmpxchg8b.com/symbols.html
* http://web.archive.org/web/20061108010907/http://www.rano.org/bcompiler.html
* https://web.archive.org/web/20081120040312/http://lists.canonical.org/pipermail/kragen-hacks/2007-February/000450.html
* https://web.archive.org/web/20090106212556/http://lists.canonical.org/pipermail/kragen-hacks/2007-February/000449.html
* http://www.andreadrian.de/tbng/
* https://web.archive.org/web/20161022180354/http://vpri.org/html/work/ifnct.htm
* https://github.com/harc/ohm
* https://www.piumarta.com/software/maru/maru-2.4/
* http://www.psirp.org/

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
Lightweight Bare-metal Stateful Firewall
OSLO: Improving the security of Trusted Computing 
Tiny-CFA: A Minimalistic Approach for Control-Flow Attestation Using Verified Proofs of Execution
DIALED: Data Integrity Attestation for Low-end Embedded Devices
BYOTEE: Towards Building Your Own Trusted Execution Environments Using FPGA
Mind the Gap: Studying the Insecurity of Provably Secure Embedded Trusted Execution Architectures
GAROTA: Generalized Active Root-Of-Trust Architecture
ASAP: Reconciling Asynchronous Real-Time Operations and Proofs of Execution in Simple Embedded Systems
DITES: A Lightweight and Flexible Dual-Core Isolated Trusted Execution SoC Based on RISC-V
TR-FSM: Transition-based Reconfigurable Finite State Machine
The Pintos Instructional Operating System Kernel
BabyOS: a fresh start
MiniOS: An Instructional Platform for Teaching Operating Systems Projects
A Scalable Operating System Experiment Platform Supporting Learning Behavior Analysis
Fast Privileged Function Calls
Direct Inter-Process Communication (dIPC): Repurposing the CODOMs Architecture to Accelerate IPC
Packrat Parsing:
Simple, Powerful, Lazy, Linear Time
Rewrite rules for the Disciplined Disciple Compiler
The computational origin of representation
OPEN-ENDED EVOLUTION AS AN EMERGENT SELF-ORGANIZING SEARCH PROCESS
Numeral Systems Across Languages Support Efficient Communication
Let's talk (efficiently) about us: Person systems achieve near-optimal compression
Putting Prototypes in Place
Inference and the structure of concepts
The mental representation of universal quantifiers
Code generation for a one register machine
Introducing conviviality as a new paradigm for interactions among IT objects
STEPS Toward The Reinvention of Programming
Bicycles for the mind have to be see-through
UVC: A Universal Virtual Computer for Long-term Preservation of Digital Information
VMKit: a Substrate for Managed Runtime Environments
Snippets: Taking the High Road to a Low Level
Z-Rays: Divide Arrays and Conquer Speed and Flexibility
Continuously Measuring Critical Section Pressure with the Free-Lunch Profiler
Draining the Swamp: Micro Virtual Machines as Solid Foundation for Language Development
On-Stack Replacement, Distilled
Scalable Concolic Testing of RTL Models
Software/Hardware Co-Verification for Custom Instruction Set Processors
Specification-Driven Conformance Checking for Virtual/Silicon Devices using Mutation Testing
A Novel Concolic Execution Approach on Embedded Device
Embedded Fuzzing: a Review of Challenges, Tools, and Solutions
Hop, Skip, & Jump Practical On-Stack Replacement for a Cross-Platform Language-Neutral VM
On-Stack Replacement for Program Generators and Source-to-Source Compilers
Micro Virtual Machines: A Solid Foundation for Managed Language Implementation
A Foundation for the Development of Programming Languages for Real-Time Systems
Designing a Low-Level Virtual Machine for Implementing Real-Time Managed Languages
An Efficient Implementation of a Micro Virtual Machine
Lowcode extending Pharo with C Types to Improve Performance
Garbage Collection and Efficiency in Dynamic Metacircular Runtimes
Extending an In-Browser C Interpreter With an Abstracted Model of the Memory 
Spreadsheets as Notational Environment for Paper Weaving
Electronic Popables: Exploring Paper-Based Computing through an Interactive Pop-Up Book 
Microcontrollers as material: crafting circuits with paper, conductive ink, electronic components, and an "untoolkit"
Programming the shape-shifting of flat soft matter
Mechanical metamaterials: a state of the art
Hybrid Paper-Digital Interfaces: A Systematic Literature Review
SYNERGY: Rethinking Secure-Memory Design for Error-Correcting Memories
The complexity of small universal Turing machines: A survey
A Simple and Efficient Universal Reversible Turing Machine
Concise Representations of Reversible Automata
Energy-Efficient Algorithms
Toward an Energy Efficient Language and Compiler for (Partially) Reversible Algorithms
The power of being explicit: demystifying work, heat, and free energy in the physics of computation
Information Effects
Theseus: A High Level Language for Reversible Computing
Starting from a Clean Slate: Creating a Top-down Parseable Runtime
Staged computation: the technique you didn’t know you were using
printr: Exploring the Potential of Paper-based Tools in Low-resource Settings
PaperWeb: Paper-triggered Web Interactions
CAM: A Mobile Interaction Framework for Digitizing Paper Processes in the Developing World
DE S I G N I N G I N T E R A C T I O N S T H AT C O M B I NE P E N , PAP E R , A N D C O M P U T E R
Computing with words and decision making
Engineering Definitional Interpreters
Definitional Interpreters for Higher-Order Programming Languages
Definitional Interpreters Revisted
BinRec: Dynamic Binary Lifting and Recompilation
Optimization of dynamic languages using hierarchical layering of virtual machines
A Data-Oriented (and Beyond) Network Architecture
An association-based model of dynamic behaviour

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
