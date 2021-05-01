create env 

```bash
conda create -n wineq python=3.7 -y
```

activate env
```bash
conda activate wineq
```

created a req file

install the req
```bash
pip install -r requirements.txt
```
download the data from 

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing

```bash
git init
```
```bash
dvc init 
```
```bash
dvc add data_given/winequality.csv
```
```bash
git add .
```
```bash
git commit -m "first commit"
```

for stages in Pipeline :
```bash
dvc repo
```

Check difference in metrics:
```bash
dvc metrics diff
```

Display Metrics
```bash
dvc metrics show
```

tox command:
```bash
tox
```

For Rebuilding:
```bash
tox -r 
```

pytet command:
```bash
pytest -v
```

setup commands
```bash
pip install -e .
```

Build your own commands
```bash
pip setup.py sdist bdist wheel
```
