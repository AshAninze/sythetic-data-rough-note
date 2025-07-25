# NHP Synthetic Data Project: Scoping & Presentation Document

## Project Overview

This repository contains the ongoing work for an internship project focused on exploring and developing **synthetic data generation techniques** for the New Hospital Programme (NHP) demand prediction model. The primary goal is to address the challenge of data accessibility and privacy, enabling the NHP's open-source model to be truly reproducible, shareable, and evaluable without compromising sensitive real patient data.


The project's key findings and methodological insights are documented through **Quarto**, utilising the **NHS Strategy Unit (SU) Presentation Theme** for a structured and visually consistent presentation of the work.

## Problem Statement

The NHP demand prediction model is a critical tool for strategic healthcare planning. While its source code aims to be open, its usability for external researchers, collaborators, and even internal testing is limited by the inability to share the sensitive real patient data. Existing artificial data solutions provided by NHS England currently lack the necessary statistical relationships and complexity to accurately represent real world patient cohorts and their interactions. As a result, it is difficult to meaningfully evaluate the model or perform a thorough analysis. 

## Objectives
 
This project aims to:

1.  **Evaluate existing synthetic/artificial data approaches**, specifically assessing their ability to preserve complex multivariate relationships that are important for healthcare demand modeling.
2.  **Research and evaluate advanced synthetic data generation techniques** for advanced synthetic data generation techniques (e.g., GANs) that can effectively mimic the statistical properties and intercolumn relationships of real NHP data.
4.  **Produce a comprehensive scoping document/presentation** detailing the findings, comparing different approaches, outlining their pros and cons, and providing clear recommendations for future full scale implementation.
5.  **Enable true open-source collaboration** for the NHP model by facilitating reproducible testing and analysis without privacy concerns.

## Getting Started

To explore this project locally:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/AshAninze/sythetic-data-rough-note.git](https://github.com/AshAninze/sythetic-data-rough-note.git)
    cd sythetic-data-rough-note
    ```
2.  **Install Quarto:**
    Ensure Quarto is installed by following the instructions on the official [Quarto website](https://quarto.org/docs/get-started/).
3.  **Render the scoping document:**
    ```bash
    quarto render sythetic-data-rough-note.qmd
    ```
    This will generate the final output, an HTML file.


