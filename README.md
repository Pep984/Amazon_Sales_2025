Titolo: Amazon Sales 2025 - Analisi
Analisi dettagliata delle vendite Amazon attraverso un modello a stella su Power BI:

1. Introduzione:
Questo progetto ha l’obiettivo di analizzare i dati di vendita di Amazon nel 2025 utilizzando Power BI.
Attraverso un modello a stella, ho esplorato metriche chiave sugli ordini, sui clienti e sulle vendite totali, offrendo visualizzazioni interattive che facilitano la comprensione dei dati.

3. Dataset Utilizzato:
Fonte: Sito internet Kaggle (a scopo dimostrativo)
Contenuto: Include dati su ordini, clienti, vendite, modalità di pagamento e categorie di prodotti
Periodo di riferimento: Febbraio 2025/Marzo 2025

3. Struttura del Modello:
Il progetto è suddiviso in tre fogli principali, ognuno con specifiche visualizzazioni:

  Schema a Stella:
  La base del modello si compone di: 
  Tabella dei Fatti:  (FactSales_Amazon) contenente metriche numeriche fondamentali (Price, Quantity, Total Sales ecc.).

  Tabelle di Dimensione: DimCategory, DimPayment,DimProduct, DimData, DimCustomer, DimStatus e una BridgeTable.

  Misure Utilizzate:
  Il report include in totale 18 misure basate in base all'esigenza di calcolo su funzioni DAX come AVG, SUM, CALCULATE, COUNT, DIVIDE, per ottenere statistiche dinamiche.

4. Organizzazione dei Fogli
Panoramica Generale (Foglio 1), Clienti (Foglio 2), Ordini (Foglio 3)

5. Conclusioni:
L’analisi dei dati evidenzia alcune tendenze chiave:
-Aumento delle vendite in determinati mesi, con picchi significativi.
-Clienti ricorrenti che generano gran parte del fatturato.
-Prodotti più venduti e categorie con il miglior rendimento.
