![Javascript](https://i.ibb.co/BsCTKJc/68747470733a2f2f75706c6f61642e.png)

# Comparison Operators 

You may be familiar with comparison operators from math class. Let’s make sure there aren’t any gaps in your knowledge.

- Comparison operators — operators that compare values and return true or false.

less than greater than or equal to

| Operator | Meaning |
| --- | --- |
| > |  Greater than |
| < | Less than |
| >= | Greater than or equal to |
| <= | Less than or equal to |
| == | Equal to |
| === |  Equal value and same type |
| != | Not Equal to |
| !== | Not Equal value or Not same type |

# Logical Operators

Comparison operators allow us to assert the equality of a statement with JavaScript. For example, we can assert whether two values or expressions are equal or whether one value is greater than another.

- Logical operators — operators that combine multiple boolean expressions or values and provide a single boolean output.


| Operator | Meaning |
| --- | --- |
| `&&` | AND |
|` ||` | OR |
| `!` | NOT |



# For Loop
For loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

## Why For Loops?

1. Like all loops, "for loops" execute blocks of code over and over again.

2. The advantage to a for loop is we know exactly how many times the loop will execute before the loop starts.

3. Generic Syntax.

## Syntax
A for statement looks as follows:
```
for (statement 1; statement 2; statement 3) {
  // code block to be executed
}
```
## Example

```
for (i = 0; i < 5; i++) {
  text += "The number is " + i + "<br>";
}
```
# While Loop
While statement executes its statements as long as a specified condition evaluates to true


## Why while Loops?
1. Like all loops, "while loops" execute blocks of code over and over again.
2. The advantage to a while loop is that it will go (repeat) as often as necessary to accomplish its goal.
3. Generic Syntax.
4. Infinite loops.

## Syntax
A while statement looks as follows:
```
while (condition) {
  // code block to be executed
}
```
## Example
```
while (i < 10) {
  text += "The number is " + i;
  i++;
}
```