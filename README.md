# Follow-up workshop: Interchange Showcase
Materials for 2022 Interchange workshop, held on September 28, 2022, at 3:00 PM UTC

## Installation instructions

Create a conda environment using the provided `environment.yaml` file:

```shell
$ conda env create --file environment.yml
```

Recall that if you are using the `osx-arm64` platform, you may need to prepend this command with `CONDA_SUBDIR=osx-64`.

Then, activate the environment:
```shell
$ conda activate interchange-workshop
```

## Contents

This workshop covers the following topics:
* Summarizing the key objectives and current scope of Interchange
* Demonstrating how to use its high-level API points
* Highlight key (current) functionality
* (Time-permitting) preview some experimental features

Instructive notebooks we will be going through today:
* `notebooks/units.ipynb`: Using unit-wrapped quantities used throughout the OpenFF software stack
* `notebooks/objectives.ipynb`: Highlighting key objectives of the project
* `notebooks/construction.ipynb`: Creating `Interchange` objects
* `notebooks/exports.ipynb`: Exporting `Interchange` objects to molecular simulation engines
* `notebooks/exploration.ipynb`: Inspecting potential handlers directly

Examples we will be going through:
* `notebooks/protein_ligand.ipynb`: Createing a protein-ligand complex from prepared structures
* `notebooks/virtual_sites.ipynb`:
