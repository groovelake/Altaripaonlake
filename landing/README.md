# Altaripa The Club — Landing Page

## Struttura file
```
altaripa/
├── index.html          ← PAGINA PRINCIPALE (aggiorni questa ogni settimana)
├── lista.html          ← Pagina lista ingresso (aggiorni con form)
├── assets/
│   └── logo.png        ← Logo Altaripa (non toccare)
└── events/             ← Metti qui i flyer settimanali
    ├── giovedi.jpg
    ├── venerdi.jpg
    ├── sabato.jpg
    └── domenica.jpg
```

## Come aggiornare ogni settimana

1. **Carica i flyer** nella cartella `events/` (formato JPG o PNG, proporzione 4:5)
2. **In index.html** aggiorna per ogni card:
   - `src=""` → `src="events/nomefile.jpg"`
   - `.event-name` → nome della serata (es: GROOVE)
   - `.event-genre` → genere musicale (es: Trap · Hip-Hop)
   - `.day-badge` → giorno della serata
   - `href` del btn-lista → URL del form di quella serata
   - `href` del btn-tavolo → numero WhatsApp (già preimpostato)

## Numeri da sostituire
- WhatsApp: cerca `39XXXXXXXXXX` in index.html e lista.html e sostituisci con il tuo numero

## Deploy su GitHub Pages (gratuito)
1. Crea repo pubblico su github.com → nome: `altaripa`
2. Carica tutti i file
3. Settings → Pages → Branch: main → Save
4. Il sito sarà su: `https://tuousername.github.io/altaripa`
5. Genera QR da quel link → stampalo sul flyer A5

