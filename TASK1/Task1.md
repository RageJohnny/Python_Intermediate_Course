# Task 1: OOP Exercise - Geometric Shapes

## Objective

Design a class-based system to represent basic geometric shapes. After implementing the classes, create instances (objects) of each shape and demonstrate their functionalities.

## Class Definitions

1. **Shape** (Base class):
   - Methods:
     - `area`: Should return the area of the shape.
     - `perimeter`: Should return the perimeter of the shape.

2. **Triangle** (Derived from Shape):
   - Attributes:
     - `base`: Represents the base of the triangle.
     - `height`: Represents the height of the triangle.
     - `side_a`: Represents one side of the triangle.
     - `side_b`: Represents the second side of the triangle.
     - `side_c`: Represents the third side of the triangle.
   - Methods (Override as necessary):
     - `area`: Should return the area of the triangle.
     - `perimeter`: Should return the perimeter of the triangle.

3. **Rectangle** (Derived from Shape):
   - Attributes:
     - `length`: Represents the length of the rectangle.
     - `width`: Represents the width of the rectangle.
   - Methods (Override as necessary):
     - `area`: Should return the area of the rectangle.
     - `perimeter`: Should return the perimeter of the rectangle.

4. **Circle** (Derived from Shape):
   - Attributes:
     - `radius`: Represents the radius of the circle.
   - Methods (Override as necessary):
     - `area`: Should return the area of the circle.
     - `perimeter`: Should return the circumference of the circle.

## Practical Demonstration

After implementing the above classes:

1. Create an instance of each shape (Triangle, Rectangle, Circle).
2. Print out and verify the area and perimeter/circumference for each shape.


## Tips

- Remember the formulas:
  - Triangle area = 0.5 * base * height
  - Rectangle area = length * width
  - Circle area = π * radius^2 
  - Triangle perimeter = side_a + side_b + side_c
  - Rectangle perimeter = 2 * (length + width)
  - Circle circumference = 2 * π * radius
- You can use `3.14159` as the value for π (pi) or leverage the `math` module in Python.
