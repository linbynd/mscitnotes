#UNIT 5

###1. Explain briefly the various static and dynamic parts of UML.
####Static parts of UML
**Class diagram**
Class diagrams are the most common diagrams used for modeling object
oriented systems. A class diagram shows a set of classes, interfaces, and
collaborations and their relationships. We use class diagrams to illustrate
the static design view of a system. Class diagrams that include active
classes deal with the static process view of a system.

**Object diagram**

An object diagram can be considered to be an instance of a class diagram
which shows a set of objects and their relationships. We use object
diagrams to illustrate data structures, the static snapshots of instances of
the things found in class diagrams. Object diagrams deal with the static
design view or static process view of a system just as the class diagrams,
but from the perspective of a real or prototype cases.

**Component diagram**

In a component diagram we can see a set of components and their
relationships. We use component diagrams to illustrate the static
implementation of view of a system. Component diagrams are related to
class diagrams in which a component is usually mapped to one or more
cases, interfaces or collaborations.

**Deployment diagrams**

A deployment diagram shows a set of nodes and their relationships. We use
deployment diagrams to depict a static view of the run-time configuration of
processing nodes and the components that run on those nodes.
Deployment diagrams are related to component diagrams as a node
normally encloses one or more components.

####Dynamic parts of UML
**Use-case diagram**

A use case diagram shows a set of use cases and actors which is a special
kind of class, and their relationships. It provides an overview of all or a part
of the usage requirements for a system or organization in the form of a
model. We can apply use-case diagrams to show the static use case view of
a system. Use-case diagrams are particularly important in organizing and
modeling the behaviors of a system.

**Sequence diagram**

A sequence diagram is an interaction diagram that lays emphasis on the
time ordering of messages. A sequence diagram shows a set of objects and
the messages sent and received by those objects. The objects are typically
named or are anonymous instances of classes, but may also represent
instances of other things, such as collaborations, components, and nodes.
We use sequence diagrams to show the dynamic view of a system.

**Collaboration diagram**

A collaboration diagram is also an interaction diagram that emphasizes the
structural organization of the objects that send and receive messages. A
collaboration diagram may show a set of objects, links among those objects,
and messages sent and received by those objects. The objects are typically
named or anonymous instances of classes, but may also represent
instances of other things, such as collaborations, components, and nodes.
We use collaboration diagrams to show the dynamic view of a system.

**State diagram**
A state diagram shows a state machine comprising of states, transitions,
events and activities. We use state diagrams to illustrate the dynamic view
of a system. They are especially useful in modeling the behavior of an
interface, class, or collaboration. Statechart diagrams emphasize the event-
ordered behavior of an object, which is especially useful in modeling
reactive systems.

**Activity diagram**
An activity diagram shows the flow from one activity to another within a
system. An activity can show a set of activities, a sequential or branching
flow from activity to activity, and objects that act and are acted upon. We
use activity diagrams to show the dynamic view of a system. Activity
diagrams are especially important in modeling the function of a system as
they highlight the flow of control among objects.


###2. Describe the working of a state diagram.
**State diagrams**
A state diagram shows the dynamic behavior of a system. The diagram
shows the various states that an object can have and the transitions that
occur between the states.
The state object is a snapshot of an instance of the object. A state may have
an activity describing the function it performs and is represented by state
symbols while transitions are represented by arrows connecting the state
symbols. A special state, the start state, is a small darkened circle. An end
state is a hollow circle enclosing a smaller colored circle (Refer figure 5.13).
It shows the initial idle state and the transition states where the action starts
and where it ends.

The “Order”object has four states: “Create”, “Check Credit”, “Filled”, and “Shipped”. The
transitions for the “Order” object comprise of “View”, “Submit”, “Reject”,
“Fill”, and “Ship”. A transition may have guard conditions. For an example,
“Bad Credit” is the guard condition for the reject transition. To continue the
transaction the guard conditions must be met. There could be one or more
actions in response to a transition. “Do fill” is the action for the “Fill”
transition. In addition, we can specify the entry and exit actions, 

