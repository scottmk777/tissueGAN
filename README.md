# In silico gene expression sample augmentation with conditional GANs.
This project is based off of a conditional GAN constructed for single-cell RNA-seq data (https://github.com/imsb-uke/scGAN/). This code extends that project to apply to patient tissue bulk RNA samples, which are notoriously difficult and expensive to obtain.

## Usage
The `main.py` script is used to train and generate new samples. At this time, samples are created after 1000 iterations of training and stored for further analysis. 

## Vignette Data
Data is included in ?geo_mat?. All data has been normalized with COMBAT to enable cross dataset and cancer comparison. 
