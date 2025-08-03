# 📊 ML su Emissioni Lombardia

Lavoro creato in collaborazione con sofcaroli2 e Anapaxx come progetto per un esame universitario.

Questo progetto sfrutta tecniche di Machine Learning per analizzare i dati sulle emissioni dei veicoli in Lombardia nel 2014, con l'obiettivo di comprendere la distribuzione degli inquinanti, individuare correlazioni tra variabili e prevedere l'andamento del PM10.

## 📁 Dataset

Il dataset originale è contenuto nel file [Emissioni.xls](https://github.com/GbriRci/ML_on_Emissioni_Lombardia/blob/main/Emissioni.xls) e contiene informazioni relative a:
- Tipo di carburante
- Normativa ambientale
- Consumo specifico
- Emissioni di vari inquinanti (SO₂, NOₓ, CO₂, PM10, ecc.)


## 🧪 Tecniche utilizzate

1. **Data Cleaning**: rimozione di righe non valide, conversione di tipi di dato, cambio delle unità di misura.
2. **Data Visualization**: istogrammi, boxplot, heatmap.
3. **Unsupervised Machine Learning**: ricerca di gruppi nascosti nei dati tramite *Clustering* (K-Means e Agglomerative Clustering).
4. **Supervised Machine Learning**: ricerca di proporzionalità nei dati con *Regressioni* (Regressione multipla e KNN Regressor).
5. **Deep Learning**: addestrameto di *Reti Neurali* (Keras) con *Splitting* dei fataset in training e test.
6. **AI Generativa**: utilizzo di modelli come BLIP e GPT-2 per generazione automatica di descrizioni.

## 📈 Risultati principali

Abbiamo riscontrato e analizzato relazioni tra i **pesi dei veicoli e il consumo di carburante**, forti correlazioni tra alcuni **inquinanti e particolati** come PM10, PM2.5 e PTS, ed evidenziato l'esistenza di **gruppi coerenti** in base al tipo di carburante.

La rete neurale addestrata con **3 hidden layers** ha ottenuto buoni risultati nella previsione del PM10 con valori di **R² maggiori di 0.7**.

Abbiamo testato anche più modelli di **AI generativa** in combinazione tra loro alla ricerca del più performante nella descrizione degli output.

## 👥 Collaboratori

Questo progetto è stato sviluppato in collaborazione con:
* [sofcaroli2](https://github.com/sofcaroli2)
* [Anapaxx](https://github.com/Anapaxx)

## Scarica la relazione completa: 
- Relazione: [ML_su_Emissioni_Lombardia.ipynb](https://github.com/GbriRci/ML_on_Emissioni_Lombardia/blob/main/ML_su_Emissioni_Lombardia.ipynb)
- Dataset: [Emissioni.xls](https://github.com/GbriRci/ML_on_Emissioni_Lombardia/blob/main/Emissioni.xls)
