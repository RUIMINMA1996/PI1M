# PI1M: A Benchmark Database for Polymer Informatics

This repository contains a benchmark database for polymer informatics. The details and utility of PI1M are described in our [paper](https://pubs.acs.org/doi/10.1021/acs.jcim.0c00726).


## Abstract

Open source data in large scale are the cornerstones for data-driven research, but they are not readily available for polymers. In this work, we build a benchmark database, called PI1M (referring to ~1 million polymers for polymer informatics), to provide data resources that can be used for machine learning research in polymer informatics. A generative model is trained on ~12,000 polymers manually collected from the largest existing polymer database PolyInfo, and then the model is used to generate ~1 million polymers. A new representation for polymers, polymer embedding (PE), is introduced, which is then used to perform several polymer informatics regression tasks for density, glass transition temperature, melting temperature and dielectric constants. By comparing the PE trained by the PolyInfo data and that by the PI1M data, we conclude that the PI1M database covers similar chemical space as PolyInfo, but significantly populate regions where PolyInfo data are sparse. We believe PI1M will serve as a good benchmark database for future research in polymer informatics. 

## Dataset

~1 million polymer structures.


### Data format

p-SMILES.

### Synthetic accessibility score added

The synthetic accessibility score is calculated using Schuffenhauer’s SA score (https://jcheminf.biomedcentral.com/articles/10.1186/1758-2946-1-8), a heuristic estimate of how hard (10) or how easy (1) it is to synthesize a given molecule. The SA score is added into the PI1M_v2.csv, and the statistics of SA score is shown in figure below.

![alt text](https://github.com/RUIMINMA1996/PI1M/blob/master/sa_PI1M.png)

## Reference

If this repository is helpful for your research please cite the following
publication:

[PI1M: A Benchmark Database for Polymer Informatics](https://pubs.acs.org/doi/10.1021/acs.jcim.0c00726)
Ruimin Ma, Tengfei Luo


## Note
Data for academic purpose only.

