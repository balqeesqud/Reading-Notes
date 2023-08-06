# Class 02

## **Java Imports**

1. ### Use an analogy to explain Built-In packages. Give examples

```
Built-in packages in programming are like toolboxes with ready-to-use tools.They help programmers
do common tasks without starting from  scratch. These toolboxes have different functions and modules that 
make  coding easier and save time. 

Examples: `java.lang`, `java.util`, `java.io`.
```

2. ### Explain the steps for creating a new package in IntelliJ

    - Right-click on the source folder.
    - Go to new and then package.
    - A pop-up box will appear where you can enter the package name.

· Once the package is created, a similar folder structure will be created  
  on your file system as well. Now, you can create classes, interfaces, and
  so on inside the package.

## **Different types of loops in Java**

1. ### Which loop types use a loop counter?

    For Loop

2. ### Explain the difference between While and Do-While loops

   - While

     ```
     It repeats a statement or a block of statements while its controlling Boolean-expression
     is true.
     ```

   - Do - While

     ```
     It executes the Do statement, then executes the while condition if its controlling
     Boolean-expression is true.
     ```

## **Java Arrays**

1. ###  Describe 3 built-in methods for Arrays** 

- ### public static void sort(Object [ ] a)

     `Sorts the specified array of objects into an ascending order.`

- ### public static void fill(int [ ] a, int val)

     `Assigns the specified int value to each element of the specified array of ints.`

- ### public static boolean equals(long [ ] a, long [ ] a<sub>2</sub> )

     ```
     Returns true if the two specified arrays of longs are equal to one another. Two arrays are considered equal if both arrays contain the same number of elements, and all corresponding pairs of elements in the two arrays are equal. This returns true if the two arrays are equal.
     ```

2. ### How is the size of an array determined in Java?

    `dataType[] arrayRefVar = new dataType[arraySize]`

## Things I want to know more about

   1. Learn about bringing external classes and packages into your code using the
      "import" statement.
   2. learn how to declare, initialize, and access Arrays.
