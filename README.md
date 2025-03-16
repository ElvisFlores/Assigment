# Assigment
# Student Grade Calculator

## Overview

This C++ program allows users to input test scores for multiple students, calculates each student's average score, and assigns a letter grade based on the average.

## Features

- Accepts any number of students and test scores.
- Validates that test scores are between **0 and 100**.
- Dynamically allocates memory for student names, scores, averages, and grades.
- Calculates average scores and assigns grades:
  - **A**: 90-100
  - **B**: 80-89
  - **C**: 70-79
  - **D**: 60-69
  - **F**: Below 60
- Displays a clean, formatted result table.

## How to Use

1. **Compile the program:**
   ```bash
   g++ -o grade_calculator program.cpp
   ```

2. **Run the program:**
   ```bash
   ./grade_calculator
   ```

3. **Follow the prompts:**
   - Enter the number of students.
   - Enter each student's name.
   - Enter how many test scores they have.
   - Input valid test scores (between 0 and 100).

4. **View Results:**
   - The program displays each student's name, average score, and letter grade.

## Example Output

```
Enter the amount of students: 2

Enter the name for student #1: Alice
 Enter the number of test scores for Alice: 3
Enter the score for #1 85
Enter the score for #2 90
Enter the score for #3 95

Enter the name for student #2: Bob
 Enter the number of test scores for Bob: 2
Enter the score for #1 70
Enter the score for #2 75

Results:
--------------------------------
Student    | Average  | Grade
--------------------------------
Alice      | 90.00    | A
Bob        | 72.50    | C
--------------------------------
```

## Notes

- The program uses dynamic memory allocation; all allocated memory is properly deallocated after use.
- Input validation ensures no invalid scores are accepted.

