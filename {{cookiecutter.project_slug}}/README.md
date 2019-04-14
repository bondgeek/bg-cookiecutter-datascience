# {{cookiecutter.title}}

{{cookiecutter.description}}

## Run Jupyter Notebooks

`> ./run_notebook.sh`

Note: the above script will define `PYTHONPATH` so that notebooks in the `notebook/` directory can import modules defined under `src/`



## Directory structure

Models: refers to the artifacts that result from training -- usually a data structure of some sort.  Ho

```
/
├── README.md
├── data
│   ├── external
│   ├── interim
│   ├── processed
│   └── raw
├── models
├── notebooks
│   └── {{cookiecutter.project_slug}}.ipynb
├── requirements.txt
├── run_notebook.sh
└── src
    ├── __init__.py
    └── {{cookiecutter.module_name}}
    ├── __init__.py
    .. *.py files go here
```
