# Personalized Job Recommendation System

### Installation
```
git clone https://github.com/KunSu/Personalized-Job-Recommendation-System.git
cd Personalized-Job-Recommendation-System
```

### For giving the sample data
unzip the "sample_data.zip" under the data folder

### For Python:
```
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
```

Deactivated the environment
```
deactivate
```

Delete the environment completely 
```
rm -r venv
```

How to pull your python dependencies into requirements.txt
```
pip freeze > requirements.txt
```

### For Conda:
Create a new environment
```
conda create -n conda-venv python=3.7
conda activate conda-venv
while read requirement; do conda install --yes $requirement; done < requirements.txt
```

How to pull your conda dependencies into requirements.txt and etc
```
conda list -e > requirements.txt
conda deactivate
conda remove conda-venv
```

Git Workflow 
https://www.atlassian.com/git/tutorials/comparing-workflows
