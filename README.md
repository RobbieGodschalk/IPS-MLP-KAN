# IPS-MLP-KAN
Comparison between deep learning networks using MLPs or KANs for the purpose of indoor localization systems based on WiFi fingerprinting.

# External material
For benchmarking the different implementations, a dataset from [Zenodo](https://zenodo.org/) was used.
While this is not included in the repository, it can be downloaded from [this link](https://zenodo.org/records/3748719#.Y1agti0RpmA).
The version used in this research is version 2.2, downloaded on 28/05/2024. 

For the implementation of KANs, the choice was made to use [FastKAN](https://github.com/ZiyaoLi/fast-kan) due to its better training performance, which better
suits the training methods of the MLP networks and therefore allows a fairer comparison. FastKAN is based on the original [pykan](https://github.com/KindXiaoming/pykan) implementation. 