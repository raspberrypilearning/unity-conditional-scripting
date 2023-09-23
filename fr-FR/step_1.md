En C#, tu peux utiliser des instructions if/else pour vérifier des conditions :

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

Tu peux utiliser des opérateurs de comparaison pour comparer des variables, des nombres et des chaînes de caractères : `<` `>` `==`.

Tu peux annuler des conditions en utilisant `!`, ainsi `!hasItem` est vrai si `hasItem` est faux.

Tu peux joindre des conditions ensemble en utilisant **Booléen et** `&&` et **Booléen ou** `||`.

Exemple :

--- code ---
---
language: cs
---
if(transform.position.x < minPosition || transform.position.x > maxPosition)
{
    transform.Rotate(0, 180, 0); // turn around
}
--- /code ---

![Un gif animé d'une voiture en vue Game qui tourne à 180 degrés lorsqu'elle atteint une position minimale ou maximale.](images/car-patrol.gif)