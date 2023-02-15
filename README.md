
## Create virtual environment

```batch

python -m pip install --user -U virtualenv

python -m virtualenv .environment

```

### Run env in linux

```bash
source .environment/bin/activate
```

### Run env in windows

```batch
.\.environment\Scripts\activate
```

```
python -m ipykernel install --user --name=venv
```

### Run jupyter

```bash
notebook jupyter
```

### Dependencies
```
python -m pip install jupyter matplotlib numpy pandas scipy scikit-learn seaborn corpus
```
