---
layout: default 
title: Schedule and lectures
nav_order: 3
---

## Overall schedule 

|:-------------|:------------------|:---------- |
| Introduction                     | Week 1 | September 1-3 |
| Analysis tools                   | Week 2, 3 | September 6-17 |
| Efficient sorting and selection  | Week 4, 5 | September 20 - October 1 |
| Problems                         | Week 6 | October 4 - 6 | 
| Techniques                       | Week 7, 8, 9 |  Ocober 13 - 29 | 
| Problems                         | Week 10 | November 1 - 5 | 
| Graphs                           | Week 11, 12, 13, 14 | November 8 - December 3 | 
| Final week                       | Week 15 | December 6 - 10 | 



## Detailed schedule


### Week 1: Introduction and warmup (bubble sort, insertion sort, selection sort). Asymptotic analysis basics.


We start by reviewing two fundamental problems---searching and sorting---and going over a couple of simple algorithms. We also review the basics of algorithms analysis using big-oh notation, as well as best-cases and worst-cases.  You are probably familiar with most of this content from Data Structures (if this  content is new, you'll need to budget more time this first week to understand these new concepts). 

__Objectives:__ By the end of this  week you should be able to: 

* Understand searching (linear search, binary search) and simple sorting (bubble sort, selection sort, insertion sort) and be able to compare them, analyze them and apply  them to various inputs

* Understand the basics of algorithm analysis, big-Oh notation best-case and worst-case analysis

__Resources:__
     
  * __Lecture notes:__ [LN-warmup.pdf](docs/week1-LN-warmup.pdf)
     
  * __Slides:__
     
  * __Videos:__    [Blackboard]("https://www.blackboard.edu")
     
  * __Precheck:__  [Precheck 1 on Blackboard]("https://www.blackboad.edu")
     
  * __Lab:__   [Lab 1](docs/week1-lab.pdf);  sol:  [Blackboard]("https://www.blackboad.edu")
     
  * __Quiz:__ [Quiz 1 on Blackboard]("https://www.blackboard.edu")
     
 ***
 
 
 
### Week 2: Asymptotic Notation and Summations

Joke: An infinite number of computer scientists walk into a bar. The first one orders a beer. The second one, half a beer. The third one, a quarter. The barman pours two beers. The computer scientists complain: Is that all you're giving us? The barman says: "Come on guys, you should know your limits! "
Introduction

The goal of week 2 and 3 is to give you the conceptual tools  to analyze algorithms.  This week (week 2) we start by introducing the concepts of "asymptotic" analysis  and "order of growth". The order of growth is analyzed with O(), Ω() and Θ() notation. We'll give a formal definition of each one and discuss the differences between them and why big-oh is not sufficient. 

When analyzing algorithms it is common to encounter the so-called "summations".  In fact, you already encountered a summation when you tried to analyze Selection Sort or Insertion Sort!  We introduce the two basic summations that come up most often in the analysis of algorithms: arithmetic and geometric summations. 

This part of the class is heavy on discrete math like logarithms, exponents, limits and recursive functions, which most of you have not seen in a long time.  Hang in there!  The bright side is that there are formulas and rules for everything and it's just a matter of practice.  Really.  Give yourself time to practice and expect it will take time.  I have included many exercises and examples  which will help you through.  It is really important that you budget plenty of time. 

If you are not fond of analysis, I have some good news: once this module is over, you'll know enough to be able to analyze pretty much anything!  The remaining of the semester will be focused on new algorithms.  If you like analysis, I have some good news for you as well:  In the next modules you'll see analysis tools at work on some pretty neat algorithms.  


__Objectives:__ By the end of this  week you should be able to: 

* By the end of this module, you should be able to:
* Understand the relevance of analysis in practice, as well as its assumptions and limitations
* Understand the definitions of O(), Ω(), Θ()
* Understand the rate of growth of common functions
* Find the rate of growth of a function
* Compare the order of growth of two arbitrary functions f(n), g(n)
* Analyze basic algorithm running times using O(), Ω(), Θ() 
* Understand arithmetic and geometric summations and their Θ() bound 
* Recognize arithmetic and geometric summations in different forms and give Θ() bounds


__Resources:__
     
  * __Lecture notes:__ LN-asymptoticNotation.pdf ;  LN-summations.pdf
     
  * __Slides:__
     
  * __Videos:__    [Blackboard](www.blackboard.edu)
     
  * __Precheck:__  [Precheck 2 on Blackboard](www.blackboad.edu)
     
  * __Lab 2:__   lab2.pdf ;  lab2-sol.pdf 
     
  * __Quiz:__ quiz2-practice.pdf ;  [Quiz 2 on Blackboard](www.blackboard.edu)
     
 ***
   
   
   
   
   
### Week 3: Mergesort and Recurrences

This week we continue with the topic of analysis and  introduce  the "recurrence" to express the running time of recursive algorithms. To motivate the first recurrence, we introduce a new sorting algorithm called Mergesort.  We express the running time of Mergesort   using a recurrence, which solves to O(n lg n).  Mergesort is the first algorithm we see in this class which beats the quadratic sorting algorithms from  previous lectures. 

__Objectives:__ By the end of this  week you should be able to: 

* Understand Mergesort: how it works, why it works, and its running time analysis using a recurrence
* Understand how to express the running time of recursive algorithms using recurrences
* Solve recurrences by repeated iteration
* Recognize broadly classes of recurrences ( logarithmic, linear, Θ(n lg n), exponential)

__Resources:__
     
  * __Lecture notes:__ LN-recurrences.pdf 
     
  * __Slides:__
     
  * __Videos:__    [Blackboard](www.blackboard.edu)
     
  * __Precheck:__  [Precheck 3 on Blackboard](www.blackboad.edu)
     
  * __Lab 3:__   lab3.pdf (includes answers)
     
  * __Quiz:__ quiz3-practice.pdf ; [Quiz 3 on Blackboard](www.blackboard.edu)
     
 ***


### Week 4: 


__Objectives:__ By the end of this  week you should be able to: 

* 
__Resources:__
     
  * __Lecture notes:__
     
  * __Slides:__
     
  * __Videos:__    [Blackboard](www.blackboard.edu)
     
  * __Precheck:__  [Blackboard](www.blackboad.edu)
     
  * __Lab 1:__   
     
  * __Quiz:__ [Blackboard](www.blackboard.edu)
     
 ***
  
  
### Week 5: 


__Objectives:__ By the end of this  week you should be able to: 

* 
__Resources:__
     
  * __Lecture notes:__
     
  * __Slides:__
     
  * __Videos:__    [Blackboard](www.blackboard.edu)
     
  * __Precheck:__  [Blackboard](www.blackboad.edu)
     
  * __Lab 1:__   
     
  * __Quiz:__ [Blackboard](www.blackboard.edu)
     
 ***



### Week 6: 


__Objectives:__ By the end of this  week you should be able to: 

* 
__Resources:__
     
  * __Lecture notes:__
     
  * __Slides:__
     
  * __Videos:__    [Blackboard](www.blackboard.edu)
     
  * __Precheck:__  [Blackboard](www.blackboad.edu)
     
  * __Lab 1:__   
     
  * __Quiz:__ [Blackboard](www.blackboard.edu)
     
 ***
 
 
### Week 7: 


__Objectives:__ By the end of this  week you should be able to: 

* 
__Resources:__
     
  * __Lecture notes:__
     
  * __Slides:__
     
  * __Videos:__    [Blackboard](www.blackboard.edu)
     
  * __Precheck:__  [Blackboard](www.blackboad.edu)
     
  * __Lab 1:__   
     
  * __Quiz:__ [Blackboard](www.blackboard.edu)
     
 ***
 

### Week 8: 


__Objectives:__ By the end of this  week you should be able to: 

* 
__Resources:__
     
  * __Lecture notes:__
     
  * __Slides:__
     
  * __Videos:__    [Blackboard](www.blackboard.edu)
     
  * __Precheck:__  [Blackboard](www.blackboad.edu)
     
  * __Lab 1:__   
     
  * __Quiz:__ [Blackboard](www.blackboard.edu)
     
 ***
 
 
 
### Week 9: 


__Objectives:__ By the end of this  week you should be able to: 

* 
__Resources:__
     
  * __Lecture notes:__
     
  * __Slides:__
     
  * __Videos:__    [Blackboard](www.blackboard.edu)
     
  * __Precheck:__  [Blackboard](www.blackboad.edu)
     
  * __Lab 1:__   
     
  * __Quiz:__ [Blackboard](www.blackboard.edu)
     
 ***




### Week 10: 


__Objectives:__ By the end of this  week you should be able to: 

* 
__Resources:__
     
  * __Lecture notes:__
     
  * __Slides:__
     
  * __Videos:__    [Blackboard](www.blackboard.edu)
     
  * __Precheck:__  [Blackboard](www.blackboad.edu)
     
  * __Lab 1:__   
     
  * __Quiz:__ [Blackboard](www.blackboard.edu)
     
 ***



### Week 11: 


__Objectives:__ By the end of this  week you should be able to: 

* 
__Resources:__
     
  * __Lecture notes:__
     
  * __Slides:__
     
  * __Videos:__    [Blackboard](www.blackboard.edu)
     
  * __Precheck:__  [Blackboard](www.blackboad.edu)
     
  * __Lab 1:__   
     
  * __Quiz:__ [Blackboard](www.blackboard.edu)
     
 ***
 
 
 
### Week 12 & 13: 


__Objectives:__ By the end of this  week you should be able to: 

* 
__Resources:__
     
  * __Lecture notes:__
     
  * __Slides:__
     
  * __Videos:__    [Blackboard](www.blackboard.edu)
     
  * __Precheck:__  [Blackboard](www.blackboad.edu)
     
  * __Lab 1:__   
     
  * __Quiz:__ [Blackboard](www.blackboard.edu)
     
 ***
 
 
### Week 14: 


__Objectives:__ By the end of this  week you should be able to: 

* 
__Resources:__
     
  * __Lecture notes:__
     
  * __Slides:__
     
  * __Videos:__    [Blackboard](www.blackboard.edu)
     
  * __Precheck:__  [Blackboard](www.blackboad.edu)
     
  * __Lab 1:__   
     
  * __Quiz:__ [Blackboard](www.blackboard.edu)
     
 ***
 
 
 
### Week 15: 


__Objectives:__ By the end of this  week you should be able to: 

* 
__Resources:__
     
  * __Lecture notes:__
     
  * __Slides:__
     
  * __Videos:__    [Blackboard](www.blackboard.edu)
     
  * __Precheck:__  [Blackboard](www.blackboad.edu)
     
  * __Lab 1:__   
     
  * __Quiz:__ [Blackboard](www.blackboard.edu)
     
 ***
