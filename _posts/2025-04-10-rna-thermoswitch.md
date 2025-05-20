---
title: 'RNA Thermoswitch'
date: 2025-04-10
permalink: /posts/papers/rna-thermoswitch
tags:
  - Molecular Biology
  - RNA
---

Review on a paper about RNA thermoswitch from Nature Plants.

# [**An RNA thermoswitch regulates daytime growth in _Arabidopsis_**](https://www.nature.com/articles/s41477-020-0633-3)

## Summary
- Translation of transcripts encoding PIF7 increases in response to warmer temperature.
- Diurnal expression of *PIF7* transcript gates the response → PIF7 protein quickly accumulates.
- Enhanced PIF7 protein levels directly activate the thermomorphogenesis pathway, and are necessary for thermomorphogenesis to occur under warm cycling daytime temperatures.
- Translation enhancement of PIF7 mRNA is mediated by 5’-UTR hairpin, which adopts an alternative conformation at higher temperature (increased protein synthesis).
- Similar hairpin sequences are identified in *WRKY22* and *HSFA2*.

## Results

### Figure 1: Rapid response to daytime warm temperature cycles, mirrored by changes in translational efficiency

Cycling warm temperature: 8h warm (4~12) vs constantly low temperature

- Fig. i) Ribosome profiling → translation efficiency (TE) computation
- Fig. j) GO terms (transcription factors, stress-related genes)
- Fig. k) *PIF7* transcript level is not significantly changed in response to 27$\degree$C.
- Fig. l) Representative western blot
- Fig. m) Quantification of PIF7-MYC fusion protein
    - Change in translational efficiency results in robust changes at the protein level.
- Fig. n) Quantification of PIF7-MYC transcript
    - Increase of protein level occurs independently of transcript abundance.

![image.png](/images/rna-thermoswitch/rna-thermoswitch-fig1.png)

- Seedlings grown at constant 17$\degree$C shifted to 27$\degree$C
    - Slight increase in protein level, sharp drop in transcript level.
    - Drop in transcript level probably counteracts enhanced translation.
- CHX (translation inhibitor) treatment strongly reduces PIF7-MYC levels.
    - Translational regulation indeed plays an important role in controlling PIF7 levels.
    - Effect is similar at both 17$\degree$C and 27$\degree$C → stability of PIF7 accumulated before CHX is independent of temperature.
- MG132 (proteasome inhibitor) treatment had no major effects.
    - Several other PIF TFs are highly regulated by proteasomal degradation in response to light or temperature signal.
    - MG132 only moderately increases PIF7-MYC levels when CHX treatment is applied.
    - PIF7 does not appear to be under major regulation by the proteasome.

### PIF7 is necessary for thermomorphogenesis in response to warm daytime temperature cycles

- Fig. a~c) *pif7-1* mutant shows strongly reduced hypocotyl elongation (warm daytime growth response abolished)
    - *pif4-2* mutant shows similar phenotypes, but two mutations are not additive.
    - *pif5-3* mutant shows similar phenotypes, but with smaller defect.
    - PIF5 plays a minor role in daytime temperature response, alongside PIF4 and PIF7.
- Fig. d~f) PIF7 is also required for petiole elongation & reduction in stomatal index
    - *PIF7::PIF7-MYC* transgene complements the phenotypes, confirming that the mutant phenotypes are due to lack of PIF7.

![image.png](/images/rna-thermoswitch/rna-thermoswitch-fig2.png)

### PIF7 directly activates the warm temperature transcriptome in response to daytime thermal cycles

- Fig. a) Clustering analysis reveals a set of *PIF7*-dependent genes that are also strongly induced in response to warm photocycles. Cluster 7 is particularly enriched for genes associated with auxin. The induction of this cluster by temperature is *PIF7*-dependent.
- Fig. c) 324 temperature-induced transcripts require *PIF7.*
- Fig. d) 82 genes are directly bound by PIF7, and are perturbed in *pif7-1* mutant.
    - Targets directly bound and transcriptionally perturbed in *pif7-1* are enriched for genes associated with cell elongation growth.
- Fig. e) Bound sequences are enriched with G-box motif (CACGTG)
- Fig. f) PIF7 binding to *ATHB2* promoter is increased in 27$\degree$C.
- Fig. g) PIF7 binding is increased in 27$\degree$C: the enhancement of PIF7 translation at higher temperature is necessary and sufficient to directly result in a marked up-regulation of genes controlling thermomorphogenesis.

![image.png](/images/rna-thermoswitch/rna-thermoswitch-fig3.png)

- Auxin-related genes in cluster 7 include *YUC8* and *YUC9*, which control rate-limiting steps in the biosynthesis of auxin.
- *IAA19* and *IAA29* are auxin-inducible genes that are also included in cluster 7.
    - Auxin-inducible genes are activated by the presence of auxin.
- *ATHB2* is a major regulator of photoperiod- and temperature-controlled hypocotyl elongation.
- PIF4, PIF7 ChIP-seq peaks overlap; PIF4-PIF7 and PIF7-PIF7 interactions are both observed
    - Two proteins can bind as heterodimers

### Thermosensitive hairpin structures in *HSFA2* and *PIF7* 5’-UTRs enhance translation in response to warm temperature

- Fig. a~c) 5’-UTR sequences of a subset of translationally enhanced genes have a low minimum free energy (MFE), and are predicted to form a hairpin at upstream of their AUG.
- Fig. d) DEGs with higher TE shows higher MFE of folding: AUG-proximal hairpin is not global.
- Fig. e) *HSFA2*::firefly luciferase (FLUC) fusion RNA translation.
- Fig. f) *PIF7*::FLUC fusion RNA translation.
- Fig. g) Lower CD-signal intensity measured at 210nm at 27$\degree$C: partially unfolded hairpin.
- Fig. h, i) FRET analysis to quantify *PIF7* 5’-UTR hairpin flexibility.
    - Fig. h shows that the conformational changes are reversible.
- Fig. j) Biggest fold change in PIF7-MYC protein levels between 17$\degree$C and 27$\degree$C was observed in lines with WT and reconstituted hairpin sequence.
- Fig. k, l) As opposed to 17$\degree$C, clear correlation between PIF7-MYC levels and hypocotyl length is observed in 27$\degree$C.
    - Variation in PIF7-MYC abundance in independent lines make it difficult to infer the effect of the different hairpin sequences via direct comparison.
- Fig. m~o) Fold change in *YUC8*, *IAA19*, and *IAA29* transcript levels.

![image.png](/images/rna-thermoswitch/rna-thermoswitch-fig4.png)

- Presence of an AUG-proximal hairpin appears here specifically: a reduction in MFE of folding in the 5’-UTRs of transcripts with enhanced TE at high temperature is not global.
- *HSFA2* is a well-known regulator of heat acclimation, and *WRKY22* is a gene linked to responses in temperature fluctuation.
- Responsiveness is restored when compensatory mutations are added to hairpin-disrupted RNA: it is structure rather than sequence identity that enhances temperature-dependent translation.
- PIF7 protein abundance affects thermomorphogenesis and represents a limiting factor for elongation growth at 27$\degree$C, but not at 17$\degree$C, where other pathways may restrict PIF7 (Fig. k, l).
- YUC8 and IAA19 induction was highest in lines with WT and reconstituted hairpin sequences: hairpin structure is relevant for the level of target gene induction.