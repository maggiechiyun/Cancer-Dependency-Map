# Cancer-Dependency-Map
Files from DepMap Public 24Q4 corresponding to the effects a gene has on a cell-line’s growth in CRISPR knockout and RNAi screens, respectively.
CRISPRGeneEffect.csv and D2 combined gene dep scores.csv files. Download the data from link inside the python files, and also run the jupyter notebook to create the cencer dependency map. 

# CHEK1 hub dependency map
Create a cancer dependency map with CHEK1 as the hub. Checkpoint kinases (Chks) encoded as CHEK1 has a central role in coordinating the DNA damage response and therefore is an area of great interest in oncology and the development of cancer therapeutics. We found the pathway of CHEK1 along with TIMELESS, RRM1, WEE1, RRM2, POLE genes, which could potentially be a target new drug.

<img width="367" height="289" alt="image" src="https://github.com/user-attachments/assets/a7b5f444-e6af-4106-8006-38b5889a7a35" />


# Notes: Why gene gene correlation are different in two knock down techniques?

***1.	The RNAi screen had a specific pipeline developed to account for off-target effects of RNAi (DEMETER2). Differences between the screens could as a result be due to some implicit biases made in the RNAi screen processing that are unreflective of the underlying biology. vice versa for CRISPR.***

***2.   These methods aim at different steps within the central dogma of biology, those being DNA for CRISPR and RNA for RNAi. With a successful gene edit in the former you would not expect any expression of the target gene whereas there may be incomplete interference in the latter.***

# Cited:
Tsherniak, Aviad et al. “Defining a Cancer Dependency Map.” Cell vol. 170,3 (2017): 564-576.e16. doi:10.1016/j.cell.2017.06.010 https://pubmed.ncbi.nlm.nih.gov/28753430/ 

<img width="635" height="359" alt="image" src="https://github.com/user-attachments/assets/8e79bb1e-3f7f-4a2f-8791-700d50c246bb" />


