# What's a Table?
A table represents information in a grid format.

## Example:
git Commands With Syntax 

| Command | Syntax |
| ----------- | ----------- |
| Add | `git add [file] ` |
| Commit	| `git commit -m “[ Type in the commit message]”` |
| Status | `git status ` |
| Rm| `git rm [file]` |
| Push|`git push [variable name] master  `|

## Basic Table Structure

* `<table>` :Used to create a table.
* `<tr>` :Indicate the start of each row.
* `<td>` :Indicate each cell of a table.


```
<table>
 <tr>
 <td>15</td>
 <td>15</td>
 <td>30</td>
 </tr>
 <tr>
 <td>45</td>
 <td>60</td>
 <td>45</td>
 </tr>
 <tr>
 <td>60</td>
 <td>90</td>
 <td>90</td>
 </tr>
</table>
```

## Spanning Columns
The colspan attribute can be used on a `<th>` or `<td>` element and indicates how many columns that cell should run across.
## Spanning Rows
The rowspan attribute can be used on a `<th>` or `<td>` element to indicate how many rows a cell should span down the table.

## Long Tables
There are three elements that help distinguish between the main content of the table and the first and last rows.
* `<thead>`
* `<tbody>`
* `<tfoot>`

# OBJECT
## WHAT IS AN OBJECT? 
JavaScript object is a standalone entity that holds multiple values in terms of properties and methods.
### Example
```
var person = {
  firstName: "John",
  lastName: "Doe",
  age: 25,
};
```
## Ways To Create Objects
1. Literal notation 
2. Object constructor notation 

## Updateing an Object:
`Person.name="Jack";` or `Person['name']="Jack";`

## JavaScript Object Constructors
```
function Person(first, last, age, eye) {
  this.firstName = first;
  this.lastName = last;
  this.age = age;
  this.eyeColor = eye;
}
```
### Call
```
var myFather = new Person("John", "Doe", 50, "blue");
var myMother = new Person("Sally", "Rally", 48, "green");
```
