---
title: "Studio Covid-19"
date: 2021-06-08T12:14:34+06:00
image: "images/portfolio/item2.JPG"
categories: ["Statistics"]
description: "Analisi andamento Terapie Intensive"
draft: false
project_info:
- name: "Client"
  icon: "fas fa-user"
  content: "Università degli studi di Bergamo"
- name: "Project Link"
  icon: "fas fa-link"
  content: "https://drive.google.com/drive/folders/1tAL87Ijp7wBSx_3n5YN1h2A6qEm9vFqp?usp=sharing"
---
Questo lavoro è stato svolto in gruppo durante il corso di Statistica 2 presso l'Università di Bergamo.
Lo studio si divide in 2 parti, la prima si concentra sullo studio del dataset, la sua correzione, e la scelta del
migliore modello per descrivere la variabile "ricoverati in terapia intensiva".
Nella seconda parte il focus è stato invece la previsione temporale utilizzando il modello trovato precedentemente.


#### Dettagli

Il dataset è relativo all'intera pandemia Covid-19 dal 24/02/2020 al 21/03/2021 con frequenza giornaliera.
La sua correzione è dovuto all'andamento "falsato dei positivi" nel primo periodo causa pochi tamponi fatti.
Il modello scelto per la descrizione dell'andamento dei ricoverati in terapia intensiva contiene (ricoverati con sintomi,
totale positivi, deceduti giornalieri).
Questo modello è poi stato scelto per effettuare previsioni tramite modello regArima, il quale si è rivelato decisamente
migliore del modello semplice Arima (che utilizza solamente i dati delle terapie intensive). 


#### Requisiti del progetto

I dati forniti dal Ministero della Salute sono stati elaborati tramite il software Matlab. Quest'ultimo è stato poi anche utilizzato (in aggiunta 
a sue estensioni) per effettuare lo studio.
Prerequisito fondamentale è stata la buona conoscenza di statistica e di modelli stocastici.