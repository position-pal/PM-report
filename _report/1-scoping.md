---
title: Scoping
date: 2024-05-24
layout: post
---

## Contesto

Luca R., Giovanni A., Luca T., Valerio sono quattro studenti di Ingegneria e Scienze Informatiche dell'Università di Bologna che, a fronte di [alcune notizie](https://www.open.online/2024/04/04/scrivi-quando-arrivi-gruppo-whatsapp-ragazze/) lette recentemente di ragazzi e ragazze che tornando a casa di notte in zone poco sicure della città condividono la loro posizione in un gruppo WhatsApp per sostenersi e sorvegliarsi a vicenda, si sono posti come obiettivo quello di creare un sistema software _open source_ di tracciamento della posizione specificatamente progettato e studiato per creare una rete di supporto e assistenza efficace e tempestiva, in grado di segnalare in maniera rapida una situazione di emergenza.

Essendo un progetto _open source_ nato in contesto universitario da alcuni studenti con l'obiettivo di apprendere nuove tecnologie, pattern di progettazione, nonché nuove metodologie di sviluppo, non c'è un vero e proprio committente, né una singola figura che lo rappresenta.
Al contrario, tutti i membri del _team_ collaborano attivamente per cercare di capire e individuare al meglio tutti i possibili bisogni e desideri dell'utenza finale del prodotto.

L'analisi, in termini di _project management_, verterà sulla valutazione dei criteri di successo e dei rischi che possono accompagnare alcune scelte, oltre che all'individuazione e decomposizione delle macro-attività in unità più piccole, a cui seguirà una stima dei tempi di lavoro previsti e i _deliverables_ attesi.

Da un punto di vista tecnico, i membri del _team_ hanno recentemente avuto modo di seguire corsi riguardo a come progettare applicazioni _software_ di medio/grandi dimensioni sfruttando approcci guidati dal dominio (_domain-driven_), architetture distribuite a micro-servizi, e hanno avuto modo di apprezzare l'importanza di applicare metodologie di sviluppo _DevOps_ in cui l'automatizzazione dei processi e l'integrazione continua di codice funzionante (_working code_) in produzione in maniera completamente automatizzata è un fattore di primaria importanza.
Per queste ragioni il progetto _software_ e il suo processo di sviluppo sarà improntato seguendo queste fondamentali linee guida.

## Riunione di definizione del progetto (_scoping meeting_)

**Scopo:** individuazione delle aspettative e dei requisiti dell'applicazione.

**Partecipanti della riunione:**

| Membro                | Ruolo              |
|-----------------------|--------------------|
| **Luca Rubboli**      | **Project Manager** |
| Luca Tassinari        | _Core Team member_ |
| Giovanni Antonioni    | _Core Team member_ |
| Valerio Di Zio        | _Core Team member_ |

**Agenda:**

- introduzione (ad opera del facilitatore);
- scopo della riunione (ad opera del facilitatore);
- descrizione dell'opportunità di business;
- discussione delle _conditions of satisfaction_;
- descrizione dei _derivable_ del progetto;
- descrizione dei requisiti e della documentazione tramite _event storming_;
- scelta del modello _PMLC_ da seguire;
- bozza e approvazione del _POS_;

**Sintesi svolgimento:**

Per fini di brevità, aggreghiamo la sintesi e i risultati delle prime 3 riunioni, tenute da tutti i componenti del gruppo, nelle quali sono stati definiti gli obiettivi principali del progetto, sono stati formalizzati i requisiti e i criteri di accettazione.

In dettaglio, l'analisi è stata raffinata incrementalmente, inizialmente definendo gli obiettivi generali del progetto, da cui sono emerse le opportunità e i rischi correlati; parallelamente, sono state stilate le condizioni e criteri di successo del sistema.

> 📂 **_Allegato_**
> Il POS è riportato nell'[Allegato 1]({{ site.baseurl }}/attachments/1-pos/)
{: .block-tip }

Al fine di estrarre le principali funzionalità dell'applicativo nel modo più rapido ed efficace possibile, è stato utilizzato **_Event Storming_**, una tecnica di modellazione collaborativa e visuale particolarmente utilizzata e apprezzata nel contesto di sviluppo _agile_ e _Domain-Driven_.
La sua potenza deriva da un gruppo eterogeneo e multidisciplinare di esperti, dagli architetti ai _product owner_, passando per i _designer_ dell'_UI/UX_ ai _tester_, che, insieme, collaborano per estrarre le principali funzionalità e i processi che le guidano, condividendo questa conoscenza per far sì che sia condivisa al di là dei compartimenti stagni di ciascun team.
Inoltre, questo approccio consente di uniformare il linguaggio utilizzato (quello che in DDD è detto _ubiquitous language_) e di sollevare e poi risolvere eventuali ambiguità o incomprensioni che possono emergere sin dalle prime fasi del progetto.

Dopo aver introdotto brevemente quali sono i vantaggi nell'utilizzo di questa tecnica rispetto a un approccio più tradizionale, è stato quindi illustrato a tutti i componenti del gruppo come si svolge una sessione di _Event Storming_.

Si parte da un problema o da un obiettivo e, attraverso l'uso di _stickynotes_ colorate e _markers_, si procede a mappare i processi e le interazioni tra le varie entità coinvolte, in modo da ottenere una visione d'insieme del sistema e delle sue interazioni.
Più in dettaglio, la sessione inizia con l'identificazione dei _domain event_, ovvero gli eventi relativi al dominio che si sta esplorando che rappresentano qualcosa di interessante che è accaduto (per questo si usa il passato) e che possa essere utile per il sistema.
Questi vengono disposti in sequenza temporale in modo da creare una _timeline_ che rappresenti il flusso di eventi che si verificano nel sistema.
A questo punto si procede con l'identificazione dei _commands_, ovvero azioni che possono essere eseguite sul sistema da parte di un attore, e delle _policy_ con cui il sistema reagisce, andando ad arricchire la _timeline_ seguendo il flusso di eventi e azioni.
Infine si pongono in evidenza i _read models_, ovvero qualunque informazione che il sistema deve mostrare all'utente.

La struttura da seguire viene riassunta di seguito:

![Meta event storming]({{ site.baseurl }}/res/meta-event-storming.png)

> 📂 **_Allegato_**
> Lo schema risultante dell'_Event Storming_ è riportato, insieme all'RBS, nell'[Allegato 2]({{ site.baseurl }}/attachments/2-rbs/)
{: .block-tip }

Attraverso la stesura dei _requirements_ in una struttura gerarchica è stato possibile identificare anche un ordine di produzione delle macro-componenti, al fine di favorire inizialmente uno sviluppo che giovi dei benefici offerti dalla _continuous integration_ fin dall'inizio, e una struttura di testing incrementale.

Essendo in uno scenario di incertezza tecnologica che necessita di una componente esplorativa, abbiamo ritenuto che il modello che più si presti a queste esigenze sia quello _adattativo_: questa scelta permette di accogliere e adeguarsi ai cambiamenti, derivanti dalla raccolta di nuove informazioni che possono emergere durante il ciclo di vita del progetto.


TODO:

- I REQUISITI COME LI VALIDIAMO?
