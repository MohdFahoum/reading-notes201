###OBJECTS 

Objects overview

Objects in JavaScript, just as in many other programming languages, can be compared to objects in real life.
The concept of objects in JavaScript can be understood with real life, tangible objects.

In JavaScript, an object is a standalone entity, with properties and type.
Compare it with a cup, for example. A cup is an object, with properties.
A cup has a color, a design, weight, a material it is made of, etc. The same way, JavaScript objects can have properties, which define their characteristics.

Objects and properties

A JavaScript object has properties associated with it.
A property of an object can be explained as a variable that is attached to the object.
Object properties are basically the same as ordinary JavaScript variables, except for the attachment to objects.
The properties of an object define the characteristics of the object. You access the properties of an object with a simple dot-notation:
(objectName.propertyName)

*Like all JavaScript variables, both the object name (which could be a normal variable) and property name are case sensitive.
You can define a property by assigning it a value. For example, let's create an object named myCar and give it properties named make, model, and year 

In my opinion, it’s an uncomfortable solution. JavaScript is prototype based, why so much pain to create objects from a prototype?

Fortunately the language is changing. Many things that were relatively frustrating in JavaScript are solved step by step.

This article demonstrates how ES2015 solves the problems described above and improves the object literal with additional goodies:

Setup the prototype on object construction
Shorthand method declarations
Make super calls
Computed property names
Also let’s look in the future and meet the new proposals (at stage 2): rest and spread properties of an object.

![link](https://dmitripavlutin.com/static/6b3285560e9919709526195d724d29e0/8ea29/ES2015-object-literal.webp)
