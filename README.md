# CCS Data analysis

Code to reproduce results from Meier et al., Deep learning the collisional cross sections of the peptide universe from a million experimental values. For the deep learning model and CCS prediction, please see also https://github.com/theislab/DeepCollisionalCrossSection. 

Reference:
- Meier, F., Köhler, N.D., Brunner, AD. et al. Deep learning the collisional cross sections of the peptide universe from a million experimental values. Nat Commun 12, 1185 (2021). https://doi.org/10.1038/s41467-021-21352-8 
- [bioRxiv](https://dx.doi.org/10.1101/2020.05.19.102285)

## Where to find the data

The mass spectrometry raw files and associated MaxQuant output files generated and analyzed throughout this study have been deposited at the ProteomeXchange Consortium via the PRIDE partner repository with the dataset identifier [PXD019086](http://proteomecentral.proteomexchange.org/cgi/GetDataset?ID=PXD019086). The previously acquired HeLa data is available through the dataset identifier [PXD010012](http://proteomecentral.proteomexchange.org/cgi/GetDataset?ID=PXD010012). The diaPASEF raw files are available through the dataset identifier [PXD017703](http://proteomecentral.proteomexchange.org/cgi/GetDataset?ID=PXD017703).

For a quick start, pre-processed 'evidence' data files are contained in the [output directory](/output).


## Installation (Python 3)

To reproduce the results presented in the paper, follow the installation instructions and run the notebooks in Jupyter Notebook.

```
- git clone https://github.com/MannLabs/DeepCollisionalCrossSection.git
- cd DeepCollisionalCrossSection
- conda create --name CCS_data_analysis python=3.8
- activate CCS_data_analysis (for Windows) or source activate CCS_data_analysis (for Linux / Mac Os X)
- pip install -r requirements.txt
```


## Interactive data analysis

To explore the CCS values of the dataset interactively, Jupyter notebooks and pre-configured html files are available [here](/interactive_visualization).  
