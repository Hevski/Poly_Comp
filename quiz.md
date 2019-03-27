# Polymorphism
## What does the word 'polymorphism' mean?
- Many Forms

## What does it mean when we apply polymorphism to OO design? Give a simple Java example.

- An abstract class that can have many subclcasses that inherit from it.

- Vehicle abstract class can have Car, Mortorbike, van etc that inherit from it - these classes are all forms of vehicle - A car is a vehicle, a Mortorbike is a vehicle.

## What can we use to implement polymorphism in Java?

- By using abstract classes and interfaces.

## How many 'forms' can an object take when using polymorphism?

- Many

## Give an example of when you could use polymorphism.

- If we had a business with many different types of employee - cleaner, assistant, chef, developer, scrum master, project manager, manager, CEO - we could make them all inherit from a parent abstract class Employee, they would inherit any property an employee has plus they would have their own properties.

- Another example is using interfaces - An interface called IEmployed - each class would implement IEmployed and take on any of the methods declared within the interface e.g. getPaid method.  This can be better than inheritance as there is no inheritance chain.

# Composition
## What do we mean by 'composition' in reference to object-oriented programming?

- Breaking a program up into smaller parts

## When would you use composition? Provide a simple example in Java.

- A car dealership can have a till, A separate till class can be written then passed in to Dealership so Dealership has all the functionality of till.

- A Car is made up of different components, each component can have its own class which is passed in to the Car as properties. A car has an engine, a car has a steering wheel.

## What is/are the advantage(s) of using composition?

- It helps if you want to make changes to something in the future - makes the program more scalable.  Also if an object is deleted it means all the components don't get deleted with it.
