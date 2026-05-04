# La Biblioteca 📚

**Títol:** Sistema de Préstec de Llibres

**Objectiu:** Manipulació avançada d'arrays d'objectes i modificació d'estats.

**Requeriments:**

- Defineix una `interface` anomenada `Llibre` amb: `títol` (text), `autor` (text) i `estaPrestat` (booleà).
    
- Crea un Array ple de llibres (almenys 4, i que alguns estiguin prestats i altres no).
    
- Crea **dues funcions** separades:
    
    1. `llibresDisponibles(...)`: Rep la llista de llibres i retorna un _nou array_ que només contingui els llibres on `estaPrestat` sigui fals.
        
    2. `prestarLlibre(...)`: Rep la llista de llibres i un `títol` (text). Ha de buscar el llibre amb aquest títol a l'array i canviar el seu estat `estaPrestat` a _true_. Si el llibre no existeix, ha de fer un console.log avisant de l'error.
        
- Executa les funcions per consola per demostrar que els llibres canvien d'estat correctament.
