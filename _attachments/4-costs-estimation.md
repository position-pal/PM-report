---
title: Allegato 4 - Stima dei costi
date: 2024-06-25
layout: post
---

Vengono di seguito riportate le stime dei costi per la realizzazione del progetto.

Nelle stime di implementazione qui riportate consideriamo anche i costi per il testing.

<details>
<summary markdown='span' style="cursor: pointer; text-decoration:underline; color:#008CFF;">
    <strong>Stime attività requisito 1</strong>
</summary>

**Attività 1.1** Configurazione _build tool_ e DVCS

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 4            | 6                  | 8              | 6,00  | 6       | 6,00           |
| Round 2 | 6            | 6,5                | 7              | 6,50  | 6,5     | 6,50           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 2   |
| Durata stimata    | 4   |

**Attività 1.2** Configurazione pipeline di _continuous integration_

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 3            | 8                  | 3              | 4,67  | 3       | 4,94           |
| Round 2 | 4            | 6                  | 6              | 5,33  | 6       | 5,22           |
| Round 3 | 5            | 6                  | 6              | 5,67  | 6       | 5,61           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 2   |
| Durata stimata    | 4,5 |

**Attività 1.3.1** Configurazione pipeline di _continuous deployment_: progettazione diagrammi deployment

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 7            | 14                 | 8              | 9,67  | 8       | 9,94           |
| Round 2 | 11           | 13                 | 12             | 12,00 | 12      | 12,00          |
| Round 3 | 12           | 13                 | 13             | 12,67 | 13      | 12,61          |

| Unità di misura   | Ore                                              |
| ----------------- | ------------------------------------------------ |
| Risorse assegnate | 3 progettisti che collaborano in _brainstorming_ |
| Durata stimata    | 13                                               |

**Attività 1.3.2** Configurazione pipeline di _continuous deployment_: Creazione struttura locale minimale di orchestrazione

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 10           | 4                  | 9              | 7,67  | 9       | 7,44           |
| Round 2 | 8            | 6                  | 8              | 7,33  | 8       | 7,22           |
| Round 3 | 8            | 7                  | 8              | 7,67  | 8       | 7,61           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 8   |

**Attività 1.3.3**: Configurazione pipeline di _continuous deployment_: Configurazione ambiente di produzione

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 10           | 8                  | 8              | 8,67  | 8       | 8,78           |
| Round 2 | 9            | 8                  | 8              | 8,33  | 8       | 8,39           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 8   |

**Attività 1.3.4** Configurazione pipeline di _continuous deployment_: Sviluppo azioni deployment da locale a produzione

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 8            | 10                 | 8              | 8,67  | 8       | 8,78           |
| Round 2 | 9            | 9                  | 10             | 9,33  | 9       | 9,39           |
| Round 3 | 9            | 9,5                | 9,5            | 9,33  | 9,5     | 9,31           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 9,5 |

**Attività 1.4** Configurazione _bot_ per aggiornamento automatico delle dipendenze

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 3            | 0.5                | 2              | 2,50  | 2,5     | 2,50           |
| Round 2 | 1,5          | 1,5                | 1,5            | 1,50  | 1,5     | 1,50           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 1,5 |

**Attività 1.5** Configurazione _bot_ per il _merge_ automatizzato di Pull Request sulla repo

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 2            | 2                  | 1,5            | 1,83  | 2       | 1,81           |
| Round 2 | 2            | 2                  | 1,75           | 1,92  | 2       | 1,90           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 2   |

**Attività 1.6** Configurazione _bot_ per il rilascio automatico delle _release_

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 3            | 3                  | 2,5            | 2,83  | 3       | 2,81           |
| Round 2 | 2,75         | 3                  | 2,5            | 2,75  | 2,75    | 2,75           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 3   |

**Attività 1.7** Configurazione di un sistema di _ticketing_ automatizzato

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 0,5          | 0,5                | 0,5            | 0,50  | 0,5     | 0,50           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 0,5 |

</details>

<details>
<summary markdown='span' style="cursor: pointer; text-decoration:underline; color:#008CFF;">
    <strong>Stime attività requisito 2</strong>
</summary>

