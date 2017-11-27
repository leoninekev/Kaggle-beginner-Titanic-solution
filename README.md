# Kaggle-beginner-Titanic solution
The Titanic: ML from disastser is a beginner level kaggle compeition aimed to initiate ML beginners to real world datasets emulating finite set of features being mapped to target variable.
Here the [Titanic challenge](https://www.kaggle.com/c/titanic) provides a finite data record of passengers who were onboard that day, sets of which include features as follows:
- Passenger Id
- Name
- Gender
- Age
- Passenger travelling class
- Family count- Parents/Sibling/Spouse
- Fare
- Ticket no
- Cabin no.
- Embarked

Along with a column of target variables to be mapped, a column Named <B>"Survived"</B> comprising <B>categorical values - 0(if dead) or 1(if survived).</B>
Similar set of feature columns are provided as test dataset excluding "Survived", as 

### The task of this ML challenge is to predict "Survived" values correspodning to given test features.

This is my first attempt with python's pandas, seaborn & common python ML libraries on a real kaggle dataset, and even documenting it in an In-browser notebook, So basic feature correction & manipulation is done using numerical correlation & statistics with numpy methods, just enough to get started with an Introductory Data science project.

Though the code is verbose at places, i'll try to concretize existing implementation with a concise one in later revisions by working out more of feature engineering into mainstream to build New features from Columns like Name, Cabin & ticket id which have been delibrately put off for sake of understanding mechanics of a working program and seeing a bigger picture towards the end later.
In the wake of this rudimentary & naive scheme, current code managed to get a fair <B>score of 0.7655</B>. Pretty optimistic eh! <B>Let's Iterate!</B>
