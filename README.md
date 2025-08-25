# IPFCE-Week-1-introduction

See `./assignment-01.pdf` for the assignment.

## Build

```bash
make
# or
cmake -S . -B build
cmake --build build --target all
```

## Exercises
### Exercise 3
During lectures, we saw a program that could find the maximum of two integers. Another type in C is `char`, representing a character. I asked ChatGPT the following: how can I compare two characters in C? and got the following answer: You can directly compare two characters using relational operators like `==`, `!=`, `<`, `>`, `<=`, and `>=`. Change the program `maxvalue.c` so that it reads in two `char`s and prints out the largest. What does "largest of two characters" mean? Did it work as expected? Did you notice issues with `scanf`?

See `src/exercise-3.c` for where to write your solution.


### Exercise 4
Write a program that adds two numbers; write a program that adds three numbers;
write a program that adds four numbers.

See `src/exercise-4.c` for where to write your solution.

### Exercise 6
A program must solve the problem, but it should also be understandable for other programmers. Modify the program above (Listing 1) so that it uses an extra variable (`t`) to store the `x` value temporarily instead of using addition and subtraction.

See `src/exercise-6.c` for where to write your solution.


### Exercise 7 (Challenge)
Challenge: Write a program that computes the maximum number that can be produced by adding at most three arbitrary (possibly negative) integer numbers.

See `src/exercise-7.c` for where to write your solution.
