# Supplementary Codes for the K-EmoPhone

This repository is for supplementary codes used to explore and analyze the **K-EmoPhone Dataset**.

* Description of the dataset: TBD
* Dataset URL: [https://doi.org/10.5281/zenodo.7606611](https://doi.org/10.5281/zenodo.7606611)

---
## Environment
We have run this code under the environment as below:
* OS: Ubuntu 20.04 installed with Windows Subsystem for Linux (WSL)
    * This code highly depends on a python multiprocessing library, [ray](https://www.ray.io/) which does not fully support Windows OS.
* CPU: AMD Ryzen 9 5900x 12-Core
    * This is not mandatory; you can run this code (with a minor modification) although you have the smaller number of cores.
* RAM: 128GB
    * This is not mandatory; we expected about 40GB of RAM to be required (but not tested).

In addition, you need to install [conda](https://conda.io/projects/conda/en/latest/index.html#) for managing packages and virtual environment.

## HOW-TO
1. Download the K-EmoPhone dataset.

2. Download this repository
```console
$ git clone https://github.com/Kaist-ICLab/K-EmoPhone_SupplementaryCodes.git
$ cd K-EmoPhone_SupplementaryCodes
```
3. Replicate our conda environment ([environment.yml](https://github.com/Kaist-ICLab/K-EmoPhone_SupplementaryCodes/blob/main/environment.yml)), referring to [this](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#create-env-from-file).

4. Run your own Jupyter environment.

5. Then, open [analysis.ipynb](https://github.com/Kaist-ICLab/K-EmoPhone_SupplementaryCodes/blob/main/analysis.ipynb).

