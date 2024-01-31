# transformers-example2024
Explaining Natural Language Processing Examples with Transformers and other effective Neural Network Models

## Project Description

Small examples of Transformer models type using _transformers_ or _torch_ libraries, and its visualization with _bertviz_ library.

## Requirements

* jupyter
* transformers
* bertviz


## How to dev

1. Move to the root dir of the project and create and activate your virtual environment.

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

2. From the activated project virtual environment, install the requirements:

   ```bash
   pip install -r requirements/base.txt
   pre-commit install #  important do not forget
   ```

3. After install the requirements run notebook:

   ```bash
   cd development
   jupyter notebook
   ```

Then you can modify the notebooks inside development folder.

## Project Roadmap

- Pick 3 different NN models to visually show why they work for the problem for which they are designed, that is, try to explain their operation in the simplest way possible.
- Design 3 different Notebooks for each NN
- Publish the conclusions in LinkedIn and discuss publicly

## Project Status

Currently is under development

## Authors

* Abel Meneses Abad
## Acknowledgments

Thanks to all authors of _Natural Language Processing with Transformers_ in which examples is based the first small test.