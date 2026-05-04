# Filtrant Dades 🔢

## Filtrador de números parells

**Objectiu:** Practicar amb arrays, tipus bàsics i funcions.

**Enunciat:** 

Crea una funció que rebi un array de números i retorni un **nou array** només amb els números parells.

---

**Guia pas a pas:**

1. Defineix la signatura de la funció: `function filtrarParells(numeros: number[]): number[] { ... }`
    
2. Dins la funció, utilitza el mètode `.filter()` dels arrays de JavaScript.
    
3. Recorda que per saber si un número és parell, pots fer servir l'operador mòdul (`%`). Si `numero % 2 === 0`, és parell.
    
4. Fes un `console.log()` passant-li un array de prova (ex: `[1, 2, 3, 4, 5, 6]`) per comprovar-ho.
