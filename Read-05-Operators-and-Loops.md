# Read: 05 - Operators and Loops

## Loops
Loops check a condition if it true will execute the block of code if the condition is false then it will break out from the loop, there are three common types of loops:

1.	For loop

We used `for` loop if we need to execute block of code fixed number of times, I mean we know how many times we need the block of code to be executed. And often used to loop through the items in an array.

```javascript
Var sum = 0;
for (i = 0; i < 10; i++) {
sum = + i;
}
```

2.	While loop
We used `while` loop if we do not know how many times we need the block of code to be executed.

```
while (i < 10) {
sum = + i;
i++;
}
```

3.	Do while
Also, we used `Do while` loop if we do not know how many times we need the block of code to be executed. But the different between the `while` and the `Do while` is `Do while` execute the block of code at least one time.
```
do {
sum = + i;
i++;
} whil e ( i < 10) ; 
```
