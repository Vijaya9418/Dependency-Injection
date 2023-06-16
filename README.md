# Dependency-Injection

![Dependency-Injection](https://github.com/Vijaya9418/Dependency-Injection/assets/56352158/b0e22da4-b829-4c55-bda1-516046e080f1)


what is dependency Injection:-

It is a design pattern commonly used in software development especially in object oriented programming which involves providing the dependencies that a class or object requires from an external source, rather than letting the class create or find its dependencies on its own. By doing so, the class becomes loosely coupled with its dependencies, making it more modular, flexible, and easier to test and maintain.

It also simplifies unit testing, as mock or stub objects can be easily provided during testing to isolate the class under test.

Overall, dependency injection helps improve modularity, maintainability, testability, and reusability of software systems by decoupling classes and their dependencies.

Advantages:-
Implementing dependency injection provides you with the following advantages:

Reusability of code
Ease of refactoring
Ease of testing


Example:-

Classes often require references to other classes. For example, a Car class might need a reference to an Engine class. These required classes are called dependencies, and in this example the Car class is dependent on having an instance of the Engine class to run.

There are three ways for a class to get an object it needs:

The class constructs the dependency it needs. In the example above, Car would create and initialize its own instance of Engine.
Grab it from somewhere else. Some Android APIs, such as Context getters and getSystemService(), work this way.
Have it supplied as a parameter. The app can provide these dependencies when the class is constructed or pass them in to the functions that need each dependency. In the example above, the Car constructor would receive Engine as a parameter.


There are 3 types of Dependency Injections.
