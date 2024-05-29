---
title: Allegato 2 - Requirements Breakdown Structure
date: 2024-05-27
layout: post
---

Vengono qui di seguito esplosi i requisiti del sistema, a partire dagli obiettivi definiti nel [POS](/attachments/1-pos/).

1. **Organizzazione, configurazione e inizializzazione dei workspace con un adeguato _build tool_, di un'infrastruttura con predisposizione a una _pipeline_ automatizzata di _continuous integration & deployment_.**
   1. configurazione di una pipeline di _continuous integration_
   2. configurazione di una pipeline di _continuous deployment_
   3. configurazione _bot_ per aggiornamento automatico delle dipendenze
   4. configurazione _bot_ per il _merge_ automatizzato di Pull Request sulla repo
   5. configurazione build tool
2. `TODO`
3. **Progettazione e implementazione di un servizio di localizzazione che permetta di geolocalizzare un utente in tempo reale, individuare coordinate a partire da indirizzi / luoghi ed esporre un'API per impostare notifiche quando l'utente arriva in prossimità di una certa posizione.**
   1. _geocoding_ di indirizzi / luoghi in coordinate
   2. impostare notifiche di prossimità
   3. salvataggio e gestione della posizione degli utenti
