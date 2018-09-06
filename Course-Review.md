# Course review: Data Science Specialization by JHU

### Author: Anderw Abisha Hu https://github.com/mchotfunk

---


## Executive Summary:

The data science specialization includes 10 courses, each of the them containing 4 weeks with different subjects.

This specialization is NOT for beginners —although it seems like. It does not assume you to have basic R knowledge. However, if you are new to R, or even with basic knowledge in R — you will still have A LOT OF hard time. 

Most of the contents are covered in a past pace explaining within a short period of time. Sadly to say, the courses are not organized well overall. 

The assignments in the class are mostly not directly related to the lecture, so you will have to do a lot of research outside the class. But the good point is that, these assignments can help you leverage your skills in data science because you are actually handling real-world problems, with real-world data. 

So my key takeaway is that— if you are really a newbie to R language, datacamp is your first choice. If you are already familiar with R, and hope to **augment your data science knowledge to another level**, learning this specialization **with datacamp together**, will enable you to be synergetic since these two MOOC are actually **complement to each other.**

---


## Difference between coursera and datacamp

Courses on coursera are taught by videos— you watch several clips, and answer quiz or complete assignments (projects). Datacamp— are taught by interactive process. You have many mini self-practices through your learning process.

The **most disadvantage from Datacamp is that**, without handling a real-project, you don’t actually understand how to apply R programming skills in real life — You only learn the syntax. Using the analogy of learning a foreign language, you only memorize the vocabulary and don’t know how to use them. Without practicing, you will forget these “vocabularies” quickly.

Hence, Datacamp has a better tutorial (learning process) and coursera, at least this Specialization, has better opportunities to practice your skills. **If you can utilize these two MOOC together, you will have a better experience and gain the most of it.**

The following is my in-depth reviews of all the courses in this Specialization:

 
## Reviews: 

1. Data Scientist ToolBox:

Rating: N/A

This course teaches you how to use terminal to submit your work from local to Github. Now the Github has a desktop version so you can manage your work in a relatively simple way. Submitting work on your Github is essential becuase this enables others to reproduce your work. It is important in today's data science industry.

---

2. R_programming: 

Rating: 1 out of 5

This is **the toughest course** in this specialization. (Yes, and it is at the beginning).

The content addressing in this class is very basic: Write a simple for-loop, introduction to self-defined functions, subset the data and the “Apply-related” functions. However, the projects (assignment) in this course are so much different —  it requires way more research online and nearly none of the required skills are covered in the lecture (that escalated quickly).

To sum up, this course is poorly managed and if you are not familiar with R (at least intermediate level), you will be very frustrated and start doubting yourself. Don't be! Keep on struggling.

---

3. Getting and Cleaning Data:

Rating: 3 out of 5

This course covers from getting data online (e.g. read HTML files) to making the data tidy. The contents starting from week 3 are very useful: It teaches you how to subset and sort the data, clean the missing values and create new variables in your data frame. 

In addition, the **introduction to “dplyr” is also killing**— the most practical package and skill I will surely apply in the future. 

Finally, the lecture also covers finding values in text, which implements frequently in the upcoming projects in this specialization. It’s a pity that the project in this course only requires you to merge the tables. It will be better if we can practice the data manipulating skill in the project.

---

4. Exploratory Analysis:

Rating: 4 out of 5

This course covers practical plotting system in R, and I found the **ggplot** most useful. Lecturer explained the concept quite concise and clear. It’s very easy to get to know how the structure for a ggplot is. This course features with practical hands-on assignment which you can practice skills you learned in this class. 

However, some of the contents might not be suitable to be addressed in this course, for example the K-means clustering. It is explained in a fast pace and did not cover completely. Overall, it’s a good course worth to take.

---

5. Reproducible Research:

Rating:  3 out of 5

This class teaches you how to develop reproducible research using R-Markdown. It’s very practical and essential in today’s data science industry. If you want to build your own Github, you should understand how to use R-markdown file to record the work you’ve done and let others to reproduce it. 

But there are some handy cheatsheets for syntax of R-markdown online. Simply following the cheatsheet should enable you to write R-markdown files. This class seems a little bit redundant and not necessary for me (just personal opinion). 

However, the assignment in this class handles well— It offers you an opportunity to practice what you’ve learned in previous class and give you an idea of how a report should look like.

---

6. Statistical Inference:

Rating: 1 out of 5

This is the **worst class in the specialization**. The lecturer tries to cover a lot of concept at the speed of light and assumes that you have a strong background in statistics. Even for me, a master student who takes marketing analytics concentration and learned statistics just months ago, I still struggled a lot and had a hard time. 

This course is so poorly managed that many people also complain at the online forum, and I have no idea why the lecturer hasn’t updated the class. The good thing is that it motivates me to review my stats knowledge, reminding me of the nightmare once again. 

---

7. Regression Model:

Rating: 3 out of 5

This course is slightly better than the statistical inference. It teaches you how to interpret the result of a regression model and how to handle the data if you are trying to fit a linear regression. (e.g. create dummy variables). It also covers some concepts of statistics ( over fitting, variance inflation factors…). 

However, the problem in this course is the same with the statistical inference: It tries to cover a lot of concept within a short period of time and did not explain well. Whenever the lecturer introduces a concept, he simulates some random data in R to justify the statistical functions, which I think it’s not what I need to learn and not practical at all.

---

8. **Practical Machine Learning (most recommended)**:

Rating: 4 out of 5

This is the most useful course in the specialization. The lecturer explained the concept in a relatively reasonable pace and in detailed. Other than theory, there are many hands-on cases you can practice during the class. 

The course covers the **“caret” package** in R, which is very useful in today’s machine learning. Lecturer demonstrates many different approaches to complete a specific objective— and you can choose the one that makes you feel the most convenient and comfortable. 

Highly recommend this course, but be prepared to handle a lot of content! (check my class notes to get what I’m saying)

![Notes]https://github.com/mchotfunk/Coursera-DataScienceSpecialization/blob/master/08_Practical%20Machine%20Learning/Class%20notes.Rmd

---

9. Developing data products:

Rating: 3 out of 5

This is overall a fun course to take. It introduces how to develop a simple Shiny App and how to make interactive plot and maps. Very interesting content to learn. 

However, developing data products might not be my future pursuit so I’m not that interested in learning these stuffs at this stage.

Check out my first app "Prediction of Ozone Emissions within NY State":

![ShinyApp]https://mchotfunk.shinyapps.io/FinalProject/

---


10. Data Science Capstone:

Rating: 1 out of 5

This Capstone is not a course— it requires you to apply what you’ve learned from this specialization and do a final project.

It is odd because the project is **nothing related to previous works**— You need to develop a Natural Language Processing App (a.k.a predict the next word given previous words). 

So I start searching what is NLP and what's the algorithm behind it. I spend almost 3 weeks to come up with a simple Shiny App. Very time-consuming, but-- you know, it's fun!

Check my language prediction app:

![ShinyApp]https://mchotfunk.shinyapps.io/DataScience-CapStone-NLP/

---


