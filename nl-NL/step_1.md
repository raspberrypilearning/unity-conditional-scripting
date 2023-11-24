In C# kun je if/else-statements (als/anders) gebruiken om voorwaarden te controleren:

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

Je kunt vergelijkingsoperatoren gebruiken om variabelen, getallen en strings te vergelijken: `<` `>` `==`.

Je kunt voorwaarden omkeren met `!` dus `!hasItem` is True als `hasItem` False is.

Je kunt voorwaarden samenvoegen met **Boolean en** `&&` en **Boolean of** `||`.

Voorbeeld:

--- code ---
---
language: cs
---
if(transform.position.x < minPosition || transform.position.x > maxPosition)
{
    transform.Rotate(0, 180, 0); // turn around
}
--- /code ---

![Een gif van een auto in de gameweergave die 180 graden draait wanneer deze een min- OF max-positie bereikt.](images/car-patrol.gif)