<!--[TLP:RED] UNDER EMBARGO UNTIL 2025-01-13!-->
```diff
- [TLP:RED] UNDER EMBARGO UNTIL 2025-01-13!
```

# Fits Header Extractor and Curator With Python

## Abstract

[FITS](https://en.wikipedia.org/wiki/FITS) files are widely used in astronomy. The content of a FITS file is in two parts: the header and the data. The goal of this Python project is to explore fits header. To this end, I created a python library: `fits_header_extractor`, providing a `FitsHeaderExtractor` class, and a notebook.

## Requirements

The library requires `python` (tested with version 3.13.1), with the `venv` module and `pip`, a `bash` interpreter (`/usr/bin/env bash` by default), and at least 1.2 MiB of available space.

## Installation

Place all the content of the archive in a directory. Then, in this directory, to create the virtual environment, run:
```bash
python3 -m venv ./venv
```
Then, to install the library, run:
```bsah
source activate.sh && pip install git+https://github.com/Yael-II/Fits-Header-Extractor && deactivate
```
You may probably also need some additional libraries for the notebook:
```bash
source activate.sh && pip install jupyter numpy matplotlib ipyaladin && deactivate
```
Create the directories `./Input/` and `./Output/` if its not already done.

## Usage

After the installation, activate the virtual environment with:
```bash
source activate.sh
```
Then, launch the notebook with:
```bash
jupyer-lab
```
and select the `exploration.ipynb` notebook. 

Once you are done, do not forget to deactivate the virtual environment with
```bash
deactivate
```

## Documentation

The `fits_header_extractor` library documentation and `FitsHeaderExtractor` class description can be found on the Github [repository](https://github.com/Yael-II/Fits_Header_Extractor) of the package.


