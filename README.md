# beecrowd_1045_Problem_Solution_With_C
This C program takes input in the form of three double values, which are assumed to represent the sides of a triangle (A, B, and C). The program's working process can be described as follows:

1. Read Input:
   - The program uses the `scanf` function to read three double values from the standard input (usually the keyboard) and assigns them to variables A, B, and C.

2. Sort the Sides:
   - The program then sorts these three values in decreasing order, ensuring that A is the largest, B is the second largest, and C is the smallest. This is done using a series of conditional statements and a temporary variable (`temp`) for swapping values.

3. Triangle Classification:
   - The program proceeds to classify the type of triangle based on the sorted sides and the conditions provided in the problem statement.

   - If A is greater than or equal to the sum of B and C, it prints "NAO FORMA TRIANGULO," indicating that the sides do not form a valid triangle.

   - Otherwise, it checks for the following conditions:
     - If A^2 (A squared) is equal to B^2 (B squared) plus C^2 (C squared), it prints "TRIANGULO RETANGULO," indicating a right-angled triangle.
     - If A^2 is greater than B^2 plus C^2, it prints "TRIANGULO OBTUSANGULO," indicating an obtuse-angled triangle.
     - If A^2 is less than B^2 plus C^2, it prints "TRIANGULO ACUTANGULO," indicating an acute-angled triangle.

   - Additionally, it checks if all three sides are equal (A == B == C) and prints "TRIANGULO EQUILATERO" if they are, indicating an equilateral triangle. If not, it checks if two sides are equal and the third is different, printing "TRIANGULO ISOSCELES" in this case.

4. Output:
   - Finally, the program displays the appropriate message based on the triangle type determined by the conditions.

The code provides a concise way to classify triangles based on their side lengths and follows the specified rules for triangle classification.
