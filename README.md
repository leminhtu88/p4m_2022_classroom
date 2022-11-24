# Python for managers | Classroom | 2021

## Hello!  

Welcome to the git repository for the 2021 python for managers ``#p4m`` hackaton.  
Here you can find all the necessary material for the ``#p4mclassroom``.  
You will learn basics about the programming language Python and some of its core libraries such as pandas, matplotlib and scikit-learn.  


## Installation and Setup

1. Clone the repository via the Anaconda prompt. If you have never worked with GitLab before, please use the clone via HTTPS option:  
```$ git clone https://code.exaas.bosch.com/p4m/p4m_2022_classroom.git```  

2. Install all packages which are required for the challenge:
* Change your current directory to the repository folder: ```(base) $ cd p4m_2022_classroom```  
* Create a virtual environment via Anaconda: ```(base) $ conda create -n p4m python=3.7.6 -y```
* Activate the environment: ```(base) $ conda activate p4m```
* Install the requirements via pip: ```(p4m) $ pip install -r requirements.txt```

Now you are ready to start hacking!  

### Starting jupyter-lab  

Start the jupyter-lab programming environment via the anaconda promt. Please make sure the (p4m) environment is activated.  
```(p4m) $ jupyter-lab```  
This comand will open your browser. In there you find everything that you need. Open a new jupyter notebook or a python script.  
Good luck with the challenge!

## Project Structure

Before you start coding take a moment to make yourself familiar with the project structure:  
``data/`` - Here you can find all relevant data which we will use to train our machine learning model.  
``notebooks/`` - The place for your notebooks (the go-to document for data scientists - it can be used to code, documentation as well as deliverable results). Every file ending with .ipynb goes in here.  
``scripts/`` - The place for raw python code, if you prefer not to use a notebook. Every file ending with .py belongs here.  
``references/`` -If you find additional material which is useful for a better understanding of the project, you can put these files here.  
``results/`` - Put your challenge results (e.g. result plots, trained models, ...) in here.  
``.gitignore`` - Can be ignored for now.  
``requirements.txt`` - File to setup and install all required python packages (See Installation and Setup).  
``README.md`` - The file you are reading right now.  

---
### Known Bugs and Workarounds
git clone via https:

Workaround for SSL errors:
```$ git config --global http.sslVerify false```  

---
