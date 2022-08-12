## EDA-Bio-Diversity

**Ensure the survival of at-risk species, to maintain the level of biodiversity within their park**
* Understand characteristics about the species and their conservations status using Descriptive statistics
* Explore relationship between species and their relationship to the national parks via Statistical Inference

### Description

1. Project goals: Define the high-level objectives and set the intentions for this project. 
2. Data: Luckily in this project, data is already provided but still needs to be checked if project goals can be met with the available data. 
3. Analysis: Will have to be thought through, which include the methods and questions that are aligned with the project goals. 
4. Evaluation: To build conclusions and findings from our analysis.


### Install Setup

This project requires **Python 2.7** and the following Python libraries installed:

- [numpy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [datetime](https://docs.python.org/3/library/datetime.html)
- [seaborn](https://seaborn.pydata.org)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer.


### Code

Template code is provided in the notebook `eda-bio-diversity.ipynb` 
[Jupyter Notebook](https://github.com/YRohitha/EDA-BioDiversity/tree/main/scripts/eda-bio-diversity.ipynb) file.


### Run

In a terminal or command window, navigate to the top-level project directory (that contains this README) and run one of the following commands:

```bash
jupyter notebook eda-bio-diversity.ipynb
```
or
```bash
ipython notebook eda-bio-diversity.ipynb
```
This will open the Jupyter Notebook software and project file in your web browser.


### Data

**Features**

#### species

The `species_info.csv` contains information on the different species in the National Parks. The columns in the data set include:
- **category** - The category of taxonomy for each species
- **scientific_name** - The scientific name of each species
- **common_names** - The common names of each species
- **conservation_status** - The species conservation status

#### observations

The `Observations.csv` contains information from recorded sightings of different species throughout the national parks in the past 7 days. The columns included are:

- **scientific_name** - The scientific name of each species
- **park_name** - The name of the national park
- **observations** - The number of observations in the past 7 days
