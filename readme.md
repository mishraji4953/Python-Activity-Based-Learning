# Case Study 1: Student Marks Calculator

## 1. Problem Statement
To develop a Python program to calculate a student's total marks, percentage, and result.

## 2. Aim
To create a program that accepts student details and marks in three subjects and displays the total, percentage, and pass/fail result.

## 3. Objectives
- To accept the student's name and subject marks.
- To calculate total marks and percentage.
- To determine the result using conditional statements.

## 4. Assumptions
- There are three subjects.
- Each subject carries 100 marks.
- A minimum of 35 marks is required in each subject to pass.

## 5. Algorithm
1. Start the program.
2. Input the student's name.
3. Input marks in three subjects.
4. Calculate the total marks.
5. Calculate the percentage.
6. Check whether the student has scored at least 35 marks in every subject.
7. Display the total, percentage, and result.
8. Stop the program.

## 6. Pseudocode
START  
INPUT name  
INPUT m1, m2, m3  
total = m1 + m2 + m3  
percentage = (total / 300) * 100  
IF m1 >= 35 AND m2 >= 35 AND m3 >= 35  
    PRINT "Pass"  
ELSE  
    PRINT "Fail"  
END IF  
STOP

## 7. Test Cases

| Subject 1 | Subject 2 | Subject 3 | Total | Percentage | Result |
|---:|---:|---:|---:|---:|---|
| 69 | 67 | 77 | 213 | 71% | Pass |
| 80 | 75 | 90 | 245 | 81.67% | Pass |
| 80 | 30 | 70 | 180 | 60% | Fail |

## 8. Conclusion
The program successfully calculates total marks and percentage and determines whether a student passes or fails based on the minimum marks requirement.