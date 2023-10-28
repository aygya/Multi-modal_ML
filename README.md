# Multi-modal_ML
Multi-modal ML methods based ADNI data (morphometry + genetic study)

Course project

Table of contents:
* [All code with data preprocessing + SVM (SVC) model + Baseline models resultsdocs](main/Multi_modal_ML.ipynb)
* [Presentation](https://drive.google.com/file/d/1cbnQkl_xCAAVFCCSpx-W_rDmhHsCRW8g/view?usp=sharing)
* [Report](main/NeuroML_report.pdf)
  
Future work:
* Find more correlations between top features of genetic and morphometric data
* Read more articles on AD and MCI genes and brain changes
Current results:
Morphometery data AD vs CN
The mean score_svm using nested cross-validation is: 0.882 ± 0.085
Genetic data AD vs CN
The mean score_svm using nested cross-validation is: 0.603 ± 0.022
Other models worked  worse

Brain sections: http://arno.uvt.nl/show.cgi?fid=149965
Important materials:
* https://article.imrpress.com/journal/JIN/22/4/10.31083/j.jin2204099/264447778a39dfc4f0197bb7be2e4fd3.pdf
* https://pubmed.ncbi.nlm.nih.gov/23202293/
* https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4876682/
* https://www.uniprot.org/uniprotkb/P49768/entry
* https://reactome.org/PathwayBrowser/#/R-HSA-1912422&FLG=Q99877&FLGINT&DTAB=AN&TOOL=AT&ANALYSIS=MjAyMzEwMjYyMDI1MjJfMTMwNTM%253D&FILTER=resource:UNIPROT
