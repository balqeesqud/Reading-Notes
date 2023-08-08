# Class 03

Understanding "int" vs. "Integer" clarifies number handling; "int" is basic, "Integer" is fancy.
Exceptions are special issues in code, like errors or surprises. Scanner reads and processes text.
These concepts ensure programs run well and manage problems.

## **Primitives vs. Objects**

   1. Explain the difference between an “int” and an “Integer” in Java.

      - int is a primitive data type in Java used to store whole numbers, & it's more efficient for simple number storage.
        Example:  int age = 25;

      - Integer is a wrapper class that represents an object around the primitive "int", it provides additional features
        and methods.
        Example: Integer object = new Integer(number);

   2. What is the default value for ints? Integers?
      - **int:** The default value is 0. When declaring an "int" variable without assigning any value to it,
        it will automatically be initialized to 0.
      - **Integer:** The default value is "null." When you declare an "Integer" variable without explicitly assigning a value to it,
        it will be initialized to "null".

   3. What is autoboxing? Unboxing?

      ```
      Autoboxing is the automatic conversion of a primitive type "int" into its wrapper class "Integer", While 
      Unboxing is the opposite where its automatically converting the wrapper class object "Integer" back to its primitive type like "int".
      ```

## **Exceptions in Java**

   1. List the three basic categories of exceptions.
      - **Unchecked Exceptions:**, are not checked by the compiler at compile time.
      - **Checked Exceptions:** (try, catch, throw), checked with the compiler at compile time.
      - **Errors:** It's beyond the control of the programmer and the program. They often indicate
         critical problems, such as JVM-related issues or severe system failures.

   2. What type of statement can you use to handle an exception?

      using try-catch statement.
      If an exception written within the "try" block, & it's caught and handled by one or more
      corresponding "catch" blocks.

## **Reading Scanner**

   1. Describe a situation where you think it would be useful to have a program that scans text.

      ```
      useful is in plagiarism detection for educational institutions. With the increasing availability of online 
      content, students might unintentionally or intentionally submit assignments or papers that contain portions 
      of text copied from external sources without proper citation. A program that scans the submitted text can compare 
      it against a database of known sources, highlighting similarities and potential instances of plagiarism. This helps 
      educators ensure academic integrity and encourage originality in student work while efficiently identifying potential
      cases of plagiarism for further review.
      ```

   2. What is input from a Scanner broken down into?

      ```
      divided into smaller parts called tokens. These tokens are separated by special characters like White space characters include
      blanks, tabs, and line terminators or commas.
      ```

## Things I want to know more about

- Exceptions handle errors and unexpected events during program execution, maintaining code reliability.
