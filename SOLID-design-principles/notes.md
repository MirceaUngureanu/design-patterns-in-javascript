#### Single Responsibility Principle
Single Responsibility states that an Object be responsible for a single unit of work.

Separation of Concerns states that applications should be split into modules whose functionalities overlap as little as possible.

Single Responsibility Principle (SRP)- give each class just one reason to change; and “Reason to change” == “responsibility”. In example: Invoice class does not have a responsibility to print itself.

Separation of Concerns (since 1974). Concern == feature of system. Taking care of each of the concerns: for each one concern, other concerns are irrelevant. Hiding implementation of behavior.

---
#### Open-Close Principle
Object/Classes are open for extension but closed for modification.
e.g. Adding additional methods to a class that's already been tested and implemented is modification.
e.g. Extension usually means inheritance.

Making use of Specifications and Combinators allows us to avoid the state space explosion problem(As the number of state variables in the system increases, the size of the system state space grows exponentially)

---
#### [liskov substitution principle](https://carstenbehrens.com/liskov-substitution-principle/#:~:text=THE%20LISKOV%20SUBSTITUTION%20PRINCIPLE&text=In%20the%20context%20of%20JavaScript%2C%20this%20means%20that%3A,the%20same%20number%20of%20arguments.&text=The%20return%20type%20of%20the,method%20of%20the%20base%20class.)
The principle defines that objects of a superclass shall be replaceable with objects of its subclasses without breaking the application. That requires the objects of your subclasses to behave in the same way as the objects of your superclass.

All this is stating is that every subclass/derived class should be substitutable for their base/parent class.
