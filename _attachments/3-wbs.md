---
title: Allegato 3 - Work Breakdown Structure
date: 2024-05-27
layout: post
---

A partire dalla RBS definita nel [Allegato 2 - Requirements Breakdown Structure]({{ site.baseurl }}/attachments/2-rbs/), vengono qui di seguito esplosi i requisiti del sistema elencando le attività necessarie per soddisfarli, nel formato di una _Work Breakdown Structure_.

1. **Progettazione, inizializzazione e configurazione dei workspace con un adeguato _build tool_, di un'infrastruttura con predisposizione a una _pipeline_ automatizzata di _continuous integration & deployment_.**
   1. Configurazione build tool e DVCS
   2. Configurazione pipeline di _continuous integration_
   3. Configurazione pipeline di _continuous deployment_
      1. Progettazione diagrammi deployment
      2. Creazione struttura locale minimale di orchestrazione
      3. Configurazione ambiente di produzione
      4. Sviluppo azioni deployment da locale a produzione
   4. Configurazione _bot_ per aggiornamento automatico delle dipendenze
   5. Configurazione _bot_ per il _merge_ automatizzato di Pull Request sulla repo
   6. Configurazione _bot_ per il rilascio automatico delle _release_
   7. Configurazione di un sistema di _ticketing_ automatizzato

2. **Progettazione e implementazione di un servizio per la gestione utente.**
   1. Il sistema deve poter gestire l'autenticazione degli utenti;
      1. Configurazione DB e implementazione schemi
      2. Implementazione token di autenticazione
      3. Regole di controllo di accesso
      4. Implementazione API di autenticazione
   2. Il sistema deve poter gestire la creazione, adesione e abbandono ai gruppi (operazioni CRUD);
      1. Configurazione DB e implementazione schemi
      2. Implementazione API di gestione gruppi
   3. Il sistema deve supportare una struttura gerarchica degli utenti appartenenti ad un gruppo;
      1. Esplorazione di plugin _on the shelf_
      2. Implementazione API di gestione dei ruoli
      3. Predisposizione dello _storage_ per la gestione dei ruoli
   4. Il sistema deve poter gestire le informazioni relative agli utenti e l'impostazione degli indirizzi preferiti.

3. **Progettazione e implementazione di un servizio di localizzazione.**
   1. Il sistema deve effettuare il _geocoding_ di indirizzi / luoghi in coordinate;
   2. Il sistema deve localizzare in tempo reale gli utenti e supportarne la condivisione con i membri del proprio gruppo;
   3. Il sistema deve gestire lo stato degli utenti in tempo reale;
   4. Il sistema deve permettere di impostare notifiche di prossimità con cui notificare gli utenti del proprio gruppo quando si raggiunge una certa posizione o se si verificano situazioni anomale (ad esempio, l'utente rimane fermo per troppo tempo).
   5. Il sistema deve permettere di poter notificare gli utenti di una situazione di pericolo, iniziando a tracciare il percorso dell'utente.

4. **Progettazione e implementazione di un servizio di chat.**
   1. Il sistema deve permettere una comunicazione sicura;
   2. Il sistema deve permettere un canale di comunicazione tra il client e il server;
   3. Il sistema deve permettere una comunicazione di natura broadcast ai membri appartenenti ai gruppi.

5. **Sistema di notifiche**
   1. Il sistema deve permettere l'invio di notifiche push;
   2. Il sistema deve permettere l'invio di notifiche mail.








<!--
1. **Progettazione e implementazione di un servizio per la gestione utente che deve occuparsi di tutti gli aspetti relativi all'autenticazione, sia per quanto riguarda l'iscrizione, sia per il log-in, a cui va aggiunta la creazione e il mantenimento dei gruppi.**
   1. Configurazione ed implementazione servizio di autenticazione
      1. Configurazione DB e implementazione schemi
      2. Implementazione token di autenticazione
      3. Regole di controllo di accesso
      4. Implementazione API di autenticazione
   2. Implementazione delle feature relative ai gruppi
      1. Configurazione DB e implementazione schemi
      2. Implementazione API di gestione gruppi
   3. Scrittura della documentazione
   4. Definizione configurazione di deployment

2. **Progettazione e implementazione di un servizio di localizzazione che permetta di geolocalizzare un utente in tempo reale, individuare coordinate a partire da indirizzi / luoghi ed esporre un'API per impostare notifiche quando l'utente arriva in prossimità di una certa posizione.**
   1. Confronto di tecnologie _MOM_ consone allo sviluppo del servizio
   2. Progettazione e design
   3. _Geocoding_ di indirizzi / luoghi in coordinate
      1. Studio di un servizio web di mappe per il _geocoding_
      2. Implementazione logica
   4. Implementazione API del servizio
      1. Impostazione di notifiche di prossimità
      2. Tracciamento real-time e gestione della posizione
      3. Configurazione DB dati e implementazione schemi
      4. Gestione stato utente
      5. Configurazione tecnologia / protocollo scelto all'interno del sistema
   5. Scrittura della documentazione
   6. Definizione configurazione di deployment

3. **Progettazione e implementazione di un servizio di chat che permetta di conversare in tempo reale con un singolo o un gruppo ristretto di utenti con la quale si vuole condividere la propria posizione e stato. Questo permetterà all,'utente di avere una comunicazione più diretta e immediata con i membri del gruppo.**
   1. Analisi di tecnologie / protocolli per lo scambio di messaggi
   2. Analisi aspetti di _sicurezza_ nella comunicazione in tempo reale tra più utenti
      1. Implementazione servizio _crittografia E2E_
   3. Implementazione API del servizio
      1. Configurazione tecnologia / protocollo scelto all'interno del sistema
      2. Implementazione funzionalità di chat
         1. Gestione invio _notifiche_
      3. Implementazione funzionalità _amministrazione_ dei gruppi chat
   4. Scrittura della documentazione
   5. Definizione configurazione di deployment

4. **Sistema di notifiche**
   1. Analisi di tecnologie / protocolli per l'invio di notifiche push
   2. Implementazione API del servizio
      1. Implementazione DB e schemi
      2. Implementazione funzionalità di invio notifiche push
      3. Implementazione funzionalità di invio notifiche mail
   3. Scrittura della documentazione
   4. Definizione configurazione di deployment

-->
