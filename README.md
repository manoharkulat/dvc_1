create env
```bash
conda create -n wineq python=3.7 -y
```

activate env
```bash
conda activate wineq
```

create req file

install req
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
dvc add data_given/winequality_red.csv
```
```bash
git add .
```
```bash 
git commit -m "first commit"
```

oneliner updates for readme
```bash
git add . && git commit -m "update Readme.md"
```
```bash
git remote add origin https://github.com/manoharkulat/dvc_1.git
```
```bash
git branch -M main
```
```bash
git push -u origin main
```
tox command
```bash
tox
```
for rebuilding -
```bash
tor -r
```
pytest command
```bash
pytest -v
```
setup commands -
```bash
pip install -e .
```
build your own package commands-
```bash
python setup.py sdist bdist wheel
```


