---
title: Allegato 2 - Requirements Breakdown Structure
date: 2024-05-27
layout: post
---

## Event Storming

Viene qui presentata la mappa concettuale dell'_Event Storming_ effettuato per la definizione dei requisiti del sistema.

<div style="width: 100%; overflow-x: auto; white-space: nowrap;">
<img 
   src="{{ site.baseurl }}/res/event-storming.svg"
   alt="Event Storming"
   style="max-width: 250%;"
/>
</div>

## Requirements Breakdown Structure

Vengono qui di seguito esplosi i requisiti del sistema, a partire dagli obiettivi definiti nel [POS]({{ site.baseurl }}/attachments/1-pos/) e sulla base dell'_Event Storming_ effettuato, nel formato di una _Requirements Breakdown Structure_.

1. **Progettazione, inizializzazione e configurazione dei workspace con un adeguato _build tool_, di un'infrastruttura con predisposizione a una _pipeline_ automatizzata di _continuous integration & deployment_**

2. **Progettazione e implementazione di un servizio per la gestione utente**
   1. Il sistema deve poter gestire l'autenticazione degli utenti;
   2. Il sistema deve poter gestire la creazione, adesione e abbandono ai gruppi (operazioni CRUD);
   3. Il sistema deve supportare una struttura gerarchica degli utenti appartenenti ad un gruppo;
   4. Il sistema deve poter gestire le informazioni relative agli utenti e l'impostazione degli indirizzi preferiti.

3. **Progettazione e implementazione di un servizio di localizzazione**
   1. Il sistema deve effettuare il _geocoding_ di indirizzi e luoghi in coordinate;
   2. Il sistema deve localizzare in tempo reale gli utenti e supportarne la condivisione con i membri del proprio gruppo;
   3. Il sistema deve gestire lo stato degli utenti in tempo reale;
   4. Il sistema deve permettere all'utente d'iniziare un percorso e condividerlo con i membri del proprio gruppo, notificando l'arrivo in prossimità della posizione di arrivo o in caso si verifichino situazioni anomale, quali: l'utente rimane fermo per troppo tempo nella stessa posizione, va _off-line_ o non ha raggiunto la destinazione entro un certo tempo stabilito all'atto della creazione del percorso;
   5. Il sistema, al sollevarsi di una situazione di pericolo, deve tracciare il percorso compiuto fino alla sua cessazione.

4. **Progettazione e implementazione di un servizio di chat**
   1. Il sistema deve permettere una comunicazione sicura;
   2. Il sistema deve permettere un canale di comunicazione tra il client e il server;
   3. Il sistema deve permettere una comunicazione (di messaggi testuali) di natura _broadcast_ ai membri appartenenti ai gruppi.

5. **Sistema di notifiche**
   1. Il sistema deve permettere l'invio di notifiche _push_;
   2. Il sistema deve permettere l'invio di notifiche mail.

6. **Frontend**
   1. Prototipazione delle interfacce utente (mockup);
   2. Il sistema deve permettere di registrarsi e autenticarsi al sistema;
   3. Il sistema deve mostrare all'utente la mappa in tempo reale e lo stato di tutti i gruppi di cui fa parte;
   4. Il sistema deve permettere la modifica delle informazioni dell'utente;
   5. Il sistema deve permettere di visualizzare le notifiche ricevute;
   6. Il sistema deve permettere di visualizzare e interagire con le chat.

```plantuml
@startwbs rbs
<style>
node {
   RoundCorner 10
   :depth(0) {
      BackgroundColor #FFD365
   }
   :depth(1) {
      BackgroundColor #D5F5E8
   }
   :depth(2) {
      BackgroundColor #FFF4E1
   }
}
boxless { // will target boxless node with '_'
   FontColor #2C3E50
}
</style>

+ **PositionPal**

++ **1.** Progettazione, \n inizializzazione e \n configurazione \n workspace

++ **2.** Servizio di gestione \n utenti e gruppi
+++ **2.1.** Autenticazione
+++ **2.2.** Gestione della creazione, \n adesione e abbandono \n ai gruppi
+++ **2.3.** Supporto struttura \n gerarchica degli utenti \n appartenenti ad un gruppo
+++ **2.4.** Gestione informazioni \n utenti e indirizzi preferiti

++ **3.** Servizio di localizzazione
+++ **3.1.** Geocoding di indirizzi
+++ **3.2.** Localizzazione real-time \n e condivisione con \n membri del gruppo
+++ **3.3.** Gestione stato utenti \n in tempo reale
+++ **3.4.** Impostazione notifiche \n di prossimità
+++ **3.5.** Tracciamento percorso \n in situazioni di pericolo

++ **4.** Servizio di chat
+++ **4.1.** Sicurezza
+++ **4.2.** Comunicazione \n client-server
+++ **4.3.** Comunicazione \n broadcast ai membri \n del gruppo

++ **5.** Sistema di notifiche
+++ **5.1.** Notifiche push
+++ **5.2.** Notifiche mail

++ **6.** Frontend
+++ **6.1.** Prototipazione delle interfacce utente
+++ **6.2.** Interfaccia di autenticazione
+++ **6.3.** Mappa in tempo reale \n con sistema di notifiche
+++ **6.4.** Dashboard utente
+++ **6.5.** Dashboard notifiche
+++ **6.6.** Chat

@endwbs
```
