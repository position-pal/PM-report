---
title: Allegato 1 - Project Overview Statement
date: 2024-05-24
layout: post
---

## Opportunità

`TODO`

## Scopo del progetto

**Lo scopo del progetto è l'implementazione di un sistema <!-- a micro-servizi --> di tracciamento e condivisione, in tempo reale, della posizione e di un'informazione di stato tra gruppi di utenti fidati.**

<!-- opportunita / problemi 

_`TODO`: quelli qui sotto mi sembrano più rischi che opportunità / problemi. Qui per opportunità e problemi sono intesi quelli che spingono alla realizzazione di questo progetto e non problemi tecnologici._

I problemi relativi all'applicativo sono palmente connessi all'inesperienza del team in materia, sia in termini di tecnologie adottate, sia in fase di design dell'applicativo.
Le opportunità sono relative sia al funzionamento del sistema, sia ad un aspetto di modularità, che se eseguito correttamente a livello di design, getta le basi di proprietà di estensibilità, replicazione di servizi e scaling e fault-tolerance.

-->

## Obiettivi

Qui di seguito vengono descritti i principali obiettivi del progetto:

1. Organizzazione, configurazione e inizializzazione dei workspace con un adeguato _build tool_, di un'infrastruttura con predisposizione a una _pipeline_ automatizzata di _continuous integration & deployment_.

2. Progettazione e implementazione di un servizio per la gestione utente che deve occuparsi di tutti gli aspetti relativi all'autenticazione, sia per quanto riguarda l'iscrizione, sia per il log-in, a cui va aggiunta la creazione e il mantenimento dei gruppi e lo stato in tempo reale.

<!--  Questi sono piu requisiti che obiettivi 

#### Autenticazione

##### Iscrizione

Il servizio deve supportare l'iscrizione di nuovi utenti

###### Mail

Il servizio deve inviare una mail con i dati relativi all'iscrizione

##### Log-in

Il servizio deve supportare il log-in di utenti già iscritti

###### Token & sessione

Il servizio deve creare e gestire token di autenticazione e la sessione a questo correlata

##### Aggiornamento utente

Il servizio deve permettere all'utente di modificare le proprie informazioni e password

#### Gestione gruppi

##### Creazione gruppo

Il servizio deve supportare la creazione di un gruppo e la stesura delle policy

##### Adesione gruppo

Il servizio deve supportare la possibilità di invitare utenti nei gruppi, oltre che notificare i facenti parte del gruppo ad ogni nuova adesione

##### Abbandono gruppo

Il servizio deve permettere all'utente di abbandonare un gruppo in cui ha precedentemente aderito

#### Gestione stato

Il servizio deve gestire tutti gli aspetti relativi allo stato, compreso l'aggiornamento con annessa notifica a tutti i membri di tutti i gruppi di cui fa parte; deve essere possibile resettare lo stato dopo un'emergenza

#### Documentazione

Il servizio deve essere corredato da una chiara documentazione, per permettere all'utente di utilizzarlo correttamente ed al personale tecnico di intervenire prontamente con manutenzioni all'evenienza

-->

1. Progettazione e implementazione di un servizio di localizzazione che permetta di geolocalizzare un utente in tempo reale, individuare coordinate a partire da indirizzi / luoghi ed esporre un'API per impostare notifiche quando l'utente arriva in prossimità di una certa posizione.

2. Progettazione e implementazione di un servizio di chat che permetta di conversare in tempo reale con un singolo o un gruppo ristretto di utenti con la quale si vuole condividere la propria posizione e stato. Questo permetterà all'utente di avere una comunicazione più diretta e immediata con i membri del gruppo.


## _Conditions of Satisfactions_

`TODO`

## Success Criteria

`TODO`

## Rischi

Un elenco dei principali rischi che ci si assumerebbero sono elencati qui di seguito:

- il team non ha esperienza nella progettazione e sviluppo di applicazioni con architettura a micro-servizi;
- il team ha limitata esperienza riguardo l'utilizzo di tecnologie e strumenti per il _continuous depoloyment_ in ambienti di produzione.

`TODO`: gestione del rischio
