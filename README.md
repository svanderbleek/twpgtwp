# twpgtwp

The Working Programmer's Guide To Working Programs

## Vision

Truly portable computation.

## Methodology

From boot develop a system for exploratory computation. The idea is to rebuild computer science from scratch. The winning technique will enable the most productive bootstrapping. An approaite system enables arbitrary hardware, from micro controllers to pen and paper. Computations are resumable and shareable.

## Feasability Study

Scenario: You are given an arbitrary computation device with input and output capabilities. You must boostrap a productive IDE for educational and exploratory programming.

The goal is not to teach contemporary bare machine practices, but to approach any future or past system with proven methodology for bootstrapping a development environment on hardware.

## Plan

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
* https://legacy.python.org/workshops/1998-11/proceedings/papers/aycock-little/aycock-little.html
* https://research.swtch.com/yaccalive
* http://www.cofault.com/2022/08/3-lisp-infinite-tower-of-meta-circular.html
* https://petsc.org/release/
* https://www.odata.org/
* https://dortania.github.io/OpenCore-Legacy-Patcher/START.html
* https://statebox.org/
* http://borisvassilev.github.io/lir/
* http://web.cecs.pdx.edu/~sheard/Omega/index.html
* http://manticore.cs.uchicago.edu/
* https://plancomps.csle.cs.rhul.ac.uk/
* https://uoycs-plasma.github.io/GP2/
* https://github.com/IMP1/blossom
* https://zephyrproject.org/
* https://fabiensanglard.net/another_world_polygons/
* https://sbtcvm.blogspot.com/
* http://users.atw.hu/gerigeri/DawnOS/index.html
* https://breandan.net/2020/06/30/graph-computation/
* https://davidbieber.com/post/2019-05-10-weisfeiler-lehman-isomorphism-test/
* https://www.math3ma.com/blog/matrices-probability-graphs
* http://logic.stanford.edu/kif/Hypertext/kif-manual.html
* https://web.eecs.umich.edu/gasm/
* https://luxxxlucy.github.io/projects/2020_terpret/terpret.html
* https://pvk.ca/Blog/2022/07/11/plan-b-for-uuids-double-aes-128/
* https://web.archive.org/web/20170825000213/http://www.cs.toronto.edu/XPL/
* https://web.archive.org/web/20170814163743/http://www.gtoal.com/languages/bcpl/amiga/bcpl/booting.txt
* http://www.homebrewcpu.com/
* https://github.com/magmide/magmide
* https://ollef.github.io/blog/posts/query-based-compilers.html
* https://linuxfromscratch.org/
* https://web.archive.org/web/20210225214156/http://mancoosi.org/software/#index2h1
* https://web.archive.org/web/20140117075044/https://gitorious.org/debian-bootstrap/botch/source/05f8d246be9ea5c6e059e27eb16a35191dca99de:
* https://gogs.librecmc.org/RISCI_ATOM/Stage0/src/master/README.org
* https://www.gnu.org/software/mes/
* https://github.com/digama0/mm0
* http://www.ulisp.com/
* http://cap-lore.com/CapTheory/upenn/Gnosis/Gnosis.html
* https://github.com/firesim/FireMarshal
* https://github.com/pulp-platform/bender
* https://www.gem5.org/
* https://github.com/litex-hub/linux-on-litex-rocket
* https://paperswithcode.com/paper/codeapeel-an-integrated-and-layered-learning
* https://github.com/bbchallenge/bbchallenge-proofs
* https://caravel-harness.readthedocs.io/en/latest/getting-started.html
* https://uniformal.github.io/
* http://fitelson.org/maclogic.htm
* http://gallium.inria.fr/~fpottier/menhir/
* https://github.com/securesystemslab/pkru-safe
* http://mbeddr.com/
* https://halium.org/
* https://github.com/GrapheneOS/hardened_malloc
* https://source.android.com/docs/security/verifiedboot
* https://attestation.app/about
* https://reprap.org/wiki/RepRap
* http://cba.mit.edu/
* https://www.haystack-mtn.org/haystack-labs
* https://www.fablabs.io/
* https://wiki.opensourceecology.org/wiki/Open_Source_Computer_Construction_Set
* http://parallel.princeton.edu/openpiton/
* https://gcc.gnu.org/onlinedocs/gccint/RTL.html
* https://www.sqlite.org/limits.html
* https://cs.lmu.edu/~ray/notes/ir/
* https://github.com/YosysHQ/yosys
* https://www.verific.com/
* https://github.com/chipsalliance/firrtl
* https://github.com/Nic30/hwt
* https://github.com/phanrahan/magma
* https://github.com/myhdl/myhdl
* https://github.com/SpinalHDL/SpinalHDL
* https://github.com/PyHDI/veriloggen
* https://github.com/rdaly525/coreir
* https://github.com/kevinkim06/Halide-FIRRTL
* https://eda.sw.siemens.com/en-US/ic/ic-design/high-level-synthesis-and-verification-platform/
* https://halide-lang.org/
* https://github.com/504ensicsLabs/LiME
* https://melt.cs.umn.edu/
* http://www.isola-conference.org/
* https://www.jetbrains.com/help/mps/shapes-an-introductory-mps-tutorial.html
* http://mbeddr.com/download.html#RequiredToolsAndVersions
* https://github.com/paulfitz/cosmicos

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

> Wherever you encounter a general-purpose computer system, you will find a chain of one or more dynamic loaders, the first of which is known as a bootloader. As a system pulls itself into a state of usefulness and readiness, a tree-shaped chain of loaders are invoked rooted by the kickoff bootloader, each loading one or more binary images some of which are themselves loaders, occasionally branching when multiple distinct processors need initialization. Loaders are the centerpiece of the chain of trust, but few have a deep understanding of the bootloading process and even fewer have developed a bootloader or a general-purpose loader from scratch. Loaders are similar to electricity in that they are ubiquitous, in a relatively transparent and seemingly-magical way, but folks will lunge for their pitchforks if they stop working. A dynamic loader’s primary objective is to breath life into a static and inanimate binary image so that it can takeover and execute on its own in whatever environment is setup for it by the loader

>  In the following years, the paradigm of Organic Computing was explored in a series of research projects, and in 2011, this work has been nicely summarized in the book Organic Computing, edited by Müller-Schloer et al. [49].Kramer et al. [50] proposed a two level monitoring approach to self-awareness. The low-level monitoring is based on counting events such as cache misses, fault occurrences, or performance counters. In principle, any event that can be counted can be subject to this mechanism. The monitor can be programmed during operation to associate any type of event with event-IDs allowing for flexibility with respect to the kind of events under observation. High-level monitoring uses the event counts for state classification to reflect relevant information about the systems performance and state. Since event grouping and limited event abstraction is possible, the resulting system can be considered rudimentarily self-aware

## Soup

