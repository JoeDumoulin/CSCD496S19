# CSCD496-001 - Spring 2019
## Topics in Machine Learning

### Course Description

This course will introduce you to linear methods of Supervised Statistical Learning and to the standard techniques of model evaluation for regression problems, followed by an extended discussion of modern neural network methods and the tools available to build them.  In this class, we will read papers and write programs focused on techniques and issues for statistical learning and "Deep" learning.

#### Goals
* Understand what Machine Learning is (and is not).
* Understand how to construct models for classification.
* Understand how to evaluate models and what makes statistical learning interesting and problematic. (Equivalently, understand the roles of *human judgement* in machine learning.)
* Understand primary concepts of modern neural network technologies.
* Understand and use some of the modern machine learning libraries (scikit-learn, tensorflow, keras).

#### What we will not do (probably)
* We are going to avoid most machine learning methods in this class.  We will not be discussing unsupervised methods or reinforcement learning.  
* We will avoid many theoretical details of the methods we discuss.  The mathematics of machine learning is complex, often subtle, and involved.  We will see a lot of mathematics, but only to help us understand how to implement these techniques and to get a basic understanding of design and model selection.
* We will not see many of the modern techniques available in supervised learning, but will focus on implementing canonical examples.  Many of these methods are undergoing very rapid advancement and we will not have time to cover everything.

#### Required Books
* Francois Chollet, *Deep Learning with Python*
* Yaser S. Abu-Mostafa, et.al., *Learning From Data* (LFD)

#### Software Tools
You should be familiar (expertise is not needed) with the following tools:

* Ubuntu 16.04/18.04 Gnu/Linux OS
* git and Github 
* python3.4+ programming 

We will be using the following tools (and possibly more) during this class:

* python virtualenv
* jupyter notebooks
* pandas
* matplotlib
* scikit-learn
* tensorflow
* keras

You may optionally choose to use Google Colab.  This is highly recommended as it makes it very easy to create, run, and share jupyter notebooks.  Jupyter notebooks will be used for all programming assignments.

