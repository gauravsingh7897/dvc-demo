
create new conda environment and activate it

```bash
conda create -n wineq-mlops python=3.7 -y
conda activate wineq-mlops
```

create requirements file and install it
add to requirements file -> 
dvc
dvc[gdrive]
sklearn

```bash
touch requirements.txt
pip install -r requirements.txt
```

Initialize First Commit

```bash
git init
dvc init
dvc add data_given/winequality.csv
git add .
git commit -m "First Commit"
```

Update README.md
```bash
git add . && git commit -m "Updated README.md"
```

To push into remote

```bash
git remote add origin https://github.com/gauravsingh7897/dvc-demo.git
git branch -m Main
git push origin main
```

Add parameters in params.py and commit it...

create get_data function to load process data.

Now create load_data file to load data from source and save it and reproduce results.

```bash
dvc repro
```

Splitting Data and Saved it to Prepared Folder and git add and commit and push to origin.