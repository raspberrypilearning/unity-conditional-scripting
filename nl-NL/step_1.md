In C# kun je if/else-statements (als/anders) gebruiken om voorwaarden te controleren:

--- code ---
---
language: cs
---

if (voorwaarde1)
{
  // code die moet worden uitgevoerd als voorwaarde1 waar is
} 
else if (voorwaarde2) 
{
  // code die moet worden uitgevoerd als voorwaarde1 onwaar is en voorwaarde2 waar is
} 
else
{
  // code die moet worden uitgevoerd als voorwaarde1 en voorwaarde2 onwaar zijn
}

--- /code ---

Je kunt vergelijkingsoperatoren gebruiken om variabelen, getallen en strings te vergelijken: `<` `>` `==`.

Je kunt voorwaarden tenietdoen met `!` dus `!hasItem` is True als `hasItem` False is.

Je kunt voorwaarden samenvoegen met **Boolean en** `&&` en **Boolean of** `||`.

Voorbeeld:

--- code ---
---
language: cs
---
if(transform.position.x < minPosition || transform.position.x > maxPosition)
{
    transform.Rotate(0, 180, 0); // keer om
}
--- /code ---

![Een gif van een auto in de gameweergave die 180 graden draait wanneer deze een min- OF max-positie bereikt.](images/car-patrol.gif)