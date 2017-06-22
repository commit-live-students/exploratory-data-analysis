![GitHub Logo](https://s3.ap-south-1.amazonaws.com/greyatom-social/GreyAtom-logo.png)

# Streetfighting with Maths and EDA

## Lets Get Rolling - Student Pre-Read
Before this lesson , we recommend you go through

*  [Measures of Location](http://www.itl.nist.gov/div898/handbook/eda/section3/eda351.htm)
*  [Measures of Spread](http://www.abs.gov.au/websitedbs/a3121120.nsf/home/statistical+language+-+measures+of+spread)
*  [Taxonomy of charts](https://pykih.com/44878804.html) 
*  [Classification of Chart Types](http://excelcharts.com/wp-content/uploads/2013/11/classification-chart-types.png)
*  [Random Variables](https://en.wikipedia.org/wiki/Random_variable)
*  [A Gentle Introduction to Scikit-Learn: A Python Machine Learning Library](http://machinelearningmastery.com/a-gentle-introduction-to-scikit-learn-a-python-machine-learning-library/)


## Learning Objectives 

After this lesson, you'll be able to 
* How to get an overview of dataset without any code?
  * Deep dive with Pima Indians Diabetes
* Perform Exploratory Data Analysis
* Work with Data
* Have a mathematical feeling of Linear Regression
  * [Derivation of OLS - Non Calculus](https://www.amherst.edu/system/files/media/1287/SLR_Leastsquares.pdf)
  * Derivation in terms of Matrices
  * Derivation of OLS - Calculus 
  * Derivation of OLS - Graphical 

## Agenda


## Slides

@[gslides](12MfGuRbSPV-Hgtpn1Xmd8GGvwgwbwVSp8Gx1NVKH1Mk)

## Instructors code alongs

* [EDA](https://raw.githubusercontent.com/commit-live-students/exploratory-data-analysis/master/notebooks/introduction_to_machine_learning.ipynb)

### About Pima Indians Diabetes
  * [Pima](https://en.wikipedia.org/wiki/Pima_people)
  * [Plasma glucose concentration a 2 hours in an oral glucose tolerance test](https://en.wikipedia.org/wiki/Glucose_tolerance_test)
  * [Diastolic blood pressure (mm Hg)](http://www.webmd.boots.com/hypertension-high-blood-pressure/guide/diastolic-systolic)
  * [Triceps skinfold thickness (mm)](https://image.slidesharecdn.com/basicanthropometryppt-121012050944-phpapp02/95/basic-anthropometry-ppt-16-728.jpg?cb=1350018882)
  * [Insulin](https://en.wikipedia.org/wiki/Insulin)
  * [BMI](https://en.wikipedia.org/wiki/Body_mass_index)

## Practical Advise 
  *  EDA is not a compulsary step. Most  
  *  Its not even a step. Its what you call as getting a feel. 
  *  Have your Checklist Ready 
  *  Apply en-masse
  
## Quantitative EDA
  * Dimensions of your data - .shape
  * Statistical Summary - .describe()
  * Get General Highlevel - .info()
  * Class Distribution - .groupby('class').size()
  * Pairwise Pearson correlations - .corr()
  * Skew for each attribute - .skew()
  * Head()/ Tail()
  
## Visual EDA
  * Keep the DAMN thing clean - Don't do a half hearted job at it - Else, don't do it
  * What every chart should have?
     *  Title 
     *  xlabels
     *  ylabels
     *  xticks
     *  yticks
     *  xmin
     *  ymin
     *  legend
     *  annotate 
  *  Have a default script - 
  *  Know the following
     *  What kind of insight is best drawn from what kind of chart? Refer Taxonomy
     *  Sacrilegious mistakes - What kind of features can be plotted? Can't do a scatter plot on catgorical variables
     *  Know your variable/ feature scales - Nominal/ Ordinal/ Interval/ Ratio
  *  Most used plots
    *  Q Q Plot
    *  Scatter
    *  Line
    *  Histogram
    *  Correlogram
    *  Box & Whiskers 

## Assignments 
*  [UCI Data Repository Review](http://archive.ics.uci.edu/ml/datasets.html)
  *  Go to the Data Repository - Select the below 10 Datasets   
    *  [Iris](https://archive.ics.uci.edu/ml/datasets/Iris)
    *  [Titanic](https://www.kaggle.com/c/titanic)
    *  [Sonar](http://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks))
    *  [Pima Indians Diabetes](https://archive.ics.uci.edu/ml/datasets/Pima+Indians+Diabetes)
    *  [Water Treatment Plant](https://archive.ics.uci.edu/ml/datasets/Water+Treatment+Plant)
    *  [Boston Housing](https://archive.ics.uci.edu/ml/datasets/housing)
    *  [Forest Fires](https://archive.ics.uci.edu/ml/datasets/Forest+Fires)
    *  [Fertility](https://archive.ics.uci.edu/ml/datasets/Fertility#)
    *  [Communities and Crime Data Set](https://archive.ics.uci.edu/ml/datasets/Communities+and+Crime)
    *  [Wine Quality Data Set ](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
    *  [Automobile](https://archive.ics.uci.edu/ml/datasets/Automobile)

  *  Make a Group of 2/3 - Download the Datasets - Read 'Data Set Description'
  *  Each team will explain the dataset and corresponding domain required to understand the day
  *  These are extremely popular the Datasets - You will most likely find ready made Python code for EDA - Google it and go through it 

## Resources & Post Reads
  * Critical Thinking 
    * How to treat Outliers?" - Are Outliers Good or Bad?
  * [Value of Exploratory Analysis](http://www.kdnuggets.com/2017/04/value-exploratory-data-analysis.html)
  * [Use of Excel for EDA](https://www.youtube.com/playlist?list=PLZzQj_sVf3slNwpohkUAkD0gHncgfCpJ3)
  * [Excel Data Analysis - Sort/ Filter/ Pivot](https://www.youtube.com/playlist?list=PLZzQj_sVf3slNwpohkUAkD0gHncgfCpJ3)
  * [How to Lie with Statistics](https://en.wikipedia.org/wiki/How_to_Lie_with_Statistics)
