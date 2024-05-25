---
title: Allegato 1 - Project Overview Statement
date: 2024-05-24
layout: post
---

## Obiettivo

L'obiettivo del progetto è l'implementazione di un sistema a micro-servizi che permetta agli utenti di formare gruppi di persone fidate, in cui condividere in tempo reale la posizione e uno stato.

## Opportunità / Problemi

_`TODO`: quelli qui sotto mi sembrano più rischi che opportunità / problemi. Qui per opportunità e problemi sono intesi quelli di dominio e non tecnologici._

I problemi relativi all'applicativo sono principalmente connessi all'inesperienza del team in materia, sia in termini di tecnologie adottate, sia in fase di design dell'applicativo.
Le opportunità sono relative sia al funzionamento del sistema, sia ad un aspetto di modularità, che se eseguito correttamente a livello di design, getta le basi di proprietà di estensibilità, replicazione di servizi e scaling e fault-tolerance.

## Objectives

L'applicativo è stato suddiviso in micro-servizi, descritti nella sezione sottostante.

### User (Luca R.)

Il servizio per la gestione utente deve occuparsi di tutti gli aspetti relativi all'autenticazione, sia per quanto riguarda l'iscrizione, sia per il log-in, a cui va aggiunta la creazione e il mantenimento dei gruppi e lo stato in tempo reale.

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

### Location (Luca T.)

### Chat (Gio)

## Success Criteria

## Rischi
