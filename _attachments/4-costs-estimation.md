---
title: Allegato 4 - Stima dei costi
date: 2024-06-25
layout: post
---

Vengono di seguito riportate le stime dei costi per la realizzazione del progetto.

Nelle stime di implementazione qui riportate consideriamo anche i costi per il testing.

<details>
<summary><h3>Stima attività requisito 1</h3></summary>

**Attività 1.1** Configurazione build tool e DVCS

| Stime | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---|---|---|---|---|---|---|
| Round 1 | 4 | 6 | 8 | 6,00 | 6 | 6,00 |
| Round 2 | 6 | 6,5 | 7 | 6,50 | 6,5 | 6,50 |


| Unità di misura:   | Ore |
|--------------------|-----|
| Risorse assegnate: | 2   |
| Durata stimata:    | 4   |


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

| Stime | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---|---|---|---|---|---|---|
| Round 1 | 3 | 3 | 2,5 | 2,83 | 3 | 2,81 |
| Round 2 | 2,75 | 3 | 2,5 | 2,75 | 2,75 | 2,75 |

| Unità di misura:   | Ore |
|--------------------|-----|
| Risorse assegnate: | 1 |
| Durata stimata:    | 2,75 |

**Attività 1.7** Configurazione di un sistema di _ticketing_ automatizzato

| Stime | Luca Rubboli | Giovanni Antonioni | Luca Tassinari | Media | Mediana | 3 point method |
|---|---|---|---|---|---|---|
| Round 1 | 0,5 | 0,5 | 0,5 | 0,50 | 0,5 | 0,50 |

| Unità di misura:   | Ore |
|--------------------|-----|
| Risorse assegnate: | 1 |
| Durata stimata:    | 0,5 |

</details>
