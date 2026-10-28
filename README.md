# 🌌 Orbita Nera Edizioni
## Casa Editrice Digitale Speculativa

“Dove il possibile si incrina.”

---

# 📖 Visione

Orbita Nera è un laboratorio editoriale AI-native dedicato a:

- Hard Sci-Fi filosofica
- Fantasy sistemico e politico
- Narrativa Weird e psicologica

Obiettivo: creare opere ad alta densità concettuale, con forte identità autoriale e coerenza strutturale.

---

# 🧠 Architettura degli Agenti

## Struttura

01 - Direzione Editoriale  
02 - Editor Strutturale  
03 - Line Editor Stilistico  
04 - Research & Scientific Consultant  
05 - Psicologo Narrativo  
06 - Beta Reader Simulato  
07 - Stratega Editoriale & Marketing  

Cartella `shared/`:
- schema-output.md
- policy-voice.md
- genre-switch.md

---

# 🔁 Workflow Standard

## Fase 1 — Ideazione
Agente: Direzione Editoriale

Input:
- Concept / sinossi
- Obiettivo (racconto, romanzo, concorso)
- Genere (se noto)

Output:
- Collana
- Posizionamento
- Roadmap

---

## Fase 2 — Architettura
Agente: Editor Strutturale

Input:
- Outline o prima bozza

Output:
- Beat sheet
- Problemi strutturali
- Interventi P0/P1/P2

---

## Fase 3 — Coerenza tecnica
Agente: Research Consultant

Input:
- Versione strutturata

Output:
- Red flags
- Glossario
- Conseguenze sistemiche

---

## Fase 4 — Profondità psicologica
Agente: Psicologo Narrativo

Input:
- Testo quasi completo

Output:
- Profilo personaggi
- Punti di rottura
- Scene suggerite

---

## Fase 5 — Prosa
Agente: Line Editor

Input:
- Testo revisionato

Output:
- Patch notes
- Interventi stilistici

---

## Fase 6 — Test lettura
Agente: Beta Reader

Input:
- Versione quasi finale

Output:
- Metriche 1–5
- Punti di calo attenzione
- Frasi memorabili

---

## Fase 7 — Packaging
Agente: Stratega Editoriale

Input:
- Versione finale

Output:
- Logline
- Sinossi
- Pitch
- Tag

---

# 🔀 Workflow Alternativi per Genere

## 🚀 SCI-FI
Ordine consigliato:
Direzione → Strutturale → Research → Psicologo → Line → Beta → Stratega

Priorità:
- Coerenza causale
- Limiti tecnologici
- Impatto sociale

---

## 🐉 FANTASY
Ordine consigliato:
Direzione → Strutturale → Research (worldbuilding) → Psicologo → Line → Beta → Stratega

Priorità:
- Sistema magico
- Economia/politica
- Mitologia coerente

---

## 🜏 WEIRD
Ordine consigliato:
Direzione → Psicologo → Strutturale → Research (coerenza interna, pass leggero) → Line → Beta → Stratega

Priorità:
- Ambiguità controllata
- Simboli ricorrenti
- Psicologia destabilizzante
- Regola segreta coerente (anche se mai esplicitata)

---

# 📊 Standard di Qualità Interno

Un testo può passare alla fase successiva solo se:

✓ La promessa narrativa è chiara  
✓ Il conflitto è leggibile  
✓ La voce è coerente  
✓ Non ci sono incoerenze sistemiche gravi  
✓ Il finale produce una trasformazione  

Ogni agente chiude il proprio output con la sezione **Gate di passaggio** (vedi `shared/schema-output.md`), che valuta questi cinque criteri.

---

# 📦 Naming Convention File Progetto

Esempio:

```
progetti/
├── _template/          # copia questa cartella per ogni nuovo progetto
└── 2026/
    └── titolo-progetto/
        ├── concept.md
        ├── outline_v1.md
        ├── draft_v1.md
        ├── draft_v2.md
        ├── draft_v3.md
        ├── draft_v4.md
        ├── final.md
        └── pitch.md
```

Versionamento consigliato:
- v1 = struttura (Fasi 1–2: Direzione, Strutturale)
- v2 = coerenza (Fasi 3–4: Research, Psicologo)
- v3 = stile (Fase 5: Line Editor)
- v4 = post-beta (Fase 6: correzioni dal test di lettura)
- final = submission ready (Fase 7: Packaging)

---

# 🧩 Modalità di Utilizzo degli Agenti

Quando usi un agente:

1. Incolla il contenuto del relativo `.md`
2. Incolla anche i tre file di `shared/` (`schema-output.md`, `policy-voice.md`, `genre-switch.md`): l'agente li richiama e senza di essi non ha schema, policy di voce e filtro di genere
3. Fornisci input chiaro
4. Specifica il GENERE (per gli ibridi: primario / secondario)
5. Specifica l’obiettivo editoriale

Esempio prompt sintetico:

"Agisci come Editor Strutturale di Orbita Nera.
Genere: Weird.
Obiettivo: racconto 4.000 parole per concorso.
Testo seguente: [incolla]"

---

# 🛑 Regole Fondamentali

- Gli agenti NON scrivono al posto dell’autore. Unica eccezione: i materiali di packaging (logline, pitch, sinossi, tag) prodotti dallo Stratega, che restano proposte da validare.
- Ogni intervento deve avere motivazione tecnica.
- Nessun agente può sovrascrivere completamente un testo senza richiesta esplicita.
- La voce autoriale è prioritaria.

---

# 🗂 Evoluzioni future

- Integrazione con sistema di tracking revisioni
- Dashboard qualità (metriche aggregate)
- Archivio simboli ricorrenti per universo condiviso
- Modulo “Serie / Saga”

---

# 🧭 Filosofia Editoriale

Orbita Nera non pubblica testi “piacevoli”.

Pubblica testi che:
- disturbano
- interrogano
- costruiscono sistemi
- lasciano residuo

Se un testo non genera frizione, non è pronto.

---

# 📌 Nota Finale

Questa struttura è modulare.
Può essere usata:
- per racconti singoli
- per raccolte tematiche
- per romanzi seriali
- per universi condivisi

---

Fine documento.
