# An analysis and discussion of race, ethnicity, and ancestry information in publicly available TCR-pMHC binding data

This is the repository for Maia Bennett-Boehms's final project in BMI 3000 (Public Health Genomics) at the University of Nebraska at Omaha. This project, "T cell receptor (TCR) sequencing for binding affinity prediction: an analysis and discussion of race, ethnicity, and ancestry representation in currently available data" was completed in December 2023.

T cells are key moderators of the adaptive immune system which utilize unique and highly diverse T cell receptors (TCRs) to facilitate recognition of specific antigens. Major histocompatibility complex (MHC) proteins found on all nucleated cells process these antigens into peptides and present them through the formation of peptide-MHC (pMHC) complexes. TCR-pMHC binding is dictated by TCR specificity and directly informs immune response to a detected pathogen. As such, there exist many models which attempt to accurately and consistently predict peptide-MHC and TCRpMHC binding affinities. MHC and TCR proteins are highly diverse, with approximately 30,000 human leukocyte antigen (HLA; human MHC) alleles across the population and upwards of 21 million TCRs in a given individual[8]. Prior analysis of TCR(β chain sequences has shown a strong association between many TCR chains and specific HLA alleles, indicating biased occurrence patterns with potential impacts on binding affinity prediction [7]. However, previous research has shown a significant disparity in HLA allele coverage across racial and ethnic populations in currently available peptide-MHC binding data [12]. These disparities were shown to negatively impact the performance of peptide-MHC binding models in underrepresented groups and may have downstream impacts on therapeutic efficacy. Similarly, analysis of currently available TCR sequencing data has shown a strong bias towards individuals of European descent and strong underrepresentation of individuals of African, Asian, and Hispanic descent [14]. Taken as a whole, these studies have shown a lack of data representativity in current HLA binding and general TCR sequencing data. As such, this report aims to assess the racial and ethnic representativity of TCR-pMHC binding sequencing data, the primary data source for TCR-pMHC binding models; it also explores and discusses the potential downstream implications of data representativity (or a lack thereof) in TCR-pMHC binding models and other genomic data. Finding disparities in paired TCR data coverage across racial and ethnic populations and establishing methods to encourage equitable coverage are of great importance to population genetics and broader public health initiatives which aim to mitigate disproportionate health burdens on specific racial and ethnic groups.

## The main goal of this project is to identify potential data bias in currently available TCR-pMHC binding data
- The first aim of this project is to quantify the coverage of racial diversity in currently-available TCR-pMHC binding data with associated self-reported race information.
- The second aim of this project is to quantify the availability of race, ethnicity, and ancestry information in currently available TCR-pMHC binding data.


## General overview of the analysis

![analysis_overview](https://github.com/maiabennett/tcr-diversity/assets/123126475/d0e77645-b0b4-4d18-868b-d0bcf0ba6b13)


## Implementation
This GitHub includes all code used to generate the results of the indicated analysis, which can be found in [this R markdown file](https://github.com/maiabennett/tcr-diversity/blob/main/basic-analysis.Rmd). Any extraneous questions on implementation and use can also be directed to Maia Bennett-Boehm at maiabennett@unomaha.edu. 

## License
This repository uses the GNU License. 
