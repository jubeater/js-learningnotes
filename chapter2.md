#Syntax

##Statements

+ without ';':
>*first statement*
*second statement*

+ with ';':
>*first statement;second statement;*  

or
>*first statement;*
*second statement;* 

##Comments

>// this is the single comment
<!- This is also a single comment

>/* this is the multi comments
this is the multi comments*/

##Variables
>var a = 'lalala';
var name, age;
name = 'jubeater';
age = 27;

##Data types
+ number
>var num = 40;
+ string
>var str = 'this is a string';
+ boolean
>var isTrue = true;  
+ arrays
>var beatles = Arrays(5);
var beatlestwo = Array();
var beatlethree = Array('one','two','three');
var beatlefour = ['one','two','three','four'];
+ Objects
>var brother = Object();
brother.nickname = 'john';
brother.age = '33';

or
>var brother = {nickname:'john',age:'33'};

##Condition statements
>if (condition) { 
    statements;
}

##Looping statements
>while(condition){
    statements;
}
//statement execute only the condition true

>do {
    statements;
} while (condition); 
//the statement will execute at least once even the condition is false

>for(init condition;test condition;alter condition){
    statements;
}

##Hoisting

<p>javascript will put all the init to the top of the current scope, but it's only put the init up, not the decla. Besides, the Let/Const which come from ES6 are not hoisted</p>

<p>the "use strict" from ES5 disable the variable to be used if it's not declared</p>