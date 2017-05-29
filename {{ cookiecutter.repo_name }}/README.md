{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}

Project Organization
------------

    ├── LICENSE
    ├── Makefile           				<- Makefile with commands like `make data` or `make train`
    ├── README.md          				<- The top-level README for developers using this project.
    ├── data                                                                    
    │   ├── external       				<- Data from third party sources.                   
    │   ├── interim        				<- Intermediate data that has been transformed.     
    │   ├── processed      				<- The final, canonical data sets for modeling.     
    │   └── raw            				<- The original, immutable data dump.               
    │                                                                           
    ├── notebooks          				<- Jupyter notebooks. Naming convention is a number (for ordering),
    │                      	  			 the creator's initials, and a short `-` delimited description, e.g.
    │                      	  			 `1.0-jqp-initial-data-exploration`.              
    │                                                                           
    ├── support            				<- Data dictionaries, manuals, and all other explanatory materials.
    │                                                                           
    ├── reports            				<- Generated analysis as HTML, PDF, LaTeX, etc.     
    │   └── figures        				<- Generated graphics and figures to be used in reporting
    │                                                                           
    ├── requirements.txt   				<- The requirements file for reproducing the analysis environment, e.g.
    │                      	   			generated with `pip freeze > requirements.txt`   
    │                                                                           
    └── code               				<- Source code for use in this project.            
        ├── __init__.py    				<- Makes src a Python module                        
    	│                                                                           
        ├── analyses       				<- Scripts to analyze the data                      
        │                                                                       
        ├── base        			   	<- Base python functions used to analyze the data   
        │   ├── __init__.py
	    │   ├── formatting_basics.py    <- Data from third party sources.
	    │   ├── plotting_basics.py      <- Intermediate data that has been transformed.
	    │   └── statistics_basics.py    <- The original, immutable data dump.
        │
        ├── data       					<- Scripts to format and transform raw data
        │   └── make_dataset.py
        │
        ├── presentation         		<- Scripts generate experimental trials and present the experiment
        │   ├── present_experiment.py	<- Experiment presentation script
	    │   ├── generate_trials.py		<- Trial generation script
	    │   ├── img      				<- Stimuli used
	    │   └── trials    				<- Trials generated
        │
        └── visualization  				<- Scripts to create exploratory and results oriented visualizations
            └── visualize.py
    


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
