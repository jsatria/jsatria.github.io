---
layout: post
title: Semester Over.
excerpt: "Thoughts and reflections over the last semester in OMSCS. "
modified: 2016-04-30
tags: [posts, school, omscs, georgiatech]
comments: true
image:
  feature: header_lisbon.jpg
---
<section id="table-of-contents" class="toc">
  <header>
    <h3>Overview</h3>
  </header>
<div id="drawer" markdown="1">
*  Auto generated table of contents
{:toc}
</div>
</section><!-- /#table-of-contents -->

### DONE.
The spring semester came to a much awaited and fulfilling end this past weekend. A casual reader will notice the lack of any posts since my last post back in January. Between graduate school, traveling, and everything in between, this blog has been regretfully neglected. After four long months, I finally have time to sit down and properly write. This post is going to be about the past semester and my thoughts on the classes I completed. In a few days I'll be posting about the travel I've done over the last few months.

### In the last episode...
I'm now 4 classes away from finishing my master's degree at Georgia Tech in the OMSCS program. For those that are new or unaware, in November 2015 I moved from Washington, D.C. to Cambridge, England with my family (more on that in a later post). Since I had to leave my last job and I was unaware of what sort of job opportunities were available in the UK, I opted to hold off on a job search and instead study full-time for at least the spring semester. This allowed me to explore new subjects I hadn't been able to due to full-time work. Machine learning and big data are becoming increasingly relevant and machines more capable, so I decided to pursue this new field of study.  More specifically, the three classes I took were:

* Introduction to Information Security CS 6035
* Machine Learning CS 7641
* Machine Learning for Trading CS 7646

I'll discuss each of these classes in further detail below.

### Introduction to Information Security CS 6035
Having come from a non-traditional CS background (I was pre-med in undergrad), I felt that I would benefit from a class that provides a fundamental overview and introduction to modern information security. I enjoyed the context and lectures of the course. They covered not only the technical issues (of which there are many), but also the human side of information security -- creating a security policy, implementing it and the varying security needs of different organizations.

Of the many topics covered in class, those that stuck with me the most were:
- stack buffer overflows
- XSRF and XSS attacks
- SQL injection attacks
- malware analysis using Cuckoo
- IPSec
- Intrusion detection and Response

The class was comprised of weekly homework quizzes, 4 projects, a midterm and final, and an optional extra credit project. The workload was extremely manageable as long as you got started on the projects early on. The solution often relied on an aha-moment sort of trick, so starting early was advantageous to allow for creative thought. Unfortunately, I felt that the quizzes and exams were a waste of time since they didn't exactly test understanding and application of the topics covered in class. Questions were often taken directly from the book with slight modification and were rote-based. I think that getting rid of of the homework quizzes and expanding the projects would be more interesting and an overall better learning experience. Otherwise, this class was a good introduction to information security and I feel that I've learned quite a bit.

#### Tips and Advice
* The textbook, though chock-full of information, is an incredibly dry read. I read all the chapters for the midterm and found that the 8 hours I spent were a waste of time.
* A lot of official announcement information and project requirements were dispersed in Piazza posts by the teaching staff. It was a slight nuisance since students often had to seek clarification in class forums and gave the impression that project requirements were half-baked. So pay attention to Piazza, and contribute as much as possible to help your fellow classmates!
* Do the extra credit project. It's fun, a good learning experience, and well... it's extra credit.


### Machine Learning CS 7641
Machine Learning (ML) was hands down one of the most difficult and challenging courses I've ever taken. It is one of the most difficult courses in the entire program and consequently holds one of the highest drop-rates. With all that being said, however, ML was one of the most rewarding and best learning experiences I've had. The class encourages learning through experimentation and analysis while placing little emphasis on the actual code implementation of the different ML algorithms. Grades are comprised purely of four analysis assignments, a midterm exam and final exam. Code contributes 0% to the grade of the written assignments -- in fact the use of existing libraries and  open-sourced tools to conduct experiments is encouraged. Ultimately, the purpose of the assignments is to understand and experience first hand the characteristics of different ML algorithms. The instructors' end goal is maximal "synthesis" of the learning material. For those accustomed to CS courses where working and efficient code is sufficient to pass a course (like myself), this type of analytical process and written assessment can be stressful and foreign at first. By the end of the semester, I appreciated this sort of learning process since it forced me to really get into the details and theory behind an algorithm. And in a field where there might not be a "right" answer and results can be surprising, investigation and being able to explain results was an immensely helpful learning process.

