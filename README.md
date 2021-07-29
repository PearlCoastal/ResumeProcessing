Resume Processing
====
## Description

A simple NLP project of resume processing using python 3.0.

## Python libraries and the dataset
![imgae](https://github.com/PearlCoastal/Leetcode_GitOn/blob/master/img-folder/resumeprocessing/%E6%88%AA%E5%B1%8F0003-07-29%2017.08.17.png)

## Show categories of resumes present in the dataset
![image](https://github.com/PearlCoastal/Leetcode_GitOn/blob/master/img-folder/resumeprocessing/%E6%88%AA%E5%B1%8F0003-07-29%2017.11.57.png)
## Visualize the number of categories in the dataset
![imgae](https://github.com/PearlCoastal/Leetcode_GitOn/blob/master/img-folder/resumeprocessing/matplot.png)
## Visualize the distribution of categories in the dataset
![image](https://github.com/PearlCoastal/Leetcode_GitOn/blob/master/img-folder/resumeprocessing/pieGraph.png)
## Remove the wrong format inside the resume and make it clean and able to read
**Wrong format included:**
- URLs
- hashtags
- mentions
- special letters
- puctuations

![image](https://github.com/PearlCoastal/Leetcode_GitOn/blob/master/img-folder/resumeprocessing/%E6%88%AA%E5%B1%8F0003-07-12%2001.05.26.png)
Left column is original dataset which contains lots of wrong format informations.
Right column is the resume dataset after cleaned.
![image](https://github.com/PearlCoastal/Leetcode_GitOn/blob/master/img-folder/resumeprocessing/%E6%88%AA%E5%B1%8F0003-07-29%2017.19.08.png)
## Import NLTK and visualize the most numbers of words larger and vice versa inside the resume
Its easily to read that "Details" appeared 484 times,"Experience" 446 times, as well as "company", "less", "year", "Machine Learning", and etc. These are those most numbers of words appeared in one resume.
![image](https://github.com/PearlCoastal/Leetcode_GitOn/blob/master/img-folder/resumeprocessing/%E6%88%AA%E5%B1%8F0003-07-12%2001.07.08.png)
## Train maching learning model for resume processing and here is the classification report of this dataset
Here I used the onevsrest classifier and KNN classifier.
First, split the data into training and data sets.
![image](https://github.com/PearlCoastal/Leetcode_GitOn/blob/master/img-folder/resumeprocessing/%E6%88%AA%E5%B1%8F0003-07-12%2001.07.23.png)
