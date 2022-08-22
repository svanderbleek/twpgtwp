# twpgtwp

The Working Programmer's Guide To Working Programs

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



## Topics

### Instructions

#### SLED
#### SSL

### Verification Stack

### Operating System

#### Trusted Execution Environments

#### Memory

##### Pointers

#### Capabilities
#### Singularity OS

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
