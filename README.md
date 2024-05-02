# Assignment6

This Java program within the `Assignment6` package prompts the user to input details about a student's exam marks and then displays the exam details.


1. It imports the `Scanner` class from `java.util` package to read user input.
2. In the `main` method:
   - It creates a new `Scanner` object to read input from the console.
   - Asks the user to input the student's name, roll number, and marks for two subjects (mark 1 and mark 2) using `System.out.println` statements.
   - Reads the input values using `sc.nextLine()`, `sc.nextInt()`, and `sc.nextDouble()` methods respectively.
   - Creates a new `Result` object with the provided details (name, roll number, mark 1, and mark 2).
   - Calls the `displayExamDetails` method of the `Result` object to display the exam details.

