Created a environment:

```bash
conda create -n Mlops python=3.7 -y
```

activate env
```bash
conda activate Mlops
```

create and install requirements.txt
```bash
pip install -r requirements.txt
```

created template.py to create a folder structure
Initialize git and dvc

Initialize git and dvc

```bash
git init
dvc init
dvc add input/winequality.csv
git add .
git commit - m "first commit"
```

