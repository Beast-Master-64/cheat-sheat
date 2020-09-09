## types of data
- text data= "hello"
- true or false data= true or false
- number data= 100
## creating variables
1. write down let
```javascript
let
```
2.write down the name
```javascript
let yishai
```
3.add =
```javascript
let yishai = 
```
4. add any type of data
```javascript
let  name1= true;
```
```javascript
let name2= "text";
```
```javascript
let name3 = 1;
```
## existing functions
- console.log=displaying something in the console
```javascript
console.log ("hello");
let v =1;
console.log (v);
```
- prompt=displaying somthing on the users screen and returns what the user typed in
```javascript
let userdata = prompt ("how are you");
```
- alert = displays something on the users screen
```javascript
alert ("how are you");
```
```javascript
let user = "hi"
alert (user);
```
## Steps to writing a if statment

1. write down if 
```javascript
if
```
2. put in ()
```javascript
if ()
```
3. put in {}
```javascript
if (){

}
```
4. put in code that = true or false
```javascript
if (true){

}
```
```javascript
let age=12;
if (age ==12){

}
```
```javascript
let name="yishai";
if (name=="yishai"){

}
```
## Steps to writing a function

1. write down functon amf the name of the function
```javascript
function nameoffunction 
```
2.put in () 
```javascript
function nameoffunction ()
```
3.put in currly braces
```javascript
function nameoffunction (){

}
```
4. (optional) put in perameters seperated by commas
```javascript
function nameoffunction (name1,name2){

}
```
5. (optional to return something
```javascript
function nameoffunction (name1,name2){
return name1;
}
```
## calling a function

1.name of the function
```javascript
nameoffunction
```
2. put in the ();
```javascript
nameoffunction ();
```
3.(optanal) put in the arguments(arguments can be text data, numbers, true false, or variables)
```javascript
nameoffunction ("perameter",1);
```
## objects

an object is a variable that can store multiple values

the key is the part after the dot

damage.**headshot**=60;

the value is whatever the key =

damage.headshot=**60**;
1. creat the object
```javascript
let damage = {};
damage.headshot=60;
damage.bodyshot=30;
damage.health=100;
damage.healthdamage=function (){
damage.health=damage.health-30;
}
```
2. using objects
```javascript
console.log (damage.headshot, damage.bodyshot, damage.health);
damage.healthdamage();
```
## what a list is
a variable that can store multiple values 
## create arrays and lists
1.make a variable
```javascript
let list
```
2. set the variable = to something and use square brackets
```javascript
let list = [];
```
3. (optinal) start a list with data in it
```javascript
let list = [1, 2, 3];
```
## how to get something from the list
1. write name of variable
```javascript
list
```
2. write down square brackets
```javascript
list[]
```
3. put in the number
```javascript
list[0]
```
4. the list starts from 0
## how to add to the list
1. write down the variables name
```javascript
list
```
2. write down ".push"
```javascript
list.push
```
3. add ()
```javascript
list.push ();
```
4. write down the data
```javascript
list.push (1, 2, 3);
```
## forEach
1. what is forEach
it is used to go through each element in the array
2. write the variable name down
```javascript
list
```
3. write the word forEach next to the variable
```javascript
list.forEach
```
4. add ()
```javascript
list.forEach ()
```
5. write the word function
```javascript
list.forEach (function)
```
6. add ()
```javascript
list.forEach (function())
```
7. write down the parameters
```javascript
list.forEach (function(item, index))
```
8. add {}
```javascript
list.forEach (function(item, index){

})
```




