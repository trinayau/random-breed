# Random Movie and Dog Generator Website
First JavaScript website in the @getfutureproof Gebru Cohort in collaboration with @iAmash412

## Brief
Our brief from Jagan was to create a website where we would use the methods Math.floor and Math.random to generate a random integer in JavaScript.

## Process
Aafthab and I decided to try building an array with 11 items, and use the randomly-generated integer to select an element in that array at that index.
We built it according to our interests, which were dogs and anime movies. 🐶🍿 
Firstly, we looked up dog breeds on Google and discussed with our colleagues our favourite anime movies. We put these into separate arrays.

We then wrote pseudocode to describe:
- How we would generate the random integer
- How we would use the random integer to select an element from the array
- How we would display that element in the HTML page

We also decided to add some CSS styling and a button with an event listener which would on click, refresh the page.

## Reflections
- After presenting our solution to the group, Jagan asked us how we would make the code more dynamic
- We realised that our initial code multiplied the Math.floor by a fixed number of items in the array (12)
- If our array increased in length, we would not generate a random number for the 12th item
- We made our code more scalable and dynamic by using array.length method rather than the fixed number to represent the total number of elements within the array
