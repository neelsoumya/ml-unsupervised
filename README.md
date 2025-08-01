# ml-unsupervised

## Introduction

This repository contains the materials for the course on applied unsupervised machine learning.

**Course Developers**: see our [guidelines page](https://cambiotraining.github.io/quarto-course-template/materials.html) if contributing materials.

These materials are released under a [CC BY 4.0](LICENSE.md) license.

## Steps for course developers

* Create a Python virtual environment

```bash
   python3 -m venv .venv
```

```bash
source .venv/bin/activate
```

* Install all requirements

```bash
   pip install -r requirements.txt
```

* Install Quarto and VS Code

<!--* Preview Quarto markdown-->

* Change the `.qmd` files

* Render using quarto

```bash
quarto render
```

* Commit files in `_freeze` folder and any other `.qmd` files changed

```bash
chmod 755 gitshell.sh
./gitshell.sh
```

## Contact

Soumya Banerjee

sb2333@cam.ac.uk
