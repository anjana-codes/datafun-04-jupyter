# Project 4: datafun-04-jupyter
Title: Specification for Project 4 Jupyter Notebook

 Anjana Dhakal, May 20,2024

## Overview
Project 4 uses a combination of Python and Markdown to create an initial data story in a Jupyter Notebook. The project includes a project virtual environment with popular libraries for data analytics including pandas, matplotlib, and seaborn, and introduces a common process for starting exploratory data analysis projects.

## Objectives
Develop a Jupyter Notebook that demonstrates skills with Jupyter and guided exploratory data analysis.

## Create GitHub Repository
```
 GitHub Repository: datafun-04-jupyter
 Documentation: README.md
 Notebook: anjana_eda.ipynb
```

## Clone to VS Code 
```
git clone site_URL
```

## Adding files 
- Add a .py file to work in.
- Add a requirements.txt file to hold the required project modules.
- Create a .venv to act as the virtual environment.
- Include a .gitignore file to exclude the .venv file from the rest of the Python environment.
  
## Create Project Virtual Environment
```
 python -m venv .venv
 source .\.venv\Scripts\activate
```

## Install all Required Packages
```
 python -m pip install -r requirements.txt
 python -m pip freeze > requirements.txt
```

## Git add and commit
```
git add .
git commit -m "final project"
git push origin main
```
## Source
This project was built to the following specifications: https://github.com/denisecase/datafun-04-spec
