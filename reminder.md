# objected oriented  analysis and design(cmt 310)

## lecture 1
cat 1 10th october 2023
  
phases of system projects  include
planning ,analysis ,design and implementation

unified modelling language(uml) accelerated the change to system analysis and design

**system analyst** analyses the business situation identify opportunity for improvement and designs the system.
challenges the way the current organization works

**objective for a system analyst**
to create value for the organisation hence increasing profits 

### The system development life cycle (SDLC)
Similar to the four fundamental phases i.e planning,analysis,design and implentation 

STEPS of SDLC
--
1.**planning**

fundamental process of understanding why a system should be build
 
 step one: of planning is identying system bussines value


 *system request* presents a brief summmary of business needs and explains how the system will increase business value

  step two: project management 

 creation of work plan staff the projects and techniques that will be used

 2.**Analysis**

  answers question of will use the system,what the system will do and when it will be used

  step one:Analysis

  step two:requirements gathering done through interviews
  
  step three:system proposal development 
  analysis system concept and models are combined into a document called **system proposal** 
  
  it describes the business requirements  the new system should meet

  3.**Design**

  decides on how the new system will operate in terms of hardware ,software requirement and type of network infrastructure;user interface forms and reports and specific programs ,databases and files that can be needed

  The design has four steps

  step one :design strategy

  step two:development of basic architecture design 
  describes hardware software and network infrastructure 

  step three:
  
  `data base and file specificaton are developed

  step four:
  
  program design defines the programs should be written and function of these programs(**system specification**)

4. **IMPLEMENTATION**

final phase,gets most attention longest and most expensive 

step one :system construction

system is build and tested to  ensure it performs as designed 

step two: system installation 
old system is turned off and the new one is included ik vn the system 

most important aspects is to train the users to the new system and help manage the new system


step three:analyst team establishes a support plan 
includes a formal and non formal review of the system 

#### SYSTEM DEVELOPMENT METHODOLOGIES
A methodology is a formalized apporach to implenting the SDLC

*categorizing the methodology*
-

**process centered methodology** emphasizes on the process models 

**data centered methodologies** emphasizes on data models as core of system concept

**object oriented methodologies** attempts to balance the focus  on both process and data and incorporating them to one model

*classes of system methodologies*
-


1.structured design

first category adopted in 1980's

adopts a step by step approach 
    example is the **1a.waterfall development**

    analysts and users proceed in sequence from one phase to the next

*advantages*

 1.identifies system requirements before programming begins

2.minimizes changes to the requirements

**1b. parallel development**

attempts to address the problem of long delays between analysis phase and delivery 

primary advantage is to reduce the time to deliver the system 

**2.rapid application development(R.A.D)**

attempt to address the weakness of structured methodology
recommends analysts to use special techniques and computer tools to speed up the analysis ,design and implementation  such as computer aided software

*2a. phased development*

breaks the overall system into a series of versions that are developed sequential

disadvantage 
users work with systems that are intentionally incomplete

*2b prototyping*

Performs the phases(analysis  design and implentation  )concurrently and all the three phases are repeated in a cycle until the system is completed 

first prototype is shown to the group for commments and approval 

*adavantage*
users can interact with system 

*disadanatage*faced paced systems undergoes many changes 

**2c throw away prototyping**
done at different points in the SDLC
have a relatively thorough analysis phase used to gather information 

design prototype is not working well helps users understand challenges facing the system(display)

design prototype are thrown away 

more stable and reliable systems 

**3.Agile methodologies**

focus is on the developers

based on 12 principles ;they include:

1.software is delivered early satisfying the customer

2.changing requirements are made

3.working software is delivered to the customer

4.customers and developers work together to face the challenges facing the system

5.motivated individuals provide solutions 

6.face to face communication within development time 

7.primary measure of the progress

8.customers and developers work at a pace that is timed 

9.simplicity 

10.technical excellence 

12.reflection from the development times to improve the end product

*critics to agile methodology*

1.business premises

2.if not carefully managed by definition its not 

3.large mission critical systems solutions 

**based on agile**

scrum and extreme programming 

*1a.extreme programming* founded on 4 core values 

comments on various systems of the code

recommended for small groups of developers

large systems build with extreme programming become hard to maintain

can not handle mission  critical business enterprises

*b.scrum programming*

as soon software development  starts to develop chaos break out and planning fails 

iteration takes about 31 working days 

most chaotic

non progress
 
 *practice*

teams organize themselves 

once iteration has began no addition of any other inputs

scrum meeting takes place on each day,any block identified its dealt with  

*limitation*

1.questionable since it cannot deal with mission critical systems 

2.not more than 7 members

*key things to consider while selecting a methodology*

1.Clarity of user requirement(users need to interact with technology to give more reliable feed back )(RAD or AGILE is best sine  the users are involved )

2.familiarity  with technology(RAD since one has to understand and learn the technology)

3.systems complexity

4.system reliability (important factor in systems development)(agile method is the best)

5.short time  schedules

6.schedule visibility

*SYSTEMS ANALYSIS ROLES AND  SKILLS*
Major categories of skills 

technical skill
( to understand the organization technical environment )

business skills
(to understand how IT will be applied to the investments)

analytical skills(problem solvers to the organization)

interpersonal skills (communication)

management skills

ethical skills 

**discuss the roles of the following in terms of their qualification 
competence**
development phases 

business analyst
system analyst
infrastructure analyst
change management
project analyst

x-stics of object oriented systems

objects 

classes template define and create objects

methods 

processes that the object should carry out include making an appointment checking last visit

inheritance 

polymorphism

## aspecs of object oriented

### Architecture-centric
means that the underlying software architecture of the evolving system specification,construction and documentation of thw system

### iterative and incremental aspects 

continous testing and refinement throughout the life of the project

### benefits of OOSAD
enable analyst to break a complex system to smaller managable modules 

makes systems development easier t grasp,easier to share among members and easier to communicate with the users 

by creating modules the project team is creating resuable pieces that can be plugged into the other systens hence saving time

### the unified process
maps out on how to use various unified modeling language techniques 

phases are inception,elaboration ,construction and transition 

### phases of the unified process

Describe how the system will evolve through time 
  1.inception

  similar to planning phase of traditional SDLC

business case is proposed which includes feasibilty analysis

primary deliverables from the inception phase are a vision doc

2.elaboration 

analysis and design workflows are the primary focus 
deals with gatjering the requirements building the UML structural models and behavioural 

developers are involved with the engineering deployment 

3.construction 

heavily focusing on programing the system 

primarly concerned with the implentation work flow 

missing requirements ar identified and analysis and design models are finally completed 

during the last iteration deployment work flows kicks in 

beta and acceptance testing 

beta testing final round of testing before releasing of the final system

4.transition

similar to implentation phase 

focus on testing and deployment workflows 


### work flows 

describe tasks and activities that a developer performs for the final product 

categories :engineering and supporting

* business model workflows - 

uncovers problems and identifies potential projects within user organisation 

purpose: 

ensure that the developers and user orgainsation understand the project

* requirements workflow

idenfying functional and non fuctional requirements
used mostly in  elaboration and inception phases 

* analysis workflow 

address the creation of an analysis model of the problem domain

purpose: 

helps user orgainzation and developer undertand underlying problem and its domain without overanalysing

* Design workflow 

tansition analysis model to form a design model after implementation

enhaces the desccription of the evolving system by adding classes 

* implentation workflow

purpose:

create an excutable solution based on design model 

testing of classes i.e new and the incorparated resuable classes

* testing workflow

purpose :

 to increase quality of the evolving system

 * Deployment workflow

 associated with the transition phase of the unified process 

 includes activies such as software packaging

 ### supporting workflows
 











# Distributed systems
 cmt 308
 ## lecture 0ne

introduction
--
distributed system/distributed computing 

This is a system with multiple components located in different locations communicate  and share resources in order to do different task in the network

include virtual machines and servers

**Benefits**

1.nodes in the distributed systems are connected to each other and one can share resources

2.easily add a node (scalability)

3.failure of one node does not lead to failure of the entire distributed systems

4.sharing of resources like printers

5.Doing different tasks at a time from different locations 

6.cost effective 

7.multiple processing can be done in the system

**challenges** 

1.overloading of a request can lead to down fall of the entire system

2.incase of malicious attack On one node it may attack the entire system

3.patching of the systems may be a bit difficult

4.data can be lost when moving it from one node to another 

5.troubleshooting and diagnostics can be difficult since you are working with different nodes at different locations

**Characteristics/elements**

1.Resources sharing 

2.scalability(adding more components to the system)

3.fault tolerance (system should continue working if a node fails)

4.compatibility

5.transparency (hides the complexity of the distributed system to the user)

6.concurrency

6.openness(no limitation )

**Types of distributed systems**

1.client - server system 

client - requests resources

server -process/allocates  resources

**adavantages**

centralized system 

cost effective in the long run

**disadvantage**

traffic issues

expensive in setting up

server failure may cripple the entire system

2.peer to peer system

nodes in peer to peer system have all equal rights

**advantages**

sharing of resources is equal to all nodes

failure of one node does not affect the system 

scalability

**Disadvantages**

no centralized system making it difficult to manage 

high risks of virus attacks

less secure due to transverse exchange 
 
files and resources are not centrally organized 

3.Three tier

uses separate servers and layers for each function of a program
 
 layers include:

 presentation layer(data encryption occurs)

 application layer(human interaction layer i.e access)

 data  link layer(defines format on data in the system)

4.N-tier distributed system

follows a similar structure to the three-tier but it can contain any number of functions in the system 

**APPLICATION AREAS OF DISTRIBUTED SYSTEMS**

finance and commerce

cloud technologies

health care (online patient records) 

education(e learning)

environment management

transport and logistics(google maps)

information society(search engines)

**evolution of distributed systems**

mainframe (1960-1967)

cluster networks(1970s)altenative for mainframe computers

internet and pcs(TCP/IP)connecting difgit ferent networks

world wide web -global interconnection

p2p,grids and web services

cloud computing,mobile and IoT(internet of things)

fog and edge computing

(Decentralization of resourcves breaches the gab between client and servers)

## client server architecture
1.client/work station -has differnt types of operating systems like windows 10

2.servers-high memory capacity,more hard drive capacity,

3.network devices;include:

    1.routers -send packets specific data to an ip address that is to receive the data

 
### types of client server architecture

1.*one tier architecture*
  
   all different layers in the architecture are compressed in one system 

2.*two tier architecture*
  
    client side -stores the user interface 
    (makes reports)

    server side - access the the data base

3.*three tier architecture*
  
  there is an intermediary between the client side and the server side 

  the intermediary is called a middleware 

  it enables the client and server side to communicate effectively 

4.N tier architecture 

also known as multi-tier architecture 

entire presentation processing applications and data management functions are completely isolated from each other
### Distributed operating systems 

Distributed operating systems(DOS) -

      systems which contains multiple components located on different machines which communicate and co-ordinate functions and apppear as a single coherent working systems to the user 

      also referred to**loosely coupled system**

  ### Types of distributed operating systems###

  1.client-server

  2.peer to peer 

  3.middleware 

  3.three-tier 

  4.N-tier
### 4.Clent -server systems ###

requires the client to request a resources and the server to process the resource 
the server may server multiple clients at the same time 

also called **tightly coupled system**

### 2.peer to peer systems
   tasks are evenly distributed among the nodes 

  also called **loosely coupled systems

### 4.middleware systems

enables the interoperability of all applications running on different operating systems

provides commuinications between to or more operating systems 

## characteristics of Distributed operating systems 
1.heterogenetty 

    components tend to have differences and variety in programming  languages,operating systems  and even hard ware commponents 

2.resource sharing 

3.openness
 extensions and improvements of distributed systems 

 4.concurrency

   enables multiples activiteies to be executed at the same time even on different machines 

5.scalability
  
  allow addition of nodes and components and the system should be able to support it (growth)

6.security

 required for:
   authentication and privacy of data messages 

  7.No global clock 
  a system should have its own clock \

  8.flexiblity

  9.transparency 

  10.fault tolerance
    achieved by recovery and redundancy

  ### Advantages of distributed systems

  1.Reliblity

  2.performance 

  ## disadvantages 

  ## applications 

  1.telecommunications network 
  
  2.real time process control

  3.grid computing

  4.parallel computation


 


# DATA STRUCTURES AND ALGORITHMS 

**Data structures** - way of collecting and organizing data in such a way that we can perform operations on this data in an effective way.

**Data structures** - building blocks of any program or software 

**Examples of data structures**

1.Array

2.Stack

3.Queue

4.Linked list

**Terminologies**

**Data** - collection of values 

**Grouped items** - data items with subordinates 

**Record** - collection of various data items

**file** - collection of various records

**Attributes** - characteristics of an entity

**field** - single elementary unit of information representing attribute of an entity

**Need for data structures**

.gives different ways of organizing data

tells how data can be stored and accused in its elementary level

provides operations on groups of data such as adding an item 

provides means to manage huge amount of data efficiently 

provides fast and searching and sorting data 

**Goals of data structures**

correctness

efficiency 

**Features of data structures**

*robustness* - generating correct output for every possible input provided.

*Adaptability* - 

*user-ability* - 

**classifications of data structures**

- **primitive data structures** 

consist of the numbers and characters build in programs 

  can  be manipulated or operated directly by machine level instructions 

  also called **Single data types** since they consist of characters that can not be divided 

  - **non-primitive data structures**
  
  they can  not be manipulated or operated by machine level operations 

  further divided into: 

  1.**Linear data structures**
     
     maintains linear relationships among its elements 

     data is arranged in a linear fashion but memory management is not sequential  

2.**Non linear data structures**

data elements are not arranged in a sequential order 

there is hierachical relationship between data items 

insertion and deletion of data is not possible examples include Tree and Graph 