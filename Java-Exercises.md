# First Java Exercises

## Basic Hello World
Our first small program is the 'Hello world' program that we will write and compile.
Write a class (containing a main function) printing "hello world" to the command line.

## Loops and Imports

Write a small program drawing random "Lotto" Numbers:

1. Create a file `LottoGenerator.java`, containing the following: 

```java
import java.util.Random;

class LottoGenerator {
  public static void main(String[] args) {
    //Random number generator
    Random rand = new Random();
    for(int i=0; i<7; i++) {
      int random_number = 1 + rand.nextInt(49);
      System.out.print(random_number + " ");
    }
  }
}
```

2. What is the result when running `javac LottoGenerator.java`?
3. Create a new file `SortedLotto.java` and modify the previous class to provide a sorted version of the lottery numbers. The sorted numbers should also be printed out in the console.

## Euler Number

Calculate an approximation of Euler's number with a user provided maximum number of steps.

Euler's Number is defined as:

$$ e = \sum_{n=0}^{\infty} \frac{1}{n!} $$

The following code snippet must be used to calculate the Euler Number:

```java
public class Euler {
 public static float eulerIterativ(int n) {
   float result = 1;
   //Your code here...
   return (result);
 }

 public static void main(String args[]) {
   // Ask the user for the maximum number of steps
   // int max = ...
   System.out.println("e("+max+")(iterativ)="+eulerIterativ(max));
 }
}
```

1. Complete the code snippets by implementing the iterative method `eulerIterativ` and requesting the maximum number of steps from the user as input to the program.
2. Extend the program by implementing a method for recursive approximation `eulerRekursiv`.

## Reading and writing of files

Implement a program that reads **semicolon**-separated files with a header line. The program should be able to identify by itself how many rows and columns should be read. The first row of the table contains the name of each column, and the first column provides the name of each row. An example file looks like this: 

```
Patient_ID;Status;Sex;Fastq_R1;Fastq_R2
P001;0;XX;p001_normal_R1.fastq.gz;p001_normal_R2.fastq.gz
P001;1;XX;p001_tumor_R1.fastq.gz;p001_tumor_R2.fastq.gz
P003;1;NA;p003_R1.fastq.gz;p003_R2.fastq.gz
P004;0;XY;p004_R1.fastq.gz;p004_R2.fastq.gz
```

The program should be able to read such files. Furthermore, it should be possible to change the name of the columns, and individual cells. Additionally, a last function should allow to change the file paths for Fastq_R1 or Fastq_R2 and save the changes in a (new) file. 
