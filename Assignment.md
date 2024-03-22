# Assignment

You are going to build out a few classes that follow an inheritance hierarchy, and test them out with some polymorphisms.

You are going to build outyour own inheritance hierarchy that fills in the diagram below:

```
                                        1
                                        |   
                     ----------------------------------------
                     |                                      |
                     2                                      3
                     |                                      |
          ----------------------                 ----------------------            
          |                    |                 |                    |    
          4                    5                 6                    7      
```

Replace the numbers above with your class names so we can see the hierarchy visually. This hierarchy can be related to any topic (school appropriate), as long as it represents a valid "is-a" relationship.

You should then make each class in its own file and make sure they all meet the following criteria:
- At least one instance variable (this goes for superclasses as well).
- A no-argument/default constructor.
- An all-argument constructor.
- `toString` and `equals` method overrides where necessary.
- Accessor and mutator methods for any instance variables.

As with the previous assignments. You should use the `Runner.java` file to test all of your classes thoroughly. Thorough testing of each class includes the following:
- Making objects using each available constructor.
- Running/printing the result of each available method to ensure it is working as intended.

Once you have tested each class, make an `ArrayList` of your overall superclass and add one object of each type to it. Then run it through a loop to print all of the objects out (utilizing the `toString` method) to ensure polymorphisms are working correctly.