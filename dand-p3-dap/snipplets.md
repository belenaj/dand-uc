
# Conda Cheatsheet


#### Saving and loading environments

You can save the packages to a YAML file with

`conda env export > environment.yaml`

The first part conda env export writes out all the packages in the environment, including the Python version.

This file can now be shared and others will be able to create the same environment you used for the project.

To create an environment from an environment file use:

`conda env create -f environment.yaml`

This will create a new environment with the same name listed in environment.yaml.

#### Listing environments
If you forget what your environments are named (happens to me sometimes), use

`conda env list`

to list out all the environments you've created.


#### Removing environments
If there are environments you don't use anymore,

`conda env remove -n env_name`

will remove the specified environment



# Jupyter Notebooks


#### Launching the notebook server
To start a notebook server, enter  
`jupyter notebook`  
 in your terminal or console.


To open notebooks in an specific folder type:   
`jupyter notebook <yournotebook>.ipynb`  

##### Converting notebooks
Since notebooks are JSON, it is simple to convert them to other formats.   

Jupyter comes with a utility called nbconvert for converting to HTML, Markdown, slideshows, etc.

For example, to convert a notebook to an HTML file, in your terminal use

`jupyter nbconvert --to html notebook.ipynb`
