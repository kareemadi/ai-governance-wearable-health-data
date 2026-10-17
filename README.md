# AI Governance Gaps in Wearable Health Data

**A Parkinson's Tremor Detection Case Study**

Kareem Adi

This is a research paper I wrote for IS490 (AI Governance) at the University of Illinois Urbana-Champaign in Spring 2026, under the supervision of Professor Meicen Sun.

## What the paper argues

Current AI governance frameworks for healthcare (including guidance from the WHO and the FDA) set out principles for oversight, data quality, and patient safety, but they stop short of technical standards for how wearable sensor data is preprocessed and validated. Using a Parkinson's tremor detection project as a case study, the paper shows how differences in feature sets, scaling, and missing-data handling changed the behavior of the same LSTM model across two public datasets (PAMAP2 and Capture-24), and argues that governance should address preprocessing consistency, cross-dataset validation, and transparency about how data is processed.

## Contents

- `AI-Governance-Gaps-Wearable-Health-Data.pdf` is the full paper, including references.

## Sources

The paper cites the WHO report *Ethics and governance of artificial intelligence for health* (2021), the FDA's overview of AI-enabled medical devices, Cross et al. (2024) on bias in medical AI, Hatherley (2025) on dataset shift, Sica et al. (2021) on home monitoring of Parkinson's disease, and the PAMAP2 and Capture-24 datasets. Full references are at the end of the PDF.

## Note

This repository contains only the written paper. The underlying tremor detection project was done as part of a university research lab and is not included here.
