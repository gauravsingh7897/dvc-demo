
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
