# deephlapan

DeepHLApan is a deep learning approach used for predicting binding affinity and level between peptides and HLA alleles. Based on the 
predcited results,researchers could identify potential neoantigens for tumor immunotherapy.


## Download

Download the latest version of DeepHLApan from https://github.com/jiujiezz/deephlapan
    
    git clone https://github.com/jiujiezz/deephlapan

## Installation

Unzip the source code and go into the directory by using the following command:

    tar xvzf deephlapan-*.tar.gz

    cd deephlapan

Invoke the setup script:

    python setup.py install

## Input files

DeepHLApan takes csv files as input with head of "Annotation,HLA,peptide".

## General usage

    deephlapan -F YOUR_file -O YOUR_output_path

