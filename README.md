# AI-in-Soccer

## Table of Contents
* [General Info](#general-info)
* [Data and Technologies](#data-and-technologies)
* [Methodology](#methodology)
* [Closing Statements](#closing-statements)

## General Info
This is my latest project. The presentation can be found [here](https://www.youtube.com/watch?v=mEMU-EshNfc&feature=youtu.be). *I did a slightly different role playing in the presentation.*

The core idea is to create an insightful product for a soccer manager to rely on making key decision in real game time. The project has two wings: 
 1) First wing is about predicting player GPS location on the football pitch in the next xx seconds by using a Deep Learning Model (Bidirectional LSTM). 
 2) Second wing takes first wing's results and predicts the probabilities of the 5 main soccer game events via Machine Learning Model-XGBoost Classifier). Finally, a simple formula selects the dominant event(s) in the next xx seconds.

## Data And Technologies

I  used the data of [this](https://www.nature.com/articles/s41597-019-0247-7) study. The core dataset is the events and the supporting datasets are players and matches.

And here are the technologies I used:
  1) NoSQL (MongoDB): The data is in document format. The notebook 01 has the demonstration of this technology.
  2) Numpy and pandas: The two core libraries for any EDA in Jupyter Notebook environment. Notebook 02 is all about them along with 03 and 04.
  3) Matplotlib and Seaborn: Great tools for visualization.
  4) Recurrent Neural Network - LSTM (Bidirectional): This was a very good choice and a lucky one given the limited time I had for this project. I continue learning about this technology. I included my reasons to use this model in book 03a.
  5) Gradient Boosted Tree - XGBoost: Second part of the case is a multiclass problem. XGBoost performs well with unbalanced classes.

## Methodology

I combined two different predictive models, added my domain knowledge along with preprocessing & feature engineering and database querying.

## Closing Statements

I want to take you into my world and show you how I see. It may assit you capturing everything and give you the ability to point out possible areas of improvement. Here we go:
  1) I include a lot of explanations in my notebooks. I want you to see how I think.
  2) Given item number one, I try to make sure that what I put in my notebooks is clear to an uninitiated reader.
  3) In some cases, my code may not be the most of the most efficient in the world. But I aim for a world class quality project by project. I will get there.
  4) I try to explain the models I picked and why I picked them. Please keep in mind, they are both very complex models used in a very hard problem.
  5) I picked the models and stick with them until the end. There may be other models (or combinations) may perform better. 
  6) I want to give credit to Pappalardo, L., Cintia, P., Rossi, A. et al, creators of A public data set of spatio-temporal match events in soccer competitions (Sci Data 6, 236 (2019). https://doi.org/10.1038/s41597-019-0247-7) for providing great insights (EDA). Their great work helped me to initiate my project.
