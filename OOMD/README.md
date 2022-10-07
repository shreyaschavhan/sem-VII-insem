## 𝐎𝐛𝐣𝐞𝐜𝐭 𝐎𝐫𝐢𝐞𝐧𝐭𝐞𝐝 𝐌𝐨𝐝𝐞𝐥𝐢𝐧𝐠 𝐚𝐧𝐝 𝐃𝐞𝐬𝐢𝐠𝐧

> - Unit I  : Introduction to Modeling
> - Unit II : Advanced Class Modeling and State Modeling


## 𝐔𝐧𝐢𝐭 𝐈: 𝐈𝐧𝐭𝐫𝐨𝐝𝐮𝐜𝐭𝐢𝐨𝐧 𝐭𝐨 𝐌𝐨𝐝𝐞𝐥𝐢𝐧𝐠

<div align=center>
  <br>

  ![image](https://user-images.githubusercontent.com/68887544/193409982-b9b0e530-fe4d-41d0-8da0-de82320c3866.png)

  <br>
</div>

- What is Object Orientation?
> - Organization of software as a collection of discrete/distinct objects that incorporate both data structure and behavior.
> - There are 4 aspects of OO:
>   - Identity: Means data is arranged in distinguished entities called objects.
>   - Classification: It's a technique in which objects with same data structure (attribute) and behavior(operations) are grouped into class.
>   - Inheritance: Allowing the class to share properties of another class in hierarchical manner.
>   - Polymorphism: Same operation can be defined differently for the different classes.

- What is OO Development?
> - Design and Development of software according to software development life cycle on the basis of OO Principles is known as OO development.
> - The oo development contains following steps:
>   - System conception
>   - Analysis
>   - System Design
>   - Class Design
>   - implementation

- The three models:
> - There are three kind of models to describe a system:
>   - State model:
>     - Describes aspects of an object that change over time.
>     - Contains state diagrams
>   - Class model:
>     - Describes static structure of objects in a system.
>     - Contains class diagrams
>   - Interaction model:
>     - Describes how the objects interacts with the system to achieve results.
>     - Contains interaction diagrams

- OO Themes:
> - There exists various themes for OO development and design
> - Some of the most essential among them are:
>   - Abstraction: Abstraction stands for hiding overall details and only looking at the information which is appropriate at a given instance.
>   - Encapsulation: Wrapping up functions into a single entity i.e. class is known as encapsulation
>   - Sharing: Also known as inheritance, share data structure and behavior with other subclasses.

- Evidence for usefulness of OO development:
> - OO development at General Electric Research and Development Research used OO techniques for developing compilers, graphics, user interface, database, oo language, cad systems, simulations, metamodes, control system, tec.
>

- Modelling as design technique:
> - Understand something by building a model before building something in real is known as modelling.
> - We use modelling as a design technique where ever we require
>   - Testing of a physical entity before building it
>   - Communication with customers
>   - Visualization
>   - Reduction of complexity

- Abstraction:
> - Abstractions stands for hiding everything except which is necessary in order to increase efficiency and reduce complexity.

- The three models:
> - Class models
> - State models
> - Interaction models

- Class modeling:
> - Modelling and organizing objects inside classes is called as class modelling.

- Object and class concept:
> - Object: Objects are data fields that has unique attributes and behaviors.
> - Class: Class is the collection of objects with similar attributes and behaviors.

- Link and association concepts:
> - Links and associations are mean for establishing relationships.
> - Link: Semantic/physical connectivity between two objects is called as a link.
> - Association: Semantic/physical connectivity between two classes is called as a link.
> - Aggregation, Multiplicity, Composition
> - Aggregation:
>   - a special form of association where:
>   - the association represents has-a relationships
>   - which is unidirectional and
>   - each entity can survive individually.
> - Composition:
>   - Is a restricted version of Aggregation where:
>   - association represents part-of relationship
>   - and each entity cannot exists without existence of other entity.


- Generalization and Inheritance:
> - Generalization:
>   - is the relationship between class and one or more variations of the class.
>   - Generally called as `is-a` relationship.
>   - Has 3 purposes:
>     - Support for Polymorphism
>     - To structure the description of objects
>     - Enable reuse of code 





## 𝐔𝐧𝐢𝐭 𝐈𝐈: 𝐀𝐝𝐯𝐚𝐧𝐜𝐞𝐝 𝐂𝐥𝐚𝐬𝐬 𝐌𝐨𝐝𝐞𝐥𝐢𝐧𝐠 𝐚𝐧𝐝 𝐒𝐭𝐚𝐭𝐞 𝐌𝐨𝐝𝐞𝐥𝐢𝐧𝐠


<div align=center>
  <br>

![image](https://user-images.githubusercontent.com/68887544/193409990-6a82fb38-1285-4563-84c0-f957d3a3402b.png)

  <br>
</div>


- Advanced objects and class concept:
> - Advanced class are special types of classes that can be used to be represented in UML diagram. These are:
>   - Enumeration
>   - Multiplicity
>   - Scope
>   - Visibility
> - Enumeration: Enumeration is a primitive data type which can have a finite set of values and can be modelled as classes.
> - Multiplicity: Multiplicity denotes how many objects can be associated with particular object.
> - Scope: Scope represents whether a feature is available for a class or not.
>   - There are 2 types of scope in UML:
>     - Static scope
>     - Object/Instance scope
> - Visibility: It represents how the attributes and operations are visible in the system.
>   - There are 4 levels of Visibility:
>     - public
>     - protected
>     - private
>     - package


- Association ends:
> - Endpoints of association relationship is called as association ends.

- n-ary Association:
> - Association is a structural relationship between two classes.
> - It can be shown by drawing a solid line between two classes.
> - Association between two classes are called binary.
> - Association between three classes are called ternary.
> - Association between three or more classes are called n-ary association.

- Aggregation:
> - Aggregation is a type of Association
> - It is used to represent whole-part relationship.
> - It normally posses has-a relationship
> - For example: car has a dvd player

- Abstract classes:
> - Abstract classes are those classes which do not have any direct instances.
> - When generalization is modelled, the abstract classes are at the top level and other classes are at the bottom.

- Concrete classes:
> - Concrete classes are those classes who have direct instance.

- Multiple Inheritance:
> - It is possible for a class to have more than one superclass in UML.
> - That means a child can have more than one parent and this property is known as multiple inheritance.
> - MI is not allowed in every oop language.
> - Java and C# only allow single inheritance.

- Metadata:
> - It is a data about data.
> - A class definition is basically a metadata.

- Reification:
> - The process of converting an element which isn't an object into an object within a scope of particular system is known as Reification.

- Constraints:
> - A condition or a restriction on UML elements are known as constraints.
> - These elements can be classes, objects, generalization set, associations, etc.
> - It must evaluate to boolean value - true or false.

- Derived data:
> - A data that can be derived by any element involved in the software system is called as derived data.
> - Derived data can be completely determined by any component of the class model and hence it is redundant.

- Package:
> - A container that organize models by grouping things is called as package.

- State Modeling:
> - It represents the number of sequence of operations that occur in response to the external stimuli.
> - The state model is represented using the state diagram.

- Event:
> - Every single thing or action occurred at a particular time instance is termed as an event.
> - Events are often denoted by the verbs in past tense.
> - Events can be classified into 4 types:
>   - Signal event : Event meant for description of an asynchronous event communicated amongst instances.
>   - Change in a state event : An event which depicts a change or transformation in state after fulfilment of certain condition.
>   - Passing of time event: An event that shows passage of time. Often denoted by `after` or `when` keywords.
>   - Call event: This event illustrates actual dispatch and report of a particular system.

- State:
> - A condition or situation where an object waits for some kind of event to occur is known as state.
> - A state has five parts:
>   - each state in a state diagram contains zero or more activities.
>   - a state name
>   - entry and exit condition
>   - Internal transition of a State
>   - Substates
>   - deferred events

- Transitions and Conditions:
> - Path or relationship between two states is called as transition.
> - It is responsible for showing the actual transformation or change from one state to any other state in the state machine configuration.
> - Transitions are shown as a line between two states or pseudostates with a solid arrowhead pointing to the destination state.

- State diagrams and its behaviors:
> - It depicts the behavior of software system and can be used to model the behavior of different elements like class, a subsystem or an entire system.
> - We use state diagram to design the dynamic aspects of the software system.
> - State diagram depicts the implementation of each specific elements involved in the software system scenario.
