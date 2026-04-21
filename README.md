# NLHR_CDM
Norwegian Linked Health Registries (NLHR) – Common Data Model
> **Institution:** University of Oslo (UiO), Norway
> **EMA Data Catalogue:** [https://catalogues.ema.europa.eu/node/4310](https://catalogues.ema.europa.eu/node/4310/quantitative-descriptors)

---

## Overview

The **Norwegian Linked Health Registries (NLHR)** is a research data source hosted at the University of Oslo (UiO). It is constructed by linking multiple data sets retrieved from different national health registries in Norway. The data source is registered in the European Medicines Agency (EMA) DARWIN EU® Catalogue of Real-World Data Sources (node 4310).

The NLHR enables population-based pharmacoepidemiology and health services research by combining administrative and clinical information from the linked registries.

---

## Administrative Details

| Field | Details |
|---|---|
| **Data Source Name** | Norwegian Linked Health Registries |
| **Acronym** | NLHR |
| **Country** | Norway |
| **Data Holder / Owner** | University of Oslo (UiO) |
| **Organisational Unit** | Department of Pharmacy, Faculty of Mathematics and Natural Sciences / Department of Pharmacoepidemiology |
| **EMA DARWIN EU Catalogue** | [Node 4310 – Administrative Details](https://catalogues.ema.europa.eu/node/4310/administrative-details) |
| **Data Source Type** | Linked administrative health registries |
| **Geographic Coverage** | National (Norway) |
| **Language** | Norwegian |

---

## Linked Registries / Data Sources

The NLHR integrates data from the following Norwegian national health registries:

- **Norwegian Patient Registry (NPR / NorPAR)** – somatic and psychiatric specialist health care contacts
- **Norwegian Prescription Database (NorPD)** – all dispensed prescriptions in Norway
- **Cause of Death Registry** – date and cause of death for Norwegian residents
- **Medical Birth Registry of Norway (MBRN)** – birth data and pregnancy outcomes
- **Norwegian Registry for Primary Health Care (NRPHC / KUHR)** – contacts with primary health care and out-of-hours emergency clinics
- **Cancer Registry of Norway (CRN)** – cancer diagnoses and treatments
- **Norwegian Immunisation Registry (SYSVAK)** – vaccination records
- **National Population Register (Folkeregisteret / FREG)** – demographic information (date of birth, sex, emigration/immigration)

---

## Population Coverage

- **Target Population**: All residents registered in Norway (approximately 5.3 million individuals)
- **Coverage**: Near-complete national coverage
- **Linkage Key**: National identity number (fødselsnummer), a unique personal identifier assigned to all Norwegian residents

---

## Temporal Coverage

- **Start of Data Availability**: Varies by registry; most registries provide data from the early 2000s onwards. Prescription data (NorPD) is available from 2004; patient registry data from 2008.
- **Ongoing**: Data are updated annually.

---

## Data Access

Access to NLHR data is restricted and subject to approval by:
- The University of Oslo data governance processes
- Regional Committees for Medical and Health Research Ethics (REK) in Norway
- The Norwegian Directorate of Health and/or the individual registry data controllers

Researchers seeking access should contact the Department of Pharmacoepidemiology at the University of Oslo.

---

## Common Data Model (CDM)

This repository contains the Common Data Model (CDM) mapping and documentation for the NLHR data source, following the OMOP CDM standard as used in the EMA DARWIN EU® framework.

---

## References

- EMA DARWIN EU® Catalogue: https://catalogues.ema.europa.eu/node/4310/administrative-details
- University of Oslo, Department of Pharmacoepidemiology: https://www.med.uio.no/farmasi/english/
- Norwegian Institute of Public Health (Folkehelseinstituttet): https://www.fhi.no/en/
