Il file progetto_completo.html contiene il report del progetto. 
Il report è suddiviso in quest'ordine:
1. Text Mining: analisi delle frequenze e delle associazioni.
2. LDA
3. STM(Structured Topic Modelling)
4. Sentiment Analisys
5. Correlazioni con rating IMDb
E' presente nella cartella anche il file in formato R markdown.

Appendice.Rmd contiene le parti di codice più meccaniche che non fanno parte delle analisi, con i relativi commenti.
In ordine contiene: Appendice A: scraping testi e scraping dati IMDb.
Appendice B: tentativo di pulizia dei dati tramite API di LLM
Appendice C: Pre-processing dei dati con la creazione dei dataset puliti: simpson e griffin(testi puliti ma prima della lemmatizzazione) , simpson_clean e griffin_clean(testi puliti con lemmatizzazione e senza i nomi dei personaggi) , simpson_clean_2 e griffin_clean_2 (testi puliti con lemmatizzazione e con nomi dei personaggi inclusi).
Appendice D: Definizione di funzioni che vengono utilizzate nel report.