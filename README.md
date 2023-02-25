# RPTree

## 	The Effect of Points Dispersion on the k-nn Search in Random Projection Forests
This is an implementation for the following paper:
```
@article{ALSHAMMARI2023100274,
	title = {Random projection tree similarity metric for SpectralNet},
	journal = {Array},
	volume = {17},
	year = {2023},
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
Provided by Mashaan Alshammari<br/>
mashaan14 at gmail dot com<br/>
mashaan dot awad at outlook dot com<br/>
September 11, 2022.
