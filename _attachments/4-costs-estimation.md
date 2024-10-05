---
title: Allegato 4 - Stima dei costi
date: 2024-06-25
layout: post
---

Vengono di seguito riportate le stime dei costi per la realizzazione del progetto.

Nelle stime di implementazione qui riportate consideriamo anche i costi per il testing.

<details>
<summary markdown='span'>
    <strong>Stima attività requisito 1</strong>
</summary>

**Attività 1.1** Configurazione _build tool_ e DVCS

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---------|--------------|--------------------|----------------|-------|---------|----------------|
| Round 1 | 4            | 6                  | 8              | 6,00  | 6       | 6,00           |
| Round 2 | 6            | 6,5                | 7              | 6,50  | 6,5     | 6,50           |

| Unità di misura:   | Ore |
|--------------------|-----|
| Risorse assegnate  | 2   |
| Durata stimata     | 4   |

**Attività 1.2** Configurazione pipeline di _continuous integration_

| Stime | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---|---|---|---|---|---|---|
| Round 1            | 3 | 8 | 3 | 4,67 | 3 | 4,94 |
| Round 2            | 4 | 6 | 6 | 5,33 | 6 | 5,22 |
| Round 3            | 5 | 6 | 6 | 5,67 | 6 | 5,61 |

| Unità di misura:   | Ore |
|--------------------|-----|
| Risorse assegnate: | 2 |
| Durata stimata:    | 4,5 |

**Attività 1.3.1** Configurazione pipeline di _continuous deployment_: progettazione diagrammi deployment

| Stime | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---|---|---|---|---|---|---|
| Round 1            | 4 | 10 | 3 | 5,67 | 4 | 5,94 |
| Round 2            | 6 | 6 | 8 | 6,67 | 6 | 6,78 |
| Round 3            | 6,5 | 6,5 | 7,5 | 6,83 | 6,5 | 6,89 |

| Unità di misura:   | Ore |
|--------------------|-----|
| Risorse assegnate: | 3 progettisti che collaborano in _brainstorming_ |
| Durata stimata:    | 3   |

**Attività 1.3.2** Configurazione pipeline di _continuous deployment_: Creazione struttura locale minimale di orchestrazione

| Stime | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---|---|---|---|---|---|---|
| Round 1 | 10 | 2 | 6 | 6,00 | 6 | 6,00 |
| Round 2 | 5 | 4.5 | 3 | 4,00 | 4 | 4,00 |
| Round 3 | 4.5 | 4.5 | 4 | 4,00 | 4 | 4,00 |

| Unità di misura:   | Ore |
|--------------------|-----|
| Risorse assegnate: | 1 esperto di deployment |
| Durata stimata:    | 4   |

**Attività 1.3.3**: Configurazione pipeline di _continuous deployment_: Configurazione ambiente di produzione

| Stime | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---|---|---|---|---|---|---|
| Round 1 | 4 | 6 | 2 | 4,00 | 4 | 4,00 |
| Round 2 | 5 | 6 | 4,5 | 5,17 | 5 | 5,19 |
| Round 3 | 5 | 6 | 5,5 |  | 5,50 | 5,5 | 5,50 |

| Unità di misura:   | Ore |
|--------------------|-----|
| Risorse assegnate: | 1   |
| Durata stimata:    | 5,5 |

**Attività 1.3.4** Configurazione pipeline di _continuous deployment_: Sviluppo azioni deployment da locale a produzione

| Stime | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---|---|---|---|---|---|---|
| Round 1 | 8 | 10 | 8 | 8,67 | 8 | 8,78 |
| Round 2 | 9 | 9 | 10 | 9,33 | 9 | 9,39 |
| Round 3 | 9 | 9,5 | 9,5 | 9,33 | 9,5 | 9,31 |

| Unità di misura:   | Ore |
|--------------------|-----|
| Risorse assegnate: | 1   |
| Durata stimata:    | 9,5 |

**Attività 1.4** Configurazione _bot_ per aggiornamento automatico delle dipendenze

| Stime | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---|---|---|---|---|---|---|
| Round 1 | 3 | 0.5 | 2 | 2,50 | 2,5 | 2,50 |
| Round 2 | 1,5 | 1,5 | 1,5 | 1,50 | 1,5 | 1,50 |

| Unità di misura:   | Ore |
|--------------------|-----|
| Risorse assegnate: | 1   |
| Durata stimata:    | 1,5 |

**Attività 1.5** Configurazione _bot_ per il _merge_ automatizzato di Pull Request sulla repo

| Stime | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---|---|---|---|---|---|---|
| Round 1 | 2 | 2 | 1,5 |  | 1,83 | 2 | 1,81 |
| Round 2 | 2 | 2 | 1,75 |  | 1,92 | 2 | 1,90 |

| Unità di misura:   | Ore |
|--------------------|-----|
| Risorse assegnate: | 1   |
| Durata stimata:    | 2   |

**Attività 1.6** Configurazione _bot_ per il rilascio automatico delle _release_

| Stime   | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---------|--------------|--------------------|----------------|-------|---------|----------------|
| Round 1 | 3 | 3 | 2,5 | 2,83 | 3 | 2,81 |
| Round 2 | 2,75 | 3 | 2,5 | 2,75 | 2,75 | 2,75 |

| Unità di misura:   | Ore  |
|--------------------|------|
| Risorse assegnate: | 1    |
| Durata stimata:    | 2,75 |

