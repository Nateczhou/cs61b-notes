# Lecture 7: Testing

## How does a programmer know that their code works?

They write _**tests**_ themselves!

Old way: rely on autograder

New way: write your own tests

Let's try out the new way

### Ad Hoc Testing

write test even before writing the method need testing.

using != to do comparison

java.util.Arrays.equals\(arraya, arrayb\)

### JUnit Testing

org.JUnit.Assert.assertEquals\(expected, input\);

term: deprecated

easy to switch test method: @org.junit.Test, no need to write main method

import in java so @Test

ADD vs Unit test vs TDD vs IT\(integration testing\)

### Example Using Selection Sort

how to test private method?? should i just switch it to public for testing, then switch it back to private. Read the book to find answer. For now, we change private to public for convenience purpose.

work around for recursion on change size array. cannot use slicing like in python. solution is to write a helper method.



## A simple JUnit test

Testing Philosophy

Selection Sort

Simpler JUnit Tests

## Lab3 : Testing Debugging

step in, out, java viz, debugger, junit, tdd, how to use git in intellij.

