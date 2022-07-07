# Modelo HIAAC de Estrutura de Repositório

**Nota**: _Esse modelo usa poetry. Se você prefere usar pip, vá para a brach adequada clicando aqui._ TODO

Nós criamos um modelo de estrutura de repositórios baseado no coockiecutter para projetos Python. Entretanto, seu projeto não precisa ser em Python, mas esteja ciente que alguns modelos de diretórios ou até mesmo arquivos possuem padrões para projetos em Python. Bastando, então, excluir de acordo com a sua necessidade.

## Ferramentas usadas neste projeto

* [Poetry](https://towardsdatascience.com/how-to-effortlessly-publish-your-python-package-to-pypi-using-poetry-44b305362f9f): Gerenciamento de Dependências.
* [Hydra](https://hydra.cc/): Gerenciamento de Arquivos de Configuração.
* [pre-commit plugins](https://pre-commit.com/): Automatização da formatação e revisão de código.
* [DVC](https://dvc.org/): Controle de Versionamento de Dados. 
* [pdoc](https://github.com/pdoc3/pdoc): Criação automática de uma documentação de API.

## Requisitos

* Python >= 3.5
* Pacote Python Cookiecutter >= 1.4.0:
  * Usando pip:

        pip install cookiecutter
  * Usando Anaconda:

        conda config --add channels conda-forge
        conda install cookiecutter

Pronto, agora você será capaz de reproduzir o modelo e criar o seu próprio modelo para projetos e artigos.

## Como começar um novo projeto usando o modelo do HIAAC

Depois que os requisitos acima estão satisfeitos, basta ir em sua linha de comando e digitar a instrução abaixo. Não existe a necessidade de criar uma pasta, o cookiecutter já vai fazer isso por você.

`cookiecutter https://github.com/sildolfogomes/hiaac-template.git`

### Exemplo de saída

TODO

## Estrutura do Diretório

      .
      ├── LICENSE
      ├── Makefile           <- Makefile with commands like `make data` or `make train`
      ├── README.md          <- The top-level README for developers using this project.
      ├── data
      │   ├── external       <- Data from third party sources.
      │   ├── interim        <- Intermediate data that has been transformed.
      │   ├── processed      <- The final, canonical data sets for modeling.
      │   └── raw            <- The original, immutable data dump.
      │
      ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
      │
      ├── models             <- Trained and serialized models, model predictions, or model summaries
      │
      ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
      │                         the creators initials, and a short "-" delimited description, e.g.
      │                         "1.0-jqp-initial-data-exploration".
      │
      ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
      │
      ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
      │   └── figures        <- Generated graphics and figures to be used in reporting
      │
      ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
      │                         generated with "pip freeze > requirements.txt"
      │
      ├── setup.py           <- Make this project pip installable with "pip install -e"
      ├── src                <- Source code for use in this project.
      │   ├── __init__.py    <- Makes src a Python module
      │   │
      │   ├── data           <- Scripts to download or generate data
      │   │   └── make_dataset.py
      │   │
      │   ├── features       <- Scripts to turn raw data into features for modeling
      │   │   └── build_features.py
      │   │
      │   ├── models         <- Scripts to train models and then use trained models to make
      │   │   │                 predictions
      │   │   ├── predict_model.py
      │   │   └── train_model.py
      │   │
      │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
      │       └── visualize.py
      │
      └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io
