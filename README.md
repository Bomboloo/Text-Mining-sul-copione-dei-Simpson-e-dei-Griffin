# Text Mining sul copione dei Simpson e dei Griffin

Progetto universitario di analisi comparativa dei testi delle serie animate **I Simpson** e **I Griffin**, attraverso tecniche di text mining, topic modeling e sentiment analysis.

L'obiettivo è esplorare somiglianze e differenze nei contenuti testuali e concettuali delle due sceneggiature, a partire dagli episodi raccolti tramite web scraping e opportunamente ripuliti e preprocessati.

---

## Contenuto del report

Il file [`progetto_completo.html`](progetto_completo.html) contiene il report principale, suddiviso in:

1. **Text Mining** — analisi delle frequenze e delle associazioni tra parole
2. **LDA** (Latent Dirichlet Allocation) — topic modeling
3. **STM** (Structured Topic Modelling)
4. **Sentiment Analysis**
5. **Correlazioni con i rating IMDb**

Il file [`Appendice.html`](Appendice.html) raccoglie il codice più meccanico, non direttamente parte delle analisi:

- **Appendice A** — web scraping dei testi (Springfield! Springfield!) e dei dati IMDb
- **Appendice B** — tentativo di pulizia dei dati tramite API di un Large Language Model
- **Appendice C** — pre-processing dei dati e creazione dei dataset puliti (con/senza lemmatizzazione, con/senza nomi dei personaggi)
- **Appendice D** — definizione delle funzioni di supporto utilizzate nel report

> I dataset con i testi degli episodi e i file di lavoro R (`.RData`) non sono inclusi nel repository: i testi sono materiale scrapato non ridistribuibile, mentre i file di lavoro sono cache locali non necessarie alla consultazione del report.

---

## Strumenti utilizzati

Analisi sviluppata in **R** (R Markdown), con l'utilizzo di:

- `quanteda`, `tm`, `tidytext` — text mining e pre-processing
- `topicmodels`, `stm`, `lda`, `LDAvis` — topic modeling
- `textstem`, `SnowballC` — lemmatizzazione e stemming
- `ggplot2`, `ggwordcloud`, `patchwork`, `cowplot` — visualizzazione
- API di modelli LLM (DeepInfra) per un tentativo di pulizia automatica dei testi

---

## Autori

Progetto realizzato in gruppo da: Caicchiolo Giorgia, Carollo Daniele, Paganelli Gabriele, Pati Riccardo, Tossici Giorgia.
