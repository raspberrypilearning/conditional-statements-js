En JavaScript, les instructions conditionnelles sont utilisées dans ton code pour prendre des décisions en fonction de certaines conditions. Les conditions sont vérifiées pour voir si elles sont vraies et le code est exécuté en fonction du résultat de ces vérifications.

Il existe trois types d'instructions conditionnelles en JavaScript :
`if`, `else if`, `else`.

### if

`if` est utilisé pour exécuter un bloc de code **si** (if) une condition spécifiée est remplie (vraie).

## --- code ---

language: js
filename:
line_numbers: true
-------------------------------------------------------

if (condition) {
// Code à exécuter si la condition est vraie
}

\--- /code ---

### else if

`else if` est utilisé pour vérifier plusieurs conditions. Différents blocs de code sont exécutés en fonction des résultats de ces vérifications.

Lorsqu'une condition `else si` est remplie, aucune vérification n'est faite sur les blocs `else if` (ou `else`) suivants.

## --- code ---

language: js
filename:
line_numbers: true
-------------------------------------------------------

if (condition1) {
// Code à exécuter si la condition1 est vraie
} else if (condition2) {
// Code à exécuter si la condition2 est vraie
}

\--- /code ---

### else

`else` définit un bloc de code alternatif qui est exécuté si les conditions précédentes (`if` et/ou `else if`) ne sont pas remplies (false).

## --- code ---

language: js
filename:
line_numbers: true
-------------------------------------------------------

if (condition1) {
// Code à exécuter si la condition1 est vraie
} else if (condition2) {
// Code à exécuter si la condition2 est vraie
} else {
// Code à exécuter si aucune des conditions n'est vraie
}

\--- /code ---

### Comment écrire une instruction conditionnelle

- Utilise le mot clé `if` pour démarrer l'instruction conditionnelle
- Place la condition que tu souhaites vérifier entre parenthèses `()`
- Ajoute à l'intérieur des accolades `{}` le code qui s'exécutera si la condition est vraie

## --- code ---

language: js
filename:
line_numbers: true
-------------------------------------------------------

var age = 18;

if (age >= 18) {
console.log("Tu es un adulte.");
}

\--- /code ---


