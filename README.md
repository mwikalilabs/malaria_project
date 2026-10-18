# malaria_project
Exploring the reported potency of approved compounds against Plasmodium falciparum using ChEMBL. A beginner-friendly bioinformatics project using Python, pandas, and data visualization to analyze compound activity data and explore the relationship between molecular weight and reported potency.
# Exploring the Reported Potency of Approved Compounds Against Plasmodium falciparum Using ChEMBL

## Overview

This project explores reported compound activity data for *Plasmodium falciparum* retrieved from the ChEMBL database. The aim was to investigate which approved compounds had the highest reported pChEMBL values in the retrieved dataset and whether there was an observable relationship between molecular weight and reported potency.

The project provided hands-on practice in applying Python and data analysis techniques to a biological question, from database querying and data cleaning to visualization and scientific interpretation.

## Research Questions

1. Which approved compounds had the highest reported pChEMBL values in the retrieved dataset?
2. Was there an observable relationship between molecular weight and reported potency?

## Data Source

- **Database:** [ChEMBL](https://www.ebi.ac.uk/chembl/explore/target/CHEMBL364)
- **Target organism:** *Plasmodium falciparum*
- **Dataset:** 17 activity records representing 8 unique approved compounds.
- **Filtering criteria:** Approved compounds with reported pChEMBL values ≥ 6.

## Tools and Technologies

- **ChEMBL:** Database querying and activity data extraction.
- **Python:** Data analysis.
- **pandas:** Data cleaning, manipulation, and descriptive statistics.
- **Matplotlib and Seaborn:** Data visualization.
- **Jupyter Notebook:** Interactive analysis and documentation.

## Methods

The analysis involved:

1. Retrieving compound activity data from ChEMBL.
2. Filtering the data for approved compounds with pChEMBL values ≥ 6.
3. Cleaning and preparing the dataset using pandas.
4. Calculating descriptive statistics and examining reported potency values.
5. Ranking compounds by their reported pChEMBL values.
6. Visualizing the relationship between molecular weight and reported potency.
7. Examining publication years represented in the dataset.
8. Interpreting the findings in the context of the dataset's limitations.

## Key Findings

- **Highest reported pChEMBL value:** Romidepsin had the highest value in the retrieved dataset, at 9.05.
- **Reported potency range:** pChEMBL values ranged from 6.67 to 9.05.
- **Molecular weight and potency:** No clear relationship was observed between molecular weight and reported potency.
- **Publication years:** The activity records spanned 2003–2023.

These findings describe the retrieved dataset and should not be interpreted as establishing the overall potency ranking of approved antimalarial compounds.

## Limitations

The dataset was small, containing 17 activity records representing 8 unique compounds. Additionally, the compounds were associated with different biological targets and assay conditions. Consequently, their reported pChEMBL values cannot be treated as directly comparable measurements of activity against a single target.

The observed patterns are therefore exploratory rather than conclusive.

## Skills Practiced

- ChEMBL database querying and data extraction
- Python programming and pandas
- Data cleaning and preparation
- Descriptive statistical analysis
- Data visualization using Matplotlib and Seaborn
- Interpretation of biological activity data
- Communicating findings and acknowledging analytical limitations

## Repository Contents

- `P.falciparum_drug_potency.ipynb` — Jupyter Notebook containing the analysis, code, and visualizations.
- `README.md` — Project overview, methods, findings, and limitations.

## Conclusion

This project provided practical experience in applying computational tools to a biological question, following the process from database retrieval and data preparation through statistical analysis, visualization, and scientific interpretation.

The analysis also highlighted the importance of considering dataset size, target differences, and assay conditions when interpreting compound activity data.
