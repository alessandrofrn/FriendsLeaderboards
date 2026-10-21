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

## Dove finiscono i dati
- Aperta da **Claude** (link dell'artifact): i dati sono condivisi online, chi ha accesso al link vede gli stessi voti.
- Ospitata come **sito tuo**: i dati restano nel browser del telefono (localStorage). Se cancelli i dati del browser li perdi.

## Installarla sul telefono come app
1. Metti online la cartella. Il modo più semplice e gratuito: trascinala su <https://app.netlify.com/drop>, oppure caricala su un repository GitHub e attiva GitHub Pages.
2. Apri l'indirizzo con Chrome su Android.
3. Menu ⋮ → **Installa app** (o "Aggiungi a schermata Home").

Per provarla sul PC: `python3 -m http.server 8000` dentro la cartella, poi apri <http://localhost:8000>.
