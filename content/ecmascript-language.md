ECMAScript was originally designed to be used as a scripting language, but is widely used as a general purpose programming language.

scripting language - a programming language used to manipulate, customize, and automate the facilities of an existing system.

ECMAScript was also originally designed to be used as a **web** scripting language, but id now used in a variety of host environments.

Web servers and web browsers are both examples of ECMAScript host environments. Web browsers provide resources for client-side computing, UI, browser navigation functionality, and handling i/o through events. Web servers provide resources for server-side computing including api for handling web requests, clients and files.

ECMAScript is object-based; language and host facilities are provided by objects, and ECMAScript programs are collections of interacting objects.

Object (in ECMAScript) - a collection of zero or more properties. Each property has attributes that control how the property can be used (Writable true / false).

Object Properties reference:
- Objects (instances of the built in Object type)
- Primitive Values
- Functions ( Callable Objects)

Primitive Values of ECMAScript:
- Undefined
- Null
- Boolean
- Number
- BigInt
- String
- Symbol

Built-In Objects Defined by ECMAScript:
- global object
- Object
- Function
- Boolean
- Symbol
- Error objects
- Math
- Number
- Date
- String
- RegExp
- Array
- Typed Arrays (including Map and Set)
- Structured Data Objects
    - JSON
    - ArrayBuffer
    - SharedArrayBuffer
    - DataView
- Promise
- Reflection Objects (Proxy and Reflect)

ECMAScript features various operators, and modules.

Objects may be created via literal notation or via constructors, which create objects and then execute code that initializes all or part of them by assigning intial values to properties.

Each constructor is a function that has a property name "prototype" that is used to implement prototype-based inheritance. 

Properties can be added to objects dynamically.

