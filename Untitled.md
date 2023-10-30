

**What do we mean by coupling and cohesion when discussing structured design?**

first of all it is important to define what structured design is :
"Structured Design is a systematic methodology to determine design specification of software". 
quoted from 'https://www.oreilly.com/library/view/software-engineering/9788131758694/xhtml/chapter006.xhtml'
meaning it is often used in large and more complex system s where the design process is required to be more structured to ensure clarity, maintainability and ease of implementation. 
it is particularly relevant for larger software systems where there is a need for collaboration between developers. It provides a structured framework for breaking down a problem into manageable components and systematically designing software solutions.
One of the historical methodologies associated with structured design is the "Structured Systems Analysis and Design Method" (SSADM), which was widely used in the field of information systems development.
source 'https://www.geeksforgeeks.org/structured-analysis-and-structured-design-sa-sd/'

so what are cohesion and coupling apart from two very important concepts in software design:
Cohesion :
The objective in structured design is to create or have modules with high cohesion because this means that the elements within a module are closelyrelated and have a common purpose.this way they easier to understand and maintain. Elemts within a module can be functions, class, components..exc and and when there is high cohesion tit means that these elements are related and have a common purpose. High cohesion means the modules have a singular purpose, and their behavior is easy to understand, they are reusable and when changes are required, it's easier to locate and update the relevant code within a highly cohesive module.
Coupling :
contrastingly to cohesion a low coupling is what is most desirable. The aim in structured desig is to reducing coupling between modules. Coupling refers to the interdependece between modules. 
This is because Modules should communicate through well-defined, limited interfaces, and information hiding is often used to reduce coupling.
When there is low coupling between modules in a software system it means  it's easier to modify one module without affecting other modules and the a change to one module should have minimal to none ripple effects on other modules. 

The relationship between cohesion and coupling can be summarized as follows: High cohesion focuses on the internal organization of a module, making it clear, understandable, and reusable, while low coupling focuses on the relationships between modules, making the system flexible, maintainable, and testable.



**What is the difference between top-down and bottom-up design? Which best describes a function oriented design?**

top-down design means the decomposition of a system into smaller parts in order to comprehend its compositional sub-systems.
quoted from 'https://www.techopedia.com/definition/9744/top-down-design#:~:text=What%20Does%20Top%2DDown%20Design,detailing%20any%20first%2Dlevel%20subsystems.'
https://www.geeksforgeeks.org/difference-between-bottom-up-model-and-top-down-model/

Bottom up is a design, individual parts of the system are specified in detail. The parts are linked to form larger components, which are in turn linked until a complete system is formed.

boht bottom up and top down represent different strategies for breaking down a problem into smaller components and then building the solution. 

Top-down design is favored when the overall system architecture and structure are critical and need to be well-defined from the beginning. It's suitable for projects where understanding the system's high-level goals is essential.

Bottom-up design is useful when you have well-established components or when you want to take advantage of existing modules. It allows for early testing and validation of components, which can be advantageous in complex systems.

because in a function-oriented design a system's functionality is organized around individual functions or methods, each of which performs a specific task or operation, basically to say that a system is decomposed into fucntion the best methodology is the top-down design. 




**In which design methodology would a class diagram be most useful?**

A class diagram 'is a type of static structure diagram that describes the structure of a system by showing the system's classes, their attributes, operations (or methods), and the relationships among objects'
quoted from : 'https://www.visual-paradigm.com/guide/uml-unified-modeling-language/what-is-class-diagram/'
it is a type of UML ( unified modeling language that is used to visually represent the structure and relationships of classes in a software system. 

Its Key components are : class, attributes, methods, dependency, composition ..exc, Class diagrams are just one type of UML diagram, and they complement other UML diagrams, such as use case diagrams, sequence diagrams, and activity diagrams, which provide different perspectives on a software system's structure and behavior.

Because class diagrams allow us to model and visualize classes in our software system including attributes and methods they are a fundamental part of object-oriented modelling. 
class diagrams play a pivotal role in representing the structure and relationships of classes within a system and therefore are most useful in the context of object- orientes design and object-oriented programming which are centralised on software systems based on objects. 





**What are the four pillars of object oriented programming? Give a single-sentence description of each.**

quoted from :https://datatrained.com/post/four-pillars-of-oops/#:~:text=Pillars%20of%20OOPs-,Object%2DOriented%20Programming%20(OOP)%20is%20a%20programming%20paradigm%20that,code%20into%20a%20single%20object.

1) Abstraction :
Abstraction involves simplifying complex reality by modeling classes based on real-world entities or concepts. 
2)Polymorphism :
Polymorphism enables objects of different classes to be treated as objects of a common base class, allowing for methods to be called on objects without knowing their specific types.
3)Inheritance :
Inheritance allows a new class to inherit the properties and behaviors of an existing class.
4) Encapsulation :
Encapsulation is the principle of bundling data (attributes) and the methods (functions) that operate on that data into a single unit (an object).





**What is the strategy pattern? How would its implementation differ between a functional and object oriented system?**

The Strategy Pattern is a design pattern in object-oriented programming that falls under the behavioral design patterns category. It defines a family of algorithms, encapsulates each one, and makes them interchangeable. The Strategy Pattern allows a client to choose the appropriate algorithm to use at runtime, providing flexibility and enabling changes to algorithm implementations without altering the client's code. It is commonly used in scenarios where there are multiple ways to perform a specific task, such as sorting algorithms, payment processing, or rendering in computer graphics.

The implementation of the Strategy Pattern can differ in how it is applied in a functional programming (FP) paradigm compared to an object-oriented programming (OOP) paradigm.

In Object-Oriented Programming (OOP):
Think of it like having different tools in a toolbox.
The toolbox (context) knows how to use tools (strategies) but can switch between them.
Each tool (strategy) has a specific job (algorithm).
You can add new tools (strategies) to the toolbox without changing how the toolbox works.

In Functional Programming (FP):
t's like having different recipes to make a sandwich.
Each recipe (strategy) tells you how to make a sandwich in a different way.
You can use one recipe at a time to make a sandwich.
You can easily switch between recipes to make different sandwiches.

The Strategy Pattern is like having a choice of tools in your toolbox or a set of recipes for making sandwiches. It allows you to pick the right tool or recipe for the job without making big changes. It's all about flexibility and having different ways to get things done.


**Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.**


because Object-Oriented Design is like building with LEGO blocks. Each block represents a piece of your software, and you can assemble them to create anything you want, i would pick this option. I would like that my payment be as flexible and original as possible for many businesses to use. The beauty ofObject-Oriented Design is that you can create a payment system that can adapt to different businesses without rewriting everything. It's like having a toolbox with versatile tools that can be used for various tasks, just like LEGO blocks for different creations.










