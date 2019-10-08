# K-NOBEL

- Aim: Use [K-index](https://arxiv.org/abs/1609.05273v2) as a predictor of Nobel Laureates in Physics.
- Manuscript: [Citation network centrality: a scientific awards predictor?](https://arxiv.org/abs/1910.02369).

## Research Team

- [Osame Kinouchi](https://publons.com/researcher/1537219/osame-kinouchi/);
- [Adriano J. Holanda](https://publons.com/researcher/1343572/adriano-de-jesus-holanda/);
- [George C. Cardoso](https://publons.com/researcher/1515858/george-c-cardoso/).

## Reproducibility

The results can be totally reproduced by performing the following instructions:

### Automatic

To reproduce the experiment, clone the repository, install `make`,
[`cweb`](https://www-cs-faculty.stanford.edu/~knuth/cweb.html) and a C
compiler and run

````
$ make
````

### Manual

The following steps are less automatized but the dependencies are
decreased:

- Download the data using the [link](https://drive.google.com/uc?export=download&id=1yuaGztX44jec657z_mSRcVv4cWG1sBaG);
- Unzip the downloaded data;
- Download the program binary [Linux-x86_64](k-nobel) or
  [Windows-x86_64](k-nobel.exe) according to the platform;
- Run the program in the same directory where the data were extracted.

## Documentation

- [Program documentation](k-nobel.pdf).

## Contributors

- [Luis Fernando Castro](https://github.com/ferdox2) - [fixes some
  grammatical and spelling
  errors](https://github.com/ajholanda/k-nobel/pull/9/).

## Reference

- [A simple impact index for scientific innovation and
  recognition](https://arxiv.org/abs/1609.05273v2). Osame Kinouchi,
  Leonardo D. H. Soares, George C. Cardoso. arXiv:1609.05273v2, 2017.