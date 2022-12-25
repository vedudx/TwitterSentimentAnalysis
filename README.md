# DSResearch

## Getting Started

### Devcontainers

Our repo has devcontainers which can be used to quickly spin up a development environment. Before you get started, make sure you have a working version of Docker.

To get started, open up the repo in VSCode, then `F1 > Dev Containers: Reopen in Container`. Once all the images are downloaded, you are done!

### Non-devcontainers

Make sure you have Python 3.8 or later installed, and the necessary extensions for Python and Jupyter notebook. Conda virtual environments are recommended since they contain preinstalled with most of the libraries.

## Raw Data

All our raw data in `data/` is stored using Git LFS, so they are not downloaded when you `git clone`. To download them, run the following:

```bash
git lfs pull
```
