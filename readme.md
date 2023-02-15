# Esercizio: "html-css-toboolist"
Riproduco un layout usando *html* e *css*
---
In particolare uso:
- Proprietà come: **vertical-align** 
- pseudoselettori: **::before / ::after**

--- 
Variabili in CSS (esempio):

```
:root {
  --blue: #1e90ff;
  --white: #ffffff;
  --spaziatura: 20px 10px;
}
```

```
button {
  background-color: var(--white);
  color: var(--blue);
  border: 1px solid var(--blue);

  margin: var(--spaziatura);
```
- le variabili si salvano in `:root {}`
- si richiamano con var(--***)