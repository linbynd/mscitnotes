#Unit.1

##1.Explain the concept of the object oriented software. 

Object oriented approach is about object. An object is the basic building block of object-oriented programming. Programmers who develop a system model create object class to represent each component of the system. This generic classes are used to create specific instance of each object in the program. Each objects contains a collection of related procedures and data for reuse. We can customize the the software system to business process easily by using objects.

We orgenize software as a collection of distinct object that has both data structure and behaviour.But in conventional programming, we find that data structure and behaviour are loosely connected the four aspect of an object of an object oriented approach are identity, classification polymorphism  and inheritance.

##2. List and describe two orthogonal views of the software.

We can easily differentiate object oriented and traditional development method as we know that traditional views software as a collection of functions. We clearly know that the primary focus of traditional approach is mainly on the functioning of the system.But object oriented system concentrates on the objects that combines data and functionality together.

So in general we have two approach in system development. The approaches are:

- Traditional approach
- Object oriented approach  

—Traditional approach has many variations in the techniques that are used to build information with the help of structured and modular programming. We call traditional approach as structured system development. 
In traditional approach we follow structured analysis and design techniques (SADT). This SADT is graphical language that describes system with a methodology. We use following three techniques in SADT

Structured Programming— We use this technique to analyze and convert business requirement in to specification and finally in to procedures.

Structured design— using this technique we define how the processing system works, what data the processing system needs to str and use the inputs that are deeded for analysis  
Structured analysis

—Object oriented approach in system development views the information system as collection of interactive object that work together to finish the task. We can develop software using object oriented software using different way.  
 Let us now discuss three different object oriented approach given below:

Object oriented analysis— we can define all the objects that are perform in the system and show the use case that are required to finish the task using the approach. we can analyze functional requirements for a system using object modelling techniques which are part of object oriented analysis. Here we do not consider any implementation constraints that exist like concurrency, distribution, persistence etc.

Object oriented design— We can define object oriented design as the process of planning a system which has interacting object for solving software problems. We can define all the types of objects that we need to communicate with people and devices in a system and show how the interaction among the objects takes place to finish the task and redefine the terms of each type of the object so that it can be used for some specific languages.

##3. What is object Oriented programming?

We can define object oriented programming as a programming paradigm that uses objects as data structures consisting of data fields and methodologies. In this method of programming, we write statements to define the objects, their types and the messages that objects send to each other. The following five basic concepts of object-oriented design are the implementation level features that are built into the programming language: 

Object – Object oriented system combines both data and functions together as a unit called as object. An object is an instance of its class. An object is defined with a specific name and is allocated memory. An object can have attributes. For example let us consider an example of the car object. The car object will have attributes like color, engine power, and speed and so on. 

Information hiding – It is the process of hiding all the details of an object that gives no contribution to its essential characteristics. In simple words, we can say that the structure of an object and the implementation of its methods are hidden. For example let us consider the stack data structure, which is a last in first out (LIFO) data structure. Here, the last item pushed on the stack will be the first item removed (pop) from the stack. An object of the class stack need not be concerned about how the stack is implemented and can make use of the push and pop operation of the stack. Information hiding is the goal of hiding all the details of an object and encapsulation is the technique used to achieve the goal. 

Inheritance – It defines the relationship among classes where one class shares the structure or behaviour of another defined class. The two types of inheritance are single inheritance and multiple inheritance. If an object obtains characteristics directly from only one object then we call it as single inheritance. If the characteristics of an object are obtained from more than one object then we call it as multiple inheritance. For example let us take a motorbike as superclass. Then the different types of bikes such as the ‘Karizma’, ‘Hero Honda’ are the subclasses of the superclass bike. The subclasses inherit the properties from the super class. 

Interface – It defines a set of services provided by a component or by a class. This allows for further encapsulation. Interface will just declare and define the methods but does not implement the methods.The interface rectangle just has a method drawrect which accepts two parameters l (length) and b (breadth) but does not show how it is implemented. 

