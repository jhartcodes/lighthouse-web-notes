# Joel Hart's Notes
# Table of Contents


## Summary 

This repository contains all of the notes taken by [Joel](git@github.com:joelhart89/lighthouse-web-notes.git) for the Lighthouse Labs Web Development Bootcamp.

* [Week 1](/Week_1)
  * [Day 1](/Week_1/Day_1)

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  console.log("I don't know what to do!");

  if (hungry === true && availableTime <= 20) {
    console.log("Pick something up and eat in the lab or kitchen in the back, where you can get to know youre fellow classmates.");
  } else if (hungry === true && availableTime >= 20 && availableTime <= 30) {
    console.log("You deserve a break and could try a place in Gastown.");
  } else if (hungry === true && availableTime >= 30) {
    console.log("This is a bootcamp and you should probably reconsider.");
  } else if (hungry === false) {
    console.log("wait till you're hungry.");
  }
};
```
