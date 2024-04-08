# 11-3 quicker notes on how to understand functions
NOTE TO FUTURE SELF: THIS ONE REMINDS YOU HOW TO DO FUNCTIONS: KEEP IT ON YOU BECAUSE I KNOW YOU _WILL_ NEED IT. CLOSURES ARE TRICKY AS HELL<br>

*examples provided are templates based off the notes, reuse and rewrite as needed in different ways in FIRST_BLOOD*

## Declaring or expressing, or argueing a function?
This is a `Declaration`
```
function divNumbers (num1, num2) {
  return  num1 / num2
```
Valuables are made inside the function and called later with outsider values

Functions can also be `expressed`, say when you use a function to declare a value
```
const calcZone = (num1, num2) => num1 + num2:
```
Variables and primitive datatypes can be easily declaired through functions, but so can other functions.
```
function result(num) {
  return 'Total is ${num}
function numberResult (num, func) {
  return func(num);
}
console.log(result(21, result)
```
!REMEMBER THE BOOMSTICK THEORY!<br>
What is happening here is that a function is being declared, and then another function is declared and structured to call another function with the `func` slot (dont call the function you need in the function, do that in the console.log line).<br>

Think of it as taking one half of a double barreled shotgun and adding two more in its place. You do this over and over until you have a boom chair that can be pulled with one trigger.


 Now go forth and code that scoreboard for the rest of the half of this assignment,
