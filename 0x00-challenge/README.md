0x00. Fix my code
Debugging
 By: Guillaume
 Weight: 1
 Project will start Feb 12, 2024 6:00 AM, must end by Feb 26, 2024 6:00 AM
 Checker will be released at Feb 15, 2024 6:00 PM
 An auto review will be launched at the deadline

     **MY SOLUTIONS FOR THIS PROJECT**

1. **0-fizzbuzz.py**:
   - To fix the FizzBuzz implementation, you would start by understanding the problem: FizzBuzz requires printing numbers from 1 to a given number, replacing multiples of 3 with "Fizz", multiples of 5 with "Buzz", and multiples of both with "FizzBuzz".
   - You would analyze the existing code to identify where it's going wrong. In this case, it incorrectly prints "Fizz" instead of "FizzBuzz" for multiples of 15 (which are multiples of both 3 and 5).
   - Next, you would modify the condition that checks for multiples of 3 and 5 to also check for multiples of 15 and print "FizzBuzz" accordingly.
   - Finally, you would test the modified code with various inputs to ensure it produces the correct output for all cases.

2. **1-print_square.js**:
   - The goal here is to print a square of a given size using characters.
   - You would examine the existing code to understand its logic and how it prints the square.
   - The issue is likely related to how the code calculates the number of rows and columns and prints the square.
   - To fix it, you would update the logic to ensure that the number of rows and columns is equal, resulting in a square shape.
   - After making changes, you would test the code with different input sizes to verify that it correctly prints a square of the desired size.

3. **2-sort.rb**:
   - This task involves sorting a list of arguments passed to a Ruby script.
   - You would review the existing code to understand its sorting algorithm and how it handles different types of input.
   - The problem arises when non-integer arguments are included in the list, leading to unexpected sorting behavior.
   - To address this, you would need to modify the sorting algorithm to handle non-integer arguments gracefully. This might involve filtering out non-integer values or treating them differently during the sorting process.
   - Once you've made the necessary changes, you would test the script with a variety of inputs, including integers and non-integers, to ensure that it sorts them correctly.

4. **3-user.py**:
   - In this task, you're dealing with a Python class that has a method for password validation.
   - You would inspect the code to understand how the password validation method works and what conditions it checks.
   - The issue is likely related to how the method validates passwords, resulting in incorrect behavior or errors.
   - To fix it, you would need to review the password validation logic and ensure that it correctly checks if the input password matches the stored password. This might involve comparing hashes of passwords or checking for specific conditions.
   - After updating the code, you would test the User class with various passwords to verify that the password validation method works as expected.

5. **4-delete_dnodeint/**:
   - This task involves debugging a C program that implements a doubly linked list.
   - You would start by examining the source code files to understand how the doubly linked list is implemented and how nodes are deleted.
   - The issue appears to be with the deletion logic, which leads to incorrect list traversal and output.
   - To debug the code, you would use techniques such as adding print statements to track the program's execution, analyzing the logic for deleting nodes, and identifying any errors or inconsistencies.
   - Once you've identified the problem, you would make the necessary changes to the code to fix the deletion logic and ensure that nodes are properly removed from the list.
   - Finally, you would test the program with various scenarios, including different lists and deletion operations, to confirm that it behaves correctly and produces the expected output.