**Attività 2.1.1** Autenticazione - Configurazione DB e implementazione repository

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 4            | 6,5                | 5              | 5,17  | 5       | 5,19           |
| Round 2 | 5,5          | 6                  | 6              | 5,83  | 6       | 5,81           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 6   |

**Attività 2.1.2** Autenticazione - Implementazione token di autenticazione

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 3            | 5                  | 20             | 9,33  | 5       | 10,06          |
| Round 2 | 12           | 12                 | 14             | 12,67 | 12      | 12,78          |
| Round 3 | 12           | 12                 | 13             | 12,33 | 12      | 12,39          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 12  |

**Attività 2.1.3** Autenticazione - Regole di controllo di accesso

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 6            | 13                 | 12             | 10,33 | 12      | 10,06          |
| Round 2 | 12           | 13,5               | 13             | 12,83 | 13      | 12,81          |
| Round 3 | 12,5         | 13,5               | 13             | 13,00 | 13      | 13,00          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 13  |

**Attività 2.1.4** Autenticazione - Implementazione API di autenticazione

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 10           | 11                 | 16             | 12,33 | 11      | 12,56          |
| Round 2 | 13           | 18                 | 19             | 16,67 | 18      | 16,44          |
| Round 3 | 17           | 19                 | 19             | 18,33 | 19      | 18,22          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 19  |

**Attività 2.2.1** Gruppi - Configurazione DB e implementazione repository

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 6            | 9                  | 12             | 9,00  | 9       | 9,00           |
| Round 2 | 9            | 9,5                | 11             | 9,83  | 9,5     | 9,89           |
| Round 3 | 9            | 10                 | 10             | 9,67  | 10      | 9,61           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 10  |

**Attività 2.2.2** Gruppi - Implementazione API di gestione gruppi

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 20           | 25                 | 35             | 26,67 | 25      | 26,94          |
| Round 2 | 26           | 30                 | 33             | 29,67 | 30      | 29,61          |
| Round 3 | 30           | 30                 | 32             | 30,67 | 30      | 30,78          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 30  |

**Attività 2.3.1** Struttura gerarchica utenti - Esplorazione di plugin _on the shelf_

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 1,5          | 1                  | 4              | 2,17  | 1,5     | 2,28           |
| Round 2 | 3            | 2,5                | 4              | 3,17  | 3       | 3,19           |
| Round 3 | 3            | 3                  | 3,5            | 3,17  | 3       | 3,19           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 3   |

**Attività 2.3.2** Struttura gerarchica utenti - Implementazione API di gestione dei ruoli

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 8            | 12                 | 20             | 13,33 | 12      | 13,56          |
| Round 2 | 12           | 14                 | 19             | 15,00 | 14      | 15,17          |
| Round 3 | 14           | 16                 | 18             | 16,00 | 16      | 16,00          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 16  |

**Attività 2.3.3** Struttura gerarchica utenti - Predisposizione dello _storage_ per la gestione dei ruoli

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 15           | 17                 | 20             | 17,33 | 17      | 17,39          |
| Round 2 | 17           | 18                 | 20             | 18,33 | 18      | 18,39          |
| Round 3 | 18           | 19                 | 19             | 18,67 | 19      | 18,61          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 19  |

**Attività 2.4.1** Il sistema deve poter gestire le informazioni relative agli utenti e l'impostazione degli indirizzi preferiti - Configurazione DB e implementazione repository

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 8            | 13                 | 12             | 11,00 | 12      | 10,83          |
| Round 2 | 12           | 14                 | 15             | 13,67 | 14      | 13,61          |
| Round 3 | 13           | 14                 | 15             | 14,00 | 14      | 14,00          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 14  |

**Attività 2.4.2** Il sistema deve poter gestire le informazioni relative agli utenti e l'impostazione degli indirizzi preferiti - Implementazione API per la gestione delle informazioni

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 22           | 20                 | 25             | 22,33 | 22      | 22,39          |
| Round 2 | 23           | 25                 | 24             | 24,00 | 24      | 24,00          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 24  |

**Attività 2.5** Definizione configurazione di _deployment_

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 16           | 18                 | 20             | 18,00 | 18      | 18,00          |
| Round 2 | 16           | 18                 | 20             | 18,00 | 18      | 18,00          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 18  |

</details>

<details>
<summary markdown='span' style="cursor: pointer; text-decoration:underline; color:#008CFF;">
    <strong>Stime attività requisito 3</strong>
