---
layout: default
title: Home
---

# Usman Zahid
Fuck it man, my username is usmanzahidcode doesnt mean I have to have everythign like thatt. 
Its ok to have the code in the username for github but everywhere I will try to make it differnet.

Example code

```js
// Function to greet a user
function greet(name) {
    console.log(`Hello, ${name}!`);
}

// Arrow function example
const add = (a, b) => a + b;

// Loop through numbers
for (let i = 0; i < 5; i++) {
    console.log(`Number: ${i}`);
}

// Object example
const user = {
    name: "Usman",
    age: 25,
    greet: function () {
        console.log(`Hi, I'm ${this.name} and I'm ${this.age} years old.`);
    }
};

// Async function example
async function fetchData() {
    try {
        let response = await fetch("https://jsonplaceholder.typicode.com/posts/1");
        let data = await response.json();
        console.log("Fetched Data:", data);
    } catch (error) {
        console.error("Error fetching data:", error);
    }
}

// Event listener example
document.addEventListener("DOMContentLoaded", () => {
    console.log("Document is fully loaded");
});

// Execute functions
greet("Usman");
console.log("Sum:", add(10, 5));
user.greet();
fetchData();

```
