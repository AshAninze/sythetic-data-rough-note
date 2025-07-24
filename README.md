# NHP Synthetic Data Project: Scoping & Proof of Concept

## Project Overview

This repository contains the ongoing work for an internship project focused on exploring and developing **synthetic data generation techniques** for the New Hospital Programme (NHP) demand prediction model. The primary goal is to address the challenge of data accessibility and privacy, enabling the NHP's open-source model to be truly reproducible, shareable, and evaluable without compromising sensitive real patient data.


The project's key findings and methodological insights are documented through **Quarto**, utilising the **NHS Strategy Unit (SU) Presentation Theme** for a structured and visually consistent presentation of the work.

## Problem Statement

The NHP demand prediction model is a critical tool for strategic healthcare planning. While its source code aims to be open, its utility for external researchers, collaborators, and even internal testing is severely limited by the inability to share the sensitive underlying real patient data. Existing "artificial data" solutions provided by NHS Digital (e.g., for software development) currently lack the necessary statistical relationships and complexity to accurately represent real-world patient cohorts and their interactions, thus hindering meaningful model evaluation and bias analysis.

## Objectives

This project aims to:

1.  **Evaluate existing synthetic/artificial data approaches**, specifically assessing their ability to preserve complex multivariate relationships crucial for healthcare demand modeling.
2.  **Research and implement Proofs of Concept (PoCs)** for advanced synthetic data generation techniques (e.g., Copula-based models, tabular GANs) that can effectively mimic the statistical properties and inter-column relationships of real NHP data.
3.  **Explore methods for bias mitigation** during synthetic data generation, ensuring the output reflects a fairer representation across sensitive demographic and socioeconomic attributes.
4.  **Produce a comprehensive scoping document/presentation** detailing the findings, comparing different approaches, outlining their pros and cons, and providing clear recommendations for future full-scale implementation.
5.  **Enable true open-source collaboration** for the NHP model by facilitating reproducible testing and analysis without privacy concerns.

## Repository Structure