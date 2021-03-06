# Supplementary data for the manuscript "Functional characterisation of the Amyotrophic Lateral Sclerosis risk locus GPX3/TNIP1"

Corresponding author f.garton@uq.edu.au 

Author list and institutions

Restuadi Restuadi<sup>1</sup>, Frederik J. Steyn<sup>2,3,8</sup>, Edor Kabashi<sup>4,5</sup>, Shyuan T. Ngo<sup>6,7,8</sup>, Fei-Fei Cheng<sup>1</sup>, Marta F. Nabais<sup>1,9</sup>, Mike J. Thompson<sup>10,11</sup>, Ting Qi<sup>1</sup>, Yang Wu<sup>1</sup>, Anjali K. Henders<sup>1</sup>, Leanne Wallace<sup>1</sup>, Chris R. Bye<sup>12</sup>, Bradley J. Turner<sup>12</sup>, Laura Ziser<sup>1</sup>, Susan Mathers<sup>13</sup>, Pamela A. McCombe<sup>3,8</sup>, Merrilee Needham<sup>14,15,16</sup>, David Schultz<sup>17</sup>, Matthew C. Kiernan<sup>18</sup>, Wouter van Rheenen<sup>19</sup>, Leonard H. van den Berg<sup>19</sup>, Jan H. Veldink<sup>19</sup>, Roel Ophoff<sup>10,11</sup>, Alexander Gusev<sup>20,21</sup>, Noah Zaitlen<sup>10,11,22,23</sup>, Allan F. McRae<sup>1</sup>, Robert D. Henderson<sup>3,6,8</sup>, Naomi R. Wray<sup>1,6</sup>, Jean Giacomotto<sup>6,24</sup>, Fleur C. Garton<sup>1</sup>*

1. Institute for Molecular Bioscience, The University of Queensland, Brisbane, QLD 4072, Australia
2. School of Biomedical Sciences, The University of Queensland, Brisbane, QLD 4072, Australia
3. Department of Neurology, Royal Brisbane and Women’s Hospital, Brisbane, QLD 4029, Australia
4. Imagine Institute, Institut National de la Santé et de la Recherche Médicale (INSERM) Unité 1163, Paris Descartes Université, 75015 Paris, France
5. Sorbonne Université, Université Pierre et Marie Curie (UPMC), Université de Paris 06, INSERM Unité 1127, Centre National de la Recherche Scientifique (CNRS) Unité Mixte de Recherche 7225, Institut du Cerveau et de la Moelle Épinière (ICM), 75013 Paris, France
6. Queensland Brain Institute, The University of Queensland, Brisbane, QLD 4072, Australia
7. Australian Institute for Bioengineering and Nanotechnology, The University of Queensland, Brisbane, QLD 4072, Australia
8. Centre for Clinical Research, The University of Queensland, Brisbane, QLD 4019, Australia
9. University of Exeter Medical School, RILD Building, RD&E Hospital Wonford, Barrack Road, Exeter, EX2 5DW, UK
10. Department of Computer Science, University of California Los Angeles, Los Angeles, CA, USA
11. Department of Bioinformatics, University of California Los Angeles, Los Angeles, CA, USA
12. Florey Institute for Neuroscience and Mental Health, University of Melbourne, Melbourne, VIC 3052, Australia
13. Calvary Health Care Bethlehem, Parkdale, VIC 3195, Australia
14. Fiona Stanley Hospital, Perth, WA 6150, Australia
15. Notre Dame University, Fremantle, WA 6160, Australia
16. Institute for Immunology and Infectious Diseases, Murdoch University, Perth, WA 6150, Australia
17. Department of Neurology, Flinders Medical Centre, Bedford Park, SA 5042, Australia
18. Brain & Mind Centre, University of Sydney, Institute of Clinical Neurosciences, Royal Prince Alfred Hospital, Sydney, NSW, 2006, Australia
19. Department of Neurology, University Medical Center Utrecht Brain Center, Utrecht University, Utrecht, The Netherlands
20. Department of Medical Oncology, Dana-Farber Cancer Institute and Harvard Medical School, Boston, MA, USA
21. Division of Genetics, Brigham and Women's Hospital, Boston, MA, USA
22. Department of Neurology, University of California Los Angeles, Los Angeles, CA 90095, USA
23. Department of Medicine, University of California San Francisco, San Francisco, CA 94158, USA
24. Queensland Centre for Mental Health Research, West Moreton Hospital and Health Service, Wacol, QLD 4076, Australia


### Methods
The Functional Mapping and Annotation (FUMA) pipeline and five tools (Conditional and Joint analysis (GCTA-COJO), Stratified Linkage Disequilibrium Score Regression (S-LDSC), Polygenic Priority Scoring (PoPs), Summary-based Mendelian Randomisation (SMR-HEIDI), and Transcriptome-Wide Association Study (TWAS) analyses) were used to perform bioinformatic integration of GWAS data (Ncases=20,806 Ncontrols=59,804) with ‘omics reference data sets including blood (eQTLgen consortium N=31,684) and brain (N=2,581). This was followed up by specific expression studies in ALS case-control cohorts (microarray Ntotal=942, protein Ntotal=300) and gene knock-down (KD) studies of human neuronal iPSC cells and zebrafish-morpholinos (MO). 


### Data
Available in this repository are the results for FUMA, PoPS, TWAS, GPX3 plasma expression data and zebrafish-MO GPX3 tracking data 
The FUMA job results are also published online (SNP2GENE jobID*366) https://fuma.ctglab.nl/browse

### External data used in analyses

The GWAS summary statistics dataset (20,806 ALS cases and 59,804 controls) used to perform the bioinformatic analyses are available for download via the GWAS tab on the ALS Variant server hosted by the University of Massachusetts Medical School (http://als.umassmed.edu).
Nicolas A, Kenna KP, Renton AE, Ticozzi N, Faghri F, Chia R, et al. Genome-wide Analyses Identify KIF5A as a Novel ALS Gene. Neuron. 2018;97(6):1268-83.e6.

Brain-eMeta eQTL summary data are available at https://cnsgenomics.com/software/smr/#DataResource. The eQTLGen summary data are for download at the eQTLGen consortium website (https://www.eqtlgen.org/cis-eqtls.html).
Qi T, Wu Y, Zeng J, Zhang F, Xue A, Jiang L, et al. Identifying gene targets for brain-related traits using transcriptomic and methylomic data from blood. Nature Communications. 2018;9(1):2282-.

The methylation summary statistics (782 ALS cases and 613 controls) is available for download through dbGAP. dbGaP Study Accession: phs002068.v1.p1
Nabais MF, Lin T, Benyamin B, Williams KL, Garton FC, Vinkhuyzen AAE, et al. Significant out-of-sample classification from methylation profile scoring for amyotrophic lateral sclerosis. npj Genomic Medicine. 2020;5(1):10.

The microarray data (397 ALS cases and 645 controls) is available are publicly available to download from the Gene Expression Omnibus (GEO): Accession GSE11268.
van Rheenen W, Diekstra FP, Harschnitz O, Westeneng H-J, van Eijk KR, Saris CGJ, et al. Whole blood transcriptome analysis in amyotrophic lateral sclerosis: A biomarker study. PLoS One. 2018;13(6):e0198874.

