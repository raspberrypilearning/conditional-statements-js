In JavaScript worden voorwaardelijke statements gebruikt om beslissingen in jouw code te nemen op basis van voorwaarden. Er wordt gecontroleerd of de voorwaarden waar zijn, op basis van de uitkomst van de controles wordt de code uitgevoerd.

Er zijn drie typen voorwaardelijke statements in JavaScript:
`if`, `else if`, `else`.

### if

`if` wordt gebruikt om een codeblok uit te voeren **als** aan een opgegeven voorwaarde is voldaan (true).

--- code ---
---
language: js
filename: 
line_numbers: true
---
if (voorwaarde) {
  // Code die moet worden uitgevoerd als de voorwaarde waar is
}

--- /code ---

### else if

`else if` wordt gebruikt om meerdere voorwaarden te controleren. Het voert verschillende codeblokken uit op basis van de resultaten van de controles.

Wanneer aan een `else if`-voorwaarde is voldaan, worden er geen controles meer uitgevoerd op daaropvolgende `else if`- (of `else`-) blokken.

--- code ---
---
language: js
filename: 
line_numbers: true
---

if (voorwaarde1) {
  // Code die moet worden uitgevoerd als voorwaarde1 waar is
} else if (voorwaarde2) {
  // Code die moet worden uitgevoerd als voorwaarde2 waar is
}

--- /code ---

### else

`else` stelt een alternatief codeblok in dat wordt uitgevoerd als aan de voorgaande (`if` en/of `else if`) voorwaarden niet wordt voldaan (false).

--- code ---
---
language: js
filename: 
line_numbers: true
---

if (voorwaarde1) {
  // Code die moet worden uitgevoerd als voorwaarde1 waar is
} else if (voorwaarde2) {
  // Code die moet worden uitgevoerd als voorwaarde2 waar is
} else {
  // Code die moet worden uitgevoerd als geen van de voorwaarden waar is
}

--- /code ---

### Hoe schrijf je een voorwaardelijk statement

- Gebruik het trefwoord `if` om de voorwaardelijke instructie te starten
- Plaats de voorwaarde die je wilt controleren tussen haakjes `()`
- Voeg code die wordt uitgevoerd als de voorwaarde waar is tussen de accolades `{}`

--- code ---
---
language: js
filename: 
line_numbers: true
---

var age = 18;

if (age >= 18) {
  console.log("Je bent volwassen.");
}

--- /code ---


