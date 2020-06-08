# Javascript first lesson

## 1 - Variable
An object that store data, value, and can be used by function. Example:

~~~
let name = 'Huong';
let width = 5;
let height = 2;
let volume = width * height;
function multiply(width,height) {
    volume = width * height;
} 
~~~

feature: global variable can be changed by function.
example:
~~~
let x = 3;
function multiply(a){
x = x * a;
}
multiply(3)
~~~

## 1- function
syntax: function functionName(parameter) {};

* trait: function that can use global variation. Function can access to any variable at global scope and change the value of that variable. Function can also has it own variable which only can be used within that function.

* type: return function: return whatever value I give to the function. example: 
```
function add(a,b) {
    return a + b
} 
```

## 2- scope
variable in global scope can be accessed by all functions, but variable in internal scope can only accessed within that function.

## 3-Quokka
A plugin that display value of variable inside vs code. This helps coder check the code immediately. Need to turn off debug feature to use quokka. To create a js file that enable Quokka. Type: shift + cmd + P, choose New Quokka Javascript file.

