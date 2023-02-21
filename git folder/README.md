### IB Data Science Coursework

This coursework is for IB students in the Department of Engineering at the University of Cambridge. It uses some of the linear algebra and Fourier analysis concepts covered in IB Paper 7 and Paper 6, respectively. The relevant material is covered in Handout 6 of Linear Algebra ("Least squares"), and in Handout 6 of Signal and Data Analysis ("Discrete Fourier Transform"). 

<br>

### Structure

This course involves two self-study, interactive Python notebook 'activities', with exercises at the end of each activity. The activity notebooks cover:

1. Introduction to time series, and using linear regression to model the trend in the time series
1. Using Fourier analysis and linear regression to model the seasonal variation (periodic components) in a time series 

There is a another optional notebook on model selection, which you are strongly encouraged to go through; but it is not compulsory.

The notebooks are designed to be completed in order. To complete an activity:

1. Read through a notebook, and change parts of the programs if you want to experiment with what 
   happens - this will help your understanding. 
1. Complete the exercises for the notebook before moving onto the next activity. 

This course is structured similarly to the IA Michaelmas computing course, where you learned the basics of Python programming. As you move through the activities you might need to revise some of the IA notebooks. As in IA, we will be using Python 3. 

<br>

### Download the files

You can download all the files in a zip file by clicking the green `Code` button on the top right. (You can also clone the repository if you are familiar with git.)

Unzip it, and name the folder `IB-Data-Science`. Open the folder and check that it has three self-study Jupyter notebooks, and three exercise notebooks with the sub-folder called `Exercises`. The sub-folder `Data` contains the data files required for the activity.

<br>

### Running notebooks

#### Running Jupyter locally on your computer

This is the most straightforward option and likely to be easier than using Google Colab (see below). If you haven't already installed Python and Jupyter on your computer, the [Anaconda](https://www.anaconda.com/download) distribution is  recommended. Be sure to download the Python 3 version. 


#### Google Colab

If you can't install and run Jupyter notebooks on your computer, you could use Google Colab. If you are using Colab, I recommend uploading your data onto Google Drive first. Follow these instructions carefully:

1. Sign in to Google Drive using your `CRSid@cam.ac.uk` . First upload the IB-Data-Science folder to the Google drive (by clicking the "New" button on the top left of the browser).

1. To open a Python notebook in Colab, navigate to it in the Google Drive browser, right click, choosen "Open with Google Colaboratory".

*Important*: If you are using Colab, you will have to mount your Google Drive before running the rest of your notebook. To do this, you just need to uncomment the relevant commands at the top of the notebook and run the cell. Click the link for authentication and follow the instructions.

Also make sure that you use the correct path when you load a file. You can find the path of a file in Google Colab, by navigating to it using the folder icon on the left and right clicking the dots. 

Cambridge students/staff: Please sign into Google Colab using your `CRSid@cam.ac.uk`

<br>



### Completing exercises

There are *three* exercise notebooks in the "Exercises" directory. You have to complete all three notebooks and submit them (see  below).

- Use Markdown cells when required to describe what your program is doing.
- Some exercises include automated testing to provide feedback on the correctness of 
  your implementations.    
 
<br>
  
### Submission and assessment

You will have to upload your three completed exercise notebooks on Moodle. You can find the submission link, deadline, and other details on check the [Moodle site](https://www.vle.cam.ac.uk/course/view.php?id=174011) .   

Please upload your notebooks in *PDF format*. In a Jupyter notebook, you can save as pdf by clicking the File menu and clicking "Download as ..."  If for some reason you cannot convert your completed notebooks to pdf, you can upload  the .ipynb files, but pdf is strongly recommended. 

You will not automatically receive feedback on your work. If you would like feedback or have questions about the lab, please drop in to one of the Help Desk sessions. 

<br>

### Getting help

1. There will be an online Helpdesk during weeks 8 and 9 of Lent Term, and during weeks 0 and 1 of Easter term. For exact dates and times, check the [Moodle site](https://www.vle.cam.ac.uk/course/view.php?id=174011).

1. There is a discussion forum on the [Moodle site](https://www.vle.cam.ac.uk/course/view.php?id=174011). Please help out by answering questions on the forum. Helping each other is encouraged - if you receive help make sure that you do understand what you have done.  If you need help or have questions, please visit a Helpdesk or post your question on the forum (rather than emailing me directly). 

<br>

### Feedback

We would love to hear your feedback about the coursework. Please send your comments to Dr Ramji Venkataramanan (rv285@cam.ac.uk). 


<br>

### Acknowledgements

Many thanks to Talay Cheema, Sumeetpal Singh, and Garth Wells for helping design this coursework. Thanks also to Tim Love, Slawomir Tadeja, Sukuan Guo, and Jake Stuchbury-Wass for their comments on the notebooks and exercises.


<br>

### License and copyright

All material is copyright of Ramji Venkataramanan (rv285@cam.ac.uk).

All text is made available under the Creative Commons Attribution-ShareAlike 4.0 International Public License (https://creativecommons.org/licenses/by-sa/4.0/legalcode).

All computer code is released under the MIT license.

The MIT License (MIT) Copyright (c) 2019-2023 Ramji Venkataramanan

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
