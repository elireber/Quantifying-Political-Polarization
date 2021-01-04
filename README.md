# Quantifying-Political-Polarization

This project was my undergraduate thesis that had two main goals - build an accurate classifier of news article political bias and use said classifier to see how polarization occurred in major news sources over the course of the 2016 election period.

### Project TL;DR:

Background - Political polarization in the US has been becoming an increasingly large threat to the American democracy, particularly during recent election periods.  Giving users a way of estimating the bias of their news article allows them to "take it with a grain of salt".

Method - First, pre process the articles.  Then, feed the processed articles into a pipeline that vectorizes and transforms the text into numerical values.  Next, use a Support Vector Machine (SVM) to classify the articles' political bias accurately.  Finally, use said trained classifier to analyze how major news sources' political bias changed from 2016 to 2017.

Results - The SVM algorithm was able to achieve ~ 80% accuracy between a 5 label selection.  Some news sources had statistically significant changes in their political biases over the course of the 2016 election period.

### Folder Contents:

Code - Jupyter Notebooks containing the code to classfication and time series analysis
