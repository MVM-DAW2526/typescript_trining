# El DOM Fosc 🌙

## Mode Fosc Vanilla

**Objectiu:** Practicar el _Type Casting_ al DOM i els esdeveniments bàsics.

**Enunciat:** 

Tingues un botó a l'HTML que, en fer-hi clic, canviï el color de fons de la pàgina entre blanc i negre.

---

**Guia pas a pas:**

1. Afegeix un `<button id="btn-tema">Canviar Tema</button>` al teu fitxer `index.html`.
    
2. A TypeScript, captura el botó assegurant el tipus:
    
    - `const boto = document.getElementById("btn-tema") as HTMLButtonElement;` // A classe us he ensenyat la forma de generics que els programadors de JAVA fan servir
        
3. Captura el body: `const body = document.body;`
    
4. Crea una variable d'estat: `let esFosc: boolean = false;`.
    
5. Afegeix un `addEventListener("click", ...)` al botó. A dins, inverteix el valor de `esFosc` i modifica `body.style.backgroundColor` i `body.style.color` en conseqüència.
