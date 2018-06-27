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
