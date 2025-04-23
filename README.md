# Model Editing Data
This repository holds the model editing datasets used in this [model editing benchmark](https://github.com/oneSebastian/model-editing/).

## Data sources
Credits for the datasets belong to the following sources:

- **zsRE and CounterFact:**
  We use the same dataset splits as [Meng et al. (2023)](https://arxiv.org/abs/2202.05262). We use the datasets distributed by them [here](https://rome.baulab.info/data/). The *CounterFact* dataset was created by them. The *zsRE* dataset was first created by [Levy et al. (2017)](https://aclanthology.org/K17-1034/).

- **MQuAKE:**
  The *MQuAKE* dataset was released by [Zhong et al. (2024)](https://arxiv.org/abs/2305.14795). The data can be found [here](https://github.com/princeton-nlp/MQuAKE).

- **RippleEdits:**  
  The *RippleEdits* dataset was released by [Cohen et al. (2023)](https://arxiv.org/abs/2307.12976). The original data can be found [here](https://github.com/edenbiran/RippleEdits). We use and distribute here an augmented version of the dataset. The authors' implementation contains calls to the wikidata API to resolve entitiy codes into entitiy labels. We resolved the API calls and added the entity labels where possible, thus creating the extended static dataset distributed here.
