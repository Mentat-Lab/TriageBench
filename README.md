# TriageBench

**Triage and Referral Behavior of Patient-Facing Artificial Intelligence Medical Products**

TriageBench is the benchmark and evaluation framework described in the manuscript above. It is designed to assess how patient-facing AI products triage symptoms, over-triage low-acuity cases, under-triage emergency cases, and refer users to affiliated clinical services.

## Manuscript

**Title:** Triage and Referral Behavior of Patient-Facing Artificial Intelligence Medical Products  
**Study design:** Cross-sectional evaluation of 9 AI products using 60 novel, physician-adjudicated standardized clinical cases (540 total conversations).

### Authors

- Samuel J. Margolis, BS
- Naga Venkata Sai Krishna Maddipatla, BS
- Kimon L.H. Ioannides, MD
- Lauren E. Wisk, PhD
- David L. Schriger, MD, MPH
- Joann G. Elmore, MD, MPH

### Corresponding Author

Samuel Margolis, BS  
David Geffen School of Medicine at UCLA  
885 Tiverton Drive  
Los Angeles, CA 90095  
SMargolis@mednet.ucla.edu

## Study Overview

- **Cases:** 60 novel standardized cases across 3 reference triage tiers:
  - Home care (n=20)
  - Clinician evaluation (n=20)
  - Emergency-department evaluation (n=20)
- **Product categories (9 total products):**
  - Branded health AI products
  - General-purpose consumer chat products
  - Foundation models via developer interfaces
- **Primary outcomes:**
  - Over-triage of home-care cases
  - Self-referral to product-affiliated clinical services (when available)
- **Exploratory outcomes:**
  - Under-triage of emergency cases
  - Clinical disclaimer presence

## Key Finding Summary

Across product categories, overall triage accuracy was similar, but referral behavior differed markedly. Branded health AI products over-triaged home-care cases more often and, when integrated with affiliated clinical services, frequently directed users to those same services.

## What TriageBench Contains

Per the manuscript Data Sharing Statement, this repository is intended to host:

- The full 60-case benchmark set
- The multi-turn standardized-patient simulator
- The data-collection harness
- Behavioral-coding prompts
- Analysis code
- De-identified conversation outputs

## Repository Status

This repository currently provides project documentation aligned with the manuscript scope. Benchmark assets and code will be made publicly available upon manuscript acceptance.

## Ethics

The protocol was determined exempt by the University of California, Los Angeles Institutional Review Board (IRB-26-0579).
