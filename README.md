# papers-with-code

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
