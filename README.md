## ESM vs. MSA: A Consistency Analysis in Protein Contact Prediction

### [Paper (coming soon)](#) | [Data](https://www.ebi.ac.uk/interpro/entry/pfam/#table)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1wz8o5HeZKbKzjjCMBisdzUlsUw6fF_g1?usp=sharing)<br>
This repository provides a framework and visualization tool to evaluate the consistency of pairwise protein contact predictions from LLM-Based ESM-2 models against multiple sequence alignments (MSA). 

## Key Features
- Fetch PFAM seed alignments by specifying a PFAM ID (e.g. `PF00069`).
- Load & evaluate ESM-2 models of different sizes on selected pairs of sequences.
- Visualize contact maps and compute consistency scores with adjustable threshold parameters.

## To Do
- Develop more advanced algorithms/metrics for consistency score evaluation.
- Extend pairwise sequence alignment consistency metric compatibility to MSA.

**License:** MIT

---

## References

1. Rao, R. M., Meier, J., Sercu, T., Ovchinnikov, S., & Rives, A. (2020). Transformer protein language models are unsupervised structure learners. *bioRxiv*. [DOI:10.1101/2020.12.15.422761](https://www.biorxiv.org/content/10.1101/2020.12.15.422761v1)

2. Lin, Z., Akin, H., Rao, R., Hie, B., Zhu, Z., Lu, W., Smetanin, N., dos Santos Costa, A., Fazel-Zarandi, M., Sercu, T., Candido, S., & others. (2022). Language models of protein sequences at the scale of evolution enable accurate structure prediction. *bioRxiv*. [Publisher: Cold Spring Harbor Laboratory](https://www.biorxiv.org/)
