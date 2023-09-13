In C# you can use if/else statements to check conditions:

```
if (condition1)
{
  // code to run if condition1 is True
} 
else if (condition2) 
{
  // code to run if condition1 is false and condition2 is True
} 
else
{
  // code to run if condition1 and condition2 are False
}
```
 
You can use comparison operators to compare variables, numbers and strings: `<` `>` `==`.

You can join conditions together using **Boolean and** `&&` and **Boolean or** `||`.

Example:

```
if(transform.position.x < minPosition || transform.position.x > maxPosition)
{
    transform.Rotate(0, 180, 0); // turn around
}
```

![An animated gif of a car in Game view turning 180 degrees when it reaches a min OR max position.](images/car-patrol.gif)
