# Perfils d'Usuari 👤

## Formatador de Perfils amb Interfaces

**Objectiu:** Entendre les `Interfaces` i les propietats opcionals.

**Enunciat:** 

Crea una interfície per a un usuari i una funció que generi una descripció de text basant-se en les seves dades.

---

**Guia pas a pas:**

1. Crea una `interface Usuari` amb: `nom` (string), `edat` (number) i `feina` (string, **opcional** afegint el símbol `?`).
    
2. Crea una funció `mostrarPerfil(usuari: Usuari): string`.
    
3. Dins la funció, fes un condicional:
    
    - Si l'usuari té feina, retorna: _"En/La [nom] té [edat] anys i treballa de [feina]."_.
        
    - Si no en té, retorna: _"En/La [nom] té [edat] anys i actualment no treballa."_
        
4. Crea dos objectes d'usuari diferents per provar els dos resultats al console.log.
    
