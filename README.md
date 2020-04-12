# AI-in-Soccer

## Table of Contents
* [General Info](#general-info)
* [Data and Technologies](#data-and-technologies)
* [Methodology](#methodology)
* [Closing Statements](#closing-statements)

## General Info
This is my latest personal project. The presentation can be found [here](https://www.youtube.com/watch?v=mEMU-EshNfc&feature=youtu.be). *I employed slightly different scenario in the execution of the models.*

The core idea is to create an insightful product for a soccer manager to rely on making key decision in real game time. The project has two wings: 
 1) First wing is about predicting player GPS location on the football pitch in the next 15 seconds by using a Deep Learning Model. 
 2) Second wing takes first wing's results and predicts the probabilities of the 5 main events via Machine Learning Model. Then a simple formula selects the dominant event(s) in the next 15 seconds.

## Data And Technologies

I  used the same data with [this](https://www.nature.com/articles/s41597-019-0247-7) study. My main datasets are events, players, and matches.

And here are the technologies I used:
  1) NoSQL (MongoDB): The data is in document format. The notebook 01 has the demonstration of this technology.
  2) Numpy and pandas: The two core libraries for any EDA in Jupyter Notebook environment.
  3) Matplotlib and Seaborn: Here, Matplotlib is the core and the Seaborn is the mask.
  4) Recurrent Neural Network - LSTM (Bidirectional): This was a very good choice and a lucky one given the limited time I was given to take this project to a presentable format. I continue learning about this technology. There will be more explanations on why I used this model.
  5) Gradient Boosted Tree - XGBoost: Second part of the case is a multiclass problem. I have read that XGBoost performs well with unbalanced classes. Again there will be more on this in the near future.

## Methodology

I combined two different predictive models, added my domain knowledge along with preprocessing & feature engineering and database querying.

## Closing Statements

I want to explain how I see and work before you start your journey in the my notebooks. It may assit you capturing everything and give you the ability to point out possible areas of improvement. Here we go:
  1) I include a lot of explanations in my notebooks. I want you to see how I think.
  2) Given the item number one, I make sure that what I put in my notebooks is clear to an uninitiated person.
  3) In some cases, my code may not be the most of the most efficient in the world. In my defense, I am only 4 months into the serious Python coding.
  4) I will put more explanations about the models I picked and why I picked them. They are both very complex models used in a very hard problem. I would like to make it clear that this is not an excuse but a time buyer :).
  5) My style is to pick a model and stick with it until the end rather than shop around and try around other models for comparison. That way I put some serious thought into the project and focus better. Also, I trust in my troops:). And, I love the joyful feeling of making a model to perform better than the previous version of itself. That gives me a reason to dig into the granular detail of what I am deling with. Finaly, it adds uniqueness to my work.
  6) I want to give credit to Pappalardo, L., Cintia, P., Rossi, A. et al, creators of A public data set of spatio-temporal match events in soccer competitions (Sci Data 6, 236 (2019). https://doi.org/10.1038/s41597-019-0247-7) for providing great insights to initiate my project.
  7) And please forgive me for any grammatical errors. I am fixing them as I go along.
