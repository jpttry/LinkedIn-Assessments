# JavaScript:  

#### Q1. You've written the event listener shown below for a form button, but each time you click the button, the page reloads. Which statement would stop this from happening?
```js
button.addEventListener('click', function(e) {
  button.className = 'clicked';
}, false);
```
- [ ]   e.stopReload();

- [x]	e.preventDefault();

- [ ]   e.Preventdefault();

- [ ]   e.PreventDefault{};
 
#### Q2. Which statement references the DOM node created by the code shown?
 `<p class="pull">Lorem Ipsum </p>`

- [ ] document.QuerySelector(".pull");

- [ ] document.QuerySelector(".pull");

- [x] document.querySelector(".pull");

- [ ] document.querySelector("#pull");
 
#### Q3. Which statement is the correct way to create a variable called rate and assign it the value 100?

- [ ] Var Rate = 100;

- [ ] const rate = 100;

- [ ] Let rate = 100;

- [x] let rate = 100;
 
#### Q4. When would the final statement in the code shown be logged to the console?
```js
let modal = document.querySelector('#results');
setTimeout(function() {
  modal.classList.remove('hidden');
}, 10000);
console.log('Results shown');
```

- [x] Immediately

- [ ] after results are received from the HTTP request

- [ ] after 10000 sec

- [ ] after 10 sec
 
#### Q5. Which statement creates a new object using the Person constructor?

- [ ] var student = new person();

- [ ] var student = new Person[];

- [x] var student = new Person();

- [ ] var student = Person();
 
#### Q6. When would you use a conditional statement?

- [ ] When you want to reuse a set of statements multiple times.

- [x] When you want your code to choose between multiple options.

- [ ] When you want to group data together.

- [ ] When you want to loop through a group of statement.
 
#### Q7. How is forEach statement different from a for statement?

- [ ] Only a for statement uses a callback function.

- [x] A for statement is generic, but a forEach statement can be used only with an array.

- [ ] Only a forEach statement lets you specify your own iterator.

- [ ] A forEach statement is generic, but a for statement ca be used only with an array.
 
#### Q8. Review the code below. Which statement calls the addTax function and passes 50 as the argument?
 
- [ ] addTax = 50;

- [ ] return addTax 50;

- `[x] addTax(50);`

- [ ] addTax 50;

#### Q9. What is the result in the console of running the code shown?
```js 
var Storm = function () {};
Storm.prototype.precip = 'rain';
var WinterStorm = function () {};
WinterStorm.prototype = new Storm();
WinterStorm.prototype.precip = 'snow';
var bob = new WinterStorm(); 

console.log(bob.precip);
```
- [ ] Storm()

- [ ] undefined

- [ ] 'rain'

- [x] 'snow'

 
#### Q10. How does a function create a closure?

- [ ] It reloads the document whenever the value changes.

- [x] It returns a reference to a variable in its parent scope.

- [ ] It completes execution without returning.

- [ ] It copies a local variable to the global scope.


#### Q11. Which keyword is used to create an error?

- [ ] catch

- [ ] error

- [x] throw

- [ ] exception


#### Q12. What would be the result in the console of running this code?

```js
for (var i = 0; i < 4; i++) {
  console.log(i);
}
```
- [ ] 12345

- [ ] 1234

- [x] 0123

- [ ] 012345

#### Q13. Which of the following operators can be used to do a short-circuit evaluation?

- [ ] \++

- [ ] \--

- [ ] \==

- [x] ||

#### Q14. What is the name of a function whose execution can be suspended and resumed at a later point?

- [ ] Async/ Await function

- [ ] Promise function

- [x] Generator function

- [ ] Arrow function


#### Q15. The following program has a problem. What is it?

```js
var a;
var b = (a = 3) ? true : false;
```

- [ ] You can't define a variable without initializing it.

- [ ] You can't use a ternary in the right-hand side of an assignment operator.

- [ ] The code is using the deprecated var keyword

- [x] The condition in the ternary is using the assignment operator.