
create env

```bash
conda create -n wineq python=3.7 -y
activate env
```bash
conda activate wineq

created a req file
install the req
```bash
pip install -r requirements.txt
```
download the data from this link
https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing
```bash
git init
```bash
dvc init
```bash
dvc add data_given/winequality.csv
```bash
git add .
```bash
git commit -m "first commit"

### oneline updates for readme
<<<<<<< HEAD
```bash
=======
>>>>>>> b9d6a0b482eeb2f2f1de4a6ef53efe20743daece
git add . && git commit -m "update Readme.md
```bash
git remote add origin https://github.com/snar2019/MLOPS_dvcproject.git
git branch -M master
git push -u origin master
```bash

tox command 
```bash
tox -r 
```
pytest command
```bash
pytest -v
```

setup commands -
pip install -e .
```

build your own commands-
```bash
 python setup.py sdist bdist_wheel
```