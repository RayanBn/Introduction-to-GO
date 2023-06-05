# Introduction to **Go**

## Installation :

### On fedora :
```
sudo dnf install golang
```

## Exercise 1:

Using a loop, print every number between 1 and 100 !

## Exercise 2:

Code a "**simpleCalculator**" function that adds two numbers together<br>
This function takes 2 parameters:
* The number on the left of the '**+**' operator
* The number on the right of the '**+**' operator

```
simpleCalculator(2, 2) -> 4
```
You can add any other operation !


## Exercise 3:

Write a "**countLetter**" function to count all letters from a file and print it.<br>
This function take 1 parameter:
* The file path of your file.

```
countLetter("myFile")
```

## Exercise 4:

Write a "**countWord**" function whose objective is to count the number of times a word appears in a sentence.<br>
This function takes 2 parameters:
* The sentence you will search through.
* The word you look for in the sentence.

```
countWord("My cat is playing with my dog!", "my") -> 2
```

## Exercise 5:

Make a simple "**checkThat**" function to check parameter integrity !<br>
This function takes 1 parameter:
* A list of input parameters.

```
checkThat([1, 2, 3, 4, 5]) -> true
checkThat([1, 2, 3, a, 5]) -> false
```

## Exercise 6:

Now, let's make an "**appendTofile**" function which appends a string to a file !<br>
That function takes 2 parameters:
* The file you want to append to.
* The string you want to append to your file.
```
appendToFile("myFile", "append this") -> if file empty : "append this"
appendToFile("myFile", "append this") -> if file is not empty : "... append this"
```

## Exercice 7:

Now to test all of your functions, make some unit tests !

## Exercice 8:

If you reached this part, you learned a lot. But if you want to learn more, take a look at class and make Human class with age, name, ect.