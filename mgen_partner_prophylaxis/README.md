# Treat the Partner, Save the Population

**Modeling the Impact of Prophylactic Partner Treatment on _Mycoplasma genitalium_ Transmission and Antibiotic Resistance**

_Mycoplasma genitalium_ (MG) is a rapidly mutating sexually transmitted infection with growing antibiotic resistance and poor routine screening coverage, especially in asymptomatic men.

Current protocols focus on treating only symptomatic index cases and testing partners after exposure. But with MG's diagnostic delay and resistance profile, **waiting to treat is already too late**.

This project simulates a different approach: **pre-treating sexual partners before exposure**, acknowledging that many so-called "healthy" partners may already be infected — just not yet detected.

## Why This Model Matters

We’re not just modeling STI transmission — we’re modeling the **cost of waiting to know**.

## Scenarios Compared

1. **Standard Care**: Only symptomatic index cases are treated.
2. **Reactive Partner Treatment**: Partners are treated after exposure and confirmed infection.
3. **Prophylactic Treatment**: Partners are treated *before* sexual contact.

## Features

- Dynamic simulation of susceptible, infected, and treated populations
- Poisson-distributed partner exposures based on real-world MG prevalence
- Adjustable resistance rates and population risk scenarios (general vs. high-risk)
- Visualization of infection curves under different strategies

## Core Assumptions

- People continue forming new partnerships whether they’re infected or treated.
- Prevalence determines likelihood of exposure to an undiagnosed infection.
- Resistance emerges both via transmission and failed treatment.

## Files

- `transmission_model.ipynb` – code for simulation and visualization
- `/figures/` – key plots for report or presentation
- `/report/` – write-up of key findings and implications
- `/data/` – reference data or synthetic inputs

## References

- CDC STD Treatment Guidelines (2021–2023)
- MyGeniUS surveillance data (2020)
- NHANES STI Prevalence Survey (2017–2018)