Overall, the course was broken up into three mini-courses. These are listed and described briefly below:

1. **Supervised Learning** - function approximation. Given a set of input and outputs, learn the function that relates the two so that predictions can be made on future unknown data.
2. **Unsupervised Learning** - Function inference. Given a set of samples, try to ascertain some hidden structure about the input data.
3. **Reinforcement Learning** - My favorite part of the course. Given a set of input (states) and outputs (rewards), learn a function that takes input states and produces ***actions*** that maximize the reward. Consider a robot moving a grid world, trying to reach a goal state with any number of ways to reach that state. RL is a field that allows this robotic agent to identify the optimal path to the goal.

I really enjoyed this course and thought it was stressful at first, I would recommend it to anyone else who is even remotely interested in machine learning. For anyone who completes all the assignments and follows the lectures, the class lays a solid groundwork understanding of ML.

#### Tips and Advice
* Pick simple but interesting datasets for the first assignment from the UCI ML repository. I spent too much time trying to find an ideal dataset that would support my expectations of how a particular algorithm would perform. As long as you can demonstrate and explain why you ***think*** you're seeing particular results, you should be fine.
* Focus on the analysis and experiments and less on the coding aspect of the assignments. Use existing libraries like scikit-learn (Python), ABAGAIL (Java), and BURLAP (Java).
* On a related note as above, don't be afraid to try new languages. I hadn't written a line of Python prior to this class, but I'm now a Python enthusiast.
* Don't procrastinate. There's a lot of material to go through.
* Don't focus too much on the math. It was helpful for me to understand some things like Backpropagation on Neural Networks, but often you want to focus on the bigger picture.
* The assigned textbook <a href="http://www.cs.cmu.edu/~tom/mlbook.html">(Machine Learning by Tom Mitchell, 1997)</a> is a great read and I wish I had read it in conjunction with the lectures. I highly recommend buying the book early and getting started.
* If working full-time, take this course on its own or with an easier paced class (like Health Informatics or Information Security)
* You can check out my code here: https://github.com/jsatria/ml

### Machine Learning for Trading (ML4T) CS 7646
I wasn't sure what to expect prior to taking this course. I thought it would couple well with the aforementioned machine learning class, but frankly I took this class because I had been waitlisted to the other classes I wanted to take. By the end of the semester, however, it became one of my favorite and important classes -- because it helped me land my first job here in Cambridge! (more on that later)

ML4T attempts to apply machine learning to predictive financial analytics. By the end of the class, I learned how to use and apply machine learning methods such as k-Nearest Neighbor and Q-learning/DYNA (reinforcement learning) to an agent that can make stock market decisions.

I thought that the course was fairly straightforward, but felt that overall it was too slow and easy at the start while piling on the most difficult assignments for the last three weeks of the semester. The first 6 weeks were spent learning how to use Python, numpy, and pandas to create a market simulator and calculate general financial indicators. It wasn't until about the last three weeks that machine learning was actually brought into the mix, which I found a bit disappointing. Too much hand holding for the pandas and numpy use, which I personally think should be otherwise completed by students on their own time. On the other hand, assignments were very straightforward and a grading rubric was made clear, which was much appreciated. I only wish there was more time for creative application of ML in the trading world.

One more note is that the exam was comprised of selected student questions. I felt that the exam was a bit of a cop-out by the teaching staff to write a legitimate exam. My studying technique boiled down to going through all of the student submitted questions and memorizing intricacies of pandas or numpy. It was an easy test based on documentation that would be otherwise freely available to any developer with access to the internet and Google. IMO, not a good assessment of learning.

Nonetheless, the class was overall a good experience and I would suggest it to anyone who has taken or is taking ML. I appreciated being able to apply the ML concepts in a practical sense, so these two classes fit well together. I just think that ML4T could be made a bit more challenging.

#### Tips and Advice
* Python, Pandas, and Numpy are the major (and actually the only permitted) libraries used for the assignments. A general understanding of these before class would put you ahead of the course
* Though I bought the Python for Finance book, I ended up not using it for the entire course. Most of the information you need to complete the assignments is easily searchable online

## Moving Forward
I've landed my first job here in Cambridge and will be starting this summer, so I'll be taking the summer semester off to focus entirely on the new job. In the fall I'll be picking back up and I anticipate to complete my degree in summer 2017. For now, I'm just happy to be done with this very difficult semester. So I'm going to have a beer.

Thanks for reading! I hope this was helpful to anyone interested in the program or classes. Comment below with any questions you might have!


Cheers,
JS
