# Examining Multilevel Interconnectedness in Entrepreneurial Ecosystems: Within-Ecosystem and Between-Ecosystem Dynamics

Supplementary material for the PhD thesis "Examining Multilevel Interconnectedness in Entrepreneurial Ecosystems: Within-Ecosystem and Between-Ecosystem Dynamics" by Pallavpreet Kaur, Deakin University, 2026.

The thesis is made up of three essays. This repository holds the analysis files supporting all three.

## Contents

| File | Relates to | Description |
|---|---|---|
| `SLR_Essay1_Process_Derivation_041126.xlsx` | Essay 1 | Systematic literature review workbook showing how the processes and propositions in the conceptual framework were derived. |
| `Thesis_Analysis_Scripts_151126.pdf` | Essays 2 and 3 | R scripts for the fsQCA analysis (Chapter 3) and the regression analysis (Chapter 4). |
| `Paper2_Homeostasis_Construction_18112026.pdf` | Essay 2 (Chapter 3) | Construction of the Homeostasis index (Equation 3.3), with the R script and its verification. |
| `fsQCA_R_Output_Paper2_Main_15112026.pdf` | Essay 2 (Chapter 3) | R output for the main fsQCA analysis (Tables 3.2–3.6, B3, B4, B8–B10). |
| `Paper2_R_Output_Robustness_18112026.pdf` | Essay 2 (Chapter 3) | R output for the robustness checks (Tables B1, B2, B5, B6, B7 and Section B.4). |
| `Paper3_R_Console_Output_181126.pdf` | Essay 3 (Chapter 4) | R console output: primary models, cross-effect checks, margins, pairwise comparisons, and the overlapping-window robustness specification with candidate controls. |

## Essays
- **Essay 1:** Develops a conceptual framework of entrepreneurial ecosystem dynamics, drawing on Developmental Systems Theory (DST) and Coleman's framework. It is built from a systematic literature review and sets out testable propositions.
- **Essay 2:** Tests the Essay 1 propositions using fsQCA on 88 Australian SA4 regions, with ecosystem homeostasis and high-growth entrepreneurship as outcomes.
- **Essay 3:** Examines how interregional networks (migration and venture-capital flows) shape homeostasis and productive entrepreneurship in Australian regions, using regression analysis.

## Run order (Chapter 3)
1. Homeostasis construction (builds the Homeostasis column of `FSQCA_data.csv`).
2. Script 1: main fsQCA analysis.
3. Script 2: robustness (calibration and consistency threshold). Run Script 2 before Scripts 3 and 4.
4. Script 3: robustness (unicorn firms).
5. Script 4: robustness (frequency threshold of two cases).

## Software
- R 4.5.3 (fsQCA with the QCA package 3.25; regression analysis)
- Microsoft Excel (systematic literature review)

## Data
The underlying data are not included in this repository. Enquiries about the data can be directed to the author.

## Maps
The maps (Figure 4.1 in Chapter 4, and the maps in Chapter 3 and Appendix B) were drawn from the ABS ASGS Edition 3 (2021) SA4 boundaries. In Chapter 3, each SA4 is coloured by its recipe membership in the fsQCA solutions (Tables 3.5 and 3.6), taken directly from the R output. The mapping code is not included.

## Notes
- Console output files contain local file paths from the author's computer.
- Where the fsQCA solution has tied models, the thesis reports the main solution and the alternative tied solution; all tied models are listed in the R output files.

## Citation
If you use this material, please cite the thesis:

Kaur, P. (2026). *Examining Multilevel Interconnectedness in Entrepreneurial Ecosystems: Within-Ecosystem and Between-Ecosystem Dynamics* [Doctoral thesis, Deakin University]. Deakin Research Online.

## Licence
MIT License. See `LICENSE`.
