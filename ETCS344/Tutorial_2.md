# Tutorial 2

**Explain with suitable example :  UML Includes the following nine diagrams**
  1. Class diagram
  2. Object diagram
  3. Use case diagram
  4. Collaboration diagram
  5. Activity Diagram
  6. Statechart diagram
  7. Deployment diagram
  8. Component diagram
  9. Sequence diagram
    
## Class Diagram
The UML class diagram is a graphical notation used to construct and visualize object oriented systems. A class diagram in the unified Modeling Language (UML) is a type of static structure diagram that describes the structure of a system by showing the system's:

  1. Classes
  2. Attributes
  3. Operations
  4. Relationship among objects
  
Class Diagram is a static diagram. It represents the static view of an application. Class diagram is not only used for visualizing , describing , and documenting different aspects of a system but also for constructing executable code of the software application.

Class diagram describes the attributes and operations of a class and also the constraints imposed on the system. The class diagrams are widely used in the modeling of objectoriented systems because they are the only UML diagrams, which can be mapped directly with object-oriented languages.

Class diagram shows a collection of classes, interfaces, associations, collaborations, and constraints. It is also known as a structural diagram.

Class diagram clearly shows the mapping with object oriented languages such as Java , C++ etc. From practical experience, class diagram is generally used for construction purpose.

Class Diagrams are used for 
  1. Describing the static view of the system.
  2. Showing the collaboration among the elements of the static view.
  3. Describing the functionalities performed by the system.
  4. Construction of software applications using object oriented languages.
