# Consistent ensemble predictions of intertidal barnacle distributions across visual and eDNA-based occurrence data

*Simons D-L, Hipperson H, Webb TJ, Spencer M, Mieszkowska N*

This GitHub repository contains data and R code for reproducing analyses presented in Simons et al 2026, "Consistent ensemble predictions of intertidal barnacle distributions across visual and eDNA-based occurrence data". If you reuse any scripts or data in this project, please cite the paper (when released). 

> **Abstract:** Accurate predictions of current and future habitat suitability using species distribution models (SDMs) are critical for understanding the impacts of climate change on marine ecosystems. However, SDM accuracy is influenced by the quality of input occurrence data, which can include opportunistic presence-only records. DNA-derived occurrences are increasingly available but have rarely been applied in SDM frameworks. The effect of different occurrence data sources, including from visual and environmental DNA (eDNA) surveys, on SDM performance and predictions is evaluated for two competing UK intertidal barnacle species with contrasting thermal affinities: the cold-affinity barnacle Semibalanus balanoides and the warm-affinity barnacle Chthamalus montagui. Using an ensemble modelling framework, three SDMs per species were constructed with GBIF records from 2000–2021 as a baseline, supplemented with either GBIF records from 2022-2023 or eDNA-based records from 2022-2023. Models were fitted with three environmental predictors (sea surface temperature, pH, and wave fetch), evaluated with AUC and TSS metrics against expert-led presence–absence data, and used to project habitat suitability under current and future conditions. The inclusion of additional occurrence records did not change the performance of SDMs, regardless of whether the records originated from GBIF or eDNA. Ensemble models performed better than or similar to individual modelling algorithms. Predicted current distributions matched the known biogeographic ranges and thermal affinities of the study species. Future projections were consistent with expected thermal responses, with the cold-affinity \textit{S. balanoides} predicted to lose suitable habitat at southern latitudes, and the warm-affinity \textit{C. montagui} predicted to gain suitable habitat in most regions. These results indicate that ensemble approaches integrating multiple occurrence data sources perform as well as models solely using existing occurrences and capture realistic ecological niches. Future research could introduce more complexity into the modelling framework used here through incorporating fuzzy, occupancy-based, or mechanistic approaches, as well as additional environmental predictors.

## Repository Structure
-   `Figures/`: Stores all figures produced from the analyses.
-   `Data/`: Contains raw data files used for analyse, including metadata, phyloseq object and long data and stores processed data files used for analyses.
-   `intertidal-eDNA-SDMs-analyses.Rproj`: RStudio project file to manage the project environment.
-   `intertidal-eDNA-SDMs-analyses.qmd`: Quarto file containing the analysis code and documentation.
-   `intertidal-eDNA-SDMs-analyses.html`: HTML output generated from the Quarto file, providing a rendered version of the analysis. This file can be download and viewed as a standard guide.

## How to run
1. Clone the repository to your local machine.
2. Open the RStudio project file intertidal-eDNA-SDMs-analyses.Rproj) to set up the project environment.
3. Run the Quarto file (intertidal-eDNA-SDMs-analyses.qmd) to reproduce the analyses and generate the figures.

Alternatively, readers can download intertidal-eDNA-SDMs-analyses.html and open in any browser to view the full output of analysis without needing to rerun. 

## Contact
For questions or suggestions, please contact Dina-Leigh Simons at dinathebiologist@gmail.com.
