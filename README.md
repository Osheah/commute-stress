# Commuting Stress
Project for GMIT Course Programming for Data Analysis


# Programming for Data Analysis Project 2018 - Create a dataset by simulating a real world phenomenon



## Requirments of the assignment

   1. Create a dataset by simulating a real world phenomenon. Model the data via python in particular numpy.random is suggested. 
   2. Choose a real world phenomenon that can be measured and for which you could collect at least  one hundred data points across at least four different variables.  
   3. Investigate the type of variables involved, their likely distributions, and their relationshps with each other. 
   4. Synthesise/simulate a data set as closely matching their properties as possible. 
   5.  Detail your research and implement the simulation in a jupyter notebook. The dataset itself can simply be displayed in an output cell within the notebook. 
   **The project is about simulation so you must simulate the data** If you base your data on real world initially then references it accordingly. 

### Other requirments 

   1. Use github version control in public repo
   2. Upload repo url to the assignment section on student page. 
   3. Commit history of at least 10
   4. Meaningful commit messages
   5. Assignment deadline 14/12/2018 at midnight
   6. README file containing an explanation of what is in the repository and how to run jupyter notebook. 
   7. Jupyter notebook with the project
         * Explain the dataset
         * Have well conceived, interesting and well researched project
         * Assignment covers jupyter notebook so include fancy stuff like images, links, code and plots
         * Any python package that you fancy. 
   8. gitignore file



## Getting Started

First get the required software, as I have windows 10 on my pc I'm only adding links to this version of various software. 

### Prerequisites

This project requires

   * Jupyter notebook
   * iPython via Anaconda and other python packages like  numpy
   * cmder 
   * Github account
    
Anaconda has python, ipython, jupyter notebook and a large number of common python packages required in Data Analysis. 

   1. Get anaconda 3.7 version for windows [Anaconda](https://www.anaconda.com/download/)
   2. Get git 2.19.1 [Git](https://git-scm.com/download/win)
   3. Get cmder 1.3.6 [Cmder](https://github.com/cmderdev/cmder/releases/download/v1.3.6/cmder.zip) - Optional (cmder comes with git so you can drop option 2 above if you go with option 3).  
   4. Get github account - set up github account and create a repo [Github](https://github.com/)


### Installing

Install the above packages. Any problems google it. Update any packages; From cmder type... 

```
conda update –all 
git - version

```

## Repository structure

The gitignore file ignores the .git and .ipynb_checkpoints in the local folder. Python files are also ignored. A standard gitignore file was used. It can be found here [Python gitignore](https://github.com/github/gitignore/blob/master/Python.gitignore) 


* .gitignore - gitignore file taken from [gitignore](https://github.com/github/gitignore/blob/master/Python.gitignore)
* License - GNU GENERAL PUBLIC LICENSE Version 3
* README.md - this readme
* project.pdf - a pdf of the assignment
* research - a folder containing pdf's Commuting-relatedstressConsequencesandimplications.pdf - a report in which the data in this repo was modelled and one titled oecdwellbeing.pdf.
* **commute-stress.ipynb** - The main body of the assignment


## Jupyter 

The main body of work is in the jupyter notebook ***commute-stress.ipynb***. 


### Running a Jupyter notebook


#### Start jupyter notebook

There are two ways to start jupyter notebook. 

   1. Via the Anaconda App 
   2. Via the command line on cmder. 

I will describe the cmder approach.


Open cmder in your home directory or from a folder within the home directory. Jupyter notebook will only be able to access this folder and any sub folders. For example ...
```
C:\Users\Username\Desktop\WorkFolder\github\
```

   * Create a repo on github [GitHub Repo](https://github.com/Osheah/commute-stress)
   * Clone the repo on github by clicking the green clone or download link
    
Go to cmder and enter ... for example

```
git clone https://github.com/username/repo-name.git

```
Open jupyter notebook using the command...

```
jupyter notebook

```
A browser should open linking the current directory in cmder to an jupyter version of windows explorer. Jupyter notebook will open at its home page http://localhost:8888/tree


### create a jupyter notebook

Navigate to your cloned folder from within the Jupyter notebook home. On the right click the 'new' button and select python 3. A new jupyter notebook for python 3 will open with the default title *untitled*. Click on the name *untitled* and rename it e.g. projectnaem.ipynb. Details on how to create cells in jupyter notebook can be found here [Jupyter Notebook Documentation](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html#basic-workflow). Save any work (although it is usually saved automatically). 

### ending a jupyter notebook session

Save any unsaved jupyter notebooks. Close jupyter notebook windows in your browser. Go to cmder and enter **control + c** i.e the control key and c key pressed at the same time. This shuts the ipython kernal that jupyter uses. Upload your notebook to github via the commands below; Make sure that you are in the directory that git is initialised in e.g. C:\Users\Username\Desktop\Workfolder\projectfolder\ for example...

```
git status
git add .
git commit -m "add a relevant commit message"
git push
```

### opening a jupyter notebook

Jupyter notebooks have the extension ipynb. When you find a notebook that you want to look at or edit, don't click on it; Instead right click and save it to your local pc. Then open jupyter notebook via the cmder commandline and navigate to the notebook. NB; **before opening the notebook make sure the notebook is saved in a sub directory of the cmder path**. Jupyter notebooks cannot access any files that are not within the path when the kernal is called. 

## Issues
1. The ratings for the distance and duration band have to be tweeked more to better match the expected shape
  


## Authors

* **Helen O'Shea** - *helen.oshe@gmail.com* - [Osheah](https://github.com/Osheah/)


## License

This project is licensed under the  GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007 - see the [LICENSE.md](LICENSE.md) file for details

