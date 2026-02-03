

##  Project Overview

This project demonstrates the development of a **Point-in-Time (PIT) Probability of Default (PD) framework** using the **Vasicek single-factor credit risk model**, aligned with **IFRS 9 Expected Credit Loss (ECL)** requirements. The notebook focuses on converting **Through-the-Cycle (TTC) PDs into forward-looking PIT PDs** by incorporating a **systematic risk factor**, a standard industry approach used in credit risk modelling.

## Objectives
* Develop an **IFRS 9–aligned PIT PD framework** using the Vasicek model
* Transform **TTC PDs into macro-sensitive PIT PDs**
* Analyse **PIT vs TTC PD behaviour** across economic conditions
* Support **lifetime PD estimation and ECL modelling**

## Methodology
### 1. Data Preparation

* Worked on **borrower-level and portfolio-level PD data**
* Used TTC PD inputs as the baseline measure of long-run credit risk

### 2. Vasicek Single-Factor Model

* Implemented the **Vasicek credit risk model** to introduce a **systematic risk factor (Z)** representing economic conditions
* **Extracted the latent Z-factor** from observed TTC and PIT PD relationships
* Explained the **Z-factor using macroeconomic variables**, specifically **House Price Index (HPI)** and **Unemployment Rate (UR)**
* Converted TTC PDs into **time-varying PIT PDs** using the Vasicek transformation

### 3. PIT PD Analysis & Z-Factor Extrapolation

* Explored the sensitivity of **default probabilities** to movements in the **systematic Z-factor**
* Analysed **PIT vs TTC PD movement** to understand credit risk cyclicality
* **Extrapolated the Z-factor** using macroeconomic forecasts to generate **forward-looking PIT PDs**

### 4. Credit Risk Applications

* Used PIT PD outputs for **forward-looking credit risk assessment**
* Supported **lifetime PD estimation** required for **IFRS 9 ECL calculation**

## Analytics & Outputs

* TTC vs PIT PD comparison
* Impact of systematic risk factor on default probabilities
* Forward-looking PIT PD term structure


## Author

**Toshar Tarte**
Credit Risk & Analytics Enthusiast

