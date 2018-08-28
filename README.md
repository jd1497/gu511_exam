# Georgetown University Math & Statistics 511 EXAMS

the `jupyter` notebooks in this repository are the exams for the GU511 course. each file exists in two states:

1. rendered: click on any of the `.ipynb` files in the repo above and you will be taken to a rendered version of the notebook for your own use
2. executable: download any of these `.ipynb` files and launch them in an active `jupyter` notebook server session to interact with them


## advanced usage: running these notebooks locally

if you would like to run these locally, you need to make sure your environment contains the appropriate packages. first, create a new environment from scratch

```bash
conda create -n [YOUR ENVIRONMENT NAME] python=3 jupyter
conda activate [YOUR ENVIRONMENT NAME]
```

this will create an environment (named `YOUR ENVIRONMENT NAME`.

if you are unable to execute and `import` statements in the notebook itself, take that package name and install it via

``` bash
conda install [PYTHON PACKAGE NAME]
```
