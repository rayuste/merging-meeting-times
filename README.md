# merging-meeting-times
Solution to Interview Cake Course practice program, Merging Meeting Times to practice array and string manipulation in Java.

## Dependencies
* [Java SE 10](https://www.oracle.com/technetwork/java/javase/downloads/jdk10-downloads-4416644.html?)
* [Junit (version 4.3 included)](https://junit.org)

## Compile and Run
~~~
$ javac -cp .:junit-4.3.jar Solution.java
$ java -cp .:junit-4.3.jar Solution
~~~

## Problem
* Write a method `mergeRanges()` that takes a list of multiple meeting time ranges and returns a list of condensed ranges. [(source)](https://www.interviewcake.com/question/java/merging-ranges?section=array-and-string-manipulation&course=fc1)
* For example, given:
```java
  [Meeting(0, 1), Meeting(3, 5), Meeting(4, 8), Meeting(10, 12), Meeting(9, 10)]
```
* `mergeRanges()` would return:
```java
  [Meeting(0, 1), Meeting(3, 8), Meeting(9, 12)]
```
* Do not assume the meetings are in order. 

## Solution
* Can be done in *O(n log n )*
