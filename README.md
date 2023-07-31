# Random projection tree similarity metric for SpectralNet

[![DOI](http://img.shields.io/badge/doi-10.1016/j.array.2022.100274-36648B.svg)](https://doi.org/10.1016/j.array.2022.100274)
[![Paper](http://img.shields.io/badge/arXiv-2302.13168-b31b1b.svg)](https://arxiv.org/abs/2302.13168)
[![Papers with Code](http://img.shields.io/badge/PaperswithCode-2302.13168-21cbce.svg)](https://paperswithcode.com/paper/random-projection-tree-similarity-metric-for)

This is an implementation for the following paper:
```bibtex
@article{ALSHAMMARI2023100274,
	title = {Random projection tree similarity metric for SpectralNet},	
	volume = {17},
	year = {2023},
	journal = {Array},
	doi = {https://doi.org/10.1016/j.array.2022.100274},
	author = {Mashaan Alshammari and John Stavrakakis and Adel F. Ahmed and Masahiro Takatsuka}
}	
```

## Python Setup:

- Download and install Anaconda Navigator
- launch Anaconda Prompt to execute the following commands:
	- `conda create -n tf15 python tensorflow=1.15`
	- `conda activate tf15`
	- `conda remove --force tensorflow-estimator`
	- `conda install -c anaconda tensorflow-estimator==1.15.1`
	- `conda install -c anaconda scikit-learn`
	- `conda install -c conda-forge munkres`
	- `conda install -c conda-forge python-annoy`
	- `conda install -c conda-forge keras==2.3.1`
	- `conda install -c anaconda spyder`

- To start working in this enviroment, launch Anaconda Prompt and type:
	- `activate tf15`
	- `spyder`

## Code Acknowledgement

We reused the [repository](https://github.com/KlugerLab/SpectralNet) provided with the SpectralNet paper.

---
written by [Mashaan Alshammari](https://mashaan14.github.io/mashaan/)<br/>
September 11, 2022.
