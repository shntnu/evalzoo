# Using matric in a Juptyer notebook

## Setup the environment

Set up the conda environment using the `environment.yml` file in this directory.

```bash
mamba env create -f environment.yml
```

If new dependencies are added to the `environment.yml` file, update the environment using

```bash
mamba env update -f environment.yml
```

To reinstall the environment from scratch, use

```bash
mamba env remove -n evalzoo
mamba env create -f environment.yml
```

To specify a specific version of python, use

```bash
mamba env create -f environment.yml python=3.8
```

To launch the environment, use

```bash
conda activate evalzoo
```

Start R within the conda environment

```bash
R
```
