# LC–MS-based metabolomic profiling of *Pseudomonas chlororaphis* wild-type R47 and derived mutants
UNIFR - SBL.20004 - Introduction to metabolomics: data acquisition and processing 

08.06.2026

---
Group 2: Charles FICHTER, Valentine MOTTAS, Gaëlle RUFFIEUX, Kailynn SMITH

---

## Introduction
*Phytophthora infestans*, the causal agent of potato late blight, is one of the most devastating pathogens for potato crops worldwide. Current control measures face challenges due to their environmental impact and the increasing resistance of pathogens (Anand et al., 2020; Guyer et al., 2015; Jerjen, L'Haridon & Weisskopf, 2026). In this context, bacteria with biocontrol potential offer a promising and sustainable alternative for managing late blight (De Vrieze et al., 2020; Guyer et al., 2015). Previous studies have demonstrated that certain potato-associated *Pseudomonas sp.* have antagonistic activity against *P. infestans* (Guyer et al., 2015). Among these is the *Pseudomonas chlororaphis* R47 isolated from potato roots (Hunziker et al., 2015), whose genome has been sequenced, revealing potential factors contributing to its biocontrol activity, including the production of pyoverdine, an iron-scavenging siderophore, and phenazine-based antibiotics, alongside other uncharacterized biosynthetic gene clusters (De Vrieze et al., 2020). To better understand how these metabolites play a role in R47’s effect against *P. infestans*, mutants deficient either in pyoverdine or phenazine production were generated using the I-SceI system and a pEMG suicide plasmid (Anand et al., 2020; Martínez-García & de Lorenzo, 2011). 

The first mutant carries a disruption of the *pvdE* gene, which encodes an ABC transporter that exports pyoverdine precursors to the periplasm, where pyoverdine maturation occurs. This mutation completely abolishes pyoverdine production (Yeterian et al., 2009). The second mutant is affected in the *phzC* gene, which encodes an enzyme involved in the early steps of the phenazine biosynthesis pathway (Biessy & Filion, 2018). Preliminary results showed that this mutation reduces phenazine production by approximately 90%. Previous experiments showed that neither the *pvdE* nor the *phzC* mutation significantly affects the ability of *P. chlororaphis* R47 to inhibit the mycelial growth of *P. infestans* (Jerjen, L'Haridon & Weisskopf, 2026), suggesting that pyoverdine and phenazines are not the primary drivers of this antagonistic activity. Identifying the metabolites responsible, therefore, remains an open question — and a relevant one, as such compounds could serve as target molecules in future screenings for biocontrol-active microorganisms.

During the generation of the *pvdE* mutant, a spontaneous mutation led to the third strain, 1F12. In addition to the loss of pyoverdine production, this strain carries a point mutation in the global regulatory system Gac. The mutant displays a slightly reduced inhibitory effect on *P. infestans* mycelial growth. The Gac system is a global master regulator known to control a wide array of secondary metabolites, including phenazine biosynthesis genes (Wang et al., 2013). Consistent with this, 1F12 no longer produces the characteristic orange pigmentation of wild-type R47, suggesting a complete loss of phenazine production in this strain. To identify metabolites potentially involved in the reduced antagonistic activity of 1F12, we compared the soluble exometabolomes (that is, the collection of metabolites secreted and retained in the liquid culture medium) of *P. chlororaphis* wild-type R47 and the three derived mutants. The liquid culture media were analyzed after bacterial growth, and the metabolites were compared across strains using an untargeted metabolomics approach.

## Methods
### Wet Lab Processing
#### *Sample Preparation*
Liquid cultures of various *Pseudomonas chlororaphis* R47 strains (wild type, *pvdE*, *phzC*, and 1F12) were grown in lysogeny broth (LB) medium under shaking conditions for 48 hours to promote aerobic growth and metabolite production. For each strain, four independent biological replicates were prepared by inoculating three colonies from solid LB medium into individual liquid culture tubes, each tube representing a distinct biological replicate. Following incubation, the optical density (OD) of each liquid culture was measured to verify comparable cell densities across replicates, and the cultures were then filtered through a 0.22 µm PVDF membrane filter to obtain cell-free filtrates (CFFs), representing the extracellular metabolite fraction. The CFFs were independently transferred into individual vials for LC-MS analysis (Figure 1). A sterile LB medium control was processed identically to account for medium-derived signals. A pooled quality control (QC) sample was prepared by combining 10 µL from each sample, including the LB medium control, to monitor instrument stability and analytical reproducibility throughout the sequence. Solvent blanks, consisting of a solvent-only injection, were run periodically throughout the sequence to monitor carry-over and background contamination.

<p align="center">
  <img src="https://github.com/user-attachments/assets/61b65ce1-e036-422c-84bb-b82db2d7bd5f" alt="LC-MS injection vials containing cell-free filtrates, arranged from left to right: pooled Quality Control (QC), P. chlororaphis wild-type R47 (replicates 1–4), phzC mutant (replicates 1–4), pvdE mutant (replicates 1–4), 1F12 mutant (replicates 1–4), and LB medium control."/>
</p>
<p align="center"><b>Figure 1</b>: LC-MS injection vials containing cell-free filtrates, arranged from left to right: pooled Quality Control (QC), <i>P. chlororaphis</i> wild-type R47 (replicates 1–4), <i>phzC</i> mutant (replicates 1–4), <i>pvdE</i> mutant (replicates 1–4), 1F12 mutant (replicates 1–4), and LB medium control. 

#### *LC-MS Data Acquisition*
To enable broad-spectrum detection of secreted compounds, an untargeted metabolomics approach was employed using ultra-high-performance liquid chromatography (UHPLC) coupled to high-resolution mass spectrometry (HRMS). Chromatographic separation was performed on a Vanquish Flex Ultra-High Performance Liquid Chromatography (UHPLC) system (Thermo Fisher Scientific) interfaced with a Q Exactive HF mass spectrometer (MS) (Thermo Fisher Scientific) equipped with a Heated Electrospray Ionization (HESI-II) source. Instrument control was carried out using Thermo Scientific Xcalibur 3.1 software. All samples were analyzed on both a reversed-phase C18 column (Waters BEH C18, 100 × 2.1 mm, 1.7 µm) and a Hydrophilic Interaction Liquid Chromatography (HILIC) column (Waters Atlantis Premier BEH Z-HILIC, 100 × 2.1 mm, 1.7 µm), maintained at 40°C. The autosampler was maintained at 10°C. Samples were injected in randomized order to minimize batch effects, with a single injection per sample. The column was re-equilibrated for 2 min between injections. For C18 separation, mobile phase A consisted of water with 0.1% formic acid (FA) and mobile phase B of acetonitrile with 0.1% FA. For HILIC separation, mobile phase A consisted of water with 10 mM ammonium formate and 0.1% FA, and mobile phase B of acetonitrile with 0.1% FA. The flow rate was 600 µL/min and the injection volume 1–2 µL. Elution was carried out using a linear gradient from 2% to 100% B over 10 min, followed by an isocratic hold at 100% B for 2 min. Pooled QC samples were injected 2–3 times at the beginning of the sequence and 6 times throughout the run at regular intervals to monitor instrument stability. Solvent blanks were injected 1–2 times at the beginning of the sequence to assess background contamination and carryover. 

Mass spectrometric detection was performed in positive ionization mode over a mass range of *m/z* 120–1800. Data were acquired in centroid mode. Full scan MS spectra were acquired at a resolving power of 35,000 Full Width at Half Maximum (FWHM) (at *m/z* 200) with an Automatic Gain Control (AGC) target of 3 × 10⁶, and data-dependent MS/MS spectra at 17,500 FWHM with an AGC target of 1 × 10⁵, both with automatically determined maximum injection times. Fragmentation was performed on the three most intense precursor ions per scan (Top3), using stepped Normalized Collision Energies (NCE) of 15, 30, and 45 units, with an MS/MS isolation window of 1 Da. Acquired precursor ions were placed on a dynamic exclusion list for 3.0 s following MS/MS acquisition. 

HESI-II source parameters were as follows: spray voltage, 3.5 kV; sheath gas flow rate (N₂), 55 units; auxiliary gas flow rate, 15 units; spare gas flow rate, 3.0 units; capillary temperature, 350°C; S-Lens Radio Frequency (RF) level, 50. The mass analyzer was calibrated using a standard mixture containing caffeine, methionine-arginine-phenylalanine-alanine acetate (MRFA), sodium dodecyl sulfate (SDS), sodium taurocholate, and Ultramark 1621 in an acetonitrile/methanol/water solution with 1% formic acid, introduced by direct injection. 

### Dry Lab Processing
Although Sample were analyzed on both C18 and HILIC columns, inspection of the Total Ion Chromatograms (TICs) revealed no substantial differences between strains in the HILIC data; subsequent data processing and statistical analysis were therefore carried out exclusively on the C18 dataset. 

#### *LC-MS Data Prcoessing (MZmine 4.9.14)*
Raw data files were imported and processed in batch mode using MZmine 4.5.0 (Schmid et al., 2023). Mass detection was performed separately for MS1 and MS2 scans using the centroid algorithm. For MS1, a noise threshold of 5.0 × 10⁵ was applied; for MS2, the threshold was set to 0, retaining all detected signals, taking advantage of the low background noise inherent to Orbitrap-based acquisition. Chromatogram building was performed using the ADAP Chromatogram Builder, restricted to positive polarity MS1 scans over a retention time window of 0–12.01 min. The following parameters were applied: minimum consecutive scans, 5; minimum intensity for consecutive scans, 5.0 × 10⁵; minimum absolute height, 5.0 × 10⁵; scan-to-scan *m/z* tolerance, 0.002 Da / 15 ppm. Chromatographic smoothing was subsequently applied using the Savitzky-Golay algorithm over a window of 5 retention time scans. Chromatogram deconvolution was performed using the Minimum Search Feature Resolver with the following parameters: chromatographic threshold, 0.30; minimum search range, 0.05 min; minimum absolute height, 5.0 × 10⁴; minimum peak top-to-edge ratio, 1.8; peak duration range, 0–1.51 min; minimum scans, 5. 

MS2 scan pairing was enabled with a precursor *m/z* tolerance of 0.01 Da / 10 ppm and a retention time filter set to feature edges. Isotope grouping was carried out using the Isotope Grouper module with an intra-sample *m/z* tolerance of 0.0015 Da / 5 ppm, a retention time tolerance of 0.04 min, a maximum charge state of 2, and monotonic shape enforced. Features carrying MS2 scans were never removed during this step. Isotope pattern detection was additionally performed using the Isotope Finder module, searching for H, C, N, O, and S isotopes with an *m/z* tolerance of 0.0015 Da / 3 ppm. 

Feature alignment across samples was performed using the Join Aligner with an *m/z* tolerance of 0.001 Da / 5 ppm (weight: 3.0) and a retention time tolerance of 0.1 min (weight: 2.0). The aligned feature list was subsequently filtered to retain only features presenting a minimum of 2 isotope pattern peaks and associated with at least one MS2 scan, while features with MS2 scans were protected from removal. Feature IDs were reset after filtering. Gap filling was performed using the multithreaded Peak Finder with an intensity tolerance of 20%, an *m/z* tolerance of 0.001 Da / 5 ppm, a retention time tolerance of 0.1 min, and a minimum of 5 data points required. 

The processed feature list was exported for Feature-Based Molecular Networking (FBMN) using the GNPS export module, generating both a feature quantification table (.csv) and an MS/MS spectral summary (.mgf) (Nothias et al., 2020; Wang et al., 2016). Feature intensity was reported as peak height without normalization. The most intense MS2 scan across samples was selected as the representative spectrum for each feature. A parallel export in SIRIUS-compatible .mgf format was also generated, using merged MS/MS spectra (merged across samples, maximum intensity merge mode, *m/z* tolerance 0.001 Da / 5 ppm) (Dührkop et al., 2019). 

#### *SIRIUS-Based Annotation*
Molecular formula prediction, structure annotation, and chemical class assignment were performed using SIRIUS 6.2. The exported SIRIUS-compatible .mgf file generated by MZmine was used as input. The instrument profile was set to Orbitrap, with a mass accuracy of 5 ppm. Chemical elements considered for formula prediction were C, H, O, N, P, S, Cl, Br, and I. Molecular formula candidates were generated and scored using SIRIUS (Dührkop et al., 2019). 

Structure annotation was performed using CSI:FingerID, which predicts molecular fingerprints and searches against the biological (bio) structure database; results are reported both as standard structure identifications and as ChEBI-mapped structure identifications (Hoffmann et al., 2022). *De novo* structure generation was additionally carried out using MSNovelist for features lacking database matches (Stravs et al., 2022). 

Chemical class prediction was performed using CANOPUS, which assigns ClassyFire and NP Classifier ontology classes based on the predicted molecular fingerprint, independently of any database match (Dührkop et al., 2021). Spectral library matching was additionally performed within the SIRIUS environment against all biological databases available on the platform. 

#### *Molceular Network Visualization and Annotation (Cytoscape)*
The Feature-Based Molecular Network generated on GNPS2 was imported into Cytoscape 3.10.4 for visualization and annotation (Shannon et al., 2003). The network was imported in GraphML format and includes both clustered features and singletons. Annotations from multiple sources: GNPS spectral library matching, ISDB *in silico* spectral matching (with taxonomic consistency scoring), and SIRIUS/CSI:FingerID/CANOPUS were consolidated using the met_annot_enhancer workflow and mapped onto network nodes as attributes (Allard et al., 2016; Rutz et al., 2019). Node attributes include putative compound names, SMILES structures, NP Classifier pathway/superclass/class assignments, ClassyFire ontology levels, and per-sample group feature intensities for all five experimental groups (wild-type R47, *pvdE*, *phzC*, 1F12, and LB medium control). Molecular structures of annotated features of interest were visualized directly on the network using the ChemViz2 plugin.

#### *Statistical Analysis and Data Visualization*
Statistical analysis and visualization were performed using the MAPP (Metabolomics Analysis and Plotting Pipeline) R-based workflow, implemented via the MAPPstructToolbox package. Prior to analysis, features were filtered to remove those present in the LB medium blank at a fold-change below 10, retaining only features detected in fewer than 100% of blank replicates. QC and blank samples were then excluded, retaining only biological samples for downstream analysis. The feature intensity matrix was normalized using Pareto scaling, followed by vector normalization and mean centering prior to ordination analyses. The statistical analysis was performed on the non-gap-filled feature table. 

Multivariate analyses included Principal Component Analysis (PCA) and Principal Coordinate Analysis (PCoA), both computed on three components, with missing values imputed using k-nearest neighbors (k = 5) prior to ordination. Partial Least Squares Discriminant Analysis (PLS-DA) was additionally performed to identify features contributing most to group separation, with Variable Importance in Projection (VIP) scores reported. A permuted Random Forest classification model was also run to assess feature importance using a mean decrease in the Gini index. 

Pairwise differential analysis between all strain combinations was performed using Honest Significant Difference with Error Model (HSDEM), without multiple testing correction, at a significance threshold of p < 0.05. Fold-changes were calculated as the ratio of group means and expressed as log2-transformed values for visualization. Results were displayed as volcano plots annotated with chemical class information derived from CANOPUS (NP Classifier pathway, superclass, and class) and SIRIUS/CSI:FingerID (ChEBI compound names). Boxplots were generated for the 16 features displaying the greatest differential abundance. A p-value heatmap was additionally produced to provide an overview of inter-group differences across the full feature set. 

All statistical outputs were subsequently mapped onto the molecular network in Cytoscape to integrate chemical annotation with differential abundance data. The GNPS2 molecular networking task ID is: 4392c1c13e394c7a8a720f3e3d10883d. All analyses were performed in R version 4.2.2 (2022-10-31), using the MAPPstructToolbox package (v1.9.1), structToolbox (v1.19.2), struct (v1.10.0), pmp (v1.10.0), pls (v2.8-3), rfPermute (v2.5.2), vegan (v2.7-3), ggplot2 (v3.5.2), and plotly (v4.10.4) (R Core Team, 2022). 

## Results and Discussion
Preliminary inspection of Total Ion Chromatograms (TICs) confirmed low background signal in the solvent blank (Figure 2), validating the cleanliness of the analytical system. The LB medium control displayed numerous peaks in the early retention time window (Figure 2), consistent with the presence of polar medium-derived compounds.  

<p align="center">
  <img src="https://github.com/user-attachments/assets/2013e39e-83ea-491c-856e-05226b689391" alt="Total Ion Chromatogram (TIC) overlay of the LB medium control (orange) and solvent blank (dark blue), showing the high signal intensity and complexity of the culture medium across the 0–5 min retention time window, and the near-baseline signal of the blank, confirming minimal background contamination of the analytical system."/>
</p>
<p align="center"><b>Figure 2</b>: Total Ion Chromatogram (TIC) overlay of the LB medium control (orange) and solvent blank (dark blue), showing the high signal intensity and complexity of the culture medium across the 0–5 min retention time window, and the near-baseline signal of the blank, confirming minimal background contamination of the analytical system. 

QC chromatograms showed strong overlap across injections (Figure 3), confirming instrument stability throughout the run.

<p align="center">
  <img src="https://github.com/user-attachments/assets/40f538d3-7a5f-43a6-b02b-3bd74e4af713" alt="TIC overlay of the six pooled Quality Control (QC) injections, showing strong chromatographic reproducibility across the analytical sequence, with consistent peak shapes and intensities, confirming stable instrument performance throughout the run."/>
</p>
<p align="center"><b>Figure 3</b>: TIC overlay of the six pooled Quality Control (QC) injections, showing strong chromatographic reproducibility across the analytical sequence, with consistent peak shapes and intensities, confirming stable instrument performance throughout the run. 

Overlay of all biological samples (Figure 4) revealed that a substantial proportion of detected features are shared across groups, with many attributable to the LB medium.

<p align="center">
  <img src="https://github.com/user-attachments/assets/8c9537ac-7cf0-4761-8d3b-689da9500009" alt="TIC overlay of all samples, including biological replicates of all four strains, QC samples, LB medium control, and solvent blank, showing the overall complexity of the dataset and the predominance of medium-derived signals across groups, with the LB medium control (orange) largely overlapping with the biological samples in the early retention time window. "/>
</p>
<p align="center"><b>Figure 4</b>: TIC overlay of all samples, including biological replicates of all four strains, QC samples, LB medium control, and solvent blank, showing the overall complexity of the dataset and the predominance of medium-derived signals across groups, with the LB medium control (orange) largely overlapping with the biological samples in the early retention time window. 

Targeted extraction of the ion corresponding to phenazine-1-carboxylic acid (C₁₃H₈N₂O₂) (Figure 5) revealed a peak consistently present in wild-type R47 and reduced or absent in the *phzC* mutant, consistent with the expected loss of phenazine biosynthesis.

<p align="center">
  <img src="https://github.com/user-attachments/assets/3ba7f584-f491-40bd-bb01-f55a2597baf4" alt="Extracted Ion Chromatogram (XIC) of the ion at m/z 225.0558, corresponding to the [M+H]⁺ adduct of phenazine-1-carboxylic acid (C₁₃H₈N₂O₂), showing a dominant peak at approximately 4.65 min exclusively in wild-type R47 replicates, with near-baseline signal across all other strains, the LB medium control, and the solvent blank. "/>
</p>
<p align="center"><b>Figure 5</b>: Extracted Ion Chromatogram (XIC) of the ion at <i>m/z</i> 225.0558, corresponding to the [M+H]⁺ adduct of phenazine-1-carboxylic acid (C₁₃H₈N₂O₂), showing a dominant peak at approximately 4.65 min exclusively in wild-type R47 replicates, with near-baseline signal across all other strains, the LB medium control, and the solvent blank. 

### Comparison Between Wild-type R47 and Its Different Mutants
#### *Metabolites Detected in the Culture Medium*
Prior to statistical analysis, features were filtered to retain only those exceeding a 10-fold abundance threshold relative to the LB medium blank, ensuring that subsequent comparisons reflect compounds of bacterial origin rather than medium- or solvent-derived background signals. Abundance variations of metabolites already present in the medium may reflect differential uptake or consumption rather than bacterial production. These data may be investigated in future analyses to determine whether the different strains exhibit distinct nutrient use. 

#### *General Comparison*
The PCA generated from the metabolomic data (Figure 6) revealed a clear separation between strain 1F12 and the other strains. Principal Component 1 (PC1), which explained 75.7% of the observed variability, clustered the *phzC*, *pvdE*, and wild-type R47 strains together, whereas 1F12 formed a distinct group. Principal Component 2 (PC2), accounting for 7% of the total variance, reflected differences among the 1F12 biological replicates, which displayed a more heterogeneous metabolic profile compared to the other strain strains. 

<p align="center">
  <img width="50%" src="https://github.com/user-attachments/assets/5a99505a-1087-417d-8221-97b03b4a16cd" alt="Principal Component Analysis (PCA) showing the distribution of samples from the 1F12, phzC, pvdE, and wild-type R47 groups after data scaling. The plot demonstrates a clear metabolomic separation of the 1F12 mutant along a Principal Component 1 (75.7% of explained variance), while the wild-type and the phzC and pvdE mutants cluster closely together. "/>
</p>
<p align="center"><b>Figure 6</b>: Principal Component Analysis (PCA) showing the distribution of samples from the 1F12, <i>phzC</i>, <i>pvdE</i>, and wild-type R47 groups after data scaling. The plot demonstrates a clear metabolomic separation of the 1F12 mutant along a Principal Component 1 (75.7% of explained variance), while the wild-type and the <i>phzC</i> and <i>pvdE</i> mutants cluster closely together. 

Based on these results, we mainly focused our subsequent analyses on comparisons between strain 1F12 and the parental strain wild-type R47 rather than performing separate comparisons between 1F12 and each of the other mutants, since the PCA suggested that the metabolomic profiles of the *phzC* and *pvdE* mutants were highly similar to that of wild-type R47. In addition, we investigated the more subtle differences between wild-type R47 and its *phzC* and *pvdE* mutants. These comparisons were performed first because they involved fewer differences and were therefore easier to interpret. Furthermore, we expected that at least some of the metabolic differences observed between wild-type R47 and these mutants would also be reflected in the comparison between wild-type R47 and 1F12. 

### The Principal Difference Between the Wild-type R47 and the *phzC* Mutant Exometabolomes is Phenazine Content
#### *Features Enriched in the Wild-type R47*
We first investigated four compounds that were significantly more abundant in the *P. chlororaphis* wild-type R47 strain than in the *phzC* mutant (highlighted in red in Figure 7).

<p align="center">
  <img width="50%" src="https://github.com/user-attachments/assets/a08c8fb5-8937-4cee-a561-346ad0ac68dd" alt="Volcano plot showing significantly differentially abundant features between wild-type R47 and phzC, following data scaling, with CANOPUS class annotations. The four phenazine-related compounds significantly enriched in the wild-type are highlighted in red. "/>
</p>
<p align="center"><b>Figure 7</b>: Volcano plot showing significantly differentially abundant features between wild-type R47 and phzC, following data scaling, with CANOPUS class annotations. The four phenazine-related compounds significantly enriched in the wild-type are highlighted in red.  

One of these compounds was identified as phenazine-1-carboxylic acid and is the only differentially abundant compound between the tested strains with a match in the ChEBI database. It is also known to be the major phenazine produced by *Pseudomonas chlororaphis* R47 (Anand et al., 2023). A second compound clustered with it in the molecular network (Figure 8), differing by an *m/z* value of 18.01; this corresponds to the addition of a water molecule. These compounds were connected to two additional features that were present at similar abundances in all strains. Although these latter compounds could not be confidently identified, their predicted structures suggested the presence of a carboxylic acid functional group.

<p align="center">
  <img src="https://github.com/user-attachments/assets/46650bce-0acf-4ee6-bef6-513bb18e04e6" alt="Molecular network cluster containing phenazine-1-carboxylic acid (node highlighted in yellow, left) and its corresponding chemical structure (right), as visualized in Cytoscape using the ChemViz2 plugin. The central node corresponds to the feature at m/z 225.0558.  "/>
</p>
<p align="center"><b>Figure 8</b>: Molecular network cluster containing phenazine-1-carboxylic acid (node highlighted in yellow, left) and its corresponding chemical structure (right), as visualized in Cytoscape using the ChemViz2 plugin. The central node corresponds to the feature at <i>m/z</i> 225.0558. 

The third compound was classified as an amino acid derivative by CANOPUS during the volcano plot analysis (Figure 7). However, both the proposed class and structure were assigned with low confidence scores (0.73 and 0.023, respectively). Because this feature exhibited the same retention time as phenazine-1-carboxylic acid and its *m/z* differed by a value consistent with the addition of H₃O+, we hypothesize that it may correspond to the same metabolite detected as a different ion species or adduct. 

Similarly, the fourth compound was classified by CANOPUS as a phenazine alkaloid with a high confidence score (0.96). Although SIRIUS proposed a structural annotation with only moderate confidence (0.52), the combination of its putative chemical class from CANOPUS, its *m/z* value, and the known phenazine profile of R47 strongly suggested that this feature corresponds to 1-hydroxyphenazine. This metabolite is a known phenazine produced by R47, although typically at lower levels than phenazine-1-carboxylic acid (Anand et al., 2023). 

The observed color change between the orange wild-type R47 and the beige *phzC* mutant when grown on LB plates (unpublished personal data) also supports the conclusion that both the yellow phenazine-1-carboxylic acid and the reddish 1-hydroxyphenazine are less abundant in the mutant.

#### *Features Enriched in the phzC Mutant*
Simple indole alkaloids (recognized as such by CANOPUS), colored in light blue in Figure 7, were more abundant in the *phzC* mutant culture medium than in wild-type R47. The two corresponding features belonged to the same molecular network cluster, suggesting a close structural relationship. 

The first feature, 1189_239.06_2.8, was annotated either as (E)-3-(4-chloro-1H-indol-3-yl)prop-2-enoic acid by SIRIUS (65% confidence) or as (2S)-2-amino-3-[(3R)-4-chloro-3H-indol-3-yl]propanoic acid by ISDB. This feature was detected at higher levels in the *phzC* mutant than in wild-type R47 (175%). Interestingly, it was not detected in the 1F12 mutant, despite this strain also being deficient in phenazine production. The second feature, 1190_222.03_2.8, was tentatively annotated as 3-(5-chloro-1H-indol-2-yl)-2-hydroxypropanoic acid by SIRIUS, although the confidence score was low (28%). The biological significance of the increased abundance of these indole alkaloids specifically in the *phzC* but not in the 1F12 mutant remains unclear. It suggests that their presence in the medium may not be solely linked to the absence of phenazine and could instead reflect a more specific metabolic consequence of the *phzC* mutation. 

### *pvdE* Mutant Exometabolome Differs Little from Wild-type R47 with Only Few Features Enriched
Only a small number of metabolites differed significantly between wild-type R47 and the *pvdE* mutant, confirming the overall similarity of their metabolomic profiles, as visually demonstrated by the scarcity of differential features in the volcano plot (Figure 9).

<p align="center">
  <img width="50%" src="https://github.com/user-attachments/assets/5a7c0684-520a-4bf9-a95d-ccffb832b3d3" alt="Volcano plot showing significantly differentially abundant features between wild-type R47 and pvdE, following data scaling. The plot visually confirms the small number of significantly altered metabolites, reflecting the overall metabolic similarity between the two strains. "/>
</p>
<p align="center"><b>Figure 9</b>: Volcano plot showing significantly differentially abundant features between wild-type R47 and <i>pvdE</i>, following data scaling. The plot visually confirms the small number of significantly altered metabolites, reflecting the overall metabolic similarity between the two strains. 

#### *Features Enriched in the pvdE Mutant*
Five compounds were detected at a significantly higher abundance in the *pvdE* mutant than in wild-type R47. Three of these compounds eluted late on the reverse-phase column (retention times of 7–7.5 min), suggesting they are apolar in nature. CANOPUS classified one of these features as a fatty acyl and another as an unsaturated fatty acid, both with high confidence scores (0.97). However, attempts to identify these compounds using different databases were inconclusive as the proposed annotations differed depending on the database consulted, and one feature did not produce any match.
Two of these features, 2030_280.26_7 and 2052_296.26_7.5, were also more abundant in the 1F12 mutants than in the wild-type R47.

The remaining two compounds enriched in the *pvdE* mutant were classified as peptides. Their database matches yielded very low confidence scores, preventing reliable identification. One of them, feature 603_568.22_1.7, was also detected at lower levels in the 1F12 mutant compared with wild-type R47.

#### *A Single Putative Peptide is Enriched in Wild-type R47*
Only one compound was found at a significantly lower abundance in the *pvdE* mutant than in wild-type R47. SIRIUS tentatively annotated this feature as the peptide H-DL-xiThr-DL-Pro-DL-xiIle-DL-Leu-OH, although the confidence score was low (36%). As no high-confidence annotation could be obtained, the identity and biological significance of this metabolite remain uncertain.

### The 1F12 Mutant Shows Broad Loss of Secondary Metabolite Production Compared to Wild-type R47
Consistent with the PCA analysis, which showed a clear separation between 1F12 and the other strains, the comparison between wild-type R47 and the 1F12 mutant revealed substantially more differences than the wild-type R47 comparisons with the *phzC* and *pvdE* mutants — as might be expected for a mutant in a master regulator affecting a broad range of metabolic pathways (Biessy & Filion, 2018; D. Wang et al., 2013).

<p align="center">
  <img width="50%" src="https://github.com/user-attachments/assets/08868bdc-50d6-4c13-b499-56d721c053dc" alt="Volcano plot showing significantly differentially abundant features between wild-type R47 and 1F12, following data scaling. In the features that are the more present in the wild-type R47, the features in the same color are part of the same molecular cluster. "/>
</p>
<p align="center"><b>Figure 10</b>: Volcano plot showing significantly differentially abundant features between wild-type R47 and 1F12, following data scaling. In the features that are the more present in the wild-type R47, the features in the same color are part of the same molecular cluster. 

#### *Phenazines and Oligopeptide Clusters Are the Primary Features Lost in the 1F12 Mutant*
Metabolites specifically produced by wild-type R47 and absent or present at reduced levels in the 1F12 mutant were prioritized, with particular attention given to compounds displaying the largest abundance differences and grouping within molecular network clusters.

#### *Phenazines*
The four compounds previously identified as phenazine derivatives and already found to be less abundant in the *phzC* mutant were also among the most discriminant metabolites between wild-type R47 and 1F12. They are displayed in orange in Figure 10. None of these compounds were detected in the 1F12 culture medium, consistent with the observed change in color when grown on LB plates indicating a loss of phenazine production in this mutant.

#### *Clustered Peptides*
Four olidopeptide-related features formed a distinct molecular cluster presented in (Figure 11) and were completely absent from the 1F12 metabolome. They are displayed in pink in Figure 10. Three of these features shared a similar retention time of approximately 3.9 min and:

- Feature 1797_492.28_3.9 was classified by CANOPUS as a cyclic peptide with a confidence score of 0.87.
- Feature 1796_983.56_3.9 was annotated as Suzukacillin B through comparison with the GNPS database. This antibacterial This peptaibol, originally isolated from fungal species of the genus Trichoderma (Ooka and Takeda, 1972), has not been reported in bacteria, which suggest a false positive match. Interestingly, its *m/z* value is twice that of feature 1797_492.28_3.9 suggesting that one feature may correspond to a dimeric ion, a different ionization state, or a related molecular species.
- Feature 1793_492.78_3.9 could not be annotated using any of the databases consulted.

These three features emerged as some of the most significant differential metabolites in our statistical analysis. As illustrated by their abundance distributions (Figure 12), these oligopeptide-related compounds remain highly expressed in wild-type R47 as well as the *phzC* and *pvdE* mutants but were not detected in the 1F12 mutant.

<p align="center">
  <img height="25%" width="25%" src="https://github.com/user-attachments/assets/505eec65-333d-43cb-9dd6-7dae9204f93f" alt="Molecular cluster containing the features 1797_492.28_3.9, 1796_983.56_3.9, and 1793_492.78_3.9. These features were enriched in wild-type R47 but completely absent from the 1F12 mutant metabolome."/>
</p>
<p align="center"><b>Figure 11</b>: Molecular cluster containing the features 1797_492.28_3.9, 1796_983.56_3.9, and 1793_492.78_3.9. These features were enriched in wild-type R47 but completely absent from the 1F12 mutant metabolome. 

<p align="center">
  <img src="https://github.com/user-attachments/assets/df51399e-590a-4669-945f-7c85f9543281" alt="Box plots showing the abundance distribution of features 1796_983.56_3.9, 1797_492.28_3.9, and 1793_492.78_3.9 across the different experimental groups (1F12, phzC, pvdE and wild-type R47). The plots visually confirm that these oligopeptide-related compounds are completely absent in the 1F12 mutant, while remaining highly abundant in the wild-type R47 and other mutant strains. "/>
</p>
<p align="center"><b>Figure 12</b>: Box plots showing the abundance distribution of features 1796_983.56_3.9, 1797_492.28_3.9, and 1793_492.78_3.9 across the different experimental groups (1F12, <i>phzC</i>, <i>pvdE</i> and wild-type R47). The plots visually confirm that these oligopeptide-related compounds are completely absent in the 1F12 mutant, while remaining highly abundant in the wild-type R47 and other mutant strains. 

Feature 1297_836.49_3 was annotated by SIRIUS as the peptide 3QFD (H-Ala-Ala-Gly-Ile-Gly-Ile-Leu-Thr-Val-OH) with a confidence score of 0.823. This peptide corresponds to a complex involving the human MHC class I protein HLA-A2 and the MART-1(27–35) peptide. Despite the high confidence score, this annotation is biologically implausible in the context of a bacterial culture and should therefore be considered an artifact of database matching rather than a true identification. Contamination with a human peptide was also considered; however, a random contamination event would not perfectly segregate by bacterial genotype. Because this feature is consistently detected across all biological replicates of wild-type R47 and the *phzC* and *pvdE* mutants, perfectly co-occurs with the other bacterial peptides in its molecular network cluster, and is completely absent from all four 1F12 replicates and the LB medium control, it is highly likely a true bacterial metabolite that shares spectral similarity with the human peptide, leading to a false-positive database match.

#### *Second Cluster*
Features 1349_390.73_3.1 and 1348_780.46_3.1, shown in red in Figure 10, are also present in 1F12 and cluster together (Figure 13). Although neither compound could be confidently identified, their molecular masses suggest that one feature may correspond to a dimeric form of the other. 

<p align="center">
  <img height="40%" width="40%" src="https://github.com/user-attachments/assets/d4a75a47-f5e0-4325-ad8f-f50e5b87347b" alt="Molecular cluster containing the features 1349_390.73_3.1 and 1348_780.46_3.1(circled in red). These features were detected in both wild-type R47 and the1F12 mutant, with their molecular masses suggesting a potential monomer-dimer relationship. "/>
</p>
<p align="center"><b>Figure 13</b>: Molecular cluster containing the features 1349_390.73_3.1 and 1348_780.46_3.1(circled in red). These features were detected in both wild-type R47 and the1F12 mutant, with their molecular masses suggesting a potential monomer-dimer relationship. 

#### *Cyclic Peptides and Depsipeptides*
Three additional oligopeptides belonging to the same molecular cluster (see Figure 14) were detected at much lower abundance in 1F12 than in wild-type R47. Feature 1308_540.34_3 was tentatively annotated as Syringolin D based on *in silico* spectral database (ISDB) comparison. It is a cyclic peptide originally described in Pseudomonas syringae pv. syringae, where it acts as a virulence factor (Wäspi et al. 1999). Feature 1329_654.38_3 was tentatively annotated by SIRIUS as desmethylisaridin G, a cyclohexadepsipeptide belonging to the isaridin family. This annotation should be interpreted cautiously because the confidence score was only approximately 42%. Desmethylisaridin G was isolated from entomopathogenic fungi of the genus Isaria and has been reported to possess antibacterial activity (Du et al., 2014). As it is not known in bacteria, the match is probably a false positive. 

<p align="center">
  <img height="60%" width="60%" src="https://github.com/user-attachments/assets/1bba81b7-cdb0-4342-933b-2afe6505bea7" alt=" Molecular cluster containing the features 1329_654.38_3 and 1308_540.34_3 (circled in red). These features, tentatively annotated as Desmethylisaridin G and Syringolin D respectively, were detected at a lower abundance in the 1F12 mutant than in wild-type R47. "/>
</p>
<p align="center"><b>Figure 14</b>: Molecular cluster containing the features 1329_654.38_3 and 1308_540.34_3 (circled in red). These features, tentatively annotated as Desmethylisaridin G and Syringolin D respectively, were detected at a lower abundance in the 1F12 mutant than in wild-type R47.  

Numerous additional metabolites were significantly less abundant in the 1F12 mutant but were not associated with molecular clusters. Among these, feature 250_409.13_1 received one of the highest confidence annotations. SIRIUS identified it as the tripeptide (S)-pyroglutamyl-(S)-glutamyl-(S)-glutamine with a confidence score of 0.982. This compound is not known for a specific bioactivity.

#### *Features Enriched in the 1F12 Mutant*
We next examined compounds that were more abundant in the 1F12 mutant than in wild-type R47. A substantial proportion of these metabolites were classified by CANOPUS as peptides, while three were classified as alkaloids, one as a carbohydrate, and one as a fatty acyl. Most of these compounds did not belong to any major molecular cluster.

Four metabolites received high-confidence structural annotations from SIRIUS (with confidence scores exceeding 0.9). Two were peptide-related compounds, including H-Val-Leu-Asp-Pro-Lys-OH, while another was identified as anthranilate. One alkaloid, kynurenate, was also assigned with high confidence.
The enrichment of these metabolites in the mutant further supports the extensive metabolic changes associated with the loss of biocontrol activity.

Interestingly, the fatty acyl detected among the metabolites enriched in 1F12 corresponded to one of the apolar compounds previously found to be more abundant in the *pvdE* mutant than in wild-type R47. As the 1F12 mutant is also deficient in pyoverdine production, this suggests a link between the abundance of this metabolite and pyoverdine biosynthesis.

## Conclusion
This metabolomic analysis highlighted clear differences between the wild-type R47 strain and its mutant derivatives. The comparison of extracellular metabolites revealed that the *phzC* and *pvdE* mutants remained highly similar to the parental strain wild-type R47, whereas the 1F12 mutant displayed a markedly different metabolic profile.

The limited number of metabolite changes observed in the *phzC* and *pvdE* mutants indicates that the mutagenesis strategy was highly specific. In the *phzC* mutant, the most significant differences were related to phenazine production, with a strong reduction in phenazine-derived metabolites and only a small number of additional metabolic changes. These minor secondary alterations, such as the accumulation of specific indole alkaloids, reflect a redirection of metabolic flux due to the blocked phenazine pathway rather than off-target genetic defects. Similarly, disruption of *pvdE( resulted in few alterations in the exometabolome. These observations suggest that the targeted mutations had minimal unintended effects on the overall metabolism of the strain, confirming the high specificity associated with the pEMG/I-Scel mutagenesis system (Martínez-García & Lorenzo, 2011). Furthermore, the highly conserved exometabolome of the *pvdE* mutant perfectly aligns with recent bioassay findings that pyoverdine plays only a minor, strain-specific role in the *in vitro* inhibition of *P. infestans* by strain R47 (Jerjen, L'Haridon & Weisskopf, 2026).

In contrast, the 1F12 mutant showed extensive metabolic reprogramming, consistent with the broad regulatory role of the Gac system, which controls secondary metabolism post-transcriptionally via the Rsm (repressor of secondary metabolism) signal transduction pathway (Wang et al., 2013). Numerous metabolites, particularly peptide-like compounds and phenazine-related metabolites, were either absent or strongly reduced in this mutant. However, the substantial number of metabolic differences identified makes it difficult to pinpoint a single metabolite or metabolic pathway responsible for the reduced anti-Phytophthora activity previously observed in this strain. Instead, the phenotype is the result of multiple coordinated changes affecting secondary metabolism. This aligns with the established understanding that bacterial biocontrol often relies on the synergistic action of multiple secondary metabolites. For example, it has been demonstrated that cyclic lipopeptides and phenazine compounds can act in synergy to effectively suppress plant diseases (Biessy & Filion, 2018). Furthermore, because LC-MS analysis captures only the soluble exometabolome, it does not account for volatile organic compounds like hydrogen cyanide, which are also regulated by the Gac system and contribute heavily to the antagonistic activity of *P. chlororaphis* R47 (Anand et al., 2020; Hunziker et al., 2015). Therefore, the 1F12 phenotype is the result of a massive loss of both soluble and volatile synergistic weapons.

A major limitation of this study was the use of LB medium, a nutrient-rich growth medium that contains many compounds capable of generating background signals in metabolomic analyses. Future experiments performed in a nutrient-poor or chemically defined medium, or during direct co-cultivation with *P. infestans*, could reduce this background noise and promote the production of specialized metabolites that are only triggered during active microbial interactions. Such conditions would facilitate metabolite identification and provide a clearer understanding of the metabolic mechanisms underlying the biological differences between these strains. However, this background noise also presents an unexplored opportunity; future mining of this dataset could investigate the abundance variations of LB-derived compounds to determine if these mutant strains exhibit distinct nutrient uptake profiles. Additionally, further targeted data mining could explore whether any of the unannotated features altered in the 1F12 mutant correspond to quorum-sensing molecules, such as N-acyl-homoserine lactones (AHLs), which are heavily linked to Gac regulation and biofilm formation (Wang et al., 2013). 

This functional profiling complements recent genomic mining of *P. chlororaphis* R47 (De Vrieze et al., 2020), bridging predicted biosynthetic potential and actual chemical expression. Further work combining metabolomics with bioactivity assays and metabolite purification will be needed to pinpoint the specific compounds — such as the oligopeptide clusters absent in 1F12 and the apolar features linked to pyoverdine deficiency — responsible for the antagonistic activity against *P. infestans*. Identifying these molecules will support the development of sustainable biocontrol alternatives to the synthetic and copper-based fungicides currently used against potato late blight (Guyer et al., 2015).

## References 
[1] Allard, P.-M., Péresse, T., Bisson, J., Gindro, K., Marcourt, L., Pham, V. C., Roussi, F., Litaudon, M., & Wolfender, J.-L. (2016). Integration of Molecular Networking and *In-Silico* MS/MS Fragmentation for Natural Products Dereplication. *Analytical Chemistry*, 88(6), 3317–3323.

[2] Anand, A., Chinchilla, D., Tan, C., Mène-Saffrané, L., L’Haridon, F., & Weisskopf, L. (2020). Contribution of Hydrogen Cyanide to the Antagonistic Activity of *Pseudomonas* Strains Against *Phytophthora infestans*. *Microorganisms*, 8(8), 1144.

[3] Biessy, A., & Filion, M. (2018). Phenazines in plant‐beneficial *Pseudomonas spp.*: Biosynthesis, regulation, function and genomics. *Environmental Microbiology*, 20(11), 3905-3917.

[4] Anand, A., Falquet, L., Abou-Mansour, E., L'Haridon, F., Keel, C., & Weisskopf, L. (2023). Biological hydrogen cyanide emission globally impacts the physiology of both HCN-emitting and HCN-perceiving *Pseudomonas*. *Bacteriology*, 14(5), e00857-23

[5] De Vrieze, M., Varadarajan, A. R., Schneeberger, K., Bailly, A., Rohr, R. P., Ahrens, C. H., & Weisskopf, L. (2020). Linking Comparative Genomics of Nine Potato-Associated *Pseudomonas* Isolates With Their Differing Biocontrol Potential Against Late Blight. *Frontiers in Microbiology*, 11. 

[6] Du, F.-Y., Zhang, P., Li, X.-M., Li, C.-S., Cui, C.-M., & Wang, B.-G. (2014). Cyclohexadepsipeptides of the Isaridin Class from the Marine-Derived Fungus *Beauveria felina* EN-135. *Journal of Natural Products*, 77(5), 1164–1169.

[7] Dührkop, K., Fleischauer, M., Ludwig, M., Aksenov, A. A., Melnik, A. V., Meusel, M., Dorrestein, P. C., Rousu, J., & Böcker, S. (2019). SIRIUS 4: A rapid tool for turning tandem mass spectra into metabolite structure information. *Nature Methods*, 16(4), 299–302.

[8] Dührkop, K., Nothias, L.-F., Fleischauer, M., Reher, R., Ludwig, M., Hoffmann, M. A., Petras, D., Gerwick, W. H., Rousu, J., Dorrestein, P. C., & Böcker, S. (2021). Systematic classification of unknown metabolites using high-resolution fragmentation mass spectra. *Nature Biotechnology*, 39(4), 462–471.

[9] Guyer, A., De Vrieze, M., Bönisch, D., Gloor, R., Musa, T., Bodenhausen, N., Bailly, A., & Weisskopf, L. (2015). The Anti-*Phytophthora* Effect of Selected Potato-Associated *Pseudomonas* Strains: From the Laboratory to the Field. *Frontiers in Microbiology*, 6. 

[10] Hoffmann, M. A., Nothias, L.-F., Ludwig, M., Fleischauer, M., Gentry, E. C., Witting, M., Dorrestein, P. C., Dührkop, K., & Böcker, S. (2022). High-confidence structural annotation of metabolites absent from spectral libraries. *Nature Biotechnology*, 40(3), 411–421. 

[11] Hunziker, L., Bönisch, D., Groenhagen, U., Bailly, A., Schulz, S., & Weisskopf, L. (2015). *Pseudomonas* Strains Naturally Associated with Potato Plants Produce Volatiles with High Potential for Inhibition of *Phytophthora infestans*. *Applied and Environmental Microbiology*, 81(3), 821–830. 

[12] Jerjen, L., L’Haridon, F., & Weisskopf, L. (in press). Pyoverdine Plays Only a Minor, Strain‐Specific Role in the Inhibition of *Phytophthora infestans* by *Pseudomonas* Strains. *MicrobiologyOpen*.

[13] Martínez-García, E., & Lorenzo, V. de. (2011). Engineering multiple genomic deletions in Gram‐negative bacteria: Analysis of the multi‐resistant antibiotic profile of *Pseudomonas putida* KT2440. *Environmental Microbiology*, 13(10), 2702-2716.

[14] Nothias, L.-F., Petras, D., Schmid, R., Dührkop, K., Rainer, J., Sarvepalli, A., Protsyuk, I., Ernst, M., Tsugawa, H., Fleischauer, M., Aicheler, F., Aksenov, A. A., Alka, O., Allard, P.-M., Barsch, A., Cachet, X., Caraballo-Rodriguez, A. M., Da Silva, R. R., Dang, T., … Dorrestein, P. C. (2020). Feature-based molecular networking in the GNPS analysis environment. *Nature Methods*, 17(9), 905–908. 

[15] Ooka, T., & Takeda, I. (1972). Studies of the Peptide Antibiotic Suzukacillin: Part II. *Agricultural and Biological Chemistry*, 36(1), 112–119. 

[16] R: The R Project for Statistical Computing. (2022). Retrieved June 6, 2026, from https://www.r-project.org/

[17] Rutz, A., Dounoue-Kubo, M., Ollivier, S., Bisson, J., Bagheri, M., Saesong, T., Ebrahimi, S. N., Ingkaninan, K., Wolfender, J.-L., & Allard, P.-M. (2019). Taxonomically Informed Scoring Enhances Confidence in Natural Products Annotation. *Frontiers in Plant Science*, 10. 

[18] Schmid, R., Heuckeroth, S., Korf, A., Smirnov, A., Myers, O., Dyrlund, T. S., Bushuiev, R., Murray, K. J., Hoffmann, N., Lu, M., Sarvepalli, A., Zhang, Z., Fleischauer, M., Dührkop, K., Wesner, M., Hoogstra, S. J., Rudt, E., Mokshyna, O., Brungs, C., … Pluskal, T. (2023). Integrative analysis of multimodal mass spectrometry data in MZmine 3. *Nature Biotechnology*, 41(4), 447–449.

[19] Shannon, P., Markiel, A., Ozier, O., Baliga, N. S., Wang, J. T., Ramage, D., Amin, N., Schwikowski, B., & Ideker, T. (2003). Cytoscape: A Software Environment for Integrated Models of Biomolecular Interaction Networks. *Genome Research*, 13(11), 2498–2504. 

[20] Stravs, M. A., Dührkop, K., Böcker, S., & Zamboni, N. (2022). MSNovelist: De novo structure generation from mass spectra. *Nature Method*s, 19(7), 865–870.

[21] Wang, D., Lee, S.-H., Seeve, C., Yu, J. M., Pierson, L. S., & Pierson, E. A. (2013). Roles of the Gac‐Rsm pathway in the regulation of phenazine biosynthesis in *Pseudomonas chlororaphis* 30‐84. *MicrobiologyOpen*, 2(3), 505-524.

[22] Wang, M., Carver, J. J., Phelan, V. V., Sanchez, L. M., Garg, N., Peng, Y., Nguyen, D. D., Watrous, J., Kapono, C. A., Luzzatto-Knaan, T., Porto, C., Bouslimani, A., Melnik, A. V., Meehan, M. J., Liu, W.-T., Crüsemann, M., Boudreau, P. D., Esquenazi, E., Sandoval-Calderón, M., … Bandeira, N. (2016). Sharing and community curation of mass spectrometry data with Global Natural Products Social Molecular Networking. *Nature Biotechnology*, 34(8), 828–837. 

[23] Wäspi, U., Hassa, P., Staempfli, A. A., Molleyres, L.-P., Winkler, T., & Dudler, R. (1999). Identification and structure of a family of syringolin variants: Unusual cyclic peptides from *Pseudomonas syringae* pv. *syringae* that elicit defense responses in rice. *Microbiological Research*, 154(1), 89–93.

[24] Yeterian, E., Martin, L. W., Guillon, L., Journet, L., Lamont, I. L., & Schalk, I. J. (2010). Synthesis of the siderophore pyoverdine in *Pseudomonas aeruginosa* involves a periplasmic maturation. *Amino Acids*, 38(5), 1447–1459.
