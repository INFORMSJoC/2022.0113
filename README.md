[![INFORMS Journal on Computing Logo](https://INFORMSJoC.github.io/logos/INFORMS_Journal_on_Computing_Header.jpg)](https://pubsonline.informs.org/journal/ijoc)

# Distributionally Robust Chance Constrained $p$-Hub Center Problem

This archive is distributed in association with the [INFORMS Journal on
Computing](https://pubsonline.informs.org/journal/ijoc) under the [MIT License](LICENSE).

This repository contains supporting material for the paper [Distributionally Robust Chance Constrained p-Hub Center Problem](https://doi.org/????) by Y. Zhao, Z. Chen and Z.Z. Zhang.

## Cite

To cite this code, please cite the paper using its DOI and the code itself, using the following DOI: 
    DOI:10.1287/ijoc.2022.0113.cd

Below is the BibTex for citing this snapshot of the respoitory.

```
@article{ZhaoChenZhang2022.0113,
  author =        {Zhao, Yue and Chen, Zhi and Zhang, Zhen Zhen},
  publisher =     {INFORMS Journal on Computing},
  title =         {Distributionally Robust Chance Constrained $p$-Hub Center Problem},
  year =          {2023},
  doi =         {10.1287/ijoc.2022.0113.cd},
  url =         {https://github.com/INFORMSJoC/2022.0113},
  note={available for download at https://github.com/INFORMSJoC/2022.0113}
}  
```

## Content

This repository includes

1. Instance data for the $p$-Hub Center Problem, which is origniated from the [Civil Aeronautic Board (CAB)](https://www.researchgate.net/publication/269396247_cab100_mok) dataset.
1. Raw results of our experiments including all the figures and tables.

### Data files

Instance data files are located in the folder [data](data). The file [CABCircle.csv](data/CABCircle.csv) contains 35 locations for most of our experiments, while [CAB.txt](data/CAB.txt) contains up to 100 locations (all the nodes in CAB dataset) to test the scalability of our algorithms. 


### Results
The folder [results](results) contains the results of the experiments, each folder corresponds to a figure/table in the paper.
