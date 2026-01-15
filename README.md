# GEOMETRIC MODEL MERGING PROJECT

**Studente:** Francesca Maggiore
**Matricola:** 2154286
**Corso:** Machine Learning

## Descrizione del Progetto
Questa repository contiene il materiale ufficiale per il progetto finale del corso di Machine Learning.
Il lavoro analizza le proprietà geometriche dello spazio dei pesi delle reti neurali, confrontando l'efficacia della **Media Euclidea** (lineare) con il **Karcher Mean** (geometrico/sferico) per la fusione di più modelli (Model Merging).

## Contenuto della Repository
* **`Report_Francesca_Maggiore.pdf`**: La relazione completa che descrive la metodologia, l'analisi teorica e i risultati sperimentali ottenuti.
* **`codice_progetto_ml_francesca_maggiore_2154286.ipynb`**: Il Notebook Jupyter contenente l'intera pipeline di implementazione (training, allineamento, merging e valutazione).

## Istruzioni per l'Esecuzione
1. Aprire il file `codice_progetto_ml_francesca_maggiore_2154286.ipynb` (consigliato Google Colab o Jupyter Lab).
2. Assicurarsi che le librerie necessarie siano installate (`torch`, `torchvision`, `numpy`, `matplotlib`).
3. Eseguire tutte le celle sequenzialmente. Il codice:
   - Addestrerà i modelli necessari (se i checkpoint non sono presenti).
   - Eseguirà l'allineamento e la fusione.
   - Produrrà le tabelle e i grafici dei risultati.
