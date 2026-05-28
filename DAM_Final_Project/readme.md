1848 Newspaper Sentiment Analysis  
Comparative digital text analysis of Copenhagen and Haderslev newspapers during the First Schleswig War

Project Overview
This repository contains the full workflow and documentation for a digital humanities project examining how newspapers from Copenhagen and Haderslev framed the First Schleswig War in 1848. The project combines historical press material with modern computational methods to identify regional differences in sentiment, tone, and narrative framing.

The analysis is based on newspaper articles retrieved from Mediestream, cleaned through OCR‑aware preprocessing, and processed using an R‑based text‑mining pipeline.

Research Focus
The project investigates:

- how Copenhagen and Haderslev newspapers differed in their emotional and narrative portrayal of the 1848 conflict  
- whether sentiment analysis can reveal distinct communicative purposes across regions  
- how historical distance, political context, and proximity to conflict shaped press coverage  

These questions are explored through quantitative sentiment scoring and qualitative interpretation.

Methods
The analysis is conducted in R using:

- **tidyverse** for data wrangling  
- **tidytext** for tokenization and word frequency analysis  
- **Sentida** for Danish sentiment scoring  
- **ggplot2** for visualizations  
- custom preprocessing steps to handle OCR noise and historical spelling variation  

All steps are documented in the R Markdown file.

Key Findings
- Copenhagen newspapers display a more positive and nationally oriented sentiment, reflecting the capital’s political role and distance from the battlefield.  
- Haderslev newspapers adopt a more neutral and situational tone, shaped by proximity to the conflict and local uncertainty.  
- The divergence suggests that the two regions served different communicative purposes in the public sphere.  
- Sentiment analysis reveals meaningful patterns, but results must be interpreted cautiously due to OCR errors, historical spelling variation, and the use of modern sentiment tools on 19th‑century text.

A full discussion of these findings appears in the report.

Limitations
- OCR mistakes and inconsistent text quality  
- Historical spelling variation affecting tokenization  
- Sentida’s modern lexicon applied to 19th‑century language  
- Uneven article lengths and publication frequencies  

These limitations are addressed in the Discussion section.

How to Run
1. Open `1848_project.Rmd` in RStudio  
2. Install required packages (tidyverse, tidytext, Sentida, ggplot2)  
3. Knit the document to generate the full report  

License
This project is released under the **CC0 1.0 Universal License**.




