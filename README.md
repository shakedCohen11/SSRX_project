# Comparing RX and SSRX Algorithms
The repository contains part of my project for the course:
Selected Topics in Images Processing, [Prof. Stanley Rotman](http://www.ee.bgu.ac.il/~srotman/)

![RIT Results](imgs/cover.jpg)

The goal of this project is to compare two anomaly detection algorithms for hyperspectral images – the RX algorithm and its subspace projection variation known as the SSRX algorithm. While these two algorithms are mathematically and logically similar, the different results achieved when applying them on real data are interesting to research.

In order to further examine the effects of subspace projection, it was also tested in the task of change detection using the Chronochrome algorithm.

## Datasets

1. [RIT Target Detection Blind Test](http://dirsapps.cis.rit.edu/blindtest/)
2. [CiTIUS Change Detection Dataset](https://gitlab.citius.usc.es/hiperespectral/ChangeDetectionDataset)

## Disclaimer
This project included a slight change to the PCA formula. While this may not affect the results dramatically, this is worth noting for future research purposes.
The PCA projection used in this project was:

![Original PCA](http://latex.codecogs.com/svg.latex?X_%7BPCA%7D%3D+%28X+-+m%29+%5Cphi%5E%7B-1%7D+V_q)

where the correct formula is:

![Original PCA](http://latex.codecogs.com/svg.latex?X_%7BPCA%7D%3D+%28X+-+m%29+%5Cphi%5E%7B-%5Cfrac%7B1%7D%7B2%7D%7D+V_q)

## License
[MIT Open Source](https://choosealicense.com/licenses/mit/)
Feel free to use this work as long as you refrence this repo.
Contact: doronser@post.bgu.ac.il
