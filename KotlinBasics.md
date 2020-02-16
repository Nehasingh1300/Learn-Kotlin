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
