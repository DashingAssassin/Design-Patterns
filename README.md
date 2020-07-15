# Design-Patterns
# <h4> This particular repository will try to explain how to implement different design patterns in java</h4>
# <h4> Please read the following to have  better understanding about design patterns </h4>
Design Patterns 
	What are design patterns?
	Design patterns are standardized solution to real life complex industry problem when designing an application.
	For example:-
	When constructing an instance is quite costly you use creational design patten(example Singleton,Factory, abstractFactory,builder)
	When you want to reuse an instance and build new instance on top of that you use Structural design patten eg. Decorator design pattern

Types of Design Patterns

	1. Creational <br/>
		a) It deals with creation of an object <br/>
	2. Structural <br/>
		a) It deals with the composition of object. <br/>
		b) More precisly what does a class contain? and what it's relationhip with other classes? Inheritance or composition <br/>
	3. Behavioural <br/>
		a) It deals with behaviour of object i.e. interaction between object <br/>


Structural Design Pattern:-
	Type:- <br/>
	1. Proxy Pattern <br/>
	2. Decorator Pattern <br/>
	3. Facade Pattern <br/>
	4. Adapter Pattern <br/>
	5. FlyWeight Pattern <br/>


Proxy Pattern:- <br/>
	A proxy hides the  complexitiy involved in communicating with real object. An object that represent another object.<br/>
	E.g. A debit card is proxy to bank account.Any transation done by debit card result in decrease of amount in  bank account.
	Similarly, you have to program an interaction with other remote object. In such scenario, <br/>
	1. you would create proxy to take care of all external communications <br/>
	2. You would communicate with it as if it were residing in your local machine <br/>
 	A good example is the EJB Home and Remote interfaces.
