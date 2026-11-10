# ch-labs-skills

Le skill della [Prompt Library di CH Labs](https://www.cryptohelvetia.com/ch-labs/prompt-library) e bazinga, un plugin vocale per Claude Code. Ogni plugin vive nel suo repo e questo marketplace li raccoglie, così bastano due righe per installarli tutti.

## Installare

```
/plugin marketplace add MicheDada21/ch-labs-skills
/plugin install tutte-le-skill@ch-labs-skills
```

`tutte-le-skill` porta con sé le 21 skill. Per una skill sola usa il suo nome, per esempio `/plugin install riassumi-preservando-linguaggio@ch-labs-skills`. Da shell i comandi sono `claude plugin marketplace add MicheDada21/ch-labs-skills` e `claude plugin install tutte-le-skill@ch-labs-skills`. Nell'app desktop premi + accanto al campo del prompt, apri Plugins, aggiungi il marketplace `MicheDada21/ch-labs-skills` con Add marketplace e poi il plugin con Add plugin.

## Plugin

| Repo | Cosa fa |
|---|---|
| [007-founders-nations](https://github.com/MicheDada21/007-founders-nations) | Trova il Paese dei fondatori di aziende e strumenti, per nazionalità, nascita o crescita, e sostiene ogni dato con una citazione letterale in un registro JSONL. |
| [007-headquarters-cities](https://github.com/MicheDada21/007-headquarters-cities) | Elenca fino a tre sedi principali di un'azienda nella forma Città (Paese), in ordine di importanza, ognuna con una citazione letterale dalle sue pagine. |
| [3d-decoration-asset](https://github.com/MicheDada21/3d-decoration-asset) | Crea mascotte che seguono il cursore, oggetti a 360° guidati dallo scroll, clip in loop e modelli GLB, con la generazione in cloud su Runware solo dopo l'approvazione del costo. |
| [decorazione-futurista-editoriale](https://github.com/MicheDada21/decorazione-futurista-editoriale) | Strania la forma di una pagina verso un futurismo essenziale, su un livello da 0 a 100 ricavato dai manifesti di Marinetti, e lascia leggibile ogni parola. |
| [optimize-crawler-access](https://github.com/MicheDada21/optimize-crawler-access) | Trova cosa impedisce a ChatGPT, Claude e Perplexity di leggere un sito, da robots.txt ai blocchi di Vercel e Cloudflare, e lo corregge. |
| [transcribe-audio-video](https://github.com/MicheDada21/transcribe-audio-video) | Trascrive il parlato di un file audio o video locale con Voxtral 3 tramite OpenRouter, con timestamp a richiesta. |
| [benchmark-letterario-llm](https://github.com/MicheDada21/benchmark-letterario-llm) | Misura le risposte di un LLM con e senza web su cultura letteraria, bibliografie, giudizio critico e riconoscimento degli errori. |
| [design-system-refactor](https://github.com/MicheDada21/design-system-refactor) | Sposta gli stili scritti a mano nei token e l'interfaccia ripetuta in componenti condivisi, con la prova che ogni pagina resta identica al pixel. |
| [umanizza-stile-linguistico](https://github.com/MicheDada21/umanizza-stile-linguistico) | Ripulisce tono, lessico e punteggiatura di un testo in prosa e propone un secondo passaggio editoriale mirato. |
| [gerarchia-tipografica-impaginazione](https://github.com/MicheDada21/gerarchia-tipografica-impaginazione) | Riorganizza la gerarchia visiva di una pagina già scritta secondo il significato dei testi. Parte solo quando la chiami per nome. |
| [iai](https://github.com/MicheDada21/iai) | Contesto e firma di IAI, Identità Agente Impersonale, con i profili di Tiziano e Michelangelo Boccaccini. |
| [coordinate-metadata-saio](https://github.com/MicheDada21/coordinate-metadata-saio) | Controlla pagina e sito per i motori di ricerca e di risposta AI, applica la bozza dei metadati e implementa i suggerimenti scelti. Parte solo quando la chiami per nome. |
| [metadata-copy-dadastickers](https://github.com/MicheDada21/metadata-copy-dadastickers) | Dà a ogni sottopagina titolo, descrizione e anteprima di condivisione propri, unendo i fatti della pagina a un enunciato Dadastickers citato alla lettera. Parte solo quando la chiami per nome. |
| [audit-skill-pocock](https://github.com/MicheDada21/audit-skill-pocock) | Rivede una skill regola per regola con le indicazioni di Matt Pocock sulla scrittura per agenti e le aggiunte di Theo, poi propone un piano di riscrittura. Parte solo quando la chiami per nome. |
| [descrivi-idea-prodotto](https://github.com/MicheDada21/descrivi-idea-prodotto) | Ordina in dieci blocchi la pagina che presenta un'idea di business a chi non ha contesto, dalla tensione iniziale alle domande aperte. |
| [riassumi-preservando-linguaggio](https://github.com/MicheDada21/riassumi-preservando-linguaggio) | Accorcia un testo tagliando incisi e digressioni e conserva le parole dell'autore, il loro ordine e il filo del discorso. |
| [addestra-comportamento-chatbot](https://github.com/MicheDada21/addestra-comportamento-chatbot) | Indaga l'intenzione disattesa in una chat, traduce i fallimenti in segnali da verificare nel codice e riscrive alla radice perché non si ripetano. |
| [check-stack-updates](https://github.com/MicheDada21/check-stack-updates) | Aggiorna dipendenze e strumenti dopo un controllo di compatibilità e l'approvazione dell'utente. |
| [scegli-variabili-ambiente](https://github.com/MicheDada21/scegli-variabili-ambiente) | Decide se una variabile d'ambiente va su Vercel, su Convex o su entrambi in base a dove il codice la legge. |
| [evaluate-voice-quality](https://github.com/MicheDada21/evaluate-voice-quality) | Controlla una traccia vocale generata dall'IA rispetto al copione e dà a ogni take di una voce clonata un punteggio da 0 a 100 di fedeltà alla voce reale. |
| [customize-metadata-widget](https://github.com/MicheDada21/customize-metadata-widget) | Apre un widget con le anteprime di Google, browser, WhatsApp e iMessage per scegliere titolo, descrizione e immagine di una pagina. Parte solo quando la chiami per nome. |
| [bazinga](https://github.com/MicheDada21/bazinga) | Voce ElevenLabs per Claude Code e Codex su macOS, con consumi per risposta e sessione. |

Ogni repo spiega i propri requisiti. Le pagine della libreria su cryptohelvetia.com restano il riferimento per il testo di ogni skill.

## Licenza

MIT, testo completo in [LICENSE](LICENSE). Ogni repo porta la propria licenza.
