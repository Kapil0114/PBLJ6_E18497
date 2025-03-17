# PBLJ6_E18497
Java Programs Using Lambda Expressions and Stream Operations
Easy Level: Sorting a List of Employee Objects
Task: Write a program to sort a list of Employee objects based on their attributes such as name, age, and salary using lambda expressions.

Input:
A list of Employee objects with the following attributes:

Name (String)
Age (int)
Salary (double)
Example:


1. Name = John, Age = 30, Salary = 50000
2. Name = Alice, Age = 25, Salary = 60000
3. Name = Bob, Age = 35, Salary = 70000
Expected Output:
Employees sorted by name:


Alice, 25, 60000
Bob, 35, 70000
John, 30, 50000
Employees sorted by age:


Alice, 25, 60000
John, 30, 50000
Bob, 35, 70000
Employees sorted by salary:


John, 30, 50000
Alice, 25, 60000
Bob, 35, 70000
Medium Level: Filter and Sort Students
Task: Write a program to filter out students who scored above 75%, sort them by marks, and display their names.

Input:
A list of Student objects with the following attributes:

Name (String)
Marks (int)
Example:


1. Name = Sarah, Marks = 80
2. Name = John, Marks = 65
3. Name = Alice, Marks = 90
4. Name = Bob, Marks = 70
Expected Output:
Students scoring above 75% and sorted by marks:

Alice, 90
Sarah, 80
Hard Level: Processing a Large Dataset of Products
Task: Write a program to process a list of products, where you:

Group products by category.
Find the most expensive product in each category.
Calculate the average price of all products.
Input:
A list of Product objects with the following attributes:

Name (String)
Category (String)
Price (double)
Example:


1. Name = Product A, Category = Electronics, Price = 1200
2. Name = Product B, Category = Electronics, Price = 1500
3. Name = Product C, Category = Furniture, Price = 800
4. Name = Product D, Category = Furniture, Price = 1000
5. Name = Product E, Category = Clothing, Price = 50
6. Name = Product F, Category = Clothing, Price = 100
Expected Output:
Grouping products by category:

mathematica

Electronics:
    Product A, 1200
    Product B, 1500
Furniture:
    Product C, 800
    Product D, 1000
Clothing:
    Product E, 50
    Product F, 100
Most expensive product in each category:


Electronics: Product B, 1500
Furniture: Product D, 1000
Clothing: Product F, 100
Average price of all products:


Average price: 783.33
General Instructions:
Implement the programs using lambda expressions and stream operations in Java.
The output format should exactly match the expected output for each level.
Ensure that the programs handle edge cases (e.g., empty lists, no students above 75%, etc.).
Submit the code along with the input/output examples and explanations for each step.
