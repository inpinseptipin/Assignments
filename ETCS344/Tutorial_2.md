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
The purpose of a diagram should be understood clearly to implement it practically. The purposes of object diagrams are similar to class diagrams.The difference is that a class diagram represents an abstract model consisting of classes and their relationships. However, an object diagram represents an instance at a particular moment, which is concrete in nature.
It means the object diagram is closer to the actual system behavior. The purpose is to capture the static view of a system at a particular moment.
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


## Activity Diagram

## Statechart Diagram

## Deployment Diagram

## Component Diagram

## Sequence Diagram
