This repository contains the code and data for the project and publication "Maintenance and loss of microbe-mediated protection in the absence of pathogens" (Kemlein *et al.* 2025, Journal of Evolutionary Biology). A corresponding release has been published at Zenodo (DOI: 10.5281/zenodo.15730064). All analyses were performed in R and code and corresponding data are archived in this repository.

## Table of Contents
•	Abstract
•	Repository Structure
•	Getting Started
•	Reproducing Results
•	License
•	Contact
•	Citation

## Abstract
Protective microbes are known for their service to hosts. While they allow hosts to survive infection, microbes, too, benefit from successful inhibition of incoming pathogens. Under constant pathogen exposure, protective symbionts should thus be selected for. Yet, it is less clear if, and how, microbe-mediated protection is maintained in symbionts in the absence of pathogen pressure. Addressing the stability of protective symbiosis during bacterial adaptation to healthy hosts, we studied microbe-mediated protection of *Pseudomonas lurida* MYb11 against pathogenic *Bacillus thuringiensis* Bt247 in its natural host *Caenorhabditis elegans* MY316. Specifically, we assessed host protection and *in vitro* inhibition of the pathogen for a collection of derived MYb11 isolates, which were previously evolved during serial passaging in healthy *C. elegans* hosts. We found that all evolved MYb11 isolates continued to inhibit the pathogen *in vitro*, while most, albeit not all, continued to protect hosts. We focused on two of these isolates, MT5 and MT11, one with and one without protection, and found that intact protection is associated with high symbiont colonization and resulting lower pathogen proportions. In sum, our study dissects the stability of a natural protective symbiosis and suggests that high colonization ability ensures microbe-mediated protection, even if microbes adapt to host association in the absence of pathogen selection.

Authors: Melinda Kemlein, Lena Peters, Hinrich Schulenburg#, Nancy Obeng# (# shared last authorship)
Acknowledgements: We thank K. Dierking, B. Pees, A. Czerwinski and the Schulenburg lab for fruitful discussions, laboratory support and feedback on the manuscript. Funding was provided by the Deutsche Forschungsgemeinschaft (DFG, German Research Foundation), Project-ID 261376515 – SFB 1182, Project A4 (NO, HS) and the CRC1182 Young Investigator Award 2021 (NO), and the Max-Planck Society (Fellowship to HS).

The repository includes all scripts and data necessary to reproduce the analyses and figures presented in the associated publication.

## Repository Structure
All files are saved under the main branch. Data files and corresponding R notebooks for analysis are labeled by figure number within the manuscript (e.g. “MYb11-mediated-protection_Fig4_[…]”. Additionally, the supplementary file including statistical analysis output (“Kemlein-et-al_supplementary.xlsx”) is part of the repository.

## Getting Started
1.	Clone the repository:
bash
git clone https://github.com/nobeng/Evolution-microbe-mediated-protection.git
cd Evolution-microbe-mediated-protection

2.	Install R and required packages:
•	R version used before upload: v4.4.1
•	All required R packages are listed at the top of each script. Install them using: install.packages(c("package1", "package2", ...))

3.	Run the analysis
•	Execute the scripts

## Reproducing Results
•	All scripts are self-contained and require no special instructions beyond installing dependencies.
•	Input data files are provided in the repository.

## License
This project is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license.

## Contact
For questions or further information, please raise a GitHub Issue or Discussion.

## Citation
If you use this code or data, please cite the associated publication: [Full citation to be added upon publication].
