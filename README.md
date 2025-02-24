# Integrating Machine Learning and Protein-Ligand Interaction Profiling for the Discovery of METTL3 Inhibitors

Wei-Cheng Huang1, Hsing-Pang Hsieh1, Chun-Wei Tung1, *

1 Institute of Biotechnology and Pharmaceutical Research, National Health Research Institutes, Miaoli County, Taiwan
* Corresponding author. E-mail: cwtung@nhri.edu.tw

Abstract
 	RNA modifications are critical in regulating gene expression and cell functions by affecting RNA stability, splicing, translation, and degradation. The catalytic core of m6A modification, METTL3 (the methyltransferase-like 3), has emerged as a key enzyme in tumorigenesis by enhancing the translation efficiency of oncogenic transcripts, which is a promising therapeutic target for cancers, including acute myeloid leukemia. In this study, we presented a novel METTL3 inhibitory bioactivity (pIC50) prediction model (ML3-mix-DPLIFE) by combining machine learning, protein-ligand docking, and protein-ligand interaction analysis, through encoding the conventional physicochemical properties, chemical fingerprint, and the docking-based protein-ligand interaction features (DPLIFE) with leveraging auto-stacking 6 algorithms. A feature selection algorithm further optimized the model (ML3-mix-DPLIFE-FS) and obtained a promising mean squared error (MSE) of 0.261 and a Pearson's correlation coefficient (CC) of 0.853 on an independent test dataset, and identified 8 residues critical for ligand interactions with METTL3. To further test the model, the pIC50s of recently reported inhibitors were predicted using the ML3-mix-DPLIFE-FS model, and a good MSE of 0.418 and CC of 0.727 were obtained. This innovative strategy seamlessly integrates machine learning prediction with structural biology insights and reveals a novel way to identify key protein-ligand interactions for further structural rational drug design.

Keywords Human methyltransferase-like 3 (METTL3), Machine learning; Feature selection, Protein-ligand docking, The docking-based protein-ligand interaction features (DPLIFE)
Highlights
*	The present work presented the first model for predicting EC50 of the methyltransferase-like 3-ligand pairs. The presented explainable model is expected to be a useful tool for drug development of the methyltransferase-like 3 and the method is applicable for the drug discovery of other drug targets.
*	A novel docking-based protein-ligand interaction profile feature was encoded and integrated with structural features to improve accuracy and provide a novel way to identify the key residues for the methyltransferase-like 3 inhibitor discovery. 
*	The identified key residues are mutually consistent and supported by previous studies, further validating their critical role in the inhibition of the methyltransferase-like 3.

