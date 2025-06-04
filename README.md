# proj-ai-ml

Kyle Johnston's repository for the **Projects in AI and Machine Learning** course at Rensselaer Polytechnic Institute.

This repository contains assignments and independent projects developed throughout the course.

## Environment and Tools

Unless otherwise specified:

- Language: Python 3.12.9  
- Framework: PyTorch 2.7.0+cu128  
- CUDA Version: 12.9  
- Hardware: Local machine with NVIDIA RTX 4080 Super GPU  
- Package management: Miniconda, with environments managed per project (`environment.yml` will be in each subfolder)

## Repository Structure

The current folder layout is as follows:

```
proj-ai-ml/
└── projects/
    └── HIGGS-classifiers/
        ├── data/
        ├── lin-reg/
        └── ensemble/
        
```

Each homework or project folder may contain its own scripts, notebooks, datasets, or documentation.

## Replicating project environments

To replicate a project environment:

1. Navigate to the desired folder.

2. Create and activate the environment:

```
conda env create -f environment.yml
conda activate <env-name>
```
Replace `<env-name>` with the environment name specified in the `environment.yml` file.

Run notebooks or scripts as within that environment.

## Notes
All code is tested and run on a machine with a CUDA compatible GPU.

Variations from the default specifications will be noted in the respective folder's README file.

## License
This repository is licensed under the MIT License.