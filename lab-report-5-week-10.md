# Lab Report 5 Week 10: 
> I found the tests by looking through the tests and seeing which ones would show the bugs in my code. Then I tried these tests until I got 2 where my implementation and the provided implementation caused different results. 
## Test 1: test file 491
> My implimentation was correct since I got ```[<b)c>]``` as the list. The provided implementation from lab 9 had the output of ```[<b]``` which is not the whole link.
> The bug in the Lab 9 implementation is that it doesn't account for if the ```)``` is in the link itsself. It returns whatever is inbetween the first set of open and closed parenthesis not including the rest of the link in the list. 

## Test 2: test file 525
> Both my implementation and the lab's implementation had an incorrect output. Mine had an illegal argument exception thrown and the lab's had the output ```[uri]```. The correct would have been an empty list since there are no links as indicated by the markdown preview. 
> The bug in my implementation is the conditions used in deciding if an illegal arugment exception should be thrown. 