####3. Explain the different states of activity diagram.
**Activity diagrams**
Activity diagrams are special cases of state chart diagrams. An activity
diagram has actions as states. It can be considered as some kind of
elaborate flow diagram and has therefore some graphical structures for
handling conditions like a diamond shaped box for conditionals and plates
for merging control flow. Activity diagrams may contain the following states.
Activity states – These represent the performance of a step within the
workflow.

**Transitions** – They show the sequence of activity states. They are shown
by a solid arrow. A transition may branch into two or more mutually
exclusive transitions. Guard expressions label the transitions coming out of
a branch. A branch and its subsequent merge marking the end of the branch
appear in the diagram as hollow diamonds.

**Decisions** – Decisions are made by a set of guard conditions. These guard
conditions control the flow of transition of a set of alternate transitions once
the activity has been completed. They are shown by a hollow diamond

**Synchronization bars** – They are represented using a thick horizontal or
vertical line and show parallel subflows. They also can show parallel
threads. These bars are used to describe any intermediate step in a process
in the activity diagram. This process forms a logical level by itself using the
results of several different inputs. There are two types synchronization bars
namely, horizontal and vertical synchronization bars.

####4. What are packages?
**Model Management: Packages and Model organization**
In the previous section we discussed about the implementation diagrams, in
this section we will discuss the package diagrams.
All UML model elements can be organized into packages. A package is
nothing but a group of model elements. The entire system can be compared
to a single high-level package with their respective sub packages or classes
in it.

A package can be represented as a folder (Refer figure 5.19), and is shown
as a large rectangle with a tab on the upper left corner of the rectangle. It
contains the name of the contents of the package.
Packages of an Order Processing System
Store, Ordering Process,
Shipping and a fourth Business package which contains all the three
packages. The dashed arrow shows model dependency. It indicates the
dependency of the element to which it points to. In the above example,
Ordering Process is dependent on the Store, and Shipping is dependent on
the Ordering Process.


####5. Explain the mechanisms of UML extensibility.
**UML Extensibility**
The extensibility mechanisms allows you to
customize and extend the UML by adding new building blocks, creating new
properties, and specifying new semantics in order to make the language
suitable for your specific problem domain. There are two common
extensibility mechanisms that can be defined in the UML - stereotypes and
constraints.

**Stereotypes**

We can use stereotypes to expand the vocabulary of the UML and create
new model elements from existing ones. But we can only use the specific
properties which are suitable for our problem domain. Stereotypes are used
for classifying or marking the UML building blocks in order to introduce new
building blocks that speak the language of our domain and that look like the
primitive, or basic, model elements. They are represented textually by
putting the text within guillemets 
For example, when we model a network we may want to use symbols for
representing routers and hubs. By using stereotype nodes we can make
these things appear as simple building blocks. Stereotypes permit the
introduction of new graphical symbols for providing visual indication to the
models that address the vocabulary of our specific domain.
Let’s take the example for the stereotype of an actor. The representation
can be done in several ways. The actor can be
shown as a class rectangle with the label <<actor>>, or a label and a stick
figure, or just a stick figure with a label beneath it.

**Constraints**

Constraints are properties for specifying semantics or conditions that must
hold true at all times for the elements of a model. They allow us to extend
the semantics of a UML building block by adding new rules, or modifying
existing ones.
For example, when modeling hard real time systems it could be useful to
provide the models with some additional information, such as time budgets
and deadlines. We can easily show these timing requirements by using
constraints.

Automatic
transmission
Car
{XOR}
Manual
transmission

Graphically, a constraint is shown as a string enclosed by curly braces,
which is placed near the associated element, or connected to the element
by dependency relationships This notation can also be
used to visualize a model element’s basic notation, in order to give the parts
of an element’s specification that have no graphical cue. Some of the
different types of constraints usually shown are ‘complete’, ‘disjoint’,
‘implicit’, ‘new’, ‘transient’, ‘xor’ etc.