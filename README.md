# ADAP1 promotes latent HIV-1 reactivation

## Abstract 
Immune stimulation fuels cell signaling-transcriptional programs inducing biological responses to eliminate virus-infected cells. Yet, retroviruses that integrate into host cell chromatin, such as HIV-1, co-opt these programs to switch between latent and reactivated states; however, the regulatory mechanisms are still unfolding. Here, we implemented a functional screen leveraging HIV-1’s dependence on CD4+ T cell signaling-transcriptional programs and discovered ADAP1 is an undescribed modulator of HIV-1 proviral fate. Specifically, we report ADAP1 (ArfGAP with dual PH domain-containing protein 1), a previously thought neuronal-restricted factor, is an amplifier of select T cell signaling programs. Using complementary biochemical and cellular assays, we demonstrate ADAP1 inducibly interacts with the immune signalosome to directly stimulate KRAS GTPase activity thereby augmenting T cell signaling through targeted activation of the ERK–AP-1 axis. Single cell transcriptomics analysis revealed loss of ADAP1 function blunts gene programs upon T cell stimulation consequently dampening latent HIV-1 reactivation. Our combined experimental approach defines ADAP1 as an unexpected tuner of T cell programs co-opted by facilitating HIV-1 for latency escape.

## scRNA-seq analysis

### Data repository
GSE169339: scRNAseq analysis comparing primary CD4+ T cells in resting memory state or stimulated with anti-CD3/anti-CD28 states and the effect of loss of ADAP1

### Folder structure
1) Download files listed below from the data repository  
  Ctrl_0hr_barcodes.tsv.gz; Ctrl_0hr_features.tsv.gz; Ctrl_0hr_matrix.mtx.gz    
  Ctrl_4hr_barcodes.tsv.gz; Ctrl_4hr_features.tsv.gz; Ctrl_4hr_matrix.mtx.gz  
  KD_0hr_barcodes.tsv.gz; KD_0hr_features.tsv.gz; KD_0hr_matrix.mtx.gz  
  KD_4hr_barcodes.tsv.gz; KD_4hr_features.tsv.gz; KD_4hr_matrix.mtx.gz

2) Create the folder structures under your working directory
2020_12_02_10X14_10480_0\analysis_results\ExpectCells\Ctrl_0hr\outs\filtered_feature_bc_matrix
2020_12_02_10X14_10480_0\analysis_results\ExpectCells\KD_0hr\outs\filtered_feature_bc_matrix
2020_12_03_10X14_10480_0\analysis_results\ExpectCells\Ctrl_4hr\outs\filtered_feature_bc_matrix
2020_12_03_10X14_10480_0\analysis_results\ExpectCells\KD_4hr\outs\filtered_feature_bc_matrix

3) Uncompress all the .gz files and store them under the corresponding folder. For example, 'Ctrl_0hr_barcodes.tsv', 'Ctrl_0hr_features.tsv', and 'Ctrl_0hr_matrix.mtx' need to be stroed under '2020_12_02_10X14_10480_0\analysis_results\ExpectCells\Ctrl_0hr\outs\filtered_feature_bc_matrix'

4) Remove prefix from the file names. For example, remove 'Ctrl_0hr_' from the file names of 'Ctrl_0hr_barcodes.tsv', 'Ctrl_0hr_features.tsv', and 'Ctrl_0hr_matrix.mtx'. 

### Run the R script
Download the R script named 'scRNAseq_Integrative_Ctrl_vs_KD_final.Rmd' from this github page onto your working directory and run the script.

## Conclusion
Single cell transcriptomics analysis revealed loss of ADAP1 function blunts genne program upon T cell stimulation consequently dampening latent HIV-1 reactivation.
