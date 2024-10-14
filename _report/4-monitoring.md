---
title: Monitoring & Controlling
date: 2024-09-05
layout: post
---

## Sistema di reporting

Aderendo al framework SCRUM, riunioni settimanali sono indette al fine di monitorare l'andamento del progetto; inoltre, gli obiettivi sono scanditi da periodi di sprint di 2 settimane.

A supporto di questo sistema di monitoraggio, è stato adottato lo strumento Youtrack, che permette di inserire i task sotto-forma di ticket, assegnargli una stima di tempo, aggiornarne lo stato e, data l'adozione del framework SCRUM, associarlo ad uno sprint. La scelta è dovuta sia alla versatilità del software, sia per l'esperienza del team con l'applicativo già maturata nel corso di progetti precedenti.


Il processo aderisce a _Cumulative reports_, in quanto è possibile visualizzare lo storico di tutti gli sprint, con particolare enfasi su eventuali task affetti da ritardo inseriti nel backlog dello sprint successivo.


Nella seguente immagine viene riportata l'interfaccia dell'applicativo, in cui è possibile delineare i 4 principali stati dei ticket, a cui va aggiunto il _Backlog_, relativo ai ticket non terminati nello sprint schedulato, che andranno ad aggiungersi ai ticket dello sprint successivo.

![Youtrack interface]({{ site.baseurl }}/res/youtrack-interface.png)

## Issues Log

Come strumento a supporto di _Issues Logging_ abbiamo selezionato GitHub in quanto offre un'interfaccia robusta per la segnalazione di problemi e il monitoraggio di questi ed è il sistema già adottato in fase di _Versioning Control_.


L'interfaccia permette la definizione di **issues** dettagliate e assegnabili, e supporta la chiusura automatica seguendo le regole di conventional commit che dettagliano i progressi dell'applicativo.
Github offre inoltre una valida integrazione con Youtrack: seguendo le regole dei conventional commit è possibile far progredire lo status dei ticket in maniera automatica.
