# CCS Data analysis

Code to reproduce results from Meier et al.: Deep learning the collisional cross sections of the peptide universe from a million training samples. For the deep learning model and CCS prediction, please see also https://github.com/theislab/DeepCollisionalCrossSection. 

Pre-print:
- biorxiv: https://www.biorxiv.org/content/10.1101/2020.05.19.102285v1 (doi: 10.1101/2020.05.19.102285)

## Where to find the data

The mass spectrometry raw files and associated MaxQuant output files generated and analyzed throughout this study have been deposited at the ProteomeXchange Consortium via the PRIDE partner repository with the dataset identifier PXD019086 (http://www.proteomexchange.org/). The previously acquired HeLa data is available through the dataset identifier PXD010012. The diaPASEF raw files are available through the dataset identifier PXD017703.

For a quick start, pre-processed 'evidence' data files are contained in the output directory.


## Installation (Python 3)

To reproduce the results presented in the paper, follow the installation instructions and run the notebooks in Jupyter Notebook.

```
- git clone https://github.com/MannLabs/DeepCollisionalCrossSection.git
- cd DeepCollisionalCrossSection
- conda create --name CCS_data_analysis python=3.8
- activate CCS_data_analysis (for Windows) or source activate CCS_data_analysis (for Linux / Mac Os X)
- pip install -r requirements.txt
```
