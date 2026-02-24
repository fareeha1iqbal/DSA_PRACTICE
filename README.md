# DSA_PRACTICE: CLASS TASK
Sample Test of your github:

**Problem Statement**
You are required to design and implement a C++ program that demonstrates runtime polymorphism using the concept of pure virtual functions.

Create an abstract base class named Shape that represents a general geometric shape. This class should contain:
•	A pure virtual function getArea() to calculate the area of the shape.
•	A virtual function showArea() that displays the calculated area.
•	A virtual destructor (recommended for proper cleanup).

Then, create two derived classes:
**1.	Circle**
o	Data member: radius
o	Override the getArea() function to calculate the area of a circle.

**2.	Rectangle**
o	Data members: length and width
o	Override the getArea() function to calculate the area of a rectangle.


**Program Requirements**
•	In the main() function:
o	Declare a pointer of type Shape*.
o	Dynamically create objects of both Circle and Rectangle.
o	Use the Shape pointer to call the showArea() function for each object.
o	This should demonstrate runtime polymorphism (late binding).


**Expected Learning Outcome**
After completing this program, students should be able to:
•	Understand abstract classes and pure virtual functions.
•	Implement runtime polymorphism using base class pointers.
•	Apply inheritance and function overriding in C++.