### Example  
![Example](https://miro.medium.com/max/1200/1*szU8ngrWSXmBNPYReMyK5w.png)

## Object Diagram
Object diagrams are derived from class diagrams so object diagrams are dependent upon class diagrams.
Object diagrams represent an instance of a class diagram. The basic concepts are similar for class diagrams and object diagrams. Object diagrams also represent the static view of a system but this static view is a snapshot of the system at a particular moment.
Object diagrams are used to render a set of objects and their relationships as an instance. 

### Purpose of Object Diagrams
The purpose of a diagram should be understood clearly to implement it practically. The purposes of object diagrams are similar to class diagrams.The difference is that a class diagram represents an abstract model consisting of classes and their relationships. However, an object diagram represents an instance at a particular moment, which is concrete in nature.It means the object diagram is closer to the actual system behavior. The purpose is to capture the static view of a system at a particular moment.

The purpose of the object diagram can be summarized as −
  
  1.Forward and reverse engineering.
  
  2.Object relationships of a system
  
  3.Static view of an interaction.
  
  4.Understand object behaviour and their relationship from practical perspective
  
### Where to use Object Diagram
Object diagrams are imagined as a snapshot of a running system at a particular moment. For example : Take an example of a car, The snapsht will show a static picture of
  1. a particular state which is running.( States such as if the car is moving , or its stopped)
  2. A particular number of passengers in the car , does it change over time.

Object Diagrams are used for 
  1. Making the prototype of a system.
  2. Reverse Engineering
  3. Modeling complex data structures.
  4. Understanding the system from practical perspective.
  
### Example

![example](https://www.tutorialspoint.com/uml/images/uml_object_diagram.jpg)

## Use Case Diagram
Use case diagram is the primary form of system/software requirements for a new software program underdeveloped. Use cases specify the expected behaivor , but no the exact method of how it happens. Use cases once specified can be denoted both textual and visual representation. A key concept of use case modeling is that it helps us design a system from the end user's perspective. It is an effective technique for communicating system behavior in the user's terms by specifying all externally visible system behavior.

### Purpose of Use Case Diagram
Use case diagrams are typically developed in the early stage of development and people often apply use case modeling for the following purposes:

  1.Specify the context of a system
  2.Capture the requirements of a system
  3.Validate a systems architecture
  4.Drive implementation and generate test cases
  5.Developed by analysts together with domain experts
  
Use case diagrams specify the events of a system and their flows. But use case diagram never describes how they are implemented. Use case diagram can be imagined as a black box where only the input, output, and the function of the black box is known.
  
### Where it is used
Use case diagrams can be used for :
  1. Requirements analysis and high level design.
  2. Model the context of a system.
  3. Reverse Engineering
  4. Forward Engineering.
  
### Example
![example](https://i.ytimg.com/vi/jhHP6AeRFj8/maxresdefault.jpg)

## Collaboration Diagram
The collaboration diagram is used to show the relationship between the objects in a system.it depicts the architecture of the object residing in the system as it is based on object-oriented programming. An object consists of several features. Multiple objects present in the system are connected to each other. The collaboration diagram, which is also known as a communication diagram, is used to portray the object's architecture in the system.

### Notations
  1. Objects 
  2. Actors
  3. Links
  4. Messages
  
  
  ![example](https://static.javatpoint.com/tutorial/uml/images/uml-collaboration-diagram.png)
  
### When to use
  1. To model collaboration among the objects or roles that carry the functionalities of use cases and operations.
  2. To model the mechanism inside the architectural design of the system.
  3. To capture the interactions that represent the flow of messages between the objects and the roles inside the collaboration.
  4. To model different scenarios within the use case or operation , involving a collaboration of several objects and interactions.
  5. To support the identification of objects participating in the use case.
  6. In the collaboration diagram, Each message constitutes a sequence number, such that the top level message is marked as one and so on. The messages sent during the same call are denoted with the same decimal prefix, but with different suffixes of 1,2 etc. as per their occurence.
  
### Example
![example](https://i.ytimg.com/vi/5VEcAG22Zzg/maxresdefault.jpg)


## Activity Diagram
Activity diagram is a flowchart to represent the flow from one activity to another activity. The activity can be described as an operation of the system. The control flow is drawn from one operation to another. This flow can be sequential,branched,or concurrent. Activity diagrams deal with all type of flow control by using different elements such as fork,join etc.

## Purpose
  1. Draw the activity flow of a system.
  2. Describe the sequence from one activity to another.
  3. Describe the parallel, branched and concurremt flow of the system.

## Use Case
  1. Modeling work flow by using activites.
  2. Modeling business requirements.
  3. High level understanding of the system's functionalities.
  4. Investigating business requirements at a later stage.

### Example
![example](https://www.guru99.com/images/1/052919_1151_UMLActivity2.png)

## Statechart Diagram
A Statechart diagram describes a state machine.Statechart diagrams define different states of an object during its lifetime and these states are changed by events. Statechart diagrams are useful to model the reactive systems. Reactive systems can be defined as a system that responds to external or internal events.

### Purpose
  1.To model the dynamic aspect of a system.
  2.To model the life time of a reactive system.
  3.To describe different states of an object during its life time.
  4.Define a state machine to model the states of an object.
  
### Where to Use
  1.To model the object states of a system.
  2.To model the reactive system. Reactive system consists of reactive objects.
  3.To identify the events responsible for state changes.
  4.Forward and reverse engineering.

### Example
  ![example](https://upload.wikimedia.org/wikipedia/commons/thumb/c/cf/Finite_state_machine_example_with_comments.svg/1200px-Finite_state_machine_example_with_comments.svg.png)

## Deployment Diagram
Deployment diagrams are used to visualize the topology of the physical components of a system, where the software components are deployed.Deployment diagrams are used to describe the static development view of a system. Deployment diagrams consists of nodes and their relationships.

### Purpose
  1. Visualize the hardware topology of a system.
  2. Describe the hardware components used to deploy software components.
  3. Describe the runtime processing nodes.

### Where to Use 
  1. To model the hardware topology of a system.
  2. To model the embedded system.
  3. To model the hardware details for a client server system.
  4. To model the hardware details of a distributed application.
  5. For Forward and Reverse Engineering.
  
### Example
![example](https://www.guru99.com/images/1/052919_0743_DeploymentD6.png)
  

## Component Diagram
Component diagrams are different in terms of nature and behavior. Component diagrams are used to model the physical aspects of a system. Component diagrams are used to visualize the organization and relationships among components in a system. These diagrams are also used to make executable systems.

### Purpose
  1. Visualize the components of a system.
  2. Construct executables by using forward and reverse engineering.
  3. Describe the organization and relationships of the components.

### Where to Use
  1. Model the components of a system.
  2. Model the database schema.
  3. Model the executables of an application.
  4. Model the system's source code.

### Example
![example](https://d3n817fwly711g.cloudfront.net/uploads/2018/09/New-Component-Diagram-for-Online-Shopping-System.png)

## Sequence Diagram
Sequence diagrams are a popular dynamic modeling solution in UML because they specifically focus on lifelines, or the processes and objects that live simultaneously, and the messages exchanged between them to perform a function before the lifeline ends.
A sequence diagram is a type of interaction diagram because it describes how—and in what order—a group of objects works together.

### Purpose
  1.Represent the details of a UML use case.
  2.Model the logic of a sophisticated procedure, function, or operation.
  3.See how objects and components interact with each other to complete a process.
  4.Plan and understand the detailed functionality of an existing or future scenario.

### Use Case
  1.Usage scenario: A usage scenario is a diagram of how your system could potentially be used. It's a great way to make sure that you have worked through the logic of every usage scenario for the system.
  2.Method logic: Just as you might use a UML sequence diagram to explore the logic of a use case, you can use it to explore the logic of any function, procedure, or complex process.
  3.Service logic: If you consider a service to be a high-level method used by different clients, a sequence diagram is an ideal way to map that out.
  4.Sequence diagram Visio - Any sequence diagram that you create with Visio can also be uploaded into Lucidchart. Lucidchart supports .vsd and .vdx file import and is a great Microsoft Visio alternative. Almost all of the images you see in the UML section of this site were generated using Lucidchart.

### Example
![example](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9b/CheckEmail.svg/340px-CheckEmail.svg.png)
