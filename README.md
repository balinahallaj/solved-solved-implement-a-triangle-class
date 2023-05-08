Download Link: https://assignmentchef.com/product/solved-solved-implement-a-triangle-class
<br>
You will implement a Triangle class. It will contain methods that will: compute the area of the trianglecompute the perimeter of the triangledisplay the triangle’s characteristics

Note: The area and the perimeter can be computed based on a formula that uses the three sites (a,b,c) of the triangle. Use Heron’s formula for the area.

1. Declare your instance variables. Hint: from other classes they should be accessed by getters.

2. Create getters and setters for the sites. The setter should check for parameter validity. The site must take a positive value.

3. Create a default constructor that will initialize all the sites to 1.Create a constructor that will take 3 parameters corresponding to site a, site b, site c. Make sure that numberTriangles will be updated each time a new triangle is created.

4. Write the methodsA method that takes the three sides of the triangle and computes the area. ( getArea())A method that takes the three sides of the triangle and computes the perimeter (getPerimeter( )) A method that will display: name, sites, area and perimeter of a given triangles (triangleInfo())

Put all the methods in the class Triangle.java

Now complete the following tester program named TriangleTester.java so that it exercises all of the methods of your class.

Test your Triangle class:

Create a triangle with default values for sites named t1 Create a triangle with the sites values: 3, 4, 5 named t2 Compute the area of triangle t1 (by using getArea( ) method) Compute area of triangle t2

Compute the perimeter of the t1Compute the perimeter of t2Display the number of created triangles.Display (using triangleInfo) the name, the area and the perimeter of triangle t1.