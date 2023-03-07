//I chose DemoClass to explain

Keypoints:
1) Instance vs Static variables and methods
2) Method overloading

- Static Variabls: Defined in the class (if a default value hasn't been assigned through initialization , the default is 0).

- Static Method: A method that is defined as "static" and is called by using the Class name

- Instance Variable: Defined in the object.

- Instance Method: A method w/o the static indication. This method is called by using an object of some class.

- Static methods can call other static methods, but NOT instance methods (the child cannot tell the parent what to do)

- Instance Methods can call either static methods or other instance methods(Children can tell eachother what to do and parents can tell children what to do)

- Method Overload: We can make a method that can take any number of parameters / return types:

    - Conditions:
    - The method can use the same name
    - Either of these can be true:
        - Same return type & different number of parameters
        - Different return type
        - These methods can return the same input parameter values