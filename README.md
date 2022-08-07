## Titanic-Data-Analysis 

#### Predict Survival Outcomes from the 1912 Titanic disaster based on each passenger's features, such as sex and age.


### Description

#### Goal and Aim of the Project: 
We take interesting steps to maximize insight into the data set, uncover underlying structure, detect outliers and anomalies and test underlying assumptions, by answering to the below questions:

* What is the survival rate of this disaster?
* Are females more likely to survive males?
* Is there a certain age group more likely to survive other age groups?
* Are childern and mothers more likely to be survived than others?
* Did people pay higher fare tend to survive?
* Are there difference of survival rate between differnt ticket classes?
* Who will more likely to survive, families or sigletons?

#### Feature Scope: Build a Machine Learning Model to make better predictions. 

- [ ] Understand the impact of bias-variance tradeoff. 
- [ ] Understand what factors are important : accuracy, precision, recall. Calculate F1 score.
- [ ] Choose and Improve on ML model selection.

### Install Setup

This project requires **Python 2.7** and the following Python libraries installed:

- [numpy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org)
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
