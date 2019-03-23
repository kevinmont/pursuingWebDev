# JavaScript 
## tackling prototype
Every **Function**, **Object** has an property called `__proto__` which is a chain to operate inheritance based on object oriented programming. 
Some aspects to consider:
	1. If a method is called then it will look first on this object and just if it doesn't defined there, then it will look up through the object `__proto__` which by default has a reference to *Object.prototype*. It last itself has a final link chain which has a reference to null. Because it's the father of every **Object**

## Constructor


## Prototype vs `__proto__`

The Object is the father of inheritance, It has a property `prototype` which refer

# References 
- [dmitrysoshnikov](http://dmitrysoshnikov.com/ecmascript/javascript-the-core/)
- [scottlogic](https://blog.scottlogic.com/2013/11/27/javascript-object-creation-patterns.html)