</summary>

**Attività 3.1.1** Il sistema deve effettuare il _geocoding_ di indirizzi e luoghi in coordinate - Ricerca di un servizio web di mappe per il _geocoding_

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 3            | 4                  | 3              | 3,33  | 3       | 3,39           |
| Round 2 | 3            | 3,5                | 3,5            | 3,33  | 3,5     | 3,31           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 3,5 |

**Attività 3.1.2** Il sistema deve effettuare il _geocoding_ di indirizzi e luoghi in coordinate - Implementazione ReST API

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 6            | 8                  | 7              | 7,00  | 7       | 7,00           |
| Round 2 | 8            | 9                  | 7,5            | 8,17  | 8       | 8,19           |
| Round 3 | 8            | 8                  | 8              | 8,00  | 8       | 8,00           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 8   |

**Attività 3.2.1** Il sistema deve tracciare in tempo reale la posizione degli utenti e supportarne la condivisione con i membri del proprio gruppo - Confronto di tecnologie _MOM_ consone allo sviluppo del servizio

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 3            | 5                  | 6              | 4,67  | 5       | 4,61           |
| Round 2 | 5            | 5                  | 6              | 5,33  | 5       | 5,39           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 5   |

**Attività 3.2.2** Il sistema deve tracciare in tempo reale la posizione degli utenti e supportarne la condivisione con i membri del proprio gruppo - Identificazione della tecnologia che consenta un tracciamento _real-time_ reattivo e potenzialmente replicabile

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 7            | 10                 | 8              | 8,33  | 8       | 8,39           |
| Round 2 | 8            | 8                  | 8              | 8,00  | 8       | 8,00           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 8   |

**Attività 3.2.3** Il sistema deve tracciare in tempo reale la posizione degli utenti e supportarne la condivisione con i membri del proprio gruppo - Progettazione e design

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 4            | 12                 | 5              | 7,00  | 5       | 7,33           |
| Round 2 | 8            | 10                 | 7              | 8,33  | 8       | 8,39           |
| Round 3 | 9            | 9                  | 8              | 8,67  | 9       | 8,61           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 9   |

**Attività 3.2.4** Il sistema deve tracciare in tempo reale la posizione degli utenti e supportarne la condivisione con i membri del proprio gruppo - Implementazione repository posizioni utenti

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 8            | 6                  | 8              | 7,33  | 8       | 7,22           |
| Round 2 | 8            | 7                  | 8              | 7,67  | 8       | 7,61           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 8   |

**Attività 3.2.5** Il sistema deve tracciare in tempo reale la posizione degli utenti e supportarne la condivisione con i membri del proprio gruppo - Implementazione comunicazione real-time tramite websocket

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 20           | 24                 | 29             | 24,33 | 24      | 24,39          |
| Round 2 | 25           | 25                 | 28             | 26,00 | 25      | 26,17          |
| Round 3 | 26           | 26                 | 27             | 26,33 | 26      | 26,39          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 2   |
| Durata stimata    | 18  |

**Attività 3.2.6** Il sistema deve tracciare in tempo reale la posizione degli utenti e supportarne la condivisione con i membri del proprio gruppo - Implementazione interazione con la tecnologia _MOM_ per la ricezione di eventi

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 10           | 21                 | 24             | 18,33 | 21      | 17,89          |
| Round 2 | 20           | 20                 | 22             | 20,67 | 20      | 20,78          |
| Round 3 | 20           | 20                 | 21             | 20,33 | 20      | 20,39          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 20  |

**Attività 3.3.1** Il sistema deve gestire lo stato degli utenti in tempo reale - Implementazione logica di gestione dello stato utente

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 10           | 5                  | 12             | 9,00  | 10      | 8,83           |
| Round 2 | 11           | 8                  | 11             | 10,00 | 11      | 9,83           |
| Round 3 | 11           | 10                 | 11             | 10,67 | 11      | 10,61          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 11  |

**Attività 3.4.1** Il sistema deve permettere all'utente d'iniziare un percorso e condividerlo con i membri del proprio gruppo, notificando l'arrivo in prossimità della posizione di arrivo o in caso si verifichino situazioni anomale - Implementazione logica di reazione a eventi

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 10           | 12                 | 16             | 12,67 | 12      | 12,78          |
| Round 2 | 12           | 13                 | 13             | 12,67 | 13      | 12,61          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 13  |

