## Inheritance
	- A **Super / Parent** class is a class whose properties are inherited from another class.
	- A **Sub / Child** class is a class that inherits the properties of another class.
	- Use the **extends** keyword to create a subclass.
	- Within a subclass, use the **super** keyword to reference its superclass, and use **@Override** to overwrite one of the superclass's methods.
- ## Abstraction
	- **Abstraction** is the idea of hiding and separating away unnecessary complexity.
	- Achieved through **interfaces** and **abstract classes.**
	- The **abstract keyword** is a non-access modifier used to make abstract classes and methods.
	- **Abstract classes** cannot be made into objects. Instead, a child class must be made and instanced.
	- **Abstract methods** can only be made in abstract classes and leave implementation up to the extending class.
	- **Interfaces** define the methods of a class with no implementation. Like abstract classes, they cannot be instanced themselves, and must instead be used by a child class through use of the  **implements** keyword.