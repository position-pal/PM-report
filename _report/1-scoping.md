---
title: Scoping
date: 2024-05-24
layout: post
---

## Contesto

Luca, Giovanni, Luca e Valerio sono quattro studenti di Ingegneria e Scienze Informatiche dell'Università di Bologna che, a fronte di [alcune notizie](https://www.open.online/2024/04/04/scrivi-quando-arrivi-gruppo-whatsapp-ragazze/) lette recentemente di ragazzi e ragazze che tornando a casa di notte in zone poco sicure della città condividono la loro posizione in un gruppo WhatsApp per sostenersi e sorvegliarsi a vicenda, si sono posti come obiettivo quello di creare un sistema software _open source_ di tracciamento della posizione specificatamente progettato e studiato per creare una rete di supporto e assistenza efficace e tempestiva, in grado di segnalare in maniera rapida una situazione di emergenza.

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
| Luca Rubboli          | **Facilitatore**       |
| Luca Tassinari        | _Core Team member_ |
| Giovanni Antonioni    | _Core Team member_ |

**Agenda:**

- introduzione (ad opera del facilitatore);
- scopo della riunione (ad opera del facilitatore);
- descrizione dell'opportunità di business;
- discussione delle _conditions of satisfaction_;
- descrizione dei _derivable_ del progetto;
- descrizione dei requisiti e della documentazione tramite _event storming_;
- scelta del modello _PMLC_ da seguire;
- bozza e approvazione del _POS_;

### Facilitatore

Per fini di brevità, aggreghiamo i risultati delle prime 3 riunioni, tenute da tutti i componenti del gruppo.
Lo scopo di queste è stato quello di definire gli obiettivi principali del progetto, formalizzare i requisiti e i criteri di accettazione.
In dettaglio, l'analisi è stata raffinata in più passi, inizialmente definendo gli obiettivi generali del progetto, da cui sono emerse le opportunità e i rischi correlati; parallelamente sono state stilate le condizioni e criteri di successo del sistema.
Attraverso la stesura dei _requirements_ in una struttura gerarchica è stato possibile identificare anche un ordine di produzione delle macro-componenti, al fine di favorire inizialmente uno sviluppo che giovi dei benefici offerti dalla _continuous integration_ fin dall'inizio, e una struttura di testing incrementale.
La frammentazione dei requisiti in più sotto-funzionalità ha permesso di avere una visione più dettagliata del sistema, il chè ha favorito una stima di tempi di consegna più accurati.

Il processo viene accompagnato dalla fase di Event Storming, con l'obiettivo di estrarre le principali funzionalità dell'applicativo.

`TODO`

> ##### TIP
>
> Dalle slide del prof:
>
> _Obiettivi della riunione:_
>
> - tracciare desideri / aspettative e bisogni dei committenti
>
> _Deliverables_
>
> - POS
> - RBS
> - CoS (Conditions of Satisfacion)
> - PMLC model da usare
>
> Il tutto seguendo un approccio incrementale e iterativo
>
> _Possibile Agenda_:
>
> - introduzione (ad opera del facilitatore);
> - scopo del meeting (facilitatore);
> - discussione delle conditions of satisfaction;
> - descrizione del problem o della business opportunity;
> - descrizione dello stato finale che si vuole raggiungere;
> - descrizione dei requisiti e della documentazione;
> - scelta del modello PMLC da seguire;
> - bozza e approvazione del POS;
> - aggiornamento a una eventuale riunione successiva;
>
> Per la relazione e i meeting si chiede di documentare l'ordine del giorno, i partecipanti e una sintesi dell'ipotetico svolgimento
>   - lo svolgimento a mo' di dialogo?
>   - individuare chi è il facilitatore e gli altri membri e i loro ruoli
