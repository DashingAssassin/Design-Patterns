# Design-Patterns
# This particular repository will try to explain how to implement different design patterns in java
# Please read the following to have  better understanding about design patterns
Design Patterns 
What are design patterns?
Design patterns are standardized solution to real life complex industry problem when designing an application.
For example:-
When constructing an instance is quite costly you use creational design patten(example Singleton,Factory, abstractFactory,builder)
When you want to reuse an instance and build new instance on top of that you use Structural design patten eg. Decorator design pattern

Types of Design Patterns

1. Creational
	a) It deals with creation of an object
2. Structural
	a) It deals with the composition of object. 
	b) More precisly what does a class contain? and what it's relationhip with other classes? Inheritance or composition
3. Behavioural
	a) It deals with behaviour of object i.e. interaction between object


Structural Design Pattern:-
Type:-
1. Proxy Pattern
2. Decorator Pattern
3. Facade Pattern
4. Adapter Pattern
5. FlyWeight Pattern


Proxy Pattern:-
	A proxy hides the  complexitiy involved in communicating with real object. An object that represent another object.
	E.g. A debit card is proxy to bank account.Any transation done by debit card result in decrease of amount in  bank account.
	Similarly, you have to program an interaction with other remote object. In such scenario, 
	1. you would create proxy to take care of all external communications
	2. You would communicate with it as if it were residing in your local machine