Polymorphism – In object-oriented programming, polymorphism is defined as the ability of an object or a reference to have more than one form. ‘Poly’ means multiple and ‘morph’ means form. The main advantage of polymorphism is that it helps to reduce complexity by allowing one interface to specify an action of a general class. For example let us consider a start operation for some vehicles such as bike, bus, and car. All vehicles will have start operation but the operation of starting will be different for different vehicles. 

##4. Why is object oriented system development methodology so important?
Object oriented development offers us a different model differing from traditional software development. So in simple words we can say that object oriented software development is a way to build software by developing objects that can be easily replaced, modified and reused. In object oriented environment we consider software as a collection of discrete objects that encapsulate there data and functionality to shape real world objects.
Object oriented is very essential for software construction. We know that each objects has attributes and methodologies. We can group objects in to classes. In object oriented system each object is responsible for itself. 
For example we know that every software needs objects. For example Microsoft Windows object takes the responsibility for things like opening, sizing and closing itself. We know that chart object is responsible for things such as maintaining its data and labels.
An object oriented system emphasizes cooperative philosophy by allocating tasks among the objects for the applications. This approach is really a powerful one for us to enrich the software development process.

5. Explain the characteristics of unified approach.
Unified approach is a better way for understanding concepts of objects oriented system development. Unified approach is a methodology for software development. The unified approach, based on methodologies given by Booch, Rum Baugh and Jacobson tries to combine the methods and guidelines of unified modelling language. 
The characteristics of unified approach are as follows: 
Iterative and incremental 
We consider unified approach as an iterative and incremental development process. We can divide elaboration construction and transition phases into a series of time boxed iterations each of which results in an increment. 
The Unified Process consists of cycles that repeat over the long-term life of a system. Each cycle ends with a release and there will be releases within a cycle. 
Let us analyze the cycles or phases briefly: 
Elaboration Phase – During this phase, we specify most of the use cases in detail and design the system architecture. This phase mainly focuses on "Do-Ability" of the project.  
Construction Phase – During this phase, we move the product from the architectural baseline to a system that is complete enough to transfer the product to the user community.  
Transition Phase – In this phase, we need to ensure that the requirements are met to satisfy the stakeholders. Other activities of this phase are site preparation, manual completion, and defect identification and correction based on beta testing and user feedback. 
Use case and risk driven 
In the Unified process, we make use of use cases to capture the functional requirements and to define the contents of the iteration. Use case will help us to drive the development in all phases successive to the requirements analysis and will affect all views of the software. For all iterations, we take a set of use cases or scenarios through implementation, test and deployment. We require the project team to focus on addressing the critical risks at an early stage in the project life cycle using unified approach. We need to select the deliverables of all iterations especially in the elaboration phase in order to make sure that we address the greater risks first. 
Architecture centric 
The architecture centric approach is the core for any project team that puts efforts to model the system. Since no single model is sufficient for us to cover all aspects of a system, the unified approach supports us with multiple architectural models. The most important deliverable of the approach that we get from elaboration phase is the executable architecture baseline. 
We develop applications using a layered architecture also. Layered architecture is an approach that allows us to develop the software system to create objects that are concrete and independent of how they represent themselves to a user via interface stored in database. Layered approach has user interface, business and access layers. Using this approach we can reduce the interdependency of user interface, access of database and business control. Thus finally it gives us a robust and flexible system to work on. 


#Unit. 2 
##1. What are Objects, attributes and classes?
**Objects**— An object is a real world entity, comprising of data and methods to manipulate the data. 
We can have many objects nested inside one object. 
We are aware of the meaning of an object, but we have to describe the exact use of an object in software development. Every real time entity can be called as an object. For example, pie charts, tables, printers, words, numbers etc. There are mainly two points to keep in mind while selecting an object. 
**Attribute**— Every object has its own state and property which help us to differentiate the behaviour of an object with another. Let us see the definition of an attribute. 
Definition: An attribute is defined as an entity that sets the properties of an object. 
**Classes**: Object grouping 
Now that we have seen the way to define an object using attributes, let us study the way to group these objects. Objects are grouped into a class. The class definition is given below. 
Definition: A class is defined as a group of objects with the same structure and behavior. 

