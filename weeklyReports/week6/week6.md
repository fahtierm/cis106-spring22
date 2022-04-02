# Week Report 6
In this week I've learned even more on how to use an brace expansions and wildcards. Wildcards were easy to understand however brace on the other hand is difficult but with practice I can get better at it.

## Weekly Report Wild cards & Brace expansion
Wild cards are letters and characters used to search a specific file name.
|character|syntax           |output                             |
|---------|-----------------|-----------------------------------|
|*        |``ls``+``*.txt`` |``dog.txt`` ``cat.txt`` ``car.txt``|
This syntax will put out any files related to .txt it will ignore what name comes before it like cat, dog and car.

## What is a Brace Expansion
A Brace Expansion ``{}`` is another cool feature to bash that you can generate arbitrary strings and also to be used with commands.

## Brace example
``mkdir -p Downloads/{Mouse,ran}`` this will make two directory's using the brace just make sure to add add a comma if you want to add another directory.