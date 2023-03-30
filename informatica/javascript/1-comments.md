# [JS] Commenti
[Indietro](./index.md) [Avanti](./2-variabili.md)

I commenti sono righe di codice che l'interprete JavaScript ignorerà intenzionalmente

## Commento a una sola riga
Per fare un commento a una sola riga basta mettere `//` davanti alla riga
```js
// Commento a una sola riga
```

## Commento a più righe
Per creare un commento a più righe bisogna mettere all'inizio `/*` e alla fine `*/`
```js
/*
Questo è
un commento
a più righe
*/
```

### Utilizzi aggiuntivi
Si può utilizzare il commento a più righe su una riga sola per togliere una parte della riga

```js
console.log(/*'ciao',*/'come va?')
```
in questo caso leggerà soltanto 'come va?' e non 'ciao',

[Indietro](./index.md) [Avanti](./2-variabili.md)
