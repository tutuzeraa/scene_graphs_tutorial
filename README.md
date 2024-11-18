# Mastering Scene Understanding: Scene Graphs to the Rescue - SIBGRAPI 2024 Tutorial

This is the official repository for the SIBGRAPI 2024 Tutorial [*Mastering Scene Understanding: Scene Graphs to the Rescue*](https://ieeexplore.ieee.org/document/10716310).

## Notebooks implemented as tutorials

In this tutorial, we have several Jupyter-style notebooks demonstrating the following applications:

- Scene Graph Generation:

    - Two-stage method: [Notebook](./scene_graph_generation/SGG_Two-Stage_tutorial_SIBGRAPI2024.ipynb).

    - One-stage method: [Notebook](./scene_graph_generation/SGG_One-Stage_tutorial_SIBGRAPI2024.ipynb).

- Image Captioning: [Notebook](./image_captioning/image_captioning.ipynb).

- Image Generation: [Notebook](./image_generation/tutorial_image_generation_with_sgs.ipynb).

- Image Retrieval: [Notebook](./image_retrieval/tutorial_image_retrieval_with_sgs.ipynb).

- Human-Object Interaction: [Notebook](./human_object_interaction/SGG_HOI.ipynb).

## Initializing the submodules

After clonning the repository, run the following commands to initalize and clone the submodules:

```bash
$ git submodule init
$ git submodule update
```

## Environment setup

For this environment setup, we use [Micromamba](https://mamba.readthedocs.io/en/latest/index.html). To install micromamba, you can follow the installation guide [here](https://mamba.readthedocs.io/en/latest/installation/micromamba-installation.html).

Then, create a new environment based on a YAML file description, like:

```bash
$ micromamba create -f base_environment.yaml
```

In order to have success when importing environments descripted, run the following command to change your micromamba channel priority config:

```bash
$ micromamba config set channel_priority flexible
```
