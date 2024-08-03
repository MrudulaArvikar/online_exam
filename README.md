# Exam Console

## Overview
The **Exam Console** is a Java-based application designed to conduct exams through a console-based user interface. Users can start the exam, answer multiple-choice questions, and receive a score based on their answers.

## Features
- **Console-based UI**: Easy-to-use text-based interface.
- **Question Management**: Predefined set of questions stored in a `QuestionDB` class.
- **Scoring System**: Automatic score calculation based on user answers.

## Components
### ExamConsole Class
- Represents the user interface for conducting exams.
- Manages user interaction, menu display, and exam initiation.

### Question Class
- Represents a single question with options and the correct answer.
- Contains getter and setter methods for question details.

### QuestionDB Class
- Manages a collection of questions.
- Provides methods to get a question and the total number of questions.

### Main Class
- Entry point of the application.
- Instantiates the `ExamConsole` class and starts the exam.

## Usage
1. **Compile the Code**
    
    

2. **Run the Application**

## Output

```plaintext
1. Start exam
2. Exit
Enter your choice
1
Question 1:
What will be the output?
String s = "abcdefgh";
System.out.println(s.indexOf("j"));
Options:
a. true
b. false
c. -1
d. 1
Type your answer (a, b, c, d): a
Wrong answer
Your score: 0/10
Question 2:
Which of the following method/s do not belong to String class?
1.length()
2.sizeof()
3.endsWith()
4.reverse()
Options:
a. 2, 4
b. 2
c. 1, 3
d. 3
Type your answer (a, b, c, d): b
Wrong answer
Your score: 0/10
Question 3:
If X, Y are classes and L, M are interfaces, then which of the following is illegal in Java?
Options:
a. class Y extends X implements L, M {}
b. class Y extends X {}
c. interface M extends L {}
d. interface M extends X {}
Type your answer (a, b, c, d): c
Wrong answer
Your score: 0/10
Question 4:
Instance variable is a variable 
declared in ___.
Options:
a. class and method
b. class
c. method
d. main()
Type your answer (a, b, c, d): d
Wrong answer
Your score: 0/10
Question 5:
System.out.println("Hello"); Here, out is of _ class.
Options:
a. PrintStream
b. String
c. System
d. PrintWriter
Type your answer (a, b, c, d): a
Answer is correct
Your score: 1/10
Question 6:
What is false?
Options:
a. Abstract class should not contain constructor.
b. Reference of super class can refer to object of subclass.
c. Abstract class is created for inheritance purpose only.
d. The keyword super helps to access an overridden method.
Type your answer (a, b, c, d): h
Wrong answer
Your score: 1/10
Question 7:
What is false about interface?
Options:
a. It contains only abstract methods and final fields
b. It can be extended by another interface.
c. It can be instantiated.
d. It can be implemented by a class.
Type your answer (a, b, c, d): a
Wrong answer
Your score: 1/10
Question 8:
Which of the following classes belong to java.lang package?
1. ArrayIndexOutOfBoundsException
2. BufferedReader
3. String
4. System
Options:
a. 3, 4
b. 1, 3, 4
c. 1, 2
d. 2, 3, 4
Type your answer (a, b, c, d): b
Answer is correct
Your score: 2/10
Question 9:
Which of the following statements is incorrect?
Options:
a. String is a class in Java.
b. Strings in java are mutable.
c. String class can not be inherited.
d. Java defines a class called StringBuffer, which allows string to be altered.
Type your answer (a, b, c, d): c
Wrong answer
Your score: 2/10
Question 10:
Which of the following lines will compile without error?
Options:
a. float f=1.3;
b. char c="a";
c. int i=10;
d. boolean b=null;
Type your answer (a, b, c, d): d
Wrong answer
Your score: 2/10
1. Start exam
2. Exit
Enter your choice
2
    
    

## License
This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.
