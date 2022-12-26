# Javascript Cheat Sheet

# Introduction
1. JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions.
2. JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles.
3. JavaScript's dynamic capabilities include runtime object construction, variable parameter lists, function variables, dynamic script creation (via eval), object introspection (via for...in and Object utilities), and source-code recovery (JavaScript functions store their source text and can be retrieved through toString()).

# A. General
Comments :- // this is a comment 
            /* or this is a comment */

# B. Numbers
## 1. Round
```
Code :-
Math.round(4.7) // 5
```

## 2. Floor
```
Code :-
Math.floor(4.7) // 4
```

## 3. Ceil
```
Code :-
Math.ceil(4.7) // 5
```

## 4. Min
```
Code :-
Math.min(2, 5, 1) // 1
```

## 5. Max
```
Code :-
Math.max(2, 5, 1); // 5
```

## 6. Random
```
Code :-
Math.random(); // 0.47231881595639025
```

# C. Alerts & Prompts
## 1. Alert
```
Code :- 
alert("Please Refresh Your Page");

let name = "Javascript Cheat Sheet";
alert(name);
```

## 2. Prompt
```
Code :- 
let firstName = prompt("What is your first name");
let lastName = prompt("What is your last name");
let fullName = firstName + " " + lastName;
alert(fullName);
``` 

# D. Variables
## 1. Variable creation
```
Code :- 
let school = "Leetcode";
let fullPackage = "Leetcode Pro";
let projects = 4;
let awesome = true;
```

## 2. Variable operations
```
Code :-
let x = 2;
let y = 3;
let z = x + y; // 5

let city = "Mumbai";
let country = "India";
let place = city + " " + country; //Mumbai India
```

## 3. Variable data Types
```
Code :- 
let age = 23; // Number
let name = "Pawan"; // String
let canCode = true; // Boolean, could also be false
```

## 4. Structure structure types
```
Code :-
let students = ["Pawan", "Rahul", "Ankit"]; // Array

let kate = {
  firstName: "Pawan",
  lastName: "Jha",
  age: 23,
  canCode: true,
}; // Object
```

# E. Strings
## 1. Creating a string
```
Code :- 
let name = "Pawan"; // "Pawan"
``` 

## 2. String concatenation
```
Code :-
let firstName = "Pawan";
let lastName = "Jha";
let fullName = firstName + " " + lastName; // "Pawan Jha"

//or
let fullName = `${firstName} ${lastName}`;
```

## 3. Trim
```
Code :-
let city = " Mumbai  ";
city.trim(); // "Mumbai"
```

## 4. Replace
```
Code :-
let city = "Mumbai";
city = city.replace("a", "e"); // "Mumbei"
```

## 5. toLowerCase
```
Code :-
let city = "MUMBAI";
city = city.toLowerCase(); // "mumbai"
```

## 6. toUpperCase
```
Code :-
let city = "Mumbai";
city = city.toUpperCase(); // "MUMBAI"
```

## 7. Template literals
```
Code :-
let city = "Mumbai";
let sentence = `Pawan is from ${city}`; // Pawan is from Mumbai
```

# F. Arrays
## 1. Array declaration
```
Code :-
let myList = [];
let fruits = ["apples", "oranges", "bananas"];
myList = ['banana', 3, go, ['John', 'Doe'], {'firstName': 'John', 'lastName': 'Smith'}]
```

## 2. Access an Array
```
Code :-
fruits
fruits[0]
fruits[1]
fruits[2]
fruits[3]
```

## 3. Update an Array item
```
Code :-
fruits[1] = "Mango";
fruits[1] = 3;
```

## 4. While loop
```
Code :-
let times = 0;
while (times < 10) {
  console.log(times);
  times = times + 1;
}
```

## 5. forEach loop
```
Code :-
let fruits = ['apples', 'oranges', 'bananas'];
fruits.forEach(function(fruit) {
  alert("I have " + fruit + " in my shopping bag");
});
```

