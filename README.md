#  Tutorial
___
To install poetry  
```Shell
$ pip install poetry
$ poetry config virtualenvs.in-project true
```
## To create new poetry repo
```python  
$ poetry new <repo_name>
```


This will create the poetry-demo directory with the following content:


poetry-demo  
├── pyproject.toml  
├── README.md  
├── poetry_demo  
│   &emsp; └── __init__.py  
└── tests  
    &emsp; &emsp;└── __init__.py  

The pyproject.toml file is what is the most important here. This will orchestrate your project and its dependencies.

Initialising a pre-existing project
```
$ cd pre-existing-project
$ poetry init
```
## Using Poetry run

```Shell
$ poetry run python your_script.py
$ poetry run pytest
```

## Activating virtual environment
To activate your virtual environment use <i> $ poetry shell<i/>
and to exit from virtual env use <i> exit </i>

```Shell
$ poetry shell
$ exit
$ deactivate
```