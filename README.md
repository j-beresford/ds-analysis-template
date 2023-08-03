# ds-analysis-template

Template repo for my personal projects. 

Conda managed virtual environment with pre-commit hooks runing checks for black formatting. 

To create a virtual environment, change the name in `environment.yml` and run:
```
conda env create -f environment.yml
```
To activate the environment:
```
conda activate <env_name>
```
To install a new package:
```
conda install <package_name>
```
Then update the `environment.yml` file with:
```
conda env export > environment.yml
```

