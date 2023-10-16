En C#, tu peux utiliser des instructions if/else pour vérifier des conditions :

--- code ---
---
language: cs
---

if (condition1)
{
  // code à exécuter si la condition1 est vraie
} 
else if (condition2) 
{
  // code à exécuter si la condition1 est fausse et la condition2 est vraie
} 
else
{
  // code à exécuter si la condition1 et la condition2 sont fausses
}

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
    transform.Rotate(0, 180, 0); // demi-tour
}
--- /code ---

![Un gif animé d'une voiture en vue Game qui tourne à 180 degrés lorsqu'elle atteint une position minimale ou maximale.](images/car-patrol.gif)