##2. How do object respond to messages?

**Object’s response to messages**

Let us see how an object responds to a message using their instances.
Consider that a person named ‘Joe’ writes with two pens of same type but
different colors say red and blue. Here ‘Joe’ is an instance of a class
‘Person’ and the ‘red pen’ and ‘blue pen’ are instances of a class ‘Pen’.
When an object of the class ‘Person’ has to interact with an object of the
class ‘Pen’, a message is sent. The person class can send a write message
to the pen class to use the pen. It can use a color message to identify and
use the different colored pens. These messages send to the objects have
three parts. They are:

- Operation requested
- Inputs for the problem given as parameters in the message
- Actual result or the output data obtained

**Response to Messages**
Here the object of the class ‘Person’ sends a write message to one object of
the class ‘Pen’. If the object of person class is ‘Joe’ and the object of the pen
class is ‘blue pen’ then using the write message Joe can write using a blue
pen. Similarly the object Joe sends a color message to the red pen object,
and the color red is displayed.

Messages are known as non specific functions. A function tells us how to do
a task and a message tells us what to do in the task. These are not equal to
sub-routines, as different objects respond to the same message in a
different way. Every object uses the message according their
requirement. The line object uses it to draw a line, the circle object uses it to
draw a circle and the rectangle object uses it to draw a rectangle.
In different programming languages methods are called differently. In a C
program, we call a function by its name, while in a Basic program we call the
sub-routine. In an object oriented program we call a method of an object by
sending a message to the object. We have to clearly know the difference
between a message and a method. If we want an object to draw a chart, we
will send a message ‘draw’ to the object. This message is used not only to
draw a chart, but also to draw other pictures and tables. We can call the
method to draw a chart using a name ‘draw chart’. This method is used to
draw only a chart. This shows the difference between a message and a
method. In object oriented programming if we send a message to an object,
it searches for the method with the same name as the message. If it finds
the method then executes the method to solve the problem. If the object
does not find the method in this class then it searches all the superclasses
until it finds the method or shows an error that the method is not found.


##3. What is encapsulation and abstraction?

**Encapsulation**
Definition: Encapsulation or information hiding is defined as the mechanism
to hide all the methods and data inside the object so that only important data
is accessible to the user.
The word ‘encapsulation’ is used so that a user cannot see inside the
‘capsule’, but can use the methods inside the object. We can say that
encapsulation is the design goal of object oriented systems. We can use this
technique to insulate the details of the internal objects from other objects.
Using encapsulation we can avoid strong dependencies among the different
components of programs. We can use encapsulation in languages other
than object oriented languages, but the ability of object oriented languages
to group the data structures and behaviors as a single entity makes
encapsulation powerful.
For the example of encapsulation, consider the loan approval process in a
bank. If we want a loan to be approved, we have to fill the form and wait for
the approval. The steps of loan approval process are carried out by the loan
department of the bank. Here these steps are hidden or encapsulated from
us.
**Abstraction**
Definition: Abstraction is defined as the mechanism that removes or hides
some characteristics of an object and shows only the relevant data to the
user.
Abstraction may seem same as encapsulation but in encapsulation we know
only the inputs and the output of the process. The implementation of the
process is fully hidden from us. In abstraction we refer the essential
properties of an object which differentiates it from other types of object.
Abstraction is used to reduce complexity and enhance efficiency of the
object oriented system.

While hiding or removing aspects of the object we have be careful that all
the relevant aspects of an object is accessible to the user and only the
extraneous ones are left out. If we are using a truck, the information about
the truck we need to know is the use of the steering wheel, brake, gas pedal
and the way of transmission. We do not have to know the mechanism of
locomotion of the truck. Here we can abstract this mechanism.

##4.Explain inheritance with an example.
vinit
What is association and aggregation.
2 edited for testing git.