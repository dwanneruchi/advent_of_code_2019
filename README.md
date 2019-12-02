# advent_of_code_2019
Location for storing output from: https://adventofcode.com/


## Working in virtual env: 
```bash
# create venv in dir
python -m venv advent

#activate
source advent/Scripts/activate

# install stuff once activated
pip install -r requirements.txt

```

## Build kernel for virtual env to use in jupyter notebook: Run within venv

```bash
pip install ipykernel
pip install jupyter
python -m ipykernel install --user --name=advent
jupyter notebook
```
