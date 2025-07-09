This repository contains simple yet essential Python programs designed to build a strong foundation in algorithmic thinking and problem-solving. Each program is written from scratch without relying on advanced libraries, making the logic easy to follow and educational for beginners.

🔢 1. Prime Number Checker
Objective: Check whether a given number is a prime number.
Approach: A number is considered prime if it's only divisible by 1 and itself. We loop from 2 to the square root of the number and check for any divisors.
Learning: Helped understand efficient iteration (up to √n) and conditional logic.

🔢 2. Sum of Digits
Objective: Find the sum of all digits in a number.
Approach: Convert the number to a string, loop through each digit, convert it back to an integer, and add it to the total sum.
Learning: Reinforced type conversions and simple loops in Python.

🔢 3. LCM and GCD Calculator
Objective: Compute the Least Common Multiple and Greatest Common Divisor of two numbers.
Approach: Used the formula LCM(a, b) = |a * b| / GCD(a, b), and the built-in math.gcd() function.
Learning: Learned the mathematical relationship between LCM and GCD and the utility of Python's standard libraries.

🔁 4. List Reversal
Objective: Reverse a list without using built-in methods.
Approach: Used a manual swapping technique — elements from both ends are swapped using a for loop.
Learning: Solidified understanding of list indexing and basic memory manipulation.

🔃 5. List Sorting (Bubble Sort)
Objective: Sort a list of integers in ascending order.
Approach: Implemented Bubble Sort, which repeatedly swaps adjacent elements if they’re in the wrong order.
Learning: Learned a classic sorting technique and the importance of nested loops.

🧹 6. Remove Duplicates from List
Objective: Eliminate duplicate values from a list.
Approach: Created a new list and added elements only if they weren’t already present, preserving order.
Learning: Understood how to use loops and conditional checks to filter data.

🔠 7. String Length without len()
Objective: Calculate the length of a string without using Python’s len() function.
Approach: Used a for loop to manually count each character.
Learning: Reinforced the concept of iteration and string traversal.

🔡 8. Count Vowels and Consonants
Objective: Count the number of vowels and consonants in a string.
Approach: Checked if each character is an alphabet and then categorized it as a vowel or consonant using a set.
Learning: Practiced use of sets, conditionals, and built-in string methods like isalpha().

🧩 9. Simple Maze Solver (DFS)
Objective: Solve a hardcoded maze using Depth-First Search (DFS).
Approach: The maze was a 2D list where 1 represents walls and 0 represents paths. DFS was used to find a path from start to finish, marking the path with 'P'.
Learning: Introduced recursive thinking and backtracking — fundamental in problem solving and AI-based logic.

📚 Final Thoughts
This project not only focused on writing functional code but also on understanding the why behind each solution. Through each task, I aimed to build a solid foundation in:
Logical thinking
Clean coding practices
Communication of technical ideas
This documentation is part of a broader effort to align coding practice with real-world development skills like explaining, debugging, and refining solutions collaboratively.
