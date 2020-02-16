## Entry Point
Main Function it will help to enter inside kotlin Code<br>
```
fun main(){
  println("Hello World!");
}
```
Function having two Int parameters with Int return type:<br>
**fun functionName (variableName : dataType, ... ): returnType**
```
fun sum(a: Int, b: Int): Int {
    return a + b
}
```
## Variables
Read-only local variables are defined using the keyword **val**. They can be assigned a value only once.
```
val a: Int = 1  // immediate assignment
val b = 2   // `Int` type is inferred
val c: Int  // Type required when no initializer is provided
c = 3       // deferred assignment
```
Variables that can be reassigned use the var keyword:
```
var x = 5 // `Int` type is inferred
x += 1
```
## Comments
```
// Single line comment

/*
* Block Comment
*/
```

## String
```
var a = 1  // simple name in template:
val s1 = "a is $a" 

a = 2     // arbitrary expression in template:
val s2 = "${s1.replace("is", "was")}, but now is $a"
```
## Available Stuff that of other languages
**if else <br><br> while <br><br> for <br><br>**
**is Operator**<br>
check whether an object conforms to a given type at runtime <br>
```
if (obj is String) {
    print(obj.length)
}
if (obj !is String) { // same as !(obj is String)
    print("Not a String")
}
else {
    print(obj.length)
}
```
**when** <br>
It is kind of switch case in other languages<br>
When a given expression or statement is satisfied then some work is done!<br>
```
when (x) {
    1 -> print("x == 1")
    2 -> print("x == 2")
    else -> { // Note the block
        print("x is neither 1 nor 2")
    }
}
```
<br>

**Range**
Check if something is in range or not
```
val x = 1
val y = 9
if (x in 1..y+1) {
    println("fits in range")
}
else{
    println("${x} is not in range")
}
```
<br><br>

## Collection
A collection usually contains a number of objects (this number may also be zero) of the same type. Objects in a collection are called elements or items. For example, all the students in a department form a collection that can be used to calculate their average age. The following collection types are relevant for Kotlin:<br><br>

**List** is an ordered collection with access to elements by indices – integer numbers that reflect their position. Elements can occur more than once in a list. An example of a list is a sentence: it's a group of words, their order is important, and they can repeat.<br>
**Set** is a collection of unique elements. It reflects the mathematical abstraction of set: a group of objects without repetitions. Generally, the order of set elements has no significance. For example, an alphabet is a set of letters.<br>
**Map** (or dictionary) is a set of key-value pairs. Keys are unique, and each of them maps to exactly one value. The values can be duplicates. Maps are useful for storing logical connections between objects, for example, an employee's ID and their position.<br>
