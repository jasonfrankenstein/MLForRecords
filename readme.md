# Machine Learning Classificiation for Records Management

## Master of Data Science Minor Thesis

### By Jason Franks

### Supervisors: Greg Rolan, Lan Du

This repository contains the source code from my Master of Data Science minor thesis.

All code was developed on Google Colab (https://colab.research.google.com/) and is intended to run there. 

In order to run these experiments you will need your data in a tab-separated .tsv file with two columns: 'label', containing the category name, and 'text', containing the records' raw text. Evey category in the data file should have at least 10 records. 

The notebooks are set up to load these data files from a google drive and must be provided with the path to mount (**mount_path**) and the name of the file containing your text data (**data_file**). The mount path must contain a folder named  **output**, into which the notebooks will write output metrics. 

The notebooks will install any software missing from the Colab environment as of 06/2020.


