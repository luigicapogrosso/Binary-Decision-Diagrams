#  Binary Decision Diagrams (BDDs) #

This is the branch that contains the source files for the course website.

The website is built using [MkDocs](https://www.mkdocs.org/) and the [Material
for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme.

To build the website locally, you need to have Python installed on your machine.


## Installation ##

To install the required dependencies, run the following command:

```bash
conda create -n BDD python=3.10
conda activate BDD
pip install -r requirements.txt
```

## Development ##

To run the website locally, run the following command:

```bash
mkdocs serve
```

## Publishing the website ##

To publish the website, run the following command:

```bash
mkdocs gh-deploy
```
