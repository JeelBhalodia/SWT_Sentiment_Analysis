# SWT-Twitter_Sentiment_Analysis
Advanced Software Engineering Exercises

## TASK - 1
For the pet project, I have used Python language and the code is relatively small. However, if time permits I would also like to do the same thing using NLP.

Here, I have used Tweepy module to stream live tweets directly from Twitter in real-time. The tweets are visualized and then the TextBlob module is used to do sentiment analysis on the tweets. Based on certain keywords, tweets are refined and then are given a sentiment score of -1(negative sentiment), 0(neutral), 1(positive).


## TASK - 2

### 1. UML Diagrams (Atleast 3)

Here, I have attached 
+ [Class Diagram](https://github.com/JeelBhalodia/SWT-Sentiment_Analysis/blob/master/UML/class_diagram.PNG)
+ [Activity Diagram](https://github.com/JeelBhalodia/SWT-Sentiment_Analysis/blob/master/UML/Activity%20Diagram.png)
+ [Use-case Diagram](https://github.com/JeelBhalodia/SWT-Sentiment_Analysis/blob/master/UML/Usecase_diagram.png)

I have used lucidchart and GitUML (class diagram) for the this task.

### 2. Metrics

I have used both Sonarcube and Codacy for the task.


Sonarcloud Code Qulity Badge
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=JeelBhalodia_SWT-Sentiment_Analysis2&metric=alert_status)](https://sonarcloud.io/dashboard?id=JeelBhalodia_SWT-Sentiment_Analysis2)

Codacy Code quality badge 
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/8d028e61c35449acad16a139efa656a3)](https://www.codacy.com/manual/JeelBhalodia/SWT-Sentiment_Analysis?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=JeelBhalodia/SWT-Sentiment_Analysis&amp;utm_campaign=Badge_Grade)

### 3. Clean Code Development

### 4. Build Management

I have used Github Actions for the Build Management.
Here is the [build file](https://github.com/JeelBhalodia/SWT-Sentiment_Analysis/blob/master/.github/workflows/pythonapp.yml).

![Python application](https://github.com/JeelBhalodia/SWT-Sentiment_Analysis/workflows/Python%20application/badge.svg?branch=master)

### 5. Unit tests

### 6. Continuous Delivery

I have used CircleCI tool for the continuous delivery. [![CircleCI](https://circleci.com/gh/JeelBhalodia/SWT-Sentiment_Analysis.svg?style=svg)](https://circleci.com/gh/JeelBhalodia/SWT-Sentiment_Analysis)

You can find the config.yml file [here](https://github.com/JeelBhalodia/SWT-Sentiment_Analysis/blob/master/.circleci/config.yml).

The pipelines can be found [here](https://app.circleci.com/github/JeelBhalodia/SWT-Sentiment_Analysis/pipelines).
Here are all the [jobs](https://circleci.com/gh/JeelBhalodia).

### 7. IDE

I have used PyCharm Community Edition as my IDE.
Some of my favourite shortcuts are 
+ shift+ctrl+/  to  comment code with block comments or
+ ctrl+/  to  comment current line or selected block with line comments
+ shift+TAB  to  unindent selection
+ ctrl+E  to  show the list of recently viewed files
+ alt+RIGHT  to  activate the next tab

And ofc it's 'Darcula' color scheme

The only drawback (not so serious) which I faced was that it doesn't generate class diagrams unlike Professional Edition.
Also there's a [cheat sheet](https://www.shortcutfoo.com/app/dojos/pycharm-win/cheatsheet) which can be handy.

### 8. DSL

I have written a simple dsl which doesn't contribute to my project, but it's generic in nature that uses other Python source files to do some work.
+ 'src1.dsl' is the DSL source file that users write. This is not Python code but contains code written in custom DSL.
+ 'dsl1.py' is the Python source file that contains the implementation of domain specific language.
+ 'module1.py' contains the Python code that users can call and execute indirectly via DSL.

[DSL-Part 1](https://github.com/JeelBhalodia/SWT-Sentiment_Analysis/blob/master/DSL/dsl1.py)

Importing a Python module dynamically at runtime using the importlib module from the standard library.

[DSL-Part 2](https://github.com/JeelBhalodia/SWT-Sentiment_Analysis/blob/master/DSL/dsl2.py)

Bit more general and flexible. Instead of hardcoding the arguments, users pass any number of arguments. 

### 9. Functional Programming