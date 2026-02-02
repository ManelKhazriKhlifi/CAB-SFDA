## CAB-SFDA 
This repository contains the implementation of "Class-Aware Balanced Source-Free Domain Adaptation for Remote Sensing Scene Classification" paper. 

Our paper suggests a novel technology for source-free domain adaptation on small datasets. This technology integrates class-balanced memory, prototype attraction, weak/strong consistency, and information maximization with a frozen classifier in a source-free setting to tackle the challenges of domain shift in Remote Sensing (RS) scene classification.
## Results
| Datasets | AID | CLRS | MLRSN | RSSCN7 | 
| -------- | ----------- | ----------- | ----------- |-----------|
| AID    | ----- | ------ | ----------- |--------------|
| CLRS   | ----- | ------ | ----------- |--------------|
| MLRSN  | ----- | ------ | ----------- |--------------|
| RSSCN7 | ----- | ------ | ----------- |--------------|
<p align="center">
  <img src="assets/tsne_category_beforeG2N.png" width="150"/>
  <img src="assets/tsne_category_afterG2N.png" width="150"/>
  <img src="assets/tsne_domain_afterG2N.png" width="150"/>
  <img src="assets/tsne_domain_beforeG2N.png" width="150"/>
</p>

## Datasets
Our paper assesses performance on 12 transfer tasks using the cross-scene dataset, as well as two transfer tasks utilizing the cross-sensor dataset.
#### Cross-scene dataset
* AID <-> CLRS
* AID <-> MLRSN
* AID <-> RSSCN7
* CLRS <-> MLRSN
* CLRS <-> RSSCN7
* MLRSN <-> RSSCN7
#### Cross-sensor dataset
* NWPU-RESISC45 <-> NaSC-TG2
* WHU-RS19 <-> EuroSAT 
## Usage
* Clone the Repository:
```ruby
  git clone https://github.com/ManelKhazriKhlifi/CAB-SFDA.git
```
## Citation

If you use any part of this work please cite using the following Bibtex format:
```
@Article {khelifi2026CAB-SFDA,
AUTHOR = {Manel Khazri Khelifi and Adel Ammar and Wadii Boulila and Imed Riadh Farah},
TITLE = {CAB-SFDA: Class-Aware Balanced Source-Free Domain Adaptation for Remote Sensing Scene Classification},
JOURNAL = {},
VOLUME = {},
YEAR = {2026},
NUMBER = {},
ARTICLE-NUMBER = {},
URL = {},
ISSN = {},
DOI = {}
}
```