## 6. do while loop
```
Code :-
let times = 0;
do {
  console.log(times);
  times = times + 1;
} while(times < 10)
```

## 7. for loop
```
Code :-
for (let i = 0; i < 10; i++) {
  console.log("i is " + i);
}

for (let i = 0; i < myList.length; i++) {
  alert("I have " + myList[i] + " in my shopping bag");
}
```

## 8. Remove first item
```
Code :-
fruits.shift()
```

# G. If else
## 1. if statement
```
Code :-
let country = prompt("What country are you from?");

if (country === "India") {
  alert("You are cool");
}

if (country !== "India") {
  alert("Too bad for you");
}
```

## 2. if else statement
```
Code :-
let age = prompt("How old are you?");

if (age < 18) {
  alert("You cannot apply");
} else {
  alert("You can apply");
}
```

## 3. Nested if else statements
```
Code :-
if (age < 18) {
  alert("you can't apply");
} else {
  if (age > 120) {
    alert("you can't apply");
  } else {
    alert("you can apply");
  }
}
```

## 4. Logical Or
```
Code :-
if (age < 18 || gender === "male") {
  alert("You can't join Community 👩‍💻");
}
```

## 5. Logical And
```
Code :-
if (continent === "Asia" && language === "Hindi") {
  alert("You are from India (IN)");
} else {
  alert("You are not from INDIA");
}
```

## 6. Comparison and Logical Operators
```
Code :-
2 > 3 // false 
2 < 3 // true 
2 <= 2 // true
3 >= 2 // true
2 === 5 // false 
2 !== 3 // true 
1 + 2 === 4 // false
```

# H. Dates
## 1. Get current time
```
Code :-
let now = new Date();
console.log(now);
```

## 2. Create a date
```
Code :-
let date = Date.parse("01 Jan 2025 00:00:00 GMT");
```

## 3. Get date data
```
Code :-
let now = new Date();
now.getMinutes(); // 0,1,2, 12
now.getHours(); //1, 2, 3, 4
now.getDate(); //1, 2, 3, 4
now.getDay(); // 0, 1, 2
now.getMonth(); // 0, 1, 2
now.getFullYear(); // 2021
```

# I. Objects
## 1.Creating a new object
```
Code :-
let fruit = new Object(); // "object constructor" syntax

let user = {}; // "object literal" syntax

let student = {
  firsName: "Pawan",
  lastName: "Jha",
};

let anotherStudent = {
  firstName: "Sarita",
  lastName: "Jha",
  female: true,
  greet: function () {
    alert("Hey");
  },
};
```

## 2. Reading an object properties
```
Code :-
let user = {
  firstName: "Pawan",
  lastName: "Jha",
  gender: "Male",
};

alert(user.firstName); // Pawan
alert(user.lastName); // Jha

// or
alert(user["firstName"]); // Pawan
alert(user["lastName"]); // Jha
```

## 3. Adding object properties
```
Code :-
let user = {
  firstName: "Pawan",
  lastName: "Jha",
  gender: "Male",
};

user.profession = "Software Developer";
```

## 4. Object Arrays
```
Code :-
let users = [
  {
    firstName: "Pawan",
    lastName: "Jha",
  },
  {
    firstName: "Rahul",
    lastName: "Jha",
  },
];

users.forEach(function (user, index) {
  for (let prop in user) {
    alert(prop + " is " + user[prop]);
  }
});
```

## 5. Enumerating the properties of an object
```
Code :-
let user = {
  firstName: 'Pawan',
  lastName: 'Jha',
  gender: 'Male'
}
for(let prop in user) {
  alert(prop); // firstName, lastName, gender
  alert(user[prop]); // 'Pawan', 'Jha', 'Male'
}
```

# J. Functions
## 1. JS Functions
```
Code :-
function sayFact() {
  let name = prompt("What's your name?");

  if (name === "Sofia") {
    alert("Your name comes from the Greek -> Sophia");
  }
}

sayFact();
```