**Attività 3.4.2** Il sistema deve permettere all'utente d'iniziare un percorso e condividerlo con i membri del proprio gruppo, notificando l'arrivo in prossimità della posizione di arrivo o in caso si verifichino situazioni anomale - Implementazione comunicazione con il servizio di notifiche

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 3            | 3                  | 4              | 3,33  | 3       | 3,39           |
| Round 2 | 3,5          | 3                  | 3              | 3,17  | 3       | 3,19           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 3   |

**Attività 3.5.1** Il sistema, al sollevarsi di una situazione di pericolo, deve tracciare il percorso compiuto fino alla sua cessazione - Implementazione logica salvataggio dei percorsi

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 12           | 11                 | 18             | 13,67 | 12      | 13,94          |
| Round 2 | 14           | 15                 | 17             | 15,33 | 15      | 15,39          |
| Round 3 | 15           | 16                 | 16             | 15,67 | 16      | 15,61          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 16  |

**Attività 3.6** Definizione configurazione di deployment

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 20           | 18                 | 24             | 20,67 | 20      | 20,78          |
| Round 2 | 21           | 20                 | 24             | 21,67 | 21      | 21,78          |
| Round 3 | 22           | 21                 | 23             | 22,00 | 22      | 22,00          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 22  |

</details>

<details>
<summary markdown='span' style="cursor: pointer; text-decoration:underline; color:#008CFF;">
    <strong>Stime attività requisito 4</strong>
</summary>

**Attività 4.1.1**

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 6            | 6                  | 7              | 6,33  | 6       | 6,39           |
| Round 2 | 6            | 6,5                | 7              | 6,50  | 6,5     | 6,50           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 6,5 |

Attività 4.1.2

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 17           | 20                 | 24             | 20,33 | 20      | 20,39          |
| Round 2 | 20           | 21                 | 22             | 21,00 | 21      | 21,00          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 21  |

Attività 4.2.1

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 6            | 6                  | 5              | 5,67  | 6       | 5,61           |
| Round 2 | 5,5          | 6                  | 5,5            | 5,67  | 5,5     | 5,69           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 5,5 |

Attività 4.2.2

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 18           | 22                 | 24             | 21,33 | 22      | 21,22          |
| Round 2 | 20           | 23                 | 24             | 22,33 | 23      | 22,22          |
| Round 3 | 22           | 24                 | 23             | 23,00 | 23      | 23,00          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 23  |

Attività 4.2.3

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 20           | 28                 | 30             | 26,00 | 28      | 25,67          |
| Round 2 | 28           | 28                 | 30             | 28,67 | 28      | 28,78          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 29  |

Attività 4.3.1

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 13           | 10                 | 14             | 12,33 | 13      | 12,22          |
| Round 2 | 12           | 12                 | 13             | 12,33 | 12      | 12,39          |
| Round 3 | 12           | 13                 | 13             | 12,67 | 13      | 12,61          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 13  |

Attività 4.3.2

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 3            | 3                  | 4              | 3,33  | 3       | 3,39           |
| Round 2 | 3,5          | 3,5                | 5              | 4,00  | 3,5     | 4,08           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 4   |

Attività 4.4

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 19           | 20                 | 26             | 21,67 | 20      | 21,94          |
| Round 2 | 20           | 22                 | 25             | 22,33 | 22      | 22,39          |
| Round 3 | 22           | 24                 | 24             | 23,33 | 24      | 23,22          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 24  |

</details>

<details>
<summary markdown='span' style="cursor: pointer; text-decoration:underline; color:#008CFF;">
    <strong>Stime attività requisito 5</strong>
</summary>

Attività 5.1.1

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 6            | 7                  | 5              | 6,00  | 6       | 6,00           |
| Round 2 | 6            | 6                  | 5              | 5,67  | 6       | 5,61           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 6   |

Attività 5.1.2

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 32           | 26                 | 30             | 29,33 | 30      | 29,22          |
| Round 2 | 31           | 30                 | 30             | 30,33 | 30      | 30,39          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 30  |

