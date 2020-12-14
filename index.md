## Phone: 817-731-8079 ⬩ Email: chesley.cecil@mavs.uta.edu ⬩ LinkedIn: https://www.linkedin.com/in/chesley-cecil/

### Undergraduate computer science major at the University of Texas at Arlington with experience using multiple programming languages including C++, Java, and JavaScript

# Education:
## University of Texas at Arlington
## Arlington, Texas 2018 - 2021
Programming Languages ⬩ Theoretical Concepts in CSE ⬩ Operating Systems ⬩ Database Systems and File Structures ⬩ Linear Algebra for CSE ⬩ Fundamentals of Software Engineering ⬩ Algorithms and Data Structures ⬩ Computer Organization and Assembly Language Programming ⬩ Practical Computer Hardware/Software systems ⬩ Object Oriented Programming

## Tarrant County College
## Fort Worth, Texas 2016 - 2018

# Skills:
## Programming Languages:
Java 8 ⬩ C89 ⬩ C++17 ⬩ Python 3 ⬩ MatLab 9.5 ⬩ MySQL ⬩ Lua ⬩ Javascript ⬩ Node.js ⬩ Processing 3.5.x ⬩ ARM 7 TDMI Assembly ⬩ R ⬩ Haskell

## Development Tools:
Github ⬩ BlueJ ⬩ Doxygen ⬩ Atom ⬩ PyCharm ⬩ Vim ⬩ Umbrello ⬩ Glade ⬩ Cmake ⬩ Geany ⬩ Android Studios ⬩ Arduino IDE ⬩ MySQL Workbench ⬩ FileZilla ⬩ PuTTY ⬩ VirtualBox

## Certificates:
Solidworks Associate

# Experience
## Team lead for app design project
## 2019
⬩ Managed the team so that the app was finished on time
⬩ Acted as scrum leader for bi-weekly progress meetings
⬩ Divided work among the team members to improve efficiency

## Team lead for Arlington Heights UIL Computer Science team
## 2017 - 2018
⬩ Managed the team so that the programs were finished on time
⬩ Organized requirements so the programs could be created quickly
⬩ Allowed the team to reach Regional level two years in a row

## Lead programmer for Arlington Heights FTC FIRST robotics team
## 2017 - 2018
⬩ Created all of the code for the robot
⬩ Performed maintenance on existing code to adapt to unexpected changes in requirements 

[Resume](https://github.com/ccecil2/ccecil2.github.io/blob/master/Resume.docx?raw=true)

[CSE 4334 Assignment 1](https://htmlpreview.github.io/?https://github.com/ccecil2/ccecil2.github.io/blob/master/Cecil_01.html)

[Download 4334 Assignment 1 from GitHub](https://github.com/ccecil2/ccecil2.github.io/blob/master/Cecil_01.ipynb)

[CSE 4334 Assignment 2](https://htmlpreview.github.io/?https://github.com/ccecil2/ccecil2.github.io/blob/master/Cecil_02.html)

[Download 4334 Assignment 2 from GitHub](https://github.com/ccecil2/ccecil2.github.io/blob/master/Cecil_02.ipynb)

[CSE 4334 Assignment 3](https://htmlpreview.github.io/?https://github.com/ccecil2/ccecil2.github.io/blob/master/Cecil_03.html)

[Download 4334 Assignment 3 from GitHub](https://github.com/ccecil2/ccecil2.github.io/blob/master/Cecil_03.ipynb)

# Term project
###### The purpose of the project is to implement a classifier that is capable of determining the rating that a review of a board game would have
###### My implementation used an algorithm called Naive Bayes. The Naive Bayes algorithm works by calculating the probability of the class given the input, and classifies the input as the class with the highest probability.
###### I learned how to use Sklearn's Naive Bayes library from the Sklearn documentation: https://scikit-learn.org/stable/modules/naive_bayes.html
###### The data to be used to train the classifier comes from https://www.kaggle.com/jvanelteren/boardgamegeek-reviews?select=bgg-15m-reviews.csv and has not been cleaned. The first thing that I had to do with this program was to throuraghly clean the data. After it had been cleaned, it had to be split into parts because it was too large to be stored on GitHub as a single file. Once the data had been dealt with, it was time to work on the main program
###### The next big thing that had to be done was to change the input data from text into numbers by using the TF-IDF vectorizer. I originally had issues with how long it took to run the vectorizer, but was able to fix it by adding in a minimum document frequency to remove terms that didn't occur very frequently. What I wasn't aware of at the time was that the vectorizer returned its matrix as a "sparse matrix" instead of a normal "dense matrix". It took quite some time before I was able to correctly turn the sparse matrix that it returned into a corresponding dense matrix.
###### Once I had fixed the dense matrix issue, the only part that was left was to actually run the classifiers. I ran the first one, and was initially a bit upset about the result being a mere 11.6% accuracy. After thinking about it for a while, I realized that a random choice would have an accuracy of 9.1% (1/11 since the rating is in the range of 0-10) and the classifier I had run was the one I expected to perform the worst. I proceeded to run the rest of the classifiers, and found that the one which did the best had an accuracy of 35.3%, significantly higher than the 11.6% of the lowest.
###### Based on the results of my program, I can conclude that a Multinomial Naive Bayes classifier works much better than a Gaussian Naive Bayes classifier (likely due to the fact that test is more likely to follow Zipf's law than a bell curve), and sublinear term-frequencies are better than standard term-frequencies. While the 35.3% accuracy of the best classifier might seem rather low, it is important to consider that the Naive Bayes algorithm is completely based on the frequencies of the inputs, and the amount of data provided pales in comparison to the set of all possible board game reviews. Of course, the poor quality of the reviews themselves (multiple languages, impropper formatting, missing values, bad values, and Markdown tags) didn't help in that regard.
###### The sourcecode for the project can be found [here](https://github.com/ccecil2/ccecil2.github.io/blob/master/Naive%20Bayes%20Games.ipynb) and the code for an implementation that runs online can be found [here](https://github.com/ccecil2/datamining-term-project). Alternatively, you can just directly go to http://ccecil2.pythonanywhere.com/ A video showing off the site can be found [here](https://youtu.be/CYdw_Ly7e3Y)