* Nail: A Practical Interface Generator for Data Formats
* Sections are Types, Linking is Policy: Using the Loader Format for Expressing Programmer Intent
* Work-in-Progress: Towards a Platform to Compare Binary Parser Generators
* PROTECTING SYSTEMS FROM EXPLOITS USING LANGUAGE-THEORETIC SECURITY
* ‘Weird Machine’ Patterns
* Automated Attacker Synthesis for Distributed Protocols
* “Weird Machines” in ELF: A Spotlight on the Underappreciated Metadata
* How the ELF Ruined Christmas
* Bootstrapping Trust in a “Trusted” Virtualized Platform
* A Logic for Secure Stratified Systems and its Application to Containerized Systems
* Automatic extraction of x86 formal semantics from its natural language description
* DSV: Disassembly Soundness Validation withoutAssuming a Ground Truth
* TYPES FOR THE CHAIN OF TRUST: NO (LOADER) WRITE LEFT BEHIND
* Trust as a Programming Primitive
* BARF: A multiplatform open source Binary Analysis and Reverse engineering Framework
* Evaluation of the Executional Power in Windows using Return Oriented Programming
* An Optimized Intermediate Representation for Binary Rewriting at Runtime
* Survey of methods for automated code-reuse exploit generation
* Poster: Challenges and next steps in binary program analysis with angr
* A framework for automated architecture-independent gadget search
* Return-oriented programming on a resource constrained device
* [m]allotROPism: a metamorphic engine for malicious software variation development
* Reliable computing with ultra-reduced instruction set co-processors
* Synthesizable-from-C Embedded Processor Based on MIPS-ISA and OISC
* An Exploration Platform for Microcoded RISC-V Cores leveraging the One Instruction Set Computer Principle
* A Multi-One Instruction Set Computer for Microcontroller Applications
* Hybrid Analog Signal-Based Models of Computation
* Review on HEROIC Framework: Homomorphically EncRypted One Instruction Computer
* Design Space Exploration of Flexible Heterogeneous Dual-Core Processor using MIPS and Extended OISC: A Case Study
* Low-complexity Two Instruction Set Computer architecture for sensor network using Skipjack encryption
* Reliable Computing with Ultra-Reduced Instruction Set Co-processors
* Everybody be cool, this is a roppery!
* Overview of software dependability computing techniques from instruction set architecture's viewpoint
* One-instruction set computer-based multicore processors for energy-efficient streaming data processing
* Simple instruction-set computer for area and energy-sensitive IoT edge devices
* Revisiting simple and energy efficient embedded processor designs toward the edge computing
* AISC: Approximate Instruction Set Computer
* An Analysis of x86 Single-Instruction Compiling as an Obfuscation Technique
* Regular Expression Order-Sorted Unification and Matching
* BAP: A Binary Analysis Platform
* SAIL: Static Analysis Intermediate Language with a Two-level Representation.
* Tortoise: Interactive System Configuration Repair
* Very simple Chaitin machines for concrete AIT
* Computable model discovery and high-level-programming approximations to algorithmic complexity
* Algorithmic Information Dynamics of Cellular Automata
* MATAR: A Performance Portability and Productivity Implementation of Data-Oriented Design with Kokkos
* API as Curriculum: Designing High-Level API Affordances as Instructional Scaffolds
* Retroactive data structures
* Programming Languages For Interactive Computing
* Bootstrap-Based Language Development: Turning an existing VM into a polyglot VM
* A Bootstrapping Infrastructure to Build and Extend Pharo-Like Languages
* Bridging the Gap between Machine and Language using First-Class Building Blocks
* IDE-Independent Program Comprehension Tools via Source File Overwriting
* Supporting Source Code Annotations with Metadata-Aware Development Environment
* A DSL for Resource Checking Using FSA-Driven Symbolic Execution
* The IDE as a Scriptable Information System
* Benzo: Reflective Glue for Low-level Programming
* Sista: a Metacircular Architecture for Runtime Optimisation Persistence
* A Golden Age of Hardware Description Languages
* Tydi an open specification for complex data structures over hardware streams
* Dataflow Hardware Design for Big Data Acceleration Using Typed Interfaces
* fault: A Python Embedded Domain-Specific Language for Metaprogramming Portable Hardware Verification Components
* Wire sorts: A language abstraction for safe hardware composition
* Programming Language Techniques for Improving ISA and HDL Design
* Twine: A Chisel Extension for Component-Level Heterogeneous Design
* Reticle: A Virtual Machine for Programming Modern FPGAs
* Implicit State Machines
* SPIRAL: Extreme performance portability
* Stateful dataflow multigraphs: A data-centric model for performance portability on heterogeneous architectures
* PALMED: Throughput Characterization for Superscalar Architectures - Extended Version
* LEGION: PROGRAMMING DISTRIBUTED HETEROGENEOUS ARCHITECTURES WITH LOGICAL REGIONS
* A Bare Machine Tool to Learn System Internals in Computer Science Education
* A Bare PC Text Based Browser
* An API for Bare Machine Computing Applications
* Bit Level Types
* An embedded language for programming protocol stacks in embedded systems
* the next 700 data description languages
* type systems for system types
* A Calculus for Describing Ad Hoc Data Formats
* Discovering Nontrivial and Functional Behavior in Register Machines
* Superoptimizer: A look at the smallest program
* Synthesis: An Efficient Implementation of Fundamental Operating System Services
* Instruction Selection Principles, Methods, and Applications
* Automatic Derivation of Compiler Machine Descriptions
* VRASED: A Verified Hardware/Software Co-Design for Remote Attestation
* APEX: A Verified Architecture for Proofs of Execution on Remote Devices under Full Software Compromise
* How Low Can You Go? Recommendations for Hardware-Supported Minimal TCB Code Execution
* Lightweight Bare-metal Stateful Firewall
* OSLO: Improving the security of Trusted Computing 
* Tiny-CFA: A Minimalistic Approach for Control-Flow Attestation Using Verified Proofs of Execution
* DIALED: Data Integrity Attestation for Low-end Embedded Devices
* BYOTEE: Towards Building Your Own Trusted Execution Environments Using FPGA
* Mind the Gap: Studying the Insecurity of Provably Secure Embedded Trusted Execution Architectures
* GAROTA: Generalized Active Root-Of-Trust Architecture
* ASAP: Reconciling Asynchronous Real-Time Operations and Proofs of Execution in Simple Embedded Systems
* DITES: A Lightweight and Flexible Dual-Core Isolated Trusted Execution SoC Based on RISC-V
* TR-FSM: Transition-based Reconfigurable Finite State Machine
* The Pintos Instructional Operating System Kernel
* BabyOS: a fresh start
* MiniOS: An Instructional Platform for Teaching Operating Systems Projects
* A Scalable Operating System Experiment Platform Supporting Learning Behavior Analysis
* Fast Privileged Function Calls
* Direct Inter-Process Communication (dIPC): Repurposing the CODOMs Architecture to Accelerate IPC
* Packrat Parsing:
* Simple, Powerful, Lazy, Linear Time
* Rewrite rules for the Disciplined Disciple Compiler
* The computational origin of representation
* OPEN-ENDED EVOLUTION AS AN EMERGENT SELF-ORGANIZING SEARCH PROCESS
* Numeral Systems Across Languages Support Efficient Communication
* Let's talk (efficiently) about us: Person systems achieve near-optimal compression
* Putting Prototypes in Place
* Inference and the structure of concepts
* The mental representation of universal quantifiers
* Code generation for a one register machine
* Introducing conviviality as a new paradigm for interactions among IT objects
* STEPS Toward The Reinvention of Programming
* Bicycles for the mind have to be see-through
* UVC: A Universal Virtual Computer for Long-term Preservation of Digital Information
* VMKit: a Substrate for Managed Runtime Environments
* Snippets: Taking the High Road to a Low Level
* Z-Rays: Divide Arrays and Conquer Speed and Flexibility
* Continuously Measuring Critical Section Pressure with the Free-Lunch Profiler
* Draining the Swamp: Micro Virtual Machines as Solid Foundation for Language Development
* On-Stack Replacement, Distilled
* Scalable Concolic Testing of RTL Models
* Software/Hardware Co-Verification for Custom Instruction Set Processors
* Specification-Driven Conformance Checking for Virtual/Silicon Devices using Mutation Testing
* A Novel Concolic Execution Approach on Embedded Device
* Embedded Fuzzing: a Review of Challenges, Tools, and Solutions
* Hop, Skip, & Jump Practical On-Stack Replacement for a Cross-Platform Language-Neutral VM
* On-Stack Replacement for Program Generators and Source-to-Source Compilers
* Micro Virtual Machines: A Solid Foundation for Managed Language Implementation
* A Foundation for the Development of Programming Languages for Real-Time Systems
* Designing a Low-Level Virtual Machine for Implementing Real-Time Managed Languages
* An Efficient Implementation of a Micro Virtual Machine
* Lowcode extending Pharo with C Types to Improve Performance
* Garbage Collection and Efficiency in Dynamic Metacircular Runtimes
* Extending an In-Browser C Interpreter With an Abstracted Model of the Memory 
* Spreadsheets as Notational Environment for Paper Weaving
* Electronic Popables: Exploring Paper-Based Computing through an Interactive Pop-Up Book 
* Microcontrollers as material: crafting circuits with paper, conductive ink, electronic components, and an "untoolkit"
* Programming the shape-shifting of flat soft matter
* Mechanical metamaterials: a state of the art
* Hybrid Paper-Digital Interfaces: A Systematic Literature Review
* SYNERGY: Rethinking Secure-Memory Design for Error-Correcting Memories
* The complexity of small universal Turing machines: A survey
* A Simple and Efficient Universal Reversible Turing Machine
* Concise Representations of Reversible Automata
* Energy-Efficient Algorithms
* Toward an Energy Efficient Language and Compiler for (Partially) Reversible Algorithms
* The power of being explicit: demystifying work, heat, and free energy in the physics of computation
* Information Effects
* Theseus: A High Level Language for Reversible Computing
* Starting from a Clean Slate: Creating a Top-down Parseable Runtime
* Staged computation: the technique you didn’t know you were using
* printr: Exploring the Potential of Paper-based Tools in Low-resource Settings
* PaperWeb: Paper-triggered Web Interactions
* CAM: A Mobile Interaction Framework for Digitizing Paper Processes in the Developing World
* DE S I G N I N G I N T E R A C T I O N S T H AT C O M B I NE P E N , PAP E R , A N D C O M P U T E R
* Computing with words and decision making
* Engineering Definitional Interpreters
* Definitional Interpreters for Higher-Order Programming Languages
* Definitional Interpreters Revisted
* BinRec: Dynamic Binary Lifting and Recompilation
* Optimization of dynamic languages using hierarchical layering of virtual machines
* A Data-Oriented (and Beyond) Network Architecture
* An association-based model of dynamic behaviour
* Predicate Abstraction with minimum Predicates
* WYSINWYX: What You See Is Not What You eXecute
* {BYTEWEIGHT}: Learning to recognize functions in binary code
* BAP: A binary analysis platform
* BitBlaze: A new approach to computer security via binary analysis
* Parsing expression grammars: a recognition-based syntactic foundation
* LL(): the foundation of the ANTLR parser generator
* Meta-Language Support for Type-Safe Access to External Resources
* FogPi: A Portable Fog Infrastructure through Raspberry Pis
* Procedural Reflection in Programming Languages
* Verifying Duff ’s device
* a reusable duff's device
* Matrix Code
* Meta-Language Support for Type-Safe Access to
* External Resources
* LAPD: Language-Agnostic Program Database
* Type-Safe, Self Inspecting Code
* Meta-Programming with Typed Object-language. Representations
* Type-level Computation Using Narrowing in Ωmega.
* A Simple Library Implementation of Binary Sessions
* A message-passing interpretation of adjoint logic
* Resource-Aware Session Types for Digital Contracts
* Session Types with Arithmetic Refinements and Their Application to Work Analysis
* RAST: A LANGUAGE FOR RESOURCE-AWARE SESSION TYPES
* Two decades of automatic amortized resource analysis
* Type-Based Amortized Resource Analysis with Integers and Arrays
* Explicitly Recursive Grammar Combinators
* Scan Grammars: Parallel Attribute Evaluation Via Data-Parallelism
* Implementing an Embedded Compiler using Program
* Transformation Rules
* Fixing Idioms A recursion primitive for applicative DSLs
* Abstract syntax graphs for DSLs
* A correspondence between type checking via reduction and type checking via evaluation 
* From type checking by recursive descent to type checking with an abstract machine 
* Certificates for incremental type checking
* A Logical Correspondence between Natural Semantics and Abstract Machines
* The Power of Simple Tabulation Hashing
* Hash Tables in Logic Programming
* Hash Tables for Embedded and Real-time systems 
* A Real-Time Distributed Hash Table
* Improving System Predictability and Performance via Hardware Accelerated Data Structures
* Shared Hardware Data Structures for Hard Real-Time Systems
* Correct and Efficient Bounded FIFO Queues
* A Scalable, Portable, and Memory-Efficient Lock-Free FIFO Queue
* A synchronous functional language with integer clocks
* COATCheck: Verifying Memory Ordering at the Hardware-OS Interface
* Using Elimination to Implement Scalable and Lock-Free FIFO Queues
* LibrettOS: A Dynamically Adaptable Multiserver-Library OS
* Memory-Optimality for Non-Blocking Containers
* BBQ: A Block-based Bounded Queue for Exchanging Data and Profiling
* A Generalized Modality for Recursion
* A general framework for combining diagrammatic and symbolic problem solving
* Is Universal Computation a Myth?
* Automated Theorem Proving in Euler Diagram Systems
* Speedith A reasoner for spider diagrams
* ABSTRACTION, VISUALISATION AND GRAPHICAL PROOF
* INHERENTLY PARALLEL GEOMETRIC COMPUTATIONS
* Parallel real-time computation: sometimes quantity means quality
* State of the art in heterogeneous strong migration of computations
* Maintaining Reference Graphs in Fully Decentralized Systems
* Process rescheduling: enabling performance by applying multiple metrics and efficient adaptations
* Reflection-based heterogeneous migration of computations
* Featherweight Concurrency in a Portable Assembly Language
* Manticore: A heterogeneous parallel language
* From Folklore to Fact: Comparing Implementations of Stacks and Continuations
* The Manticore runtime model
* ABSTRACTION, VISUALISATION AND GRAPHICAL PROOF 
* Defunctionalized Interpreters for Call-by-Need Evaluation
* Deriving a lazy abstract machine.
* A portable mechanism for thread persistence and migration.
* Mirrors: Design principles for meta-level facilities of object-oriented programing languages
* Dynamic typing for distributed programming in polymorphic languages
* On inter-deriving small-step and big-step semantics: A case study for storeless call-by-need evaluation
* refocusing in reducation semantics
* Refunctionalization at work
* A systematic derivation of the STG machine verified in Coq
* Correct and optimal implementations of recursion in a simple programming language
* The revised report on the syntactic theories of sequential control and state
* On graph rewriting, reduction and evaluation
* A study of syntactic and semantic artifacts and its application to lambda definability, strong normalization, and weak normalization in the presence of state
* A functional correspondence between call-by-need evaluators and lazy abstract machines
* A syntactic correspondence between context-sensitive calculi and abstract machines
* Three syntactic theories for combinatory graph reduction
* The dynamic Geometry of Interaction machine: a token-guided graph rewriter
* Efficient implementation of evaluation strategies via token-guided graph rewriting
* Cactus environment machine
* TIM: A simple, lazy abstract machine to execute supercombinators.
* Abstract machines for programming language implementation
* TRAM: An abstract machine for order-sorted conditional term rewriting systems
* Operational Semantics with Hierarchical Abstract Syntax Graphs
* The Machinery of Interaction
* The weak lambda calculus as a reasonable machine
* Computation by interaction for spacebounded functional programming
* Game Semantics & Abstract Machines
* Local and asynchronous beta-reduction
* Reversible, irreversible and optimal lambda-machines
* Parsimonious Types and Nonuniform Computation
* On the Relation of Interaction Semantics to Continuations and Defunctionalization
* Functional Abstract Machine 
* The Problem of Space Invariance for Sequential Machines.
* The design of Hume: a high-level language for the real-time embedded systems domain
* Juniper: A Functional Reactive Programming Language for the Arduino
* Distributed REScala: An Update Algorithm for Distributed Reactive Programming
* Interactive Programs in Dependent Type Theory
* A Distributed Processing Platform With Reconfigurable Autonomous Nodes 
* Decision strategies for a P2P computing system
* DisCoP: A P2P Framework for Managing and Searching Computing Markets
* Koorde: A simple degreeoptimal distributed hash table
* MAAN: A Multi-Attribute Addressable Network for Grid Information Services
* A SURVEY AND COMPARISON OF PEER-TO-PEER OVERLAY NETWORK SCHEMES
* Tapestry: A Resilient Global-scale Overlay for Service Deployment
* Multiparty Computation, an Introduction
* How to Play any Mental Game or A Completeness Theorem for Protocols with Honest Majority
* Minimal Complete Primitives for Secure Multi-party Computation
* Viaduct An Extensible, Optimizing Compiler for Secure Distributed Programs
* TOWARDS PERFORMANCE PORTABLE GRAPH ALGORITHMS
* LogP: Towards a Realistic Model of Parallel Computation
* DARE: High-Performance State Machine Replication on RDMA Networks
* A Divide and Conquer Algorithm for DAG Scheduling under Power Constraints
* Cacheap: Portable and Collaborative I/O Optimization for Graph Processing
* Portable High-Performance Programs
* a portable software support system for irregular computations
* Recursive machines and computing technologies
* Logic circuits from zero forcing
* Object Graph Rewriting: An Experimental Parallel Implementation
* Dactl: An Experimental Graph Rewriting Language
* Implementing concurrent logic and functional languages in Dactl
* Janus: a step towards distributed constraint programming,
* MONSTR: term graph rewriting for parallel machines
* The flagship parallel machine
* Concurrent constraint programming languages
* Alice – a multiprocessor reduction machine for the parallel evaluation of applicative languages
* GRIP – a high performance architecture for parallel graph reduction
* Efficient Graph Rewriting
* Rooted graph programs
* Verification of graph programs
* GP 2: efficient implementation of a graph programming language
* Towards a Navigational Logic for Graphical Structures
* Incorrectness Logic for Graph Programs
* Axiomatic Bootstrapping: A guide for compiler hackers
* Hoare-style verification of gr erification of graph programs 
* Confluence up to Garbage
* Proof-Carrying Data
* Weisfeiler-Lehman Graph Kernels
* Computing extremal and approximate distances in graphs having unit cost edges
* Parsing Linear Context-Free Rewriting Systems with Fast Matrix Multiplication
* Newtonian Program Analysis via Tensor Product
* Newtonian Program Analysis
* Cost-Effectiveness of Strategies to Improve HIV Testing and Receipt of Results
* Fast Parallel Matrix and GCD Computations 
* Lower Bounds on Arithmetic Circuits via Partial Derivatives
* Learning Restricted Models of Arithmetic Circuits
* ParaMoC: A Parallel Model Checker for Pushdown Systems
* Decoding with Finite-State Transducers on GPUs
* Accelerated Finite State Machine Test Execution Using GPUs
* Solving Parity Games on the GPU
* Graph Algorithms in the Language of Linear Algebra
* A formal method for provably correct composition of a real-life processor out of basic components 
* Specification and Verification of Pipelining in the ARM2 RISC Microprocessor
* A Practical Method for Rigourously Controllable Hardware Design
* Modelling and Analysis of Distributed and Reactive Systems using Evolving Algebras
* Universal Plug and Play Machine Models
* An Approach to Dynamic Context Discovery and Composition
* High-Level Executable Specification of the Universal Plug and Play Architecture 
* A Survey of Architecture Description Languages
* A classification and comparison framework for software architecture description
* Giotto: A Time-Triggered Language for Embedded Programming
* Software Component Models
* Evaluating software architectures
* Palladio component model for model-driven performance prediction
* Towards a Taxonomy of Software Connectors
* The BRICS component model: a model-based development paradigm for complex robotics software systems
* Twenty-eight years of component-based software engineering
* ALI: An Extensible Architecture Description Language for Industrial Applications
* An Architecture Description Language for Massively Parallel Processor Architectures
* Processor description languages
* CGADL: An architecture description language for coarse-grained reconfigurable arrays
* XPDL: extensible platform description language to support energy modeling and optimization
* SkePU 2: Flexible and type-safe skeleton programming for heterogeneous parallel systems
* MeterPU: a generic measurement abstraction API
* GreenML: A methodology for fair evaluation of machine learning algorithms with respect to resource consumption
* Automatic deployment of distributed software systems: Definitions and state of the art
* ABS: A core language for abstract behavioral specification
* A survey of self-management in dynamic software architecture specifications
* A Model-Driven Deployment Approach for Scaling Distributed Software Architectures on a Cloud Computing Platform 
* Behavior Protocols for Software Components
* Partial Computation of Programs
* Practical partial evaluation for high-performance dynamic language runtimes
* Shallow Embedding of DSLs via Online Partial Evaluation
* TerpreT: A Probabilistic Programming Language for Program Induction
* Neural Turing Machines
* DARTS: DIFFERENTIABLE ARCHITECTURE SEARCH
* DreamCoder: Bootstrapping Inductive Program Synthesis
* Program Synthesis with Pragmatic Communication
* Semantic Code Search via Equational Reasoning
* Equality Saturation: A New Approach to Optimization
* Graph Representation Learning 
* Graph Algorithms in the Language of Linear Algebra
* Representation of Events in Nerve Nets and Finite Automata 
* Efficient Implementation of a BDD Package 
* An Optimal Solution for Test Case Generation Using ROBDD Graph and PSO Algorithm
* Biconditional BDD: A Novel Canonical BDD for Logic Synthesis targeting XOR-rich Circuits
* ALITHEIA: Towards Practical Verifiable Graph Processing
* Binary Decision Diagrams: An Algorithmic Basis for Symbolic Model Checking
* The Binary Decision Diagram: Abstraction and Implementation
* A Language and Environment for Architecture-Based Software Development and Evolution
* Dependent Types for Low-Level Programming
* C O M P I L I N G W I T H D E P E N D E N T T Y P E S
* Dependent Type Theory for Verification of Information Flow and Access Control Policies
* Týr: a dependent type based codetransformation for spatial memory safety in LLVM
* Requirements in Feature Algebra
* Bootstrapping Domain-Specific Meta-Languages in Language Workbenches
* PIE: A Domain-Specific Language for Interactive Software Development Pipelines
* The art of bootstrapping
* Language-Parametric Methodsfor Developing Interactive Programming Systems
* Machine Function based Control Code Algebras
* A formalism for translator interactions
* Machine independence: Its technology and economics
* Machine Structure Oriented Control Code Logic
* Putting instruction sequences into effect
* Outsourcing competence
* Towards Formal Grammars As Institutions
* Formal verification of OIL component specifications using mCRL2
* Decision taking as a service
* Platform Projections, Compilers,Cognitieve Interpreters and Portability
* development of a build system for cross platform open source projects
* Abstract machine construction through operational semantics refinements
* BabySteps: An approach to bootstrap an interactive system on COLA
* Bootstrapping the Object Oriented Operating System Merlin: Just Add Reflection
* Accessible Language-Based Environments of Recursive Theories
* Bootstrapped Semantics-Directed Compiler Generation
* Code generation for a family of executable modelling notations
* Semantically Configurable Code Generation
* BSML-mbeddr: integrating semantically configurable state-machine models in a C programming environment
* Geppetto: Versatile Verifiable Computation
* A Brief History of Just-In-Time
* The Virtual Processor: Fast, Architecture-Neutral Dynamic Code Generation
* YETI: A GRADUALLY EXTENSIBLE TRACE INTERPRETER
* VMKit: a Substrate for Managed Runtime Environments
* The Project Maxwell Assembler System
* A Step Towards Ubiquitous Computing : an Efficient Flexible micro-ORB
* Approximate Compilation for Embedded Model-based Reasoning
* A Basic Unit of Computation in Distributed Systems
* Toward Automatic Data Distribution for Migrating Computations
* Migratable User Interfaces: Beyond Migratory Interfaces 
* Automatic State Capture of Self-Migrating Computations
* State-Migration Shared-Variable Programming and its Runtime Support for Fine-Grained Cooperative Tasks
* Nomadic Pict: Programming Languages, Communication Infrastructure Overlays, and Semantics for Mobile Computation
* Developing correctly replicated databases using formal tools
* Seamless distributed computing from the geometry of interaction
* THE UNIVERSAL PROCESS
* Computation-by-Interaction for Structuring Low-Level Computation
* Krivine Nets: A semantic foundation for distributed execution
* Towards native higher-order remote procedure calls
* DI S T R I B U T I NG A B S T R AC T M AC H I N E S
* Defunctionalisation as Modular Closure Conversion
* The Geometry of Interaction as a Module System
* Distributed call-by-value machines
* ABS-NET: Fully decentralized runtime adaptation for distributed objects
* On the power of name-passing communication
* Thesis for Interaction
* Self-Organizing Migrating Algorithm
* Architecture-Centric Software Migration for the Evolution of Web-based Systems 
* A Formal Architectural Description Language based on Symbolic Transition Systems and Modal Logic
* looking outwards when dependent types meet io
* A Dependently Typed Programming Language, with applications to Foundational Certified Code Systems
* singleton: A general-purpose dependently-typed assembly language
* High-Level Separation Logic for Low-Level Code
* Hoare Logic for ARM Machine Code
* SBCL: a Sanely-Bootstrappable Common Lisp
* A Practical Property-based Bootstrap Architecture
* Translating HOL functions to hardware
* Debootstrapping without Archeology: Stacked Implementations in Camlboot
* Solving the Bootstrap Problem for Free and Open Source Binary Distributions
* MPM :A Modular Package Manager
* A formal approach to distributed application synthesis and deployment automation
* Zephyrus2: On the Fly Deployment Optimization using SMT and CP Technologies?
* The Case for Using Guix to Enable Reproducible RISC-V Software & Hardware
* Bootloader Design for MCUs in Embedded Systems
* embedded Hardware Testing Using Bootloader
* Study on Debugging Method Based on Embedded System Development Platform
* Analysis of U-Boot booting process and the realization of command menu
* Porting and board bring up of Mini2440 using U-boot 
* A Novel Approach to Develop Dynamic Portable Instructional Operating System for Minimal Utilization 
* an automatic testing framework for embedded software
* Controlling the Bootstrap Process 
* Methods of Securing the Bootstrap Process of an Operating System
* A Secure and Reliable Bootstrap Architecture 
* BITS: A Smartcard Protected Operating System 
* Safe to the Last Instruction: Automated Verification of a Type-Safe Operating System
* Resourceable, retargetable, modular instruction selection using a machine-independent, type-based tiling of low-level intermediate code
* Synthesizing an Instruction Selection Rule Library from Semantic Specifications
* Centaur technology media unit verification. 
* A DFA-based x86-32 validator for Native Client
* Native Client: A Sandbox for Portable, Untrusted x86 Native Code
* Arrakis: The Operating System Is the Control Plane
* Specialized Accelerators and Compiler Flows: Replacing Accelerator APIs with a Formal Software/Hardware Interface
* Effective Simulation and Debugging for a High-Level Hardware Language Using Software Compilers
* Bluespec SystemVerilog: Efficient, Correct RTL from High-Level Specifications 
* Instruction-Level Abstraction 
* A-QED Verification of Hardware Accelerators
* Integrating Memory Consistency Models with Instruction-Level Abstractions for Heterogeneous System-on-Chip Verification
* A Formal Instruction-Level GPU Model for Scalable Verification
* Synthesizing Environment Invariants for Modular Hardware Verification
* Isla: Integrating full-scale ISA semantics and axiomatic concurrency models
* An integrated concurrency and core-ISA architectural envelope definition, and test oracle, for IBM POWER multiprocessors
* Simplifying ARM Concurrency: Multicopy-Atomic Axiomatic and Operational Models for ARMv8
* Modelling the ARMv8 Architecture, Operationally: Concurrency and ISA
* Engineering with Logic: Rigorous Test-Oracle Specification and Validation for TCP/IP and the Sockets API
* Petr4: Formal Foundations for P4 Data Planes
* Formal Verification of Communication Protocols
* Promising-ARM/RISC-V: A Simpler and Faster Operational Concurrency Model
* The Missing Link: Explaining ELF Static Linking, Semantically
* Formal specification and verification of safety and performance of TCP selective acknowledgment
* Model checking large network protocol implementations
* Formal verification of standards for distance vector routing protocols
* What packets m come: automata for network monitoring
* A ormal Approach for Passive Testing of Protocol Data Portions
* Specifications and Proofs for Ensemble Layers
* Building reliable, high-performance networks with the Nuprl proof development system. 
* Verifying Network Protocol Implementations by Symbolic Refinement Checking
* Designing DCCP: Congestion Control Without Reliability
* Discovering Chatter and Incompleteness in the Datagram Congestion Control Protocol
* Abstraction of Communication Channels in Promela
* Verification and Improvement of the Sliding Window Protocol
* Abruptly-Terminated Connections in TCP – A Verification Example
* On Defining the Service Provided by TCP
* Closed form expressions for the state space of TCP’s Data Transfer Service operating over unbounded channels
* Service specification and protocol construction for the transport layer
* A verified connection management protocol for the transport layer
* Not-QuiteSo-Broken TLS: Lessons in Re-Engineering a Security Protocol Specification and Implementation
* Detailed Models of Instruction Set Architectures: From Pseudocode to Formal Semantics
* Specifying verified x86 software from scratch
* A Mechanised Semantics for HOL with Ad-hoc Overloading
* Metamath Zero: The Cartesian Theorem Prover
* A Formally Verified Checker for First-Order Proofs
* The TESC Proof Format for First-Order ATPs
* Semantic derivation verification: Techniques and implementation. 
* TSTP Data-Exchange Formats for Automated Theorem Proving Tools
* Recording Completion for Certificates in Equational Reasoning
* Mechanized Metatheory for the Masses: The PoplMark Challenge
* A compositional logic for control flow.
* Parsing Expression Grammars: A Recognition-Based Syntactic Foundation
* Incremental Computation with Names
* Incrementally Verifiable Computation or Proofs of Knowledge Imply Time/Space Efficiency
* On Valiant’s Conjecture: Impossibility of Incrementally Verifiable Computation from Random Oracles
* Computationally sound proofs
* Universal Arguments
* proof checking and the hardness of approximation
* Probabilistic checking of proofs: A new characterization of NP
* VERI-ZEXE: Decentralized Private Computation with Universal Setup
* Cluster Computing in Zero Knowledge
* SMART: Secure and minimal architecture for (establishing a dynamic) root of trust.
* TrustLite: A Security Architecture for Tiny Embedded Devices
* CHAINIAC: Proactive softwareupdate transparency via collectively signed skipchains and verified builds
* Decentralized Review and Attestation of Software Attribute Claims
* Reproducibility and Performance: Why Choose?
* Using FireSim to Enable Agile End-to-End RISC-V Computer Architecture Research
* Firemarshal: Making hw/sw co-design reproducible and reliable
* The BRISC-V Platform: A Practical Teaching Approach for Computer Architecture
* bootstrapping a libre self hosting riscv computer
* Challenges and solutions in creating a RISC-V computing platform
* A Framework for Microarchitecture Traces as Abstraction Layer in Computer Architecture Education
* PIPS: An Instruction Set Architecture for Teaching Computer Organization
* RISC-V Reward: Building Out-of-Order Processors in a Computer Architecture Design Course with an Open-Source ISA
* Computer Engineering Education Experiences with RISC-V Architectures—From Computer Architecture to Microcontrollers
* CodeAPeel: An Integrated and Layered Learning Technology For Computer Architecture Courses
* A Flexible Uncore Infrastructure for RISC-V Core Development
* Teaching Out-of-Order Processor Design with the RISC-V ISA
* Porting_OpenBSD_to_RISCV
* Verified Transformations and Hoare Logic: Beautiful Proofs for Ugly Assembly Language
* Flex: A Working Computer with an Architecture Based on Procedure Values
* Intermediate Representations in Imperative Compilers: A Survey
* Generalized Instruction Selection using SSA-Graphs
* Code Instruction Selection Based on SSA-Graphs
* Fast and flexible instruction selection with on-demand tree-parsing automata
* BURG – Fast Optimal Instruction Selection and Tree Parsing
* Optimal Code Selection in DAGs
* Optimal code generation for expression trees
* the MPG System: A Machine-Independent Efficient Microprogram Generator
* Architecture Description Languages for Retargetable Compilation
* Architecture Description Language (ADL)-Driven Software Toolkit Generation for Architectural Exploration of Programmable SOCs
* Pbexplore: A framework for compilerin-the-loop exploration of partial bypassing in embedded processors
* Automatic Design Space Exploration of Register Bypasses in Embedded Processors
* Automatic generation of operation tables for fast exploration of bypasses in embedded processors
* A framework for GUI-Driven design space exploration of a MIPS4K-like processor
* Automatic Pipeline Synthesis and Formal Verification from transactional Datapath Specifications
* Retargetable compiled simulation of embedded processors using a machine description language
* Instruction set compiled simulation: A technique for fast and flexible instruction set simulation.
* RTGEN: An algorithm for automatic generation of reservation tables from architectural descriptions
* EXPRESSION: A language for architecture exploration through compiler/simulator retargetabilit
* ‘A methodology for accurate performance evaluation in architecture exploration
* Data and memory optimization techniques for embedded systems
* ArchC: A SystemC-based architecture description language
* Flexible and formal modeling of microprocessors with application to retargetable simulation
* Modern development methods and tools for embedded reconfigurable systems: A survey
* Pydgin: Generating Fast Instruction Set Simulators from 
* Simple Architecture Descriptions with Meta-Tracing JIT Compilers
* ASAM: automatic architecture synthesis and application mapping
* Organizing the Aggregate: Languages for Spatial Computing
* Shrink: Reducing the isa complexity via instruction recycling
* TERAFLUX: Harnessing dataflow in next generation teradevices
* A System for Generating Static Analyzers for Machine Instructions
* Rapid Generation of High-Quality RISC-V Processors from Functional Instruction Set Specifications
* A grand unified theory for structural computing.
* Carbon nanotube computer
* Unifying Structure, Behavior, and Data with Themis Types and Templates
* As we should have thought
* Linking considered harmful.
* AHA! An open Adaptive Hypermedia Architecture
* Structure and behavior awareness in Themis. 
* IUHM: a hypermedia-based model for integrating open services, data and metadata.
* Rethinking structural computing infrastructures
* THEORY AND PRACTICE OF THE TERNARY RELATIONS MODEL OF INFORMATION MANAGEMENT 
* Traces of ternary relations
* Compositions of ternary relations
* Architecting structure-aware applications
* Implementing a simple proof assistant
* growing a proof assistant
* Information accountability
* From the semantic web to social machines
* computational logic and the social
* Dynamic first-order ontology repair
* An interaction-based approach to semantic alignment
* Repairing ontologies via axiom weakening
* Plans, actions and dialogues using linear logic
* The interaction of representation and reasoning
* Modeling ontology evolution with SetPi
* On understanding types, data abstraction, and polymorphism
* PKRU-Safe: Automatically Locking Down the Heap Between Safe and Unsafe Languages
* Defense in Depth of Resource-Constrained Devices
* Reinventing the Privilege Drop
* Classes of recursively enumerable sets and their decision problems
* Mismorphism: a Semiotic Model of Computer Security Circumvention
* Exploit programming: From buffer overflows to weird machines and theory of computation
* Unlimited Lives: Secure In-Process Rollback with Isolated Domains
* EPEX: Processor Verification by Equivalent Program Execution
* RVVRadar: A Framework for Supporting the Programmer in Vectorization for RISC-V
* Trust Extension as a Mechanism for Secure Code Execution on Commodity Computers
* Secure bootstrap is not enough: Shoring up the trusted computing base
* An Evil Copy: How the Loader Betrays You.
* NetQuery: A knowledge plane for reasoning about network properties
* TrustFound: Towards a Formal Foundation for Model Checking Trusted Computing Platforms
* Open reusable object models.
* Embedding languages without breaking tools
* An implementation substrate for languages composing modularized crosscutting concerns
* Programming as planning
* Register allocation via puzzle solving via planning
* Jumble of Heuristic Notions
* Context-oriented programming: A software engineering perspective
* Language and IDE Modularization and Composition with MPS
* mbeddr: an extensible C-based programming language and IDE for embedded systems
* Mashup of metalanguages and its implementation in the kermeta language workbench
* mbeddr: Instantiating a Language Workbench in the Embedded Software Domain
* A research on debugging tools’ platform independency
* Functional Debug Techniques for Embedded Systems
* Transaction-Based Communication-Centric Debug
* Debug support for complex systems on-chip: a review
* How eCos can be shrunk to fit
* EMBEDDED SOFTWARE DEVELOPMENT WITH ECOS
* HARDWARE ABSTRACTION LAYER
* Introduction to hardware abstraction layers for SoC
* Abstraction Layers and Energy Efficiency in TockOS, a Rust-based Runtime for the Internet of Things
* SPACE: a new approach to operating system abstraction
* An Object-Oriented Nano-Kernel for Operating System Hardware Support
* Verification-Based Multi-backup Firmware Architecture, an Assurance of Trusted Boot Process for the Embedded Systems
* Trusted Boot for Embedded Systems Using Hypothesis Testing Benchmark
* A Novel Trusted Boot Model for Embedded Smart Device without TPM
* A Survey of Secure Boot Schemes for Embedded Devices
* THE DEVELOPMENT OF A HARDWARE ABSTRACTION LAYER GENERATOR FOR SYSTEM-ON-CHIP FUNCTIONAL VERIFICATION
* Writing Testbenches - Functional verification of HDL models
* Writing Testbenches Using System Verilog
* An automatic testbench generation tool for a systemc functional verification methodology
* Efficient Techniques for Directed Test Generation using Incremental Satisfiability
* Rely-Guarantee Protocols for Safe Interference over Shared Memory
* Robust Composition: Towards a Unified Approach to Access Control and Concurrency Control
* Universes: A Type System for Controlling Representation Exposure
* Type and Effect Systems
* MPI: A Message-Passing Interface Standard
* Reasoning about object capabilities with logical relations and effect parametricity
* A Logic of Secure Systems and its Application to Trusted Computing
* A derivation system and compositional logic for security protocols
* Protocol Composition Logic
* Collapse (& Other Futures) Software Engineering 
* Macroscopically Sustainable Networking: On Internet Quines
* A pluriverse of local worlds: a review of Computing within Limits related terminology and practices
* Implementation and Implications of a Stealth Hard-Drive Backdoor
* Sustainable Interaction Design: Obsolescence in a Future of Collapse and Resource Scarcity
* Unplanned obsolescence: Hardware and software after collapse
* Architecture of a Junkyard Datacenter
* Century-Scale Smart Infrastructure
* New Directions: The Future of Sensing is Batteryless, Intermittent, and Awesome
* Design of an RFID-based battery-free programmable sensing platform
* Ember: energy management of batteryless event detection sensors with deep reinforcement learning
* Marble: collaborative scheduling of batteryless sensors with meta reinforcement learning
* tinyMAN: Lightweight Energy Manager using Reinforcement Learning for Energy Harvesting Wearable IoT Devices
* ZEL: Net-Zero-Energy Lifelogging System using Heterogeneous Energy Harvesters
* Repurposing Cathodic Protection Systems as Reliable, in-situ, Ambient Batteries for Sensor Networks
* Capacity over capacitance for reliable energy harvesting sensors
* TerraWatt: Sustaining Sustainable Computing of Containers in Containers
* ACT: Designing Sustainable Computer Systems With An Architectural Carbon Modeling Tool
* Towards Deploying Decommissioned Mobile Devices as Cheap Energy-Efficient Compute Nodes
* Data Centers from Discarded Cell Phones
* Renee: New Life for Old Phones
* Revolutionising Computing Infrastructure For Citizen Empowerment
* The mote is dead: long live the discarded smartphone!
* Computing while charging: Building a distributed computing infrastructure using smartphones
* A Networked Embedded System Platform for the Post-Mote Era
* Software-Defined Internet Architecture: Decoupling Architecture from Infrastructure
* Networking in the Long Emergency
* A delay-tolerant network architecture for challenged internets
* Designing an architecture for delivering mobile information services to the rural developing world
* OpenPiton: An Open Source Manycore Research Framework
* FireSim: FPGA-accelerated cycle-exact scale-out system simulation in the public cloud
* Reusability is FIRRTL ground: Hardware construction languages, compiler frameworks, and transformations
* Architectural Implications of Function-as-a-Service Computing
* Faasm: Lightweight isolation for efficient stateful serverless computing
* The Design and Application of a Retargetable Peephole Optimizer 
* DESCRIPTION OF A MACHINE ARCHITECTURE FOR USE WITH BLOCK STRUCTURED LANGUAGES
* The EM Interpreter
* The design and implementation of the EM Global Optimizer
* The Constructive Semantics of Pure Esterel
* The Esterel synchronous programming language: design, semantics, implementation
* An Occam Compiler
* A methodology and tool suite for C compiler generation from ADL processor models
* LISA: A uniform ADL for embedded processor modeling, implementation, and software toolsuite generation
* RTL processor synthesis for architecture exploration and implementation
*  Ingredients of Adaptability: A Survey of Reconfigurable Processors.
* MyHDL: A Python-based Hardware Description Language
* ArchHDL: A Novel Hardware RTL Design Environment in C++
* Veriloggen: A library for constructing a Verilog HDL source code in Pytho
* PyMTL: A Unified Framework for Vertically Integrated Computer Architecture Research
* Avoiding game over: Bringing design to the next level
* JHDL-an HDL for reconfigurable systems
* HML, a novel hardware description language and its translation to VHDL
* Chisel: Constructing Hardware in a Scala Embedded Language
* Programming Heterogeneous Systems from an Image Processing DSL
* AutoPilot: A platform-based ESL synthesis system
* High-level synthesis: Past, present, and future
* High-level synthesis for FPGAs: From prototyping to deployment
* Computer generation of hardware for linear digital signal processing transforms
* Fpgabased accelerator design from a domain-specific language
* Darkroom: Compiling high-level image processing code into hardware pipelines
* A compiler and runtime for heterogeneous computing
* Software Language Engineers' Worst Nightmare
* The Software Language Extension Problem
* Language composition untangled
* SugarJ: Library-based syntactic language extensibility 
* Reliable and automatic composition of language extensions to C: The ablec extensible language framework
* Rascal: A domain specific language for source code analysis and manipulation
* Modular language composition for the masses
* Extensibility for the masses practical extensibility with object algebras
* Language and IDE modularization and composition with MPS
* Neverlang: A framework for featureoriented language development
* Recaf: Java dialects as libraries
* Revisiting visitors for modular extension of executable dsmls
* Modular visitor components
* Melange: A meta-language for modular and reusable development of dsls
* Modular well-definedness analysis for attribute grammars
* Silver: an extensible attribute grammar system
* EVF: an extensible and expressive visitor framework for programming language reuse
* Language design with the spoofax language workbench
* The art of bootstrapping
* Bootstrapping domain-specific meta-languages in language workbenches
* Playground for multi-level modeling constructs
* Teaching Language Engineering Using MPS
* Leveraging Applications of Formal Methods, Verification and Validation
* Automated Verification of Embedded Control Software
* Rigorous Engineering of Collective Adaptive Systems
* A distributed API for coordinating AbC programs
* Programming of CAS systems by relying on attribute-based communication
* From distributed coordination to field calculus and aggregate computing
* From Field-Based Coordination to Aggregate Computing
* vIRONy:, a tool for analysis and verification of ECA rules in intelligent environments
* Mastering the Supply Chain by a Concept of a Digital Control-Twin
* Digital Twin: Enabling Technologies, Challenges and Open Research
* Leveraging Digital Twin Technology in Model-Based Systems Engineering
* A program transformation approach to automating software re-engineering
* KernelF - an Embeddable and Extensible Functional Language
* DPF Workbench: a multi-level language workbench for MDE
* Bootstrapping MDE Development from ROS Manual Code – Part 1: Metamodeling
* MROS: Runtime Adaptation For Robot Control Architectures
* Modelling of Language Syntax and Semantics: The Case of the Assembler Compiler
* Alien vs. Quine
* Underdesigned and Opportunistic Computing in
* Presence of Hardware Variability
* Software adaptation in quality sensitive applications to deal with hardware variability
* A simple mechanism for improving the accuracy and efficiency of instruction-level disambiguation
* VaMV: Variability-aware memory virtualization
* Dynamic knobs for responsive power-aware computing
* Green: A framework for supporting energy-conscious programming using controlled approximation
* AppAdapt: Opportunistic application adaptation to compensate hardware variation
* Design and architectures for dependable embedded systems
* VarEMU: An emulation testbed for variability-aware software
* ADeLe: A description language for approximate hardware
* Self-Awareness in Systems on Chip— A Survey
* Cyberphysical-systemon-chip (CPSoC): A self-aware MPSoC paradigm with cross-layer virtual sensing and actuation
* Hierarchical agent monitoring design approach towards self-aware parallel systemson-chip
* Coadapt: Predictable behavior for accuracy-aware applications running on power-aware systems
* Self-aware hardware acceleration of financial applications on a heterogeneous cluster
* Continuous online self-monitoring introspection circuitry for timing repair by incremental partial-reconfiguration (cosmic trip)
* Cross-layer exploration of heterogeneous multicore processor configurations
* On-chip self-awareness using cyberphysical-systems-on-chip (CPSoC)
* Smart-balance: A sensing-driven Linux load balancer for energy efficiency of heterogeneous MPSoCs
* Organic computing – A new vision for distributed embedded systems
* Monitoring and self-awareness for heterogeneous, adaptive computing systems
* Combining software and hardware LS for lightweight on-chip learning
* DodOrg – A self-adaptive organic manycore architecture
* Organic computing at the system on chip level
* Autonomic system on chip platform
* SEEC: A Framework for Self-Aware Computing
* Application heartbeats: A generic interface for specifying program performance and goals in autonomous computing environments
* A generalized software framework for accurate and efficient management of performance goals
* HAMSoC: A monitoring-centric design approach for adaptive parallel computing
* Hierarchical agent monitored parallel on-chip system: A novel design paradigm and its formal specification
* Self-adaptive NoC power management with dual-level agents: Architecture and implementation
* Toward smart embedded systems: A self-aware system-on-chip (SoC) perspective
* Towards self-explaining digital systems: A design methodology for the next generation
* CLaSH: Structural Descriptions of Synchronous Hardware using Haskel
* Verifying SystemC using an intermediate verification language and symbolic simulation
* Verifying the structure and behavior in UML/OCL models using satisfiability solvers
* Self-verification as the key technology for next generation electronic systems
* Envisioning self-verification of electronic system
* Towards a methodology for self-verification
* Towards lightweight satisfiability solvers for self-verification
* Analyzing functional coverage in bounded model checking
* Self-Organizing and Self-Explaining Pervasive Environments by Connecting Smart Objects and Applications
* Safe, Intelligent and Explainable Self-Adaptive Systems
* Which Adaptation Logic? An Objective and Subjective Performance Evaluation of HTTP-based Adaptive Media Streaming Systems
* The Orchestration Stack: The Impossible Task of Designing Software for Unknown Future Post-CMOS Hardware
* Network on chip: An architecture for billion transistor era
* Single-isa heterogeneous multi-core architectures: The potential for processor power reduction
* He-p2012: architectural heterogeneity exploration on a scalable many-core platform
* Understanding fundamental design choices in single-isa heterogeneous multicore architectures
* An energy-efficient network-on-chip for a heterogeneous tiled reconfigurable systems-on-chip
* Runtime mapping of dynamic dataflow applications on heterogeneous multiprocessor platforms
* A hybrid task mapping algorithm for heterogeneous MPSoCs
* A compiler infrastructure for embedded heterogeneous MPSoCs
* Popcorn: Bridging the programmability gap in heterogeneous-ISA platforms
* Helios: Heterogeneous multiprocessing with satellite kernels
* Probabilistic model checking for energy-utility analysis
* Memory access patterns: The missing piece of the multi-gpu puzzle
* M3: A hardware/operating-system co-design to tame heterogeneous manycores
* Swarm: A scalable architecture for ordered parallelism
* An application-specific instruction set for accelerating set-oriented database primitives
* Tomahawk: Parallelism and heterogeneity in communications signal processing MPSoCs
* Model checking techniques for design and analysis of future hardware and software systems
* System Simulation with gem5, SystemC and other Tools
* Transaction Level Modeling: An Overview
* TLM 2.0 Simple Sockets Synthesis to RTL
* A hardware/software stack for heterogeneous systems
* Algorithmic communication with extraterrestrial intelligence

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
