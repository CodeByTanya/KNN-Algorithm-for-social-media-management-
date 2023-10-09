# KNN-Algorithm-for-social-media-management-
This project is a walkthrough of a simple KNN model in an
attempt to strategize a basic ad-targeting campaign for a social
media network/website. One of our sponsor's commercials seems to
be particularly successful among our older, wealthier users but
seemingly less-so with our younger ones. We'd like to put in place an
effective model so that we can figure out who our target
demographic is for this particular event, thus maximizing our click-
through rate. We'd like to show this ad to younger users with a lower
probability than older/wealthier users, and use the time/space to
expose them to content they're more likely to be interested in.

**DataSet Description:** 
The dataset contains some information about all of our users in the
social network, including their User ID, Gender, Age, and Estimated
Salary. The last column of the dataset is a vector of Booleans
describing whether or not each individual ended up clicking on the
advertisement (0 = False, 1 = True)
* Age: Age of an individual in years.
* User ID: Unique ID assigned to each individual. 
* Gender: Gender of each individual ( Male/ Female). 
* Estimated Salary: Salary of an individual
* Purchased : 0 =False , 1= True

We're just concerned right now about how the users' Age and
Estimated Salary influence their decision to click or not click on the
advertising. To do so, we'll use our dataset to derive the related
vectors: the independent variables (X) and the dependent variable (Y).

[Dataset Link: Social Network Ads](https://drive.google.com/file/d/1ug137IwNAyI_Ph0O_QUTngvz3Asjuuz5/view?usp=drive_link)

**ALGORITHM USED :**
The algorithm used for our project is a very simple & versatile and
one of the topmost machine learning algorithms- K Nearest
Neighbour(KNN).
