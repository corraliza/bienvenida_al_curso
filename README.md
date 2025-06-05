# I Curs de Bioinformàtica (SCB)

**Autoria:** Marta Coronado i Ana Maria Corraliza  
**Data:** 5 de juny de 2025  
**Organitza:** Societat Catalana de Biologia (SCB)  
**Format del curs:** En línia i asíncron (8 hores totals)

## 🎯 Objectiu

Aquest curs introductori a la bioinformàtica té com a finalitat ensenyar els conceptes bàsics de l’anàlisi de dades biomèdiques utilitzant **R** i **RStudio**, amb aplicacions en transcriptòmica (RNA-seq) i virologia. Es treballaran aspectes pràctics com el processament i la visualització de dades, i també es farà servir **Galaxy** com a eina complementària.

## 📦 Contingut del `.Rmd`

Aquest document R Markdown conté:

- Introducció al curs i objectius
- Guia d’instal·lació de R i RStudio
- Instruccions per accedir a **RStudio Cloud**
- Codi per a la instal·lació de llibreries (CRAN i Bioconductor)
- Explicació del format de les sessions
- Configuració del document HTML (TOC, estils, tema, etc.)

## 🛠 Requisits previs

Abans d’obrir el `.Rmd`, assegureu-vos de tenir:

- **R** instal·lat: [Enllaços d’instal·lació](https://cran.r-project.org/)
- **RStudio Desktop** o accés a [RStudio Cloud](https://posit.cloud/)
- Connexió a Internet per descarregar paquets

## 🔧 Instal·lació de paquets

Un cop tingueu **RStudio** obert, executeu aquest codi al panell `Console` per preparar l’entorn de treball:

```r
install.packages(c(
  "dplyr", "ggplot2", "ggpubr", "readr", "gtsummary", "tidyverse",
  "janitor", "lubridate", "tidyr", "ggsignif", "rstatix", 
  "tibble", "viridis", "BiocManager", "utils", "learnr", "readxl", "car"
))

BiocManager::install(c("limma", "DESeq2", "clusterProfiler"))
