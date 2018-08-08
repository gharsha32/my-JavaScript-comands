# my-JavaScript-comands
 write
### Naming an external javascript file
```javascript
nameOfFile.js
```

### To make an alert dilog box appear with a message
```javascript
alert("message");
```

### Writing directly to a web page
```javascript
document.write("message");
```

### To check for errors in you code if the code does'nt run on the web page
Right click on the web page/inspect/console

### To write a message to the console
```javascript
console.log("message");
```

### Creating a variable
```javascript
var variableName;
```

### To assign a value to a variable(a number, string, boolean)
```javascript
var variableName="string"; //For a string
var variableName=5; //For a number
var variableName=true; //For a boolean
```
### To recive a user's input
```javascript
prompt("question");
```

### To link external javascript file to the main html file
```javascript
<script src="nameOfExternaljavascriptfile">
```

### To create a function
```javascript
function nameOfTheFunction(parameter1, parameter2){
  code here
}
```

### Calling a function
```javascript
functionName(argument1, argument2)
```

### Alerting variables
```javascript
var nameOfVariable="some text"
alert(namwOfVariable)
```

### creating a loop (WHILE loop)
```javascript
wile(condition){
 code here
} //The code in the code block runs as long as the condition is true
```

### Conditional statement
```javascript
if(condition){
 code here
}else{
 //If the condition in the if statement is not satisfied, the code in here runs 
}
```

### To create many conditional statements
```javascript
if(condition){
 code here
}else if (condition){
 code here
}...

}else{
 code here
}`
```

### Creating an array
```javascript
var arrayName=[item1, item2, ...];
```

### Adding items at the end of an array
```javascript
arrayName.push("string1", "string2", ...)//you may even place numbers
```

### Accessing an item in an array
```javascript
arrayName[indexvalue]
```

### Adding items at the beginning of an array
```javascript
arrayName.push("string1", "string2", ...)//you may even place numbers
```

### Removing items from the beginning of an array
```javascript
arrayName.shift()
```

### Removing items from the end of an array
```javascript
arrayName.pop() /*You can get the removed item from the array by placing arrayName.pop() in console.log() or document.write() */ 
```

### To create a loop(FOR loop)
```javascript
for(var i=theNumberYouWantToBeginWith; condition; i+=1/i-=1/*According to the requirement*/)
```

### To know the length of the array
```javascript
arrayName.length
```

### Return
```javascript
function functionName(x, y){
 return x+y
}
console.log(functionName(2, 3))
//Expected outcome: 5 in the console.
```

### To join two or more arrays
```javascript
mainarray.concat(array1, array2, ...)
```

### To bring all the elements of an array in a line
```javascrit
arrayName.join()
```
### To create an object
```javascript
var nameOfobject={};
```

### Adding items to an object
```javascript
objectName.newProperty: value;
```

### Removing items from objects
```javascript
remove objectName.property
```
### Placing functions inside a property
```javascript
someproperty: function(){ //This is called a method
 code here
}
```

### To access a method
```javascript
objectName.propertyName() //That property name you gave a function to.
```

### Changing the value of a property
```Javascript
objectName.property=new value// a number, string
```

### For in loop
```javascript
for(var variableName in objectName){
 code here
}
```

### To select an element in html to code it in javascript with the some id
```javascript
document.getElementById("")//id name in brackets
```

### To change the text in side a tag
first get the element by id name and store it in a variable
```javascript
variableName.innerHTML
```

### To run the javascript code only after the page is completely loaded
first create a function containing all the code that is to be run
```javascript
window.onlode=functionName;
```

### Shortcut for setting an atribute
```javascript
nameOfVariable.setAtribute("atribute1", "atribute2");
```

### To get the value of a atribute
```javascript
variableName.getAtribute//name of atribute you want value for
```

### To compare two strings or numbers
```javascript
==//this equality operator converts a string into a number
```
### Strict comparision
```javascript
===//gives true if everything is true including the type
```

### To split a string
```javascript
first store the string in a variable
variableName.split("the way you want to split")
```

### To assign any value
```javascript
=
```

### To compare two objects(step-by-step)
```javascript
step1 : create two objects
step2: create a variable and assign one object to the variable
step3: Now compare both the objects
step4: Compare the variable to the free object
//The two objects must be with same properties so that the output comes true
```

### Concatinating between strings and numbers
```javascript
var variableName="1"+3
console.log(variableName)//ouput: 13
```
### To get your current location in the web
```javascript
location.href//In the console 
