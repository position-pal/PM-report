---
title: Allegato 1 - Project Overview Statement
date: 2024-05-24
layout: post
---

## Opportunità

Da un'indagine di mercato è emersa la presenza di applicativi già esistenti per questo ambito.
Tuttavia, dall'analisi di questi ultimi è affiorata la possibilità di fornire una versione _open source_, che al contempo permetta al gruppo di impratichirsi con tecnologie e metodologie avanzate, cercando di migliorare l'esperienza utente.

## Scopo del progetto

**Lo scopo del progetto è l'implementazione di un sistema <!-- a micro-servizi --> di tracciamento e condivisione, in tempo reale, della posizione e di un'informazione di stato tra gruppi di utenti fidati.**

<!-- opportunita / problemi 

_`TODO`: quelli qui sotto mi sembrano più rischi che opportunità / problemi. Qui per opportunità e problemi sono intesi quelli che spingono alla realizzazione di questo progetto e non problemi tecnologici._

I problemi relativi all'applicativo sono totalmente connessi all'inesperienza del team in materia, sia in termini di tecnologie adottate, sia in fase di design dell'applicativo.
Le opportunità sono relative sia al funzionamento del sistema, sia ad un aspetto di modularità, che se eseguito correttamente a livello di design, getta le basi di proprietà di estensibilità, replicazione di servizi e scaling e fault-tolerance.

-->

## Obiettivi

Qui di seguito vengono descritti i principali obiettivi del progetto:

1. Organizzazione, configurazione e inizializzazione dei workspace con un adeguato _build tool_, di un'infrastruttura con predisposizione a una _pipeline_ automatizzata di _continuous integration & deployment_.

2. Progettazione e implementazione di un servizio per la gestione utente che deve occuparsi di tutti gli aspetti relativi all'autenticazione, sia per quanto riguarda l'iscrizione, sia per il log-in, a cui va aggiunta la creazione e il mantenimento dei gruppi e lo stato in tempo reale.

3. Progettazione e implementazione di un servizio di localizzazione che permetta di geolocalizzare un utente in tempo reale, individuare coordinate a partire da indirizzi / luoghi ed esporre un'API per impostare notifiche quando l'utente arriva in prossimità di una certa posizione.

4. Progettazione e implementazione di un servizio di chat che permetta di conversare in tempo reale con un singolo o un gruppo ristretto di utenti con la quale si vuole condividere la propria posizione e stato. Questo permetterà all'utente di avere una comunicazione più diretta e immediata con i membri del gruppo.

## _Conditions of Satisfactions_

- Il sistema deve essere completato entro Luglio 2024;
- Utilizzo di architettura a micro-servizi e di _tool_ di orchestrazione come Kubernetes;
- Utilizzo di approccio _Domain_ e _Test Driven_ (DDD e TDD);
- Organizzazione di focus group per raccolta di feedback sulla user experience.

## Success Criteria

- Il downtime del sistema deve essere minore dell'1% rispetto al tempo di attività;
- I costi del progetto per servizi esterni e tecnologie non devono eccedere 100€;
- Tutti i requisiti funzionali devono essere soddisfatti e verificati mediante test automatici;
- La copertura del codice del dominio deve essere > 90%.

## Rischi

Un elenco dei principali rischi che ci si assumerebbero sono elencati qui di seguito:

- il team non ha esperienza nella progettazione e sviluppo di applicazioni con architettura a micro-servizi;
- il team ha limitata esperienza riguardo l'utilizzo di tecnologie e strumenti per il _continuous depoloyment_ in ambienti di produzione;
- il sistema finale potrebbe avere meno _appeal_ rispetto a quello dei _competitor_ nel mercato.

L'analisi e la gestione del rischio è trattata [Allegato 3 - Analisi dei rischi](/PM-report/attachments/3-risk-analysis/)

## Milestone

Si prevede di rilasciare i servizi in questo ordine:

1. predisposizione infrastruttura di continuous integration & deployment;
2. sotto-sistema autenticazione e gestione gruppi;
3. sotto-sistema di localizzazione;
4. sotto-sistema di notifiche;
5. sotto-sistema di chat.
6. predisposizione di un sistema di diagnosi e monitoraggio.
