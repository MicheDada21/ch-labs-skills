# ch-labs-skills

Le skill della [Prompt Library di CH Labs](https://www.cryptohelvetia.com/ch-labs/prompt-library) e bazinga, un plugin vocale per Claude Code. Ogni plugin vive nel suo repo e questo marketplace li raccoglie, così bastano due righe per installarli tutti.

## Installare

```
/plugin marketplace add MicheDada21/ch-labs-skills
/plugin install tutte-le-skill@ch-labs-skills
```

`tutte-le-skill` porta con sé le 13 skill. Per una skill sola usa il suo nome, per esempio `/plugin install riassunto-per-sottrazione@ch-labs-skills`. Da shell i comandi sono `claude plugin marketplace add MicheDada21/ch-labs-skills` e `claude plugin install tutte-le-skill@ch-labs-skills`. Nell'app desktop premi + accanto al campo del prompt, apri Plugins, aggiungi il marketplace `MicheDada21/ch-labs-skills` con Add marketplace e poi il plugin con Add plugin.

## Plugin

| Repo | Cosa fa |
|---|---|
| [007-founders-nations](https://github.com/MicheDada21/007-founders-nations) | Trova il Paese dei fondatori di aziende e strumenti, per nazionalità, nascita o crescita, e sostiene ogni dato con una citazione letterale in un registro JSONL. |
| [007-headquarters-cities](https://github.com/MicheDada21/007-headquarters-cities) | Elenca fino a tre sedi principali di un'azienda nella forma Città (Paese), in ordine di importanza, ognuna con una citazione letterale dalle sue pagine. |
| [3d-decoration-asset](https://github.com/MicheDada21/3d-decoration-asset) | Crea mascotte che seguono il cursore, oggetti a 360° guidati dallo scroll, clip in loop e modelli GLB, con la generazione in cloud su Runware solo dopo l'approvazione del costo. |
| [ai-crawler-access](https://github.com/MicheDada21/ai-crawler-access) | Trova cosa impedisce a ChatGPT, Claude e Perplexity di leggere un sito, da robots.txt ai blocchi di Vercel e Cloudflare, e lo corregge. |
| [audio-transcription](https://github.com/MicheDada21/audio-transcription) | Trascrive il parlato di un file audio o video locale con Voxtral 3 tramite OpenRouter, con timestamp a richiesta. |
| [design-system-refactor](https://github.com/MicheDada21/design-system-refactor) | Sposta gli stili scritti a mano nei token e l'interfaccia ripetuta in componenti condivisi, con la prova che ogni pagina resta identica al pixel. |
| [filtra-stile-linguistico](https://github.com/MicheDada21/filtra-stile-linguistico) | Ripulisce tono, lessico e punteggiatura di un testo in prosa e propone un secondo passaggio editoriale mirato. |
| [gerarchia-editoriale-impaginazione](https://github.com/MicheDada21/gerarchia-editoriale-impaginazione) | Riorganizza la gerarchia visiva di una pagina già scritta secondo il significato dei testi. Parte solo quando la chiami per nome. |
| [iai](https://github.com/MicheDada21/iai) | Contesto e firma di IAI, Identità Agente Impersonale, con i profili di Tiziano e Michelangelo Boccaccini. |
| [metadati-dadastickers](https://github.com/MicheDada21/metadati-dadastickers) | Dà a ogni sottopagina titolo, descrizione e anteprima di condivisione propri, unendo i fatti della pagina a un enunciato Dadastickers citato alla lettera. Parte solo quando la chiami per nome. |
| [riassunto-per-sottrazione](https://github.com/MicheDada21/riassunto-per-sottrazione) | Accorcia un testo tagliando incisi e digressioni e conserva le parole dell'autore, il loro ordine e il filo del discorso. |
| [stack-update](https://github.com/MicheDada21/stack-update) | Aggiorna dipendenze e strumenti dopo un controllo di compatibilità e l'approvazione dell'utente. |
| [voice-check](https://github.com/MicheDada21/voice-check) | Controlla una traccia vocale generata dall'IA rispetto al copione e dà a ogni take di una voce clonata un punteggio da 0 a 100 di fedeltà alla voce reale. |
| [bazinga](https://github.com/MicheDada21/bazinga) | Modalità vocale per Claude Code. «bazinga on» legge ad alta voce le risposte con la tua voce ElevenLabs, «bazinga off» la spegne. |

Ogni repo spiega i propri requisiti. Le pagine della libreria su cryptohelvetia.com restano il riferimento per il testo di ogni skill.

## Licenza

MIT, testo completo in [LICENSE](LICENSE). Ogni repo porta la propria licenza.
