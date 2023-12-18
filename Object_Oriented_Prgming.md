1. An object is a bit of self contained code and data
   - key aspect: to divide and conquer
     - Class: a template or blueprint (e.g. dog)
     - Object: a particular instance of a class (e.g. golden retriever)
     - Method/Message: a defined capability of a class (e.g. bark())
     - Field/Attribute: a bit of data in the class (e.g. length)
2. dir()
   - lists capabilities, e.g. type() tells us sth about a variable
3. Object Life Cycle
   - Constructors: called when the object is created, and can have additional parameters used to set up instance variables for the particular instance of the class
     - __init__
     - are more used than destructors, called when the object is destroyed
     - __del__
4. Inheritanace
   - When we make a new class, we can reuse an existing class and inherit capabilities of an existing class, and then add more to it to create the new class.
