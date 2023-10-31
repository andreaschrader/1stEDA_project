# :wave: Welcome

# EDAsale-types_detailed_analysis

This repository is my first repository for an EDA project and my first EDA for a stakeholder in a bootcamp in 2022.  
Thank you to [neuefische](https://www.neuefische.de/en) and all participants for this journey!

In the workflow and assignment (workflow.md, assignment.md), the project and tasks are outlined.  
The dataset is the well known "King County House Data" and the task included selecting a stakeholder and finding, analysing and extracting information in the data in line with the stakeholders needs and requirements.

My specific project can be characterized as follows:  

# EDA project - Andrea Schrader

**Dataset:**
 "King County House Data" on home sales in King County (USA)  
The available columns of this dataset are described in column_names.md.  

<br>

**Stakeholder choice**   
    * Person chosen: Erin Robinson   
    * Stakeholder type: Buyer   
    * Stakeholder Description: Invest in poor neighborhood, buying & selling, costs back + little profit, socially responsible.   

---  

**Idea for my analysis:**   

I focussed on sales types. In particular, I eventually gained insights from multi-sale houses in King County as compared to single-sale houses for both: financial and social gain.    

This matches the stakeholders description as a buyer who is buying houses and aims to get money back plus a little profit from the respective sale in a socially responsible way.  

---

[A minimal notebook](./EDA.ipynb) was provided as a template for the assignment. The [optional material](./optional) was not used in this assignment.
The [jupyter notebook](./EDAsale-types_detailed_analysis.ipynb) contains the analysis conducted during this 2 day assignment of a bootcamp.
In parallel a presentation was prepared.  
The project ended with [presentation](./EDA_project_presentation.pdf)s of all participants in front of the respective stakeholder.

Before inspecting the jupyter notebook, please make sure that all requirements are fulfilled:

## Requirements

- pyenv
- python==3.9.8
- several packages as provided in the requirements file

## Setup

To use the jupyter notebook in this repository, please create a virtual environment.

* setting the python version locally to 3.9.8
* creating a virtual environment using the `venv` module
* activating your newly created environment 
* upgrading `pip` (This step is not absolutely necessary, but will save you trouble when installing some packages.)
* installing the required packages via `pip`
* install the required packaged e.g. via using the requirements file (requirements.txt)
* 
<br>

```zsh
$ pyenv local 3.9.8
$ python -m venv .venv
$ source .venv/bin/activate
$ pip install --upgrade pip
$ pip install -r ./requirements.txt
```

## ___Enjoy :)___ <br>

*CC-BY 4.0 Andrea Schrader*  
*For material form the neuefische template see LICENSE.*