Attività 5.1.3

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 20           | 24                 | 27             | 23,67 | 24      | 23,61          |
| Round 2 | 21           | 24                 | 26             | 22,50 | 22,5    | 22,50          |
| Round 3 | 23           | 24                 | 25             | 24,00 | 24      | 24,00          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 24  |

Attività 5.2.1

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 8            | 4                  | 5              | 5,67  | 5       | 5,78           |
| Round 2 | 7,5          | 7                  | 8              | 7,50  | 7,5     | 7,50           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 8   |

Attività 5.2.2

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 5            | 5                  | 6              | 5,33  | 5       | 5,39           |
| Round 2 | 5,5          | 5                  | 6              | 5,50  | 5,5     | 5,50           |
| Round 3 | 5,5          | 5,5                | 6              | 5,67  | 5,5     | 5,69           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 6   |

Attività 5.3

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 16      | 12  | 18         | 15,33 | 16      | 15,22          |
| Round 2 | 14      | 14  | 15         | 14,33 | 14      | 14,39          |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 14  |

</details>

<details>
<summary markdown='span' style="cursor: pointer; text-decoration:underline; color:#008CFF;">
    <strong>Stime attività requisito 6</strong>
</summary>

**Attività 6.1**

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 4            | 12                 | 8              | 8,00  | 8       | 8,00           |
| Round 2 | 9            | 10                 | 10             | 9,67  | 10      | 9,61           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 3   |
| Durata stimata    | 4   |

**Attività 6.2.1**

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 3            | 2                  | 2              | 2,33  | 2       | 2,39           |
| Round 2 | 3,5          | 2,5                | 3              | 3,00  | 3       | 3,00           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 3   |

**Attività 6.2.2**

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 4            | 4                  | 3              | 3,67  | 4       | 3,61           |
| Round 2 | 3,5          | 3,5                | 3              | 3,33  | 3,5     | 3,31           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 3,5 |

**Attività 6.3.1**

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 6            | 3                  | 4              | 4,33  | 4       | 4,39           |
| Round 2 | 4,5          | 5                  | 4              | 4,75  | 4,75    | 4,75           |
| Round 3 | 5            | 5                  | 4,5            | 4,83  | 5       | 4,81           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 5   |

**Attività 6.3.2**

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 6            | 9                  | 10             | 8,33  | 9       | 8,22           |
| Round 2 | 8            | 10                 | 9              | 9,00  | 9       | 9,00           |
| Round 3 | 9,5          | 10                 | 10             | 9,83  | 10      | 9,81           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 10  |

**Attività 6.4.1**

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 3            | 2                  | 2              | 2,33  | 2       | 2,39           |
| Round 2 | 2,5          | 2                  | 2,5            | 2,25  | 2,25    | 2,25           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 2,5 |

**Attività 6.4.2**

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 1            | 3                  | 3              | 2,33  | 3       | 2,22           |
| Round 2 | 2            | 3                  | 3              | 2,50  | 2,5     | 2,50           |
| Round 3 | 2,5          | 2,5                | 3              | 2,67  | 2,5     | 2,69           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 2,5 |

**Attività 6.5.1**

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 2,5          | 2                  | 3              | 2,50  | 2,5     | 2,50           |
| Round 2 | 3            | 3                  | 3              | 3,00  | 3       | 3,00           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 3   |

**Attività 6.5.2**

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 4            | 5                  | 5              | 4,67  | 5       | 4,61           |
| Round 2 | 4,5          | 4,5                | 5              | 4,50  | 4,5     | 4,50           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 5   |

**Attività 6.6.1**

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 4            | 2                  | 5              | 3,67  | 4       | 3,61           |
| Round 2 | 4            | 3,5                | 4,5            | 3,75  | 3,75    | 3,75           |
| Round 3 | 4            | 4                  | 4              | 4,00  | 4       | 4,00           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 4   |

**Attività 6.6.2**

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
| ------- | ------------ | ------------------ | -------------- | ----- | ------- | -------------- |
| Round 1 | 9            | 7                  | 10             | 8,67  | 9       | 8,61           |
| Round 2 | 9            | 8,5                | 9              | 8,75  | 8,75    | 8,75           |

| Unità di misura   | Ore |
| ----------------- | --- |
| Risorse assegnate | 1   |
| Durata stimata    | 9   |

</details>