**Attività 1.7** Configurazione di un sistema di _ticketing_ automatizzato

| Stime | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---|---|---|---|---|---|---|
| Round 1 | 0,5 | 0,5 | 0,5 | 0,50 | 0,5 | 0,50 |

| Unità di misura:   | Ore |
|--------------------|-----|
| Risorse assegnate: | 1   |
| Durata stimata:    | 0,5 |

</details>

<details>
<summary markdown='span'>
    <strong>Stima attività requisito 2</strong>
</summary>

**Attività 2.1.1** Autenticazione - Configurazione DB e implementazione schemi

| Stime | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---|---|---|---|---|---|---|
| Round 1 | 4 | 6,5 | 5 | 5,17 | 5 | 5,19 |
| Round 2 | 5,5 | 6 | 6 | 5,83 | 6 | 5,81 |

| Unità di misura    | Ore |
|--------------------|-----|
| Risorse assegnate  | 1   |
| Durata stimata     | 6   |

**Attività 2.1.2** Autenticazione - Implementazione token di autenticazione

| Stime | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---|---|---|---|---|---|---|
| Round 1 | 3 | 5 | 20 | 9,33 | 5 | 10,06 |
| Round 2 | 12 | 12 | 14 | 12,67 | 12 | 12,78 |
| Round 3 | 12 | 12 | 13 | 12,33 | 12 | 12,39 |

| Unità di misura    | Ore |
|--------------------|-----|
| Risorse assegnate  | 1   |
| Durata stimata     | 12  |

**Attività 2.1.3** Autenticazione - Regole di controllo di accesso

| Stime | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---|---|---|---|---|---|---|
| Round 1 | 6 | 13 | 12 |  | 10,33 | 12 | 10,06 |
| Round 2 | 12 | 13,5 | 13 | 12,83 | 13 | 12,81 |
| Round 3 | 12,5 | 13,5 | 13 | 13,00 | 13 | 13,00 |

| Unità di misura:   | Ore |
|--------------------|-----|
| Risorse assegnate  | 1   |
| Durata stimata     | 13  |

**Attività 2.1.4** Autenticazione - Implementazione API di autenticazione

| Stime | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---|---|---|---|---|---|---|
| Round 1 | 10 | 11 | 16 |  | 12,33 | 11 | 12,56 |
| Round 2 | 13 | 18 | 19 |  | 16,67 | 18 | 16,44 |
| Round 3 | 16 | 19 | 19 |  | 18,00 | 19 | 17,83 |

| Unità di misura:   | Ore |
|--------------------|-----|
| Risorse assegnate  | 1   |
| Durata stimata     | 19  |

**Attività 2.2.1** Gruppi - Configurazione DB e implementazione schemi

| Stime | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---|---|---|---|---|---|---|
| Round 1 | 6 | 9 | 7 | 7,33 | 7 | 7,39 |
| Round 2 | 9 | 9,5 | 8 | 8,83 | 9 | 8,81 |
| Round 3 | 8,5 | 9,5 | 9 | 9,00 | 9 | 9,00 |

| Unità di misura:   | Ore |
|--------------------|-----|
| Risorse assegnate  | 1   |
| Durata stimata     | 9,5 |

**Attività 2.2.2** Gruppi - Implementazione API di gestione gruppi

| Stime | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---|---|---|---|---|---|---|
| Round 1 | 20 | 23 | 16 | 19,67 | 20 | 19,61 |
| Round 2 | 20 | 20 | 20 | 20,00 | 20 | 20,00 |

| Unità di misura:   | Ore |
|--------------------|-----|
| Risorse assegnate  | 1   |
| Durata stimata     | 20  |

**Attività 2.3.1** Struttura gerarchica utenti - Esplorazione di plugin _on the shelf_

| Stime | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---|---|---|---|---|---|---|
| Round 1 | 1,5 | 1 | 4 | 2,17 | 1,5 | 2,28 |
| Round 2 | 3 | 2,5 | 4 | 3,17 | 3 | 3,19 |
| Round 3 | 3 | 3 | 3,5 | 3,17 | 3 | 3,19 |

| Unità di misura:   | Ore |
|--------------------|-----|
| Risorse assegnate  | 1   |
| Durata stimata     | 3   |

**Attività 2.3.2** Struttura gerarchica utenti - Implementazione API di gestione dei ruoli

| Stime | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---|---|---|---|---|---|---|
| Round 1 | 8 | 8 | 16 | 10,67 | 8 | 11,11 |
| Round 2 | 14 | 20 | 20 | 18,00 | 20 | 17,67 |
| Round 3 | 18 | 18 | 19 | 18,33 | 18 | 18,39 |

| Unità di misura:   | Ore |
|--------------------|-----|
| Risorse assegnate  | 1   |
| Durata stimata     | 18  |

**Attività 2.3.3** Struttura gerarchica utenti - Predisposizione dello _storage_ per la gestione dei ruoli

| Stime | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---|---|---|---|---|---|---|
| Round 1 | 6 | 7 | 6 | 6,33 | 6 | 6,39 |
| Round 2 | 6 | 6,5 | 6,5 | 6,33 | 6,5 | 6,31 |

| Unità di misura    | Ore |
|--------------------|-----|
| Risorse assegnate  | 1   |
| Durata stimata     | 6,5 |

</details>
