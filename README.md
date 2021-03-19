
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

git init

dvc init

dvc add data_given/winequality.csv

git add .
git commit -m "first commit"

### online updates for readme
git add . && git commit -m "update Readme.md

git remote add origin https://github.com/snar2019/MLOPS_dvcproject.git
526  git branch -M master
527  git push -u origin master
