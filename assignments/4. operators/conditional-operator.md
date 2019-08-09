## If Statement
1.  🎖Make a simple calculator with these functions. Using prompt, type conversion, if else statement. Use prompt to take the input from user i.e two numbers and an operation (Add, Sub, Mul, Div).


  ⛑ Rule
    * [ ] While substracting and dividing keep in mind the number one should be greater then number two. If not show alert saying `Number Two is larger then Number one`.
  ⚡️ Operations
    * [ ] Add
    * [ ] Sub
    * [ ] Mul
    * [ ] Div


```
var num1 = +prompt("give a number");
var num2 = +prompt("give a number");
var operator =prompt("give an operator like add,sub,div,mul");
if (operator=="+"){alert (num1 + num2);}
else if (operator=="-"){
 if (num1 < num2){alert ("num2 is greater than num1");}
}
else { alert (num1 - num2);}
else if (operator=="/"){
 if (num1 < num2){alert ("num2 is greater than num1");}
}
else { alert (num1 / num2);}
else if (operator=="*"){alert (num1 * num2);}


```

2. 🎖Write a if else statement which checks if the status is single `console.log` the message `John is single` or else `John is married`

```js
var firstName = 'John';
var status = 'single';
// Your code goes here
if(status=='single')
{console.log("John is single");}
else{console.log("John is married");}

3. 🎖Write a JavaScript program that takes two `integers` from user (using prompt) and alerts the larger number.
```js
// your code goes here
var integer1=prompt("Put a number");
var integer2=prompt("Put a number");
if (integer1>integer2) 
{alert(integer1 + " is larger");}
else{alert(integer2 + " is larger);}

4. 🎖Write a JavaScript conditional statement to find the sign (+, -) of product of three numbers. Take those three numbers from user using `prompt`. Display an alert box with the specified sign.

```js
// Your code goes here
var num1 = prompt("write a number");
var num2 = prompt("write a number");
var num3 = prompt("write a number");
var product = num1, num2, num3;
if(product >= 0)
{alert("+");}
else{alert("-");}

## Switch Statement

1. 🎖Using switch statement do the following

Take a number value from user and alert the message if it matches the conditions.
* [ ] ONE, if `number` is equal to 1.
* [ ] TWO, if `number` is equal to 2.
* [ ] THREE, if `number` is equal to 3.
* [ ] FOUR, if `number` is equal to 4.
* [ ] FIVE, if `number` is equal to 5.
* [ ] SIX, if `number` is equal to 6.
* [ ] SEVEN, if `number` is equal to 7.
* [ ] EIGHT, if `number` is equal to 8.
* [ ] NINE, if `number` is equal to 9.
* [ ] PLEASE TRY AGAIN, if  is none of the above.
```js
// Your code goes here

let value = +prompt("Enter a number");

	switch(value) {
		case 1:
		alert("One");
		break;
		case 2:
		alert ("Two");
		break;
		case 3:
		alert ("Three");
		break;
		case 4:
		alert ("Four");
		break;
		case 5:
		alert ("Five");
		break;
		case 6:
		alert ("Six");
		break;
		case 7:
		alert ("Seven");
		break;
		case 8:
		alert ("Eight");
		break;
		case 9:
		alert ("Nine");
		break;
		default: alert("Please Try Again");
		break;
	}





```

2. 🎖Using switch statement do the following

Take the value of `marks` (0-100) from user using `prompt` and `alert` the message (Your Grade is AA) as giver below.
* [ ] `AA` if `marks` is greater than 90.
* [ ] `AB` if `marks` is greater than 80 and less than or equal to 90
* [ ] `BB` if `marks` is greater than 70 and less than or equal to 80
* [ ] `BC` if `marks` is greater than 60 and less than or equal to 70
* [ ] `CC` if `marks` is greater than 50 and less than or equal to 60
* [ ] `CD` if `marks` is greater than 40 and less than or equal to 50
* [ ] `DD` if `marks` is greater than 30 and less than or equal to 40
* [ ] `FF` if `marks` is less than or equal to 30
```js
// 
var input = +prompt("Enter Your Marks")
	
	switch(true){
		case(input > 90 && input <= 100 ):
		alert("AA");
		break;
		case(input > 80 && input <= 90):
		alert("AB");
		break;
		case(input > 70 && input <= 80 ):
		alert("BB");
		break;
		case(input > 60 && input <= 70 ):
		alert("BC");
		break;
		case(input > 50 && input <= 60 ):
		alert("CC");
		break;
		case(input > 40 && input <= 50 ):
		alert("CD");
		break;
		case(input > 30 && input <= 40 ):
		alert("DD");
		break;
		case(input <= 30 ):
		alert("FF");
		break;
		default: alert("default value");
	}
```
