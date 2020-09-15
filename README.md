Modern Data Structures
======================

QMSS G5072 - Columbia University
--------------------------------

**Fall 2020**  
**Lecture: Mondays 8.10 - 10pm (but see weekly schedule)**  
**Location: [Zoom Link Lecture](https://columbiauniversity.zoom.us/meeting/tJUpd--oqD8vGte-Pa3LbGN0zm8DcsSm123N/ics?icsToken=98tyKuCpqjssGtKRtRmERowcBoigM_TwpilYjbdY0S_kUAxRRS2mLO8aFrFsI9WB)**

Instructor: Thomas Brambor  
[tb2729@columbia.edu](tb2729@columbia.edu)  
Office Hours: Mon 5.30-6.30pm [Zoom Link OH](https://columbiauniversity.zoom.us/meeting/tJAqcuCtpzIqEtYwhjI_BOfS-OQsEeAOHA8K/ics?icsToken=98tyKuCsqT4jH92csBGFRowIB4_4Xe_xmFhfj7dkixfvKh9xTQXFe81zIZd6Mff4)

TA1: Xiaoyu Dai
[xd2236@columbia.edu](xd2236@columbia.edu)  
Office Hours: Th 2-4pm (odd weeks)  
Section: Th 3-4pm (even weeks)

TA2: Wenjun Sun
[wenjun.sun@columbia.edu](wenjun.sun@columbia.edu)  
Office Hours: Fr 2-4pm (even weeks)  
Section: Fr 2-3pm (odd weeks)

Please sign up for the TA's office hours and find the zoom links [here](https://docs.google.com/spreadsheets/d/1hfGfRc_lpRnNSALiOrvwwoUaFVdkvTJQQU5EIlYDKrM/edit?usp=sharing).

------------------------------------------------------------------------

Quick Links
-----------

-   [Course Description](#course-description)
-   [References and Resources](#references-and-resources)
-   [Requirements and Assessments](#requirements-and-assessments)
-   [Policies](#policies)
-   [Lecture Topics](#lecture-topics)
    -   [Part 1 - Data Manipulation & Coding](#part-1---data-manipulation)
    -   [Part 2 - Getting Data in](#part-2---getting-data-in)
    -   [Part 3 - Other “Big Data” Considerations](#part-3---other-big-data-considerations)

### Course Description

This course is intended to provide some foundational day-to-day tools for a data scientist in industry. Participants will learn how to access and clean data, organize and test code using functions and classes, how to set up and publish their own python package, and use Github to keep code version-controlled and in sync with others. In addition, the course will enable participants to work with APIs, deal with data in a variety of formats, and access databases via SQL. Lastly, participants will receive an introduction to Amazon Web Services on how to store data, create databases, and parallelize computing as well as introduce a way to schedule repeated computing jobs via Airflow. 

The goal is prepare students for their role as a data scientist (and incidentally a flavor of what would be expected of them in a typical data science interview.) Each week will have simple, moderate, and complex examples in class, with code to follow. Students will then practice additional exercises at home. The cap stone project is the creation of your own python package to make sure you can show off your newly gained skills to the world. No analysis or visualization (beyond just basic tables and plots to make sure everything was correctly organized) will be taught; and this will free up substantial time for the “nitty-gritty” of the data science workflow.

### Course Website

All lecture materials, exercises, and (links to) readings will be made available in the GitHub course repository.

https://github.com/QMSS-G5072-2020/course_materials

The repository is private. All enrolled students can add their name [to this form](https://forms.gle/XPogm4zgzwYovoCU6) to be added.

### Communications

For all questions to the members of the teaching team, we will be using a discussion forum on Campuswire. The forum will be used to exchange questions about lectures, assignments, software etc. Students are encouraged to help each other!

Link to course on Campuswire: https://campuswire.com/c/G27163EBA

If you have not joined yet, please use this [invite link](https://campuswire.com/p/G27163EBA) and the code `1110` to sign up for the course.

Students are asked to customize their Campuswire notification preferences to receive immediate (ASAP) notifications of messages and announcements through the third-party provider of choice (e.g. email, SMS/text). Students are also asked to log into the course regularly (more than twice a week) and check announcements and the Campuswire inbox immediately upon logging in to stay on top of developments in the course as they occur.

Please send all emails and messages to the instructor and teaching assistants through Campuswire. Messages sent through the Campuswire Inbox (Send a Message) feature will be answered within 24 hours during the week and within 48 hours on weekends. Please consider these response times when asking about assignments etc.

### References and Resources

#### Books

There are no required books for the course. All required readings will be provided as PDFs or links. However, here are some books that you may find useful in addition to the lectures and course readings.

- McKinney, Wes. (2017). _Python for data analysis: Data wrangling with Pandas, NumPy, and IPython_. O'Reilly Media: Good manual for understanding the capabilities of pandas as well as its strengths written by pandas' creator. Learn how to manipulate, process, clean, and crunch data in Python and learn Pandas for real work. ([PDF](https://www.programmer-books.com/wp-content/uploads/2019/04/Python-for-Data-Analysis-2nd-Edition.pdf))

- Sweigart, Al. (2019). _Automate the boring stuff with Python: practical programming for total beginners_. No Starch Press: Really useful worked examples on on how to use Python to automate part of your workflow. For the 'total beginner' is probably an overstatement - well suited even for advanced Pythonistas who want to learn some additional tricks. ([PDF](https://iedu.us/wp-content/uploads/edd/2019/11/Al_Sweigart__Automate_the_Boring_Stuff_with_Pytho-iedu.us_.pdf))

- VanderPlas, Jake. (2016). _Python data science handbook: Essential tools for working with data_. O'Reilly Media. ([HTML](https://jakevdp.github.io/PythonDataScienceHandbook/) | [Github](https://github.com/jakevdp/PythonDataScienceHandbook))

- Reitz, K., Schlusser, T. (2016). _The Hitchhiker's Guide to Python: Best Practices for Development_ (1st Edition). O’Reilly Media. - Not so much to learn Python, but a set of recommendations and best practices for making your code more "pythonic". A bit dated now. ([HTML](https://docs.python-guide.org) | [Github](https://github.com/realpython/python-guide))

- Matthes, E. (2019). _Python crash course: a hands-on, project-based introduction to programming_. No Starch Press. ([PDF of 1st Ed.](http://uchsdavis.weebly.com/uploads/3/1/6/3/31636201/python_crash_course.pdf)) - Comprehensive guide to Python for beginners. 

#### Free Online Resources

##### Datacamp

This class is supported by [Datacamp](https://www.datacamp.com/), an intuitive learning platform for data science. Learn R, Python and SQL the way you learn best through a combination of short expert videos and hands-on-the-keyboard exercises.

If you do not already have access to datacamp through QMSS, please use [this invite link to sign up](https://datacamp.com/groups/shared_links/73b919e17b2692420ab36ab2a47fc7cc6fac6d24707194774b659dc0be4597be) to access datacamp for free  (limited to columbia.edu email addresses).

The syllabus indicates **suggested Datacamp modules** to complement the lecture material and graded assignments. Of course, feel free to try out other offerings you are interested in from Datacamp's high quality content.

##### Python

-   [Python Cheat Sheet](https://www.pythoncheatsheet.org/) a refresher and reference for basic Python commands.
-   [Awesome-Python](https://awesome-python.com) A curated list of great Python packages and tools.

##### Git and GitHub

-   Git
    -   [Official git command line and GUI clients, official documentation](https://git-scm.com/)
-   Clients
    -   [Desktop Client for Mac and Windows](https://desktop.github.com/). Comes standard with github and is easy to use, but limited.
    -   [Gitkraken](https://www.gitkraken.com/student-resources). Professional git client. Students get the full-version for free. Recommended!
-   Tutorials
    -   [Learning resources for git and github](https://help.github.com/en/articles/git-and-github-learning-resources)
    -   [Setting up commandline git](https://help.github.com/articles/set-up-git/)
    -   [Interactive tutorial to learn branching](https://learngitbranching.js.org/)
    -   [Hello World - GitHub for the non-programming beginner.](https://guides.github.com/activities/hello-world/)
    -   [Guides at GitHub](https://guides.github.com/)
    -   [Git and Github guide from plot.ly](https://plot.ly/r/github-getting-started-for-data-scientists/) Extensive screen-shot guided intro to Git, Github, Git in RStudio and GitHub pages.
    -   [Pro Git - a full book with lots of details](https://git-scm.com/book/en/v2)
    -   [Datacamp - Introduction to Git for Data Science](https://www.datacamp.com/courses/introduction-to-git-for-data-science)

##### Coding Help Sites

-   <http://stackoverflow.com/> Programming Q&A site. Excellent first stop if you have questions on coding. Searching for keywords, and restrict your queries by adding tags about the coding language or package in square brackets, e.g. `[Python]`,`[git]`, or `[sql]`.

-   <http://stats.stackexchange.com/> A stackoverflow off-shoot with a bit more focus on conceptual questions in statistics.

##### Cloud Computing

All students in the course receive free credits to start using the following cloud computing resources:

- **Amazon Web Services (AWS)**: All students enrolled in the course or on the waitlist on the first day of the semester were added to our AWS classroom. Each student receives $50 AWS promotional credit. If you would like to be added later, please contact the instructor.

- **Google Cloud**: Use the following link ([Student Coupon Retrieval Link](TBA)) to request a $50 Google Cloud Platform coupon. You will be asked to provide your school email address and name. An email will be sent to you to confirm these details before a coupon is sent to you. 

### Requirements and Assessments

#### Requirements

This course will guide you through the data wrangling process using the software package `Python` for most exercises.

Some familiarity with the software, in particular with regards to the base functions in Python is assumed. Knowledge of specific packages and other software tools will be built throughout the course. If you have extensive experience with other similar programming tools, say R or Matlab, you will be fine. However, if you are completely new to `Python` and do not have compensatory experience in other coding languages, please consider the QMSS course "Data Mining" instead.

You will need to have access to your own computer to install software and packages, do your assignments etc. 
 <!--- I highly recommend bringing your laptop to class to follow along the coding tutorials and examples. --->

#### Assessments

**Homework**

Homework problems will be assigned on a weekly basis, and students are expected to work on them ALONE.

The teaching assistants will take turns grading the weekly assignments. If you have a question about your weekly homework grading assessment, please respond on the same github issue with which you submitted the assignment and `@` mention the specific TA who graded it.

- HW 1 - Xiaoyu
- HW 2 - Wenjun
- HW 3 - Xiaoyu
- HW 4 - Wenjun
- HW 5 - Xiaoyu
- HW 6 - Wenjun
- HW 7 - Xiaoyu
- HW 8 - Wenjun
- HW 9 - Xiaoyu
- HW 10 - Wenjun
- Final Project: TBA

**Exams**

There is no in-class final exam. Instead, the focus will be on developing a final project in the form of a Python package. 

**Grade Distribution**

The distribution of the parts for your grade is as follows:

-   Final Project = 30%
-   Homework Assignments = 60%
-   Participation (Lecture and in class forum) = 10%

#### Policies

**Format of the Class**:  

The course will be taught online only. All lectures, office hours, and one-on-one meetings will take via live Zoom.

**Synchronous Participation vs. Asynchronous Participation**:  It is my strong hope you will participate in this class synchronously so that you can benefit fully from your peers and the live instruction happening. That said, I completely understand your circumstances may make that very difficult, at least on some occasions.  In which case, this course can be done asynchronously as well.  Lectures will be recorded and available on Courseworks for at least 14 days after the class is held.  Likewise, assignments and some forms of participation can also be done remotely and asynchronously.

**Expectation of Regular Participation and Utilization of Campuswire**:  We will be monitoring student participation and completion of assignments throughout the semester.  We want to make sure that students are consistently engaged, and if that becomes difficult, that students alert us to their situations. 


**Attendance and Class Participation**

Your attendance and participation are necessary at every meeting. This class will work best when students ask a lot of questions.

**Academic Integrity**

This course is based on the principles of academic integrity established by Columbia University and agreed to by each student. The same rules hold in this course. Academic dishonesty will not be tolerated. All submitted work must be your own work and properly cited.

The full guidelines on academic integrity as well as a review of how or what to cite, can be found here: <http://gsas.columbia.edu/academic-integrity>

Students found guilty of plagiarism or academic dishonesty will be subject to appropriate disciplinary action, which may include reduction of grade, a failure in the course, suspension or expulsion. This includes lab reports – if they are copied from another student, severe penalties may be applied. \*\* Note that plagiarism is also possible when writing code, so be careful to write your own code.

**Late Assignment Policy**

Students will lose points for handing in late assignments, at the discretion of the instructor and teaching assistants.

<!--
**Other**

Turn off or silence your cell phones prior to the beginning of class. I reserve the right to answer all calls (your's, not mine) received during class time and let your friends know what you are learning that day.

Feel free to use laptops in class - in fact, I encourage it. Respecting your classmates and myself, please refrain from using Facebook, shopping sites or other random distractions during class.
-->

**Changes**

There may be adjustments of readings, assignments, exams, and classrooms. Changes will be posted on Campuswire/Github along with announcements.

**Slides**

Lecture slides will be made available on the course website. However, I believe that learning and understanding is better served when you need to aggregate and structure your notes yourself, so I suggest you do so as well.

-----

## Lecture Topics

#### Week 1: (Sep 14) Introduction [\[Link\]](Lectures/Week01/week01_lecture.md) [\[Recording\]](https://columbiauniversity.zoom.us/rec/share/TbD2fQl83PAlvIGTkczkT-6NykAuadW8AakLznM09a9nSmIqvCNfOWiyajwFVHbZ.6t7aRhW3dzYzoUQa?startTime=1600127461000)

-   **On your own:**
    - Sign up for a GitHub account. If you like free stuff, they have a nice [student pack](https://education.github.com/pack) as well.
    - Install [GitHub Desktop](GitHub Desktop) or [Gitkraken](https://www.gitkraken.com/student-resources) (if you are confident in using command-line Git or have a different software preference, feel free to skip this step.)
    - Claim your private Github repository connected with this class. The repository should be named `LastName_FirstName` (e.g. `Brambor_Thomas`)
-   **Reading:**:
    - McKinney, chp.2 _Python Language Basics, IPython, and Jupyter Notebooks_

-   **Datacamp**: 
    - To review base Python complete the course [_Introduction to Python_](https://campus.datacamp.com/courses/intro-to-python-for-data-science/).

### Part 1 - Data Manipulation & Coding

#### [Week 2: (Sep 21) Intro to Python and Virtual Environments](Lectures/Week02/week02_lecture.md)

-   **On your own:**
    - Install `pyenv` ([WIN](https://github.com/pyenv-win/pyenv-win) | [MacOSX](https://pythoneveryday.com/pyenv-macos)) and learn the basics about pyenv (e.g. via this [Intro to pyenv](https://realpython.com/intro-to-pyenv/))
    - Install `poetry` ([WIN & MacOSX](https://python-poetry.org/docs/)) as your virtual environment manager  
-   **Reading**:
    -   [Hello World - GitHub for the non-programming beginner.](https://guides.github.com/activities/hello-world/)
    -   [An Intro to Git and GitHub for Beginners (Tutorial)](http://product.hubspot.com/blog/git-and-github-tutorial-for-beginners), by Meghan Nelson.
    - [Managing Multiple Python Versions With pyenv](https://realpython.com/intro-to-pyenv/)
-   **Datacamp**: 
      - **Git**: Feel free to check out this fairly comprehensive [introduction to Git](https://www.datacamp.com/courses/introduction-to-git-for-data-science). Several things are beyond what is required in the course (undo, branches, collaboration) but useful nonetheless. 

- **Advanced Topics (optional, on your own only)**:
    - **Git**: 
        - The in-class introduction to Git was centered around GitHub. To learn a bit more, get comfortable with [command line git](http://rogerdudler.github.io/git-guide/) usage. 
        - Also, make sure you understand how branches work and how to work with a group of people. This [interactive tutorial](https://learngitbranching.js.org) is useful.
        - Submit something to a public repository on Github using a pull request.

> **Homework 1**: [Using Jupyter Notebooks and Github](Exercises/hw01/hw01.md). Also see the [homework submission instructions](Exercises/homework_submission_instructions.md).


#### [Week 3: (Sep 28) Data Wrangling with pandas](Lectures/Week03/week03_lecture.md)

-   **Reading**:
    - McKinney, chapter 5 _Getting Started with pandas_, chapter 7 _Data Cleaning and Preparation_, chapter 10 _Data Aggregation and Group Operations_
-   **Datacamp**: 
    - There are several pandas related courses that overlap a bit in content. There is no need to complete them all. Pick and choose what is most useful to complement your skills.:
        - [Data Manipulation with pandas](https://learn.datacamp.com/courses/data-manipulation-with-pandas)
        - [Joining data with pandas](https://learn.datacamp.com/courses/joining-data-with-pandas) - chapter 1 & 2 are the standard operations.
        - [Manipulating DataFrames with pandas](https://learn.datacamp.com/courses/manipulating-dataframes-with-pandas)
-   **Advanced Topics (optional, on your own only)**:
    - Datacamp [Joining data with Pandas](https://learn.datacamp.com/courses/joining-data-with-pandas) - chapters 3 & 4
    - McKinney, chapter 12 _Advanced pandas_
    
> **Homework 2**: [Data Wrangling with pandas](Exercises/hw02/hw02.md). Also see the [homework submission instructions](Exercises/homework_submission_instructions.md).


#### [Week 4: (Oct 5) Functions I: the basic logic and simple steps](Lectures/Week04/week04_lecture.md)

-   **Reading**:
    - Sweigart, _Automate the boring stuff with Python_, chapter 3, [Functions]( Automate the boring stuff with Python)
    - Some basics of [code styling](https://docs.python-guide.org/writing/style/)
-   **Datacamp**:
    - Chapter 4 on _Loops_ in [Intermediate Python](https://learn.datacamp.com/courses/intermediate-python)
    - [Python Data Science Toolbox (Part 1)](https://learn.datacamp.com/courses/python-data-science-toolbox-part-1) to cover function scope, lambda functions, and error handling   

> **Homework 3**: [`for` loops and functions](Exercises/hw03/hw03.md). Also see the [homework submission instructions](Exercises/homework_submission_instructions.md).


#### [Week 5: (Oct 12) Functions II: nested operations and complex sets of commands](Lectures/Week05/week05_lecture.md)

-  **Reading**: TBD
-  **Datacamp**:
    - Iterators, generators, and list comprehension. [Python Data Science Toolbox (Part 2)](https://learn.datacamp.com/courses/python-data-science-toolbox-part-2)
    - Context managers and decorators in the Datacamp course [Writing functions in Python](https://learn.datacamp.com/courses/writing-functions-in-python)
    - _Utilizing classes_ from [Software Engineering for Data Scientists in Python](https://learn.datacamp.com/courses/software-engineering-for-data-scientists-in-python)
        
- **Advanced Topics (optional, on your own only)**:
    - Check your understanding by completing the datacamp course [Practicing Coding Interview Questions in Python](https://learn.datacamp.com/courses/practicing-coding-interview-questions-in-python)
    - Practice coding skills on [Hackerank](https://www.hackerrank.com) or [Leetcode](https://leetcode.com)
    - Check out this advanced Python book to master your understanding: Ramalho, Luciano. (2015). _Fluent python: Clear, concise, and effective programming_. O'Reilly Media".
  
> **Homework 4**: [Functions II](Exercises/hw04/hw04.md). Also see the [homework submission instructions](Exercises/homework_submission_instructions.md).


#### [Week 6: (Oct 19) Functions IV: Working with strings](Lectures/Week06/week06_lecture.md)

- **Reading**: 
    * McKinney, _7.3 String Manipulation_ (p.211-218)
    * Sweigart, chapter 7 _Pattern Matching with Regular Expressions_
- **Datacamp**:
    - Learn about [Regular expressions in Python](https://learn.datacamp.com/courses/regular-expressions-in-python)
- **Advanced Topics (optional, on your own only)**:
    - There are so many great tools to work with text as data. To get started with natural language processing and modeling, I recommend the following readings and tutorials (all things here are well beyond what this course covers):
        * Bird, S., Ewan K., and Loper, E. Natural language processing with Python: Analyzing text with the natural language toolkit. O'Reilly Media. 2009. ([HTML](https://www.nltk.org/book/)) - Very practice-oriented: you won’t be introduced to complex theories behind, just plenty of code and concepts to start experimenting right away.
        * the datacamp course on [Introduction to Natural Language Processing in Python](https://learn.datacamp.com/courses/introduction-to-natural-language-processing-in-python) is worth a look.
        * Grimmer, J., & Stewart, B. M. (2013). Text as Data: The Promise and Pitfalls of Automatic Content Analysis Methods for Political Texts. Political Analysis, 21(3), 267-297. https://doi.org/10.1093/pan/mps028
        * Or jump straight into cutting edge [NLP with Tensorflow](https://www.tensorflow.org/hub/tutorials/tf2_text_classification)

> **Homework 5**: [Working with Strings](Exercises/hw05/hw05.md). Also see the [homework submission instructions](Exercises/homework_submission_instructions.md).


#### [Week 7: (Oct 26) Testing](Lectures/Week07/week07_lecture.md)

- **Reading**: 
    * chapter 5 _Testing_ from Hillard, Dane. (2020). "Practices of the Python Pro." Manning Publications (1st edition). Harvard. ([PDF](http://webéducation.com/wp-content/uploads/2020/01/Dane-Hillard-Practices-of-the-Python-Pro-Manning-Publications-2020.pdf))
    * Reitz, K., Schlusser, T. The Hitchhiker's Guide to Python, _Testing_ (p72-81)
- **Datacamp**:
    - Get an intro to [Unit Testing for Data Science in Python](https://learn.datacamp.com/courses/unit-testing-for-data-science-in-python)
- **Advanced Topics (optional, on your own only)**:
    - We just scratched the surface on code testing. Diving deeper in the usage of pytest is well worth it. Try Okken, B. (2017). _Python Testing with Pytest: Simple, Rapid, Effective, and Scalable_. Pragmatic Bookshelf. Chicago	([PDF](http://www.3testing.com/doc/23.pdf))
 
 > **Homework 6**: [Writing unit tests](Exercises/hw06/hw06.md). Also see the [homework submission instructions](Exercises/homework_submission_instructions.md).


#### [(Nov 2) University holiday. NO CLASS is held.

Try to catch up with any material. Ask questions on the course forum  to clarify any issues. 


#### [Week 8: (Nov 9) Creating your own Python Package](Lectures/Week08/week08_lecture.md)
 
-   **Reading**: 
    * chapter 6 _Shipping Great Code_ from  Reitz, K., Schlusser, T. _The Hitchhiker's Guide to Python_ (167-171)
    * [_An Overview of Packaging for Python_](https://packaging.python.org/overview/) by the Python Packaging Authority
- **Advanced Topics (optional, on your own only)**:
    - create an executable file from your Python code for distribution in _Shipping Great Code_ from  Reitz, K., Schlusser, T. _The Hitchhiker's Guide to Python_ (172-184)
    
> **Homework 7**: [Writing a Python Package](Exercises/hw07/hw07.md). Also see the [homework submission instructions](Exercises/homework_submission_instructions.md).


### Part 2 - Getting data in

#### [Week 9: (Nov 16) APIs](Lectures/Week09/week09_lecture.md)

-   **Reading**:
    * McKinney, _Interacting with Web APIs_ (p.187-188)
    * [API Integration in Python – Part 1](https://realpython.com/api-integration-in-python/)
    * [Getting started with APIs in Python to Gather Data](https://towardsdatascience.com/getting-started-with-apis-in-python-to-gather-data-1185796b1ec3) by Nik Piepenbreier
-   **Datacamp**:
    * [Intermediate Importing Data in Python](https://learn.datacamp.com/courses/intermediate-importing-data-in-python)
-   **Advanced Topics (optional, on your own only)**:
    * If interested, there is a detailed example of using the Census API in [this Datacamp course](https://learn.datacamp.com/courses/analyzing-us-census-data-in-python)
    * Learn [How to Make a Twitter Bot in Python With Tweepy](https://realpython.com/twitter-bot-python-tweepy/)

> **Homework 8**: [Writing a simple API client](Exercises/hw08/hw08.md). Also see the [homework submission instructions](Exercises/homework_submission_instructions.md).


#### [Week 10: (Nov 23) Web Scraping from HTML](Lectures/Week10/week10_lecture.md)

-   **Reading**:
    * Sweigart, chapter 12 _Web Scraping_
-   **Datacamp**:
    * [Web Scraping in Python](https://learn.datacamp.com/courses/web-scraping-with-python) 

> **Homework 9**: [Web Scraping from Wikipedia](Exercises/hw09/hw09.md). Also see the [homework submission instructions](Exercises/homework_submission_instructions.md).


#### [Week 11: (Nov 30) SQL](Lectures/Week11/week11_lecture.md)

- **Reading**:
    - There are lots of great SQL Tutorials to go further. Here are a few pointers:
        - [Codeacademy's SQL Tutorial](https://www.codecademy.com/learn/learn-sql)
        - [SQLzoo's SQL Tutorial](https://sqlzoo.net/)
        - [W3School.com SQL reference](https://www.w3schools.com/sql) (also interactive)
    - Practice using [SQLZOO](http://sqlzoo.net/)
    
-   **Datacamp**:
    - Try to complete [_Intro to SQL for Data Science_](https://www.datacamp.com/courses/intro-to-sql-for-data-science) before the lecture. The course covers the set of commands for single table operations.
    - Joins in SQL are essential, especially given the usually _relational_ nature of the data. Cover joins and relational set theory in [_Joining Data in PostgreSQL_](https://www.datacamp.com/courses/joining-data-in-postgresql).
    
- **Advanced Topics (optional, on your own only)**:  
      - Try your hand on connecting to a remote SQL database of your choice.

> **Homework 10**: [Practicing SQL Queries](Exercises/hw10/hw10.md). Also see the [homework submission instructions](Exercises/homework_submission_instructions.md).

> **Final Project Proposal**: [Final Project Proposal due on Dec 4](Exercises/final_project/final_project.md).

### Part 3 - Cloud computing

#### [Week 12: (Dec 7) Amazon Web Services and Parallelization](Lectures/Week12/week12_lecture.md)

-   **Reading**: TBD
-   **Datacamp**:
    * [Introduction to AWS Boto in Python](https://learn.datacamp.com/courses/introduction-to-aws-boto-in-python)
-   **Advanced Topics (optional, on your own only)**:
    * Gorelick, M., & Ozsvald, I. (2020). _High Performance Python: Practical Performant Programming for Humans_. O'Reilly Media. ([PDF](https://pdfs.semanticscholar.org/f42f/23a99b56cc4547dc61bf47fd5556cb71d13d.pdf)) provides good coverage on code profiling, vectorization, parallelization, and cluster computing.
    * Want a fuller intro to Amazon Web Services?: Wittig, M., Wittig, A., & Whaley, B. (2019). _Amazon web services in action_. Manning. ([PDF](https://www.programmer-books.com/wp-content/uploads/2019/02/Amazon-Web-Services-in-Action-2nd-Edition.pdf))
    * **Online Tutorials**:  
        - [Launch a Linux Virtual Machine with Amazon EC2](https://aws.amazon.com/getting-started/tutorials/launch-a-virtual-machine/)
        - [Store and Retrieve a File with Amazon S3](https://aws.amazon.com/getting-started/tutorials/backup-files-to-amazon-s3)
        - [Create and Connect to a MySQL Database with Amazon RDS](https://aws.amazon.com/getting-started/tutorials/create-mysql-db)


#### [Week 13: (Dec 14) Airflow and Spark](Lectures/Week13/week13_lecture.md)

-   **Reading**: TBD  
-   **Datacamp**:
    - [Introduction to Airflow in Python](https://learn.datacamp.com/courses/introduction-to-airflow-in-python)
    - The course [_Introduction to PySpark_](https://learn.datacamp.com/courses/introduction-to-pyspark) is beyond what we can cover but provides a good start on Spark using R. More info about the Big Data benefits and use of Spark is discussed in [Big Data Fundamentals with PySpark](https://learn.datacamp.com/courses/big-data-fundamentals-with-pyspark)
-   **Online Tutorials (only recommended)**: TBD


> **Final Project due on Dec 18**: [Final Project Description](Exercises/final_project/final_project.md).