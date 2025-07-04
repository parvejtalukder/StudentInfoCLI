# Student_Information (CLI) 

<pre>
----------------------------------------
----------------------------------------
*====|| Student Info Software ||====*
1. Add New Student
2. Show All Students
3. Exit
4. Tutorial
----------------------------------------
----------------------------------------
</pre>

## INPUT 

<pre> 
Student Name: John Doe
Roll No: 101
Registration No: 202301
Department: Computer Science
University: ABC University
</pre>
Note: Type <pre>end</pre> after completing of your input

## OUTPUT (FROM information.txt)
<pre>
-----------------------------
Name      : John Doe
Roll      : 101
Reg.      : 202301
Department: Computer Science
University: ABC University
-----------------------------
</pre>


A simple Command Line Interface (CLI) program in C that allows users to store and retrieve student information using basic file handling techniques.

---

## Features

- * Add new student records
- * Display all stored student records
- * Exit the program
- * Type `end` anytime to stop data input

---

## File Used

- **information.txt**  
  Stores all the student records in a structured format. It is created automatically in the same directory as the program.

---

## Concepts Covered

- Functions and modular programming
- Input/output with `scanf`, `fgets`, `getchar`
- File handling in C (`fopen`, `fprintf`, `fgets`, `fclose`)
- String manipulation with `strcmp`, `strcspn`
- CLI menu interaction

---

## How to Compile & Run
### Compile:
```bash
gcc main.c 


