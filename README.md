# Traduzione Italiana – Day of the Shell

---

## ☕ Supporta il progetto

Questa è la traduzione **non ufficiale in italiano** di *Day of the Shell*.  
Se ti piace questo progetto, puoi offrirmi un caffè:

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-%E2%98%95-yellow?style=for-the-badge)](https://www.buymeacoffee.com/lele344)

---

Per installarla basta copiare alcuni file nella cartella principale del gioco.

## 📂 Dove trovare la cartella del gioco
Se hai il gioco su **Steam**:
1. Apri la Libreria di Steam
2. Clicca con il tasto destro su **Day of the Shell**
3. Vai su **Gestisci → Sfoglia file locali**

Si aprirà la cartella principale del gioco (root).

---

## ⚙️ Installazione

Nella **root del gioco** (la stessa cartella dove si trova l’`exe` del gioco) devi copiare i seguenti file e cartelle:

```text
📂 Day of the Shell
├── DayOfTheShell.exe
├── winhttp.dll
├── doorstop_config.ini
├── .doorstop_version
└── 📂 ItLocStandalone
    ├── 0Harmony.dll
    ├── ItLocStandalone.dll
    └── multilingua.tsv



- `winhttp.dll` → libreria necessaria per caricare la traduzione  
- `doorstop_config.ini` e `.doorstop_version` → configurazione del loader  
- **Cartella `ItLocStandalone`** → contiene i file della traduzione  
  - `0Harmony.dll` → libreria richiesta dal plugin  
  - `ItLocStandalone.dll` → plugin della traduzione italiana  
  - `multilingua.tsv` → file con i testi tradotti  

---

## ▶️ Avvio
1. Avvia il gioco normalmente da Steam.  
2. Se l’installazione è corretta, i testi compariranno in **italiano**.  

---

## ❓ Problemi comuni
- **Il gioco resta in inglese** → controlla che `winhttp.dll` e `doorstop_config.ini` siano nella stessa cartella dell’`exe`.  
- **Crash all’avvio** → assicurati di non avere altre versioni di `winhttp.dll` o mod in conflitto.  
- **Vuoi rimuovere la traduzione?** → elimina `winhttp.dll`, `.doorstop_version`, `doorstop_config.ini` e la cartella `ItLocStandalone`.

---

## 📜 Note
Questa traduzione è **fan-made**, non ufficiale e non affiliata agli sviluppatori.  
Usare a proprio rischio.
