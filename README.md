# Groovy NullPointerException in List Iteration

This repository demonstrates a common NullPointerException in Groovy when attempting to iterate over a list that might be null. The `myMethod` function iterates through the list, printing each item. However, if a null list is passed, a `NullPointerException` occurs.

The solution involves adding a null check before the iteration to prevent the exception.