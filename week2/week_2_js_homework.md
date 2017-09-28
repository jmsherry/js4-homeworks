# Week 2 homework

So, we've learned about the primitives:

* **strings** (text)
* **numbers**
* **boolean** (true/false)
* **null** (for you to nullify things)
* **undefined** (when the system has no value for something)

Primitives hold 1 piece of data

We then learned about the '[Custom] Object Family':

* **objects** - a store of 'key - value pairs'
* **arrays** - an enhanced object for dealing with 'order' and associating/grouping things together
* **functions** - an object that can run its stored code. Functions are our plans: We create them, then, when we know the information we need, we execute them to make things happen.

Now it's time to put all that together.

## Helpful Hints
### Iteration
We've not done loops yet, SO, if you have some things in an array and you want to go over item and do something (read/write) then you use forEach:

```javascript
var myArr = [1,2,3];
myArr.forEach(/* callback --> */function(item){
  // do something with the item
  console.log(item);
});
```

The above function runs your callback function once for each item in the array, passing that item as the argument to the callback.

### Control Structures
We did this in the first week in the pseudo-code. In JavaScript you've got `if - else if - else`

```javascript
if(<expression1>) {
  // code block 1
} else if(<expression2>) {
  // code block 2
} else if(<expression3>) {
  // code block 3
} else {
  // code block 4
}
```
** Whatever your expressions are they must evaluate to `true` or `false`, or a truthy/falsy value. **

Each expression is checked for 'truthiness': If it's true, then it goes into that block of code: So if <expression1> was true, then code block 1 would execute; if not then we check <expression1>, etc. until finally, if none are true, we execute code block 4.

You can find out what a particular expression returns by logging it to the console. Typing in `console.log(person.name === 'dad');` will show you `true` or `false` in the console, for example.

### typeof
You can tell the type of a variable by using the `typeof` operator. `typeof myVar` returns a string with the name of the type as its value:

```javascript
var age = 32;
var name = 'tom';
var isDeveloper = true;
var friends = [];
var newFriend = {};
var fn = function(){};
console.log(typeof age); // 'number'
console.log(typeof name); // 'string'
console.log(typeof isDeveloper); // 'boolean'
console.log(typeof friends); // 'object'
console.log(typeof newFriend); // 'object'
console.log(typeof fn); // 'function'
console.log(typeof null): // 'object'
console.log(typeof undefined); // 'undefined'
```
____________________________________________


## Tasks

Tasks are available [here](https://codepen.io/jmsherry/pen/oGWyNp)
