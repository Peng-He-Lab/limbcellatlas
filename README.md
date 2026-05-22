# Human limb development cell atlas
This repository contains codes and data used for [the human embryonic limb cell atlas](https://www.nature.com/articles/s41586-023-06806-x).
<img width="736" alt="image" src="https://github.com/user-attachments/assets/51cb199c-e15a-46ac-8f6e-ed057cf8503b">
<img width="727" height="653" alt="image" src="https://github.com/user-attachments/assets/90a4a10e-64e6-4534-8895-ff76f00771cc" />

| Data type | Description | Access |
|---|---|---|
| **Interactive browsers** | Cell-level exploration of gene expression and metadata | [CZI CellxGene](https://cellxgene.cziscience.com/collections/4fefa187-5d14-4f1e-915b-c892ed320aab) · [Working data portal](https://limb-dev.cellgeni.sanger.ac.uk/) · [Developmental Cell Atlas](https://developmental.cellatlas.io/embryonic-limb) |
| **Raw scRNA-seq** | FASTQ files and raw count matrices | [BioStudies: human limb scRNA-seq](https://www.ebi.ac.uk/biostudies/arrayexpress/studies/E-MTAB-8813) |
| **Raw spatial transcriptomics (Visium)** | FASTQ files and spatial gene expression matrices | [BioStudies: human limb Visium](https://www.ebi.ac.uk/biostudies/arrayexpress/studies/E-MTAB-10367) |
| **Imaging data** | FISH, IF, RNAscope of human embryonic limbs | [BioImage Archive](https://www.ebi.ac.uk/biostudies/bioimages/studies/S-BIAD2364) , [3D Videos](https://ucsfonline-my.sharepoint.com/:f:/g/personal/peng_he_ucsf_edu/IgD62ktnBeGsRLezodtZ_OjrAV3wfwZdPA0QNnkKbbLRbyc?e=h9liVU)|
| **Marker genes** | Marker genes for annotated cell types and cell states | [MarkerGenes.md](./MarkerGenes.md) |
| **Gene regulatory networks** | Cell type–specific regulons inferred using pySCENIC | [pyscenic results](./pyscenic) |
| **Downstream analysis notebooks** | pySCENIC workflow and visualization | [running_pyscenic_and_visualization.ipynb](running_pyscenic_and_visualization.ipynb) |


## [VisiumStitcher](https://github.com/Teichlab/visium_stitcher)
* [notebook for image stitching with hard-coded positioning](https://nbviewer.jupyter.org/github/Teichlab/limbcellatlas/blob/main/Visium_image_stitching.ipynb)
* [notebook for RNA stitching following image stitching](https://nbviewer.jupyter.org/github/Teichlab/limbcellatlas/blob/main/Visium_RNA_stitching.ipynb)

# Mouse limb development cell atlas
The mouse limb cell atlas was built by integrating our newly generated data and previously published data ([Kelly et al.](https://pubmed.ncbi.nlm.nih.gov/31874220/),[Allou etal.](https://pubmed.ncbi.nlm.nih.gov/33568816/), [He et al.](https://www.nature.com/articles/s41586-020-2536-x))
<img width="756" height="336" alt="image" src="https://github.com/user-attachments/assets/cc7eed2f-e75f-4bb7-b0ba-48984a4043e8" />
<img width="735" height="693" alt="image" src="https://github.com/user-attachments/assets/0147b6f7-5ebb-43f5-8eed-15bc076035de" />

| Data type | Description | Access |
|---|---|---|
| **Interactive browsers** | Integrated mouse limb atlas | [CZI CellxGene](https://cellxgene.cziscience.com/collections/4fefa187-5d14-4f1e-915b-c892ed320aab) · [Working data portal](https://limb-dev.cellgeni.sanger.ac.uk/) · [Developmental Cell Atlas](https://developmental.cellatlas.io/embryonic-limb) |
| **Raw scRNA-seq** | FASTQ files and raw count matrices | [BioStudies: mouse limb scRNA-seq](https://www.ebi.ac.uk/biostudies/arrayexpress/studies/E-MTAB-10514) |

---

acknowledgments - We would like to thank Valentina Lorenzi for her feedback and contribution 

![image](https://github.com/Teichlab/limbcellatlas/assets/4110443/cd34fe7b-53fb-485e-95a0-3b1b04394102)

