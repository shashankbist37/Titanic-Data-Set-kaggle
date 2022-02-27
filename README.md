# Titanic-Data-Set-kaggle

<h3>Titanic Data Science Solutions</h3>

This notebook is a companion to the book Data Science Solutions.

The notebook walks us through a typical workflow for solving data science competitions at sites like Kaggle.

There are several excellent notebooks to study data science competition entries. However many will skip some of the explanation on how the solution is developed as these notebooks are developed by experts for experts. The objective of this notebook is to follow a step-by-step workflow, explaining each step and rationale for every decision we take during solution development.

<h3>Workflow stages</h3>
The competition solution workflow goes through seven stages described in the Data Science Solutions book.

<h6>1.Question or problem definition.</h6>
<h6>2.Acquire training and testing data.</h6>
<h6>3.Wrangle, prepare, cleanse the data.</h6>
<h6>4.Analyze, identify patterns, and explore the data.</h6>
<h6>5.Model, predict and solve the problem.</h6>
<h6>6.Visualize, report, and present the problem solving steps and final solution.</h6>
<h6>7.Supply or submit the results.</h6>
  
The workflow indicates general sequence of how each stage may follow the other. However there are use cases with exceptions.
  

  
 <h3>Question and problem definition</h3
   
Competition sites like Kaggle define the problem to solve or questions to ask while providing the datasets for training your data science model and testing the model results against a test dataset. The question or problem definition for Titanic Survival competition is described here at Kaggle.

Knowing from a training set of samples listing passengers who survived or did not survive the Titanic disaster, can our model determine based on a given test dataset not containing the survival information, if these passengers in the test dataset survived or not.
We may also want to develop some early understanding about the domain of our problem. This is described on the Kaggle competition description page here. Here are the highlights to note.

On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. Translated 32% survival rate.
One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew.
Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.
Workflow goals
   
   <h3>The data science solutions workflow solves for seven major goals.</h3>

<b>Classifying.</b> We may want to classify or categorize our samples. We may also want to understand the implications or correlation of different classes with our solution goal.

<b>Correlating.</b> One can approach the problem based on available features within the training dataset. Which features within the dataset contribute significantly to our solution goal? Statistically speaking is there a correlation among a feature and solution goal? As the feature values change does the solution state change as well, and visa-versa? This can be tested both for numerical and categorical features in the given dataset. We may also want to determine correlation among features other than survival for subsequent goals and workflow stages. Correlating certain features may help in creating, completing, or correcting features.

<b>Converting.</b> For modeling stage, one needs to prepare the data. Depending on the choice of model algorithm one may require all features to be converted to numerical equivalent values. So for instance converting text categorical values to numeric values.

<b>Completing.</b> Data preparation may also require us to estimate any missing values within a feature. Model algorithms may work best when there are no missing values.

<b>Correcting.</b> We may also analyze the given training dataset for errors or possibly innacurate values within features and try to corrent these values or exclude the samples containing the errors. One way to do this is to detect any outliers among our samples or features. We may also completely discard a feature if it is not contribting to the analysis or may significantly skew the results.

<b>Creating.</b> Can we create new features based on an existing feature or a set of features, such that the new feature follows the correlation, conversion, completeness goals.

<b>Charting.</b> How to select the right visualization plots and charts depending on nature of the data and the solution goals.

<img src=https://storage.googleapis.com/kaggle-media/welcome/screen1.png>
