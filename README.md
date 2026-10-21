# FriendsLeaderboards

Web app installabile (PWA) per raccogliere i voti di più persone su diversi prodotti e vedere chi vince.

## Come funziona
- **Gestisci**: aggiungi le persone che votano e i prodotti da votare.
- **Vota**: scegli chi sta votando e dai a ogni prodotto un voto da 1 a 10 (tocca di nuovo per toglierlo).
- **Classifica**: prodotti ordinati per media dei voti (a parità, vince chi ha più voti), con podio e tabellone completo.

## File
| File | Cosa fa |
|---|---|
| `index.html` | L'app completa, da mettere online |
| `app.html` | Stesso contenuto, senza intestazione HTML (versione pubblicata su Claude) |
| `manifest.webmanifest` | Nome, icona e colori quando la installi sul telefono |
| `sw.js` | Service worker: fa funzionare l'app anche offline |
| `icon-*.png` | Icone dell'app |

## Installarla sul telefono come app
1. Vai al link https://alessandrofrn.github.io/FriendsLeaderboards/
2. salva la pagina sulla home
