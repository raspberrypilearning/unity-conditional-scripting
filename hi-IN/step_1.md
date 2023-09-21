In C# you can use if/else statements to check conditions:

--- code ---
---
language: cs
---

if (condition1)
{
  // code to run if condition1 is True
} 
else if (condition2) 
{
  // code to run if condition1 is false and condition2 is True
} 
else
{ // code to run if condition1 and condition2 are False }

--- /code ---

You can use comparison operators to compare variables, numbers and strings: `<` `>` `==`.

You can negate conditions using `!` so `!hasItem` is True if `hasItem` is False.

You can join conditions together using **Boolean and** `&&` and **Boolean or** `||`.

Example:

--- code ---
---
language: cs
---
if(transform.position.x < minPosition || transform.position.x > maxPosition)
{
    transform.Rotate(0, 180, 0); // turn around
}
--- /code ---

![An animated gif of a car in Game view turning 180 degrees when it reaches a min OR max position.](images/car-patrol.gif)