Written assignments, if any, should be submitted as pdf or markdown (see [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) or [here](https://daringfireball.net/projects/markdown/syntax) for more info).  Find a markdown editor appropriate for you or use a text editor.  Please do not use Microsoft Word for assignments.

### Class Schedule
An approximate sequence of events for this course is outlined below:

<table>
<tr><th>Date</th><th>Contents</th><th>Assignment Info</th><th>Project</th></tr>
<tr><td>04/02</td> <td>Introduction, Resources, Mathematics Review, Python basics and installation</td><td>Reading: Read Chapter 1, Learning From Data and Chapter 1 & 2, Chollet.</td><td></td></tr>
<tr><td>04/04</td> <td>What is AI/Machine Learning?</td> <td>Assignment 1: Complete Exercise 1.10 LFD, as a jupyter notebook.</td><td></td></tr>
<tr><td>04/09</td> <td>Two methods of Learning: Linear and KNN Classification</td> <td>Assignment 2: Implement Linear and KNN and perform bias/variance analysis using provided data. Reading: LFD chapter 3</td><td>Selection of Project Teams due</td></tr>
<tr><td>04/11</td> <td>Creating and Using Example data, Evaluating models with training data</td><td>Assignment I Due. Reading: LFD 2.3</td><td></td></tr>
<tr><td>04/16</td> <td>Machine Learning Landscape I, Bias & Variance tradeoff</td><td>Reading: LFD Chapter 4, optionally LFD echapter 6</td><td></td></tr>
<tr><td>04/18</td> <td>Machine Learning Landscape II, Loss & Accuracy</td><td></td><td></td></tr>
<tr><td>04/23</td><td>Machine Learning Landscape III, Regularization</td><td>Assignment 2 due.  Reading: Chollet, Chapter 3 Assignment 3: Implement the neural networks in Chollet, Ch 3.4 and 3.5. Graph training and test loss.</td><td></td></tr>
<tr><td>04/25</td><td>Linear Supervised Learning in Detail</td><td></td><td>Final Project Topics due</td></tr>
<tr><td>04/30</td><td>Linear Classification Learning again</td><td>Assignment 3 due.  Assignment 4: MNIST solution using linear solver.  Reading: Chollet, Chapter 4</td><td></td></tr>
<tr><td>05/02</td><td>Neural Networks I: Theory, Multilayer Perceptron, and Examples</td><td></td><td></td></tr>
<tr><td>05/07</td><td>Neural Networks II: Learning strategies for deep networks</td><td>Assignment 4 due.  Assignment 5: Solve MNIST with a deep convolutional network.  Reading: Chollet, Chapter 5</td><td></td></tr>
<tr><td>05/09</td><td>Convolutional Networks I: Convolution, what's the point?  simple networks</td><td></td><td></td></tr>
<tr><td>05/14</td><td>Convolutional Networks II: The power of learning convolutions.</td><td></td><td>Preliminary project report is due</td></tr>
<tr><td>05/16</td><td>Convolutional Networks III: Transfer Learning</td><td>Assignment 5 due.  Assignment 6: Create the sentiment analyzer from Chollet, Chapter 6.1.  Reading: Chollet, Chapter 6</td><td></td></tr>
<tr><td>05/21</td><td>Learning for time series analysis.  Recurrent Neural networks in theory.</td><td></td><td></td></tr>
<tr><td>05/23</td><td>Recurrent Networks I: Basic construction</td><td>Assignment 6 due.  Assignment 7: Train a recurrent network to generate text output.</td><td></td></tr>
<tr><td>05/28</td><td>Recurrent Networks II: Variations and examples</td><td></td><td></td></tr>
<tr><td>05/30</td><td>Recurrent Networks III: Very Modern networks for Natural Language Tasks</td><td>Assignment 7 due.</td><td></td></tr>
<tr><td>06/04</td><td>Recap.</td><td>Final Project Presentations</td><td></td></tr>
<tr><td>06/06</td><td>Recap.</td><td>Final Project Presentations</td><td></td></tr>

</table>


### Grading and Assessment
I am a strong believer in skill-building through examples.  I have planned a number of assignments for this class and this will be most of the grade.  We will probably complete a final project rather than a final test for this course as well.  These assignments will tend to be challenging and oriented toward building skills.  We will likey not have any tests, but in the event that class participation is low or assignments are not completed on time, We may change from a final project to a final test.

Grading will look like this:
10% quizes
70% assignments (almost entirely programming projects)
20% Final Project (or Test)

Things that will matter to your assignment grade:

* I can run your code (training and evaluation).  This is about correctness of your code.
* I can understand what is happening when I run your code (What is it doing, What are the results).  This involves both style and documentation.
* Things that do not work or that you do not understand are marked out and documented in your code.  This will help you (and me) learn new things.
* On-time submission of homework assignments. 

### Other Policies
* **Lectures**. You are expected to attend every class session. Please do not use my office hours as a substitute for attending lectures. If you are unsure as to what will be covered next, please ask at the end of the class period.
* **Preparation**.  You are expected to read assigned material that is being discussed in class AHEAD of time.  Examples given in class and in the reading should be confirmed by the student at home to guarantee complete understanding of the subject.
* **Homework**. Homework assignments will be in the form of programming projects, and written assignments. Homework is due at the specified time typically to Canvas. An assignment that is 1 day late incurs a 20% penalty.  Assignments will NOT be accepted for points beyond one day late without discussion with the instructor! Note that all assignments must be turned in (in working order) before quarter's end to be eligible to earn a passing grade (2.5).
* **Participation and Attendance**. You are not graded on participation and attendance directly, however regular attendance and participation are expected.  Quizes will happen and they will not be annouced at regular intervals, so attendance is important for this portion of your grade. At quarter's end, regular attendance and participation will positively influence your final grade. 
* **Professional Behavior**. All students are expected to act in accordance with the ACM Standards for Professional Behavior. Should you have any questions about appropriate behavior, please talk with me before submitting your work.  Instances of poor ethical conduct will be dealt with SEVERELY.  You may be expelled from the university, expelled from the degree program, or given a 0.0 in the class.
* **Incompletes**. Incompletes will NOT be granted except under extreme circumstances. They will not be granted in cases where you were simply unable to keep up with the workload. Requests for an incomplete must be submitted prior to finals week and is subject to the following catalog restriction: "PASSING work/progress (2.5 or above) must be demonstrated through three weeks prior to the end of the term."
* **Disclaimer**. The instructor reserves the right to make changes to these policies as necessary.  You will ALWAYS be informed of these changes in class.

