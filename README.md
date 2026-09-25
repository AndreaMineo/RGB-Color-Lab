# 💡 RGB Color Lab - Codifica Digitale e Sintesi Additiva

![Uso Didattico](https://img.shields.io/badge/Uso-Didattico-indigo)
![Licenza](https://img.shields.io/badge/Licenza-MIT-green)
![Tech Stack](https://img.shields.io/badge/Tech-HTML5%20%7C%20TailwindCSS%20%7C%20JS-blue)

Un'applicazione web interattiva e visuale per l'insegnamento dell'Informatica e delle scienze STEM. Lo strumento guida gli studenti nell'esplorazione pratica della **sintesi additiva dei colori** e della **notazione esadecimale (#RRGGBB)** utilizzata per la codifica delle immagini digitali nei display.

---

## 🎯 Obiettivi Didattici

- **Sintesi Additiva della Luce**: Sperimentare il funzionamento dei fasci luminosi (Rosso, Verde, Blu) partendo dal nero assoluto fino al bianco puro.
- **Scomposizione HEX & RGB**: Comprendere la struttura del codice esadecimale `#RRGGBB` e la corrispondenza tra valori in base 16 e intensità numeriche decimali ($0 - 255$).
- **Ispezione Puntuale (Pixel Inspector)**: Analizzare in tempo reale i contributi di luce di ciascun canale RGB sulla tela attiva.
- **Lavoro Guidato e Mixer Rapido**: Confrontare le combinazioni cromatiche secondarie (Ciano, Magenta, Giallo) e terziarie attraverso controlli parametrici immediati.

---

## 🚀 Caratteristiche Principali

1. **🎨 Tab 1: Pittura Additiva Interattiva**:
   - **Pennelli Primari**: Seleziona i fasci di luce Rosso, Verde o Blu.
   - **Intensità Parametrica**: Imposta l'apporto luminoso per singola pennellata ($+25$, $+50$, $+100$, $+255$).
   - **Modalità di Composizione Lighter**: Calcolo nativo della somma dei fotoni su Canvas HTML5.
   - **Griglia dei Pixel & Mixer Rapido**: Visualizza la griglia di riferimento e testa al volo i valori decimale/HEX.
   - **Ispezione Pixel Puntato**: Passando il mouse o il tocco sulla tela, mostra la scomposizione RGB e le barre di livello in tempo reale.

2. **🔍 Tab 2: Scomposizione HEX & Canali RGB**:
   - **Parsing del Codice Esadecimale**: Notazione visiva suddivisa per byte (`#`, `RR`, `GG`, `BB`).
   - **Indicatori a Liquido/Splash**: Serbatoi grafici dinamici per la percentuale di luce erogata da ogni LED primario.
   - **Preset Cromatici Rapidi**: Selezione istantanea di tonalità chiave (Arancione, Ciano, Magenta, Rosa, Viola, ecc.).
   - **Spiegazione Didattica Automatica**: Generazione di un testo esplicativo basato sull'equilibrio di luce selezionato.

---


## 🛠️ Tecnologie Utilizzate

- **HTML5 & Canvas API**: Rendering grafico nativo ad alte prestazioni per la fusione additiva delle luci.
- **Tailwind CSS (CDN)**: Interfaccia scura (Dark Mode) moderna, reattiva e ottimizzata per schermi touch/desktop.
- **Google Fonts**: Tipografia tecnica integrata (*Inter* e *JetBrains Mono*).
- **JavaScript ES6**: Gestione degli eventi touch/mouse, calcoli di conversione esadecimale-decimale e aggiornamento dinamico della GUI.

---

## 📜 Licenza

Questo progetto è rilasciato sotto licenza **MIT**. È liberamente utilizzabile, modificabile e distribuibile per finalità didattiche, scolastiche e formative.
