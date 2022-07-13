# datasets-gcims-demo
Few samples of different complexities to demonstrate the GC-IMS package.


This repository contains few samples of different complexities that can be used to showcase the GCIMS package features.

## Contributing more samples

Avoid contributing more samples if you can.

git is not meant to store binary files.

If you have a proper whole dataset to share, please use https://zenodo.org/, https://www.ebi.ac.uk/metabolights/ or any other proper data repository.

GitHub has multiple limits:

- Each file in the git repository can't take more than 25MB.
- The git repository (including all its history) shouldn't take more than 1GB and can't take more than 5GB
- GitHub has limits on bandwidth: If you put a dataset here that is downloaded too often, GitHub may start blocking the downloads.

Neither git nor GitHub were meant to store datasets. This repository is a convenient way to store a few samples, but it's not the best way.

A better approach is to store the dataset in a FAIR repository. Then, write a function in the package that needs the data that takes care of downloading it.

