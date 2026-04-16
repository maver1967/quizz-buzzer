# 🎯 Quiz Buzzer

Gioco quiz interattivo per la classe con proiettore e cellulari.

## Come funziona

1. Il docente apre il sito sul PC collegato al proiettore
2. Crea una stanza → appare un QR code
3. Gli studenti scansionano il QR col cellulare
4. Ogni squadra sceglie nome e colore
5. Il docente avvia il quiz
6. Le domande appaiono sul proiettore con opzioni A B C D colorate
7. Gli studenti premono BUZZ sul cellulare → il primo sceglie la risposta
8. Verde/rosso + punteggio automatico

## Tasti rapidi (docente)

| Tasto | Azione |
|-------|--------|
| Spazio | Apri i buzzer |
| N | Prossima domanda |
| C | Classifica |

## Deploy su GitHub Pages

1. Crea un repository su GitHub
2. Carica i file (`index.html`)
3. Vai in **Settings → Pages → Source: main branch**
4. Il sito sarà disponibile su `https://tuousername.github.io/nome-repo/`

## Formato domande JSON

```json
[
  {
    "q": "Testo della domanda?",
    "options": ["Opzione A", "Opzione B", "Opzione C", "Opzione D"],
    "correct": 0
  }
]
```

`correct` = indice della risposta giusta (0 = A, 1 = B, 2 = C, 3 = D)
