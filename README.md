## Titanic-Data-Analysis

Exploratory Data Analysis on Titanic Data set


### Install Setup

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer.


### Code

Template code is provided in the notebook `titanic-data-analysis.ipynb` 
[Notebook](https://github.com/YRohitha/Titanic-Data-Analysis/tree/main/src/titanic-data-analysis.ipynb) file. 


### Run

In a terminal or command window, navigate to the top-level project directory (that contains this README) and run one of the following commands:

```bash
jupyter notebook titanic-data-analysis.ipynb
```
or
```bash
ipython notebook titanic-data-analysis.ipynb
```
This will open the Jupyter Notebook software and project file in your web browser.


### Data

The dataset used in this project is included as `titanic_data.csv`. This dataset is sourced from public domain and contains the following attributes:

**Description**

The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

Here, we are trying to answers few questions: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

**Features**
- `pclass` : Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
- `name` : Name
- `sex` : Sex
- `age` : Age
- `sibsp` : Number of Siblings/Spouses Aboard
- `parch` : Number of Parents/Children Aboard
- `ticket` : Ticket Number
- `fare` : Passenger Fare
- `cabin` : Cabin
- `embarked` : Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

**Target Variable**
- `survival` : Survival (0 = No; 1 = Yes)
