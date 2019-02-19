# In silico gene expression sample augmentation with conditional GANs.
This project is based off of a conditional GAN constructed for single-cell RNA-seq data (https://github.com/imsb-uke/scGAN/). This code extends that project to apply to patient tissue bulk RNA samples, which are notoriously difficult and expensive to obtain.

## Usage
The `main.py` script is used to train and generate new samples. At this time, samples are created after 1000 iterations of training and stored for further analysis. 

## Vignette Data
Data is expected in the form of an hdf5 file in the folder specificed in `parameters.json`. All data must have been normalized with COMBAT to enable cross dataset and cancer comparison. The current dataset is too big to be hosted; a minuature one for a vignette is under development. 
