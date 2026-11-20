# Rajasthan Royals CLUTCH | Performance Under Pressure

### Cricket Analytics | Python | Statistical Modelling | Tableau

**Who delivers when the pressure rises, and how sure can we be?**

RR CLUTCH is an independent cricket analytics project developed for Rajasthan Royals' SupeRR Selector Season 2.

I wanted to explore a question that conventional batting averages, strike rates and bowling figures cannot fully answer: **Which players consistently perform when match conditions become difficult?**

The project combines cricketing understanding with statistical analysis to evaluate batting and bowling performance in specific pressure situations.

## Project Objectives

1. Identify batters who perform effectively during demanding run chases.
2. Evaluate bowlers defending tight targets and bowling at the death.
3. Compare individual performances against relevant expectations and benchmarks.
4. Account for sample size, match coverage and statistical uncertainty.
5. Test whether player rankings remain consistent when modelling assumptions change.

## Methodology

### 1. Data Preparation

Used Python and Pandas to investigate six structured cricket datasets.

The analysis included data quality checks, delivery classification, dismissal validation, scoring reconstruction and match context development.

### 2. Batting Under Pressure

Reconstructed match situations using required run rate, available deliveries and wicket information.

Compared batting performance under pressure with expected performance in the relevant source.

### 3. Bowling Under Pressure

Evaluated three important bowling outcomes:

1. Clean dot balls
2. Boundary suppression
3. Credited wickets

Considered tight chase defence and death overs against batting sides with wickets available.

### 4. Reliability Assessment

Incorporated sample coverage, confidence intervals and statistical uncertainty to distinguish stronger evidence from inconclusive findings.

### 5. Scenario Testing

Evaluated ranking sensitivity across three batting scenarios and nine bowling scenarios.

This helped identify which rankings remained consistent under different modelling assumptions.

## Interactive Tableau Dashboard

The Tableau workbook contains three dashboards:

**Pressure Rankings:** Batting and bowling leaderboards with supporting reliability indicators.

**Rank Stability:** Evaluates how player rankings respond to changes in modelling assumptions.

**Context Evidence:** Examines performance differences and statistical uncertainty across pressure situations.

[Explore RR CLUTCH on Tableau Public](https://public.tableau.com/app/profile/aryan.gadkar/viz/RR_CLUTCH_FINAL/RRCLUTCHContextEvidence)

## Tools and Technologies

1. Python
2. Pandas and NumPy
3. Jupyter Notebook
4. Statistical modelling and bootstrap analysis
5. Tableau Public

## Key Takeaway

A strong performance under pressure is valuable, but a reliable scouting decision requires more than an impressive number.

RR CLUTCH focuses on identifying players whose performances are supported by meaningful evidence while acknowledging the limits of the available data.

## Data Availability

The original datasets were provided exclusively for Rajasthan Royals' SupeRR Selector Season 2.

The competition data is proprietary and is not included in this repository. Reproducing the analysis requires authorised access to those datasets.

## Project Information

**Author:** Aryan Gadkar

**Project:**
