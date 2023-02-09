create env
activate env
create requirements.txt
install the requirements
create templates

Download the data from kaggle (wine quality)

git init 
git commit
dvc init
dvc add datagiven/winequality.csv

create a file in src directory to read the parameters

load data to source directory

split data x and y


after creating report 
    -dvc metrics show (metrics show)
    -dvc metrics diff (difference between old and new)

if you want make changes and make experiments then 
    - make the required changes 
        - dvc repro


TESTING 
-PYTEST AND TOX

1) to run the test in terminal (pytest -v)


Creating setup
setup(
    name="src",
    version="0.0.1",
    description="its a mlops package",
    author="vinay",
    packages=find_packages(),
    license="MIT",
)

pip install -e . [to run the setup.py]

setup file is created 
--> cd..
--> python 
--> import src

install jupyter notebook lab
- pip install jupyterlab

jupyter-lab notebooks/ -- to open the notebook