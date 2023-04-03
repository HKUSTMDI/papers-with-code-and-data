# Papers with Code and Data

### Pathologist-level interpretable whole-slide cancer diagnosis with deep learning <https://github.com/zizhaozhang/nmi-wsi-diagnosis>

### [PathVQA](https://arxiv.org/abs/2003.10286)

paper repository <https://github.com/UCSD-AI4H/PathVQA>

[dataset download](https://github.com/UCSD-AI4H/PathVQA/issues/10)

* Image source: 1,670 pathology images collected from two pathology textbooks: “Textbook of Pathology" and “Basic Pathology”, 3,328 pathology images collected from the PEIR7 digital library
* 32,799 question-answer pairs generated
* Avg. # of questions per image: 6.6
* Max # of questions for a single image: 14
* Min # of questions for a single image:  1
* Avg. # of words per question: 9.5
* Avg. # of words per answer: 2.5
* \# of question types = 7
* Open-ended questions: what(40.9%), where(4%), when(0.9%), whose(0.6%), how(3%), how much/how many(0.9%).
* Close-ended questions: yes/no. The number of “yes" and “no" answers are balanced
* total # of images in downloaded PVQA (splitted): train: 3021, val: 992, test: 991. (6:2:2) Indexed (q2a, qid2a, qid2q, etc.)

### [Inference of captions from histopathological patches](https://openreview.net/forum?id=9gKn7SDb83v)

paper repository <https://github.com/masatsuneki/histopathology-image-caption>

[PatchGastricADC22 download](https://zenodo.org/record/6550925#.ZB2G4OxByDU)
* Patches extracted from 991 Whole Slide Images (WSI) of H&E-stained gastric adenocarcinoma specimens with associated diagnostic captions extracted directly from existing medical reports.
* The slides were digitized into WSIs at a magnification of x20.
* All of collected cases were diagnosed as having adenocarcinoma and were reviewed by three pathologists to confirm the diagnoses.
* adenocarcinoma subtypes: 9
* The vocabulary consisted of 277 words with a maximum sentence length of 50 words.
* Patch size: 300*300
* Available dataset contains patches extracted from WSI at 20x. No 10x patches
* \# of tiles: 262777
* Captions columns: wsi_id, subtype ,text
* Patch filename convention: {wsi_id}_{random_hash}

### [ARCH](https://arxiv.org/abs/2103.05121)
 Not available

### More open datasets
| title                                                                                                                               | date      | #views | #downloads | data                                                   | link                                                                                           | paper link                                                                                                                                                                  | Code repository                                                                                                          |
| ----------------------------------------------------------------------------------------------------------------------------------- | --------- | ------ | ---------- |--------------------------------------------------------|------------------------------------------------------------------------------------------------| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |--------------------------------------------------------------------------------------------------------------------------|
| PESO: Prostate Epithelium Segmentation on H&E-stained prostatectomy whole slide images                                              | 26-Jul-21 | 8060   | 21960      | WSI & masks                                            | [https://zenodo.org/record/5137717#.ZCTnTOxByDU](https://zenodo.org/record/5137717#.ZCTnTOxByDU) | [Epithelium segmentation using deep learning in H&E-stained prostate specimens with immunohistochemistry as reference standard](https://doi.org/10.1038/s41598-018-37257-4) |                                                                                                                          |
| The Single-Cell Pathology Landscape of Breast Cancer                                                                                | 4-Nov-19  | 7047   | 51045      | ome-tiff &masks                                        | [https://zenodo.org/record/4607374#.ZCTnf-xByDU](https://zenodo.org/record/4607374#.ZCTnf-xByDU) |                                                                                                                                                                             | [https://github.com/BodenmillerGroup/SCPathology_publication](https://github.com/BodenmillerGroup/SCPathology_publication) |
| Histological images for MSI vs. MSS classification in gastrointestinal cancer, FFPE samples                                         | 7-Feb-19  | 10498  | 43835      | patch (wsi on https://portal.gdc.cancer.gov/)          | [https://zenodo.org/record/2530835#.ZCTm1uxByDU](https://zenodo.org/record/2530835#.ZCTm1uxByDU) |                                                                                                                                                                             |                                                                                                                          |
| Segmentation of Nuclei in Histopathology Images by deep regression of the distance map                                              | 16-Feb-18 | 8108   | 4434       | patch(small slide) and mask(gt)                        | [https://zenodo.org/record/2579118#.ZCTm3exByDU](https://zenodo.org/record/2579118#.ZCTm3exByDU) |                                                                                                                                                                             |                                                                                                                          |
| 100,000 histological images of human colorectal cancer and healthy tissue                                                           | 7-Apr-18  | 29467  | 34556      | patch (&masks?)                                        | [https://zenodo.org/record/1214456#.ZCTmi-xByDU](https://zenodo.org/record/1214456#.ZCTmi-xByDU) |                                                                                                                                                                             |                                                                                                                          |
| Collection of textures in colorectal cancer histology                                                                               | 26-May-16 | 14800  | 33858      | patch(small & large size)                              | [https://zenodo.org/record/53169#.ZCTmuexByDU](https://zenodo.org/record/53169#.ZCTmuexByDU)   |                                                                                                                                                                             |                                                                                                                          |
| BACH Dataset : Grand Challenge on Breast Cancer Histology images                                                                    | 31-May-19 | 5829   | 8360       | patch(class labeled) wsi (region partially? Annotated) | [https://zenodo.org/record/3632035#.ZCTy6-xByDU](https://zenodo.org/record/3632035#.ZCTy6-xByDU) |                                                                                                                                                                             |                                                                                                                          |
| Data for: Tang et al., Interpretable classification of Alzheimer's disease pathologies with a convolutional neural network pipeline | 1-Nov-18  | 2601   | 4782       | WSI & patch (class annotation)                         | [https://zenodo.org/record/1470797#.ZCT2EuxByDU](https://zenodo.org/record/1470797#.ZCT2EuxByDU) | [Interpretable classification of Alzheimer’s disease pathologies with a convolutional neural network pipeline](https://doi.org/10.1101/454793)                              | https://github.com/keiserlab/plaquebox-paper                                                                             |
| Digital Pathology Dataset for Prostate Cancer Diagnosis                                                                             | 4-Feb-22  | 1022   | 620        | WSI & annotations & patch                              | https://zenodo.org/record/7152243#.ZCT3B-xByDU                                                 | [An AI-assisted Tool For Efficient Prostate Cancer Diagnosis in Low-grade and Low-volume Cases](https://www.cell.com/patterns/fulltext/S2666-3899(22)00274-4)               |                                                                                                                          |