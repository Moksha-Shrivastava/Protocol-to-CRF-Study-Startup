# Protocol to CRF Study Startup

## Background
This project covers pre-EDC as a project that converts a published clinical trial protocol into a operational study startup documents — SoA, Case Report Forms (CRFs) with CDASH-aligned field names, metadata specification, and building a Requirements Traceability Matrix (RTM).

## Workflow
1. Protocol review and generation of a Study Summary
2. Schedule of Assessments (SoA) designed to establish visit schedule and assessment requirements
3. CRF package designed based on SoA — 11 forms covering all study assessments
4. CRF Metadata Specification completed for CDASH alignment — defining fields, data types, controlled terminology, and allowed values
5. Requirements Traceability Matrix built linking every protocol requirement to the corresponding CRF and field
6. Edit Check Specification written for the EDC build team

## Protocol
- **Protocol:** Breast and Endometrial Safety of Micronised Progesterone Versus Norethisterone Acetate in Menopausal Hormone Therapy (PROBES)
- **ClinicalTrials.gov Identifier:** NCT05586724
- **Design:** Double-blind, Randomised, Controlled Trial
- **Indication:** Menopausal hormone therapy safety — breast and endometrial outcomes

## Deliverables
- **Study Summary:** Executive summary of the clinical study including objectives, design, population, and visit schedule
- **Schedule of Assessments:** Visit-by-visit assessment matrix extracted from the protocol
- **CRF Package:** 11 CRFs covering all study assessments, each annotated with CDASH variable names inline
- **CRF Metadata Specification:** CDASH variable mapping, data types, required fields, and controlled terminology for every CRF field
- **Requirements Traceability Matrix:** Links every protocol requirement to the corresponding assessment, CRF, and field

## Repository Structure
```
01 Protocol/          — StudySummary.md
02 Schedule_of_Assessments/ — SoA.xlsx
03 CRFs/              — 11 CRF documents (PDF)
04 Metadata/          — MetadataSpecification.xlsx
06 Traceability/      — RTM.xlsx
```

## Disclaimer
This is a simulated CDM exercise based on a publicly available protocol (CC BY 4.0). No patient data was used.