## 2. JS Functions Parameters
```
Code :-
function fullName(firstName, lastName) {
  alert(firstName + " " + lastName);
}

let firstName = prompt("What's your first name?");
let lastName = prompt("What's your last name?");
fullName(firstName, lastName);
fullName("Pawan", "Jha");
```

## 3. JS Functions Return
```
Code :-
function add(x, y) {
  return x + y;
}

let result = add(3, 4);
let result2 = add(result, 0);


function getFullName(firstName, lastName) {
  let fullName = firstName + " " + lastName;
  return fullName;
}

let userFullName = getFullName("Pawan", "Jha");
alert(userFullName); // Pawan Jha
alert(getFullName("Rahul", "Jha")); // Rahul Jha
```

## 4. Closures
```
Code :-
function hello() {
  function go() {
    alert go(name);
  }

  let name = "Pawan";
  go();
}
```

# K. Debugging
## 1. Console.log
```
Code :-
console.log(name);
console.log("Let's code!");
```

# L. Selectors
## 1. QuerySelector :: Returns the first element (if any) on the page matching the selector.
```
Code :-
let li = document.querySelector("li");
let day = document.querySelector(".day");
let paragraph = document.querySelector("ul#list p");
```

## 2. QuerySelectorAll :: Returns all elements (if any) on the page matching the selector.
```
Code :-
let lis = document.querySelectorAll("li");
let paragraphs = document.querySelectorAll("li#special p");
```

# M. Events
## 1. Creating an event listener
```
Code :-
function sayHi() {
  alert("hi");
}

let element = document.querySelector("#city");
element.addEventListener("click", sayHi);

Note :: The sayHi function will be executed each time the city element is clicked. Click is the most common event type but you can also use click | mouseenter | mouseleave | mousedown | mouseup | mousemove | keydown | keyup.
```

## 2. setTimeout
```
Code :-
function sayHello() {
  alert('Hello')
}
setTimeout(sayHello, 3000);

Note :: It will only alert Hello after a 3 second delay.
```

## 3. setInterval
```
Code :-
function sayHello() {
  alert('Hello')
}
setInterval(sayHello, 3000);

Note :: It will say Hello every 3 seconds.
```

# N. AJAX
## 1. AJAX with Fetch
```
Code :-
let root = 'https://jsonplaceholder.typicode.com'
let path = 'users/1'

fetch(root + '/' + path)
  .then(response => (
    response.json()
  ))
  .then(json => (
    console.log(json)
  ));

Note :: We recommend axios instead
```

## 2. AJAX with Axios
```
Code :-
<!DOCTYPE html>
<html>
  <body>
    <script src="https://unpkg.com/axios/dist/axios.min.js"></script>
    <script>
      function showUser(response) {
        alert(`The user name is ${response.data.name}`);
      }

      let url = "https://jsonplaceholder.typicode.com/users/1";
      axios.get(url).then(showUser);
    </script>
  </body>
</html>
```

# O. Element manipulation
## 1. HTML classes
```
Code :-
let li = document.querySelector("li#special");
li.classList.remove("liked");
li.classList.add("something");

Note :: Update the element class names.
```

## 2. HTML content
```
Code :-
let li = document.querySelector("li")
li.innerHTML = "Hello World";

Note :: Update the HTML content of the selected element.
```

## 3. Forms
```
Code :-
<form>
  <input type="text" id="email" />
</form>
<script>

function signUp(event) {
  event.preventDefault();
  let input = document.querySelector("#email");
  console.log(input.value);
}
let form = document.querySelector("form");
form.addEventListener("submit", signUp);
</script>
```

# P. APIs
## 1. Geolocation API
```
Code :-
function handlePosition(position) {
  console.log(position.coords.latitude);
  console.log(position.coords.longitude);
}

navigator.geolocation.getCurrentPosition(handlePosition);

Note :: The Geolocation API allows the user to provide their location to web applications if they so desire. For privacy reasons, the user is asked for permission to report location information.
```
