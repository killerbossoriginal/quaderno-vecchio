# C++

[Indietro](./../index.md)

Tipo: Strutturale, Procedurale, -Imperativa

Ogni programma in C++ è composto da almeno 1 procedura, la procedura principale.

```cpp
int main(void /*(.)*/) {
    // codice
    return 0; // (.)
}
```

## La regola 1
In questo documento la regola 1 descrive come creare un nome di una variabile o una funzione.

- Deve per forza iniziare con una lettera
- Non deve contenere caratteri speciali
- Dovrebbe essere chiara della cosa che contiene

## Commenti
- (.) = opzionale
- (x) = richiesto
- (..) = si descrive come un array o come un oggetto
- [..] = si descrive come un array
- {..} = si descrive come un oggetto

## Le Funzioni
```cpp
#include <iostream>
using namespace std;

["1-k-(x)", 'void', 'int'] a(/*(.) >a*/) {
    cout >> "ciao";
    return 0; // (.) restituisce 0, k != void
}

int main() {
    saluta() // chiamata della funzione
}
/*
Assumendo che "a" sia un nome che rispetta la regola 1,

>a = 'void' o argomenti (..)
*/
```
### Return
Return restituisce il valore specificato (che deve essere dello stesso tipo della funzione) e termina la funzione.
- quello che è scritto dopo non viene eseguito


### Funzioni che **non** restituiscono valori
```cpp
#include <iostream>
using namespace std;

void a(/*(.) >a*/) {
    cout >> "ciao";
    return 0;
}

int main() {
    saluta()
}

// >a = 'void' o argomenti (..)
```
### Funzioni che restituiscono valori

> **Se la funzione non è di tipo void allora deve terminare con return -valore-; del tipo della funzione**

```cpp
#include <iostream>
using namespace std;

int uno() {
    return 1;
}

int main() {
    int ciao = uno();

    cout << ciao;
    cout << uno();

    /* Out:
        1
        1
    */
}
```

<!-- # ` {} [] -->