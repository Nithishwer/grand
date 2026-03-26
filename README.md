[![Anaconda-Server Badge](https://anaconda.org/essexlab/grand/badges/version.svg)](https://anaconda.org/essexlab/grand)
[![Anaconda-Server Badge](https://anaconda.org/essexlab/grand/badges/downloads.svg)](https://anaconda.org/essexlab/grand)
[![Documentation Status](https://readthedocs.org/projects/grand/badge/?version=latest)](https://grand.readthedocs.io/en/latest/?badge=latest)
[![DOI](https://zenodo.org/badge/270705695.svg)](https://zenodo.org/badge/latestdoi/270705695)

# _grand-alchemical-ligand_ 

Extension of essexlab/grand enabling GCMC sampling of alchemically perturbed ligands in OpenMM.

### 🔬 Overview

This repository is a modified version of the original grand package developed by Essex Lab, which implements grand canonical Monte Carlo (GCMC) water sampling in OpenMM.

This fork introduces new functionality to perform GCMC sampling in the presence of alchemically perturbed ligands and
enable integration with alchemical free energy workflows

These modifications were developed for:

XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

### ⚠️ Relationship to upstream

This code is derived from:
👉 https://github.com/essexlab/grand

All original functionality and core methods are due to the Essex Lab authors. This repository adds new methods on top of the original implementation.

### 🛠️ Installation & Usage

This module can be installed from this directory by running the following
command:

```commandline
python setup.py install
```

The unit tests can then be carried out by running the following command from
this directory:
```commandline
python setup.py test
```

The dependencies of this module can be installed as:

```commandline
conda install -c conda-forge -c omnia openmmtools
pip install lxml
```
Many of grand's dependencies (openmm, mdtraj, pymbar, parmed) are also dependencies of 
openmmtools, and will be installed alongside openmmtools.

Alternatively, _grand_ and its dependencies can be installed via conda:
```commandline
conda install -c omnia -c anaconda -c conda-forge -c essexlab grand
```

### 🧪 Reproducing the paper

The exact version of the code used in the paper is:

👉 Release: v1.0-paper
👉 Branch: alchemical_ligand

To reproduce results:

```bash
git checkout v1.0-paper
```


### 📜 Citing _grand-alchemical-ligand_

If you use this code, please cite:

This work
Nithishwer Mouroug Anand, *XXXXXXXXXXXXXXXXXXXX*, 2026

Original grand package

1. M. L. Samways, H. E. Bruce Macdonald, J. W. Essex, _J. Chem. Inf. Model._,
2020, 60, 4436-4441, DOI: https://doi.org/10.1021/acs.jcim.0c00648
2. O. J. Melling, M. L. Samways, Y. Ge, D. L. Mobley, J. W. Essex, _J. Chem. Theory Comput._, 2023,
DOI: https://doi.org/10.1021/acs.jctc.2c00823

### 👤 Authors

**Modifications for alchemical ligand GCMC**
- Nithishwer Mouroug Anand
- Philip C Biggin 

**Original authors (grand)**
- Marley Samways
- Hannah Bruce Macdonald
- Ollie Melling
- Will Poole
- J. W. Essex

### 📜 License

This project is distributed under the same license as the original grand repository (MIT).

### 📬 Contact

For questions about:

- alchemical ligand modifications → contact nithishwer.mourouganand@reuben.ox.ac.uk or philip.biggin@bioch.ox.ac.uk
- original grand → contact Essex Lab

