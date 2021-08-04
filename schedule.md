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
| Problems                         | Week 6 | October 4 - 8 | 
| Techniques                       | Week 7, 8, 9 |  Ocober 13 - 29 | 
| Problems                         | Week 10 | November 1 - 5 | 
| Graphs                           | Week 11, 12, 13, 14 | November 8 - December 3 | 
| Final week                       | Week 15 | December 6 - 10 | 



## Detailed schedule


### Week 1: Introduction and warmup (bubble sort, insertion sort, selection sort). Asymptotic analysis basics.

_Sept 1-3_

We start by reviewing two fundamental problems---searching and sorting---and going over a couple of simple algorithms. We also review the basics of algorithms analysis using big-oh notation, as well as best-cases and worst-cases.  You are probably familiar with most of this content from Data Structures (if this  content is new, you'll need to budget more time this first week to understand these new concepts). 

__Objectives:__ By the end of this  week you should be able to: 

* Understand searching (linear search, binary search) and simple sorting (bubble sort, selection sort, insertion sort) and be able to compare them, analyze them and apply  them to various inputs
* Understand the basics of algorithm analysis, big-Oh notation best-case and worst-case analysis

__Resources:__
     
  * __Lecture notes:__ [LN-warmup.pdf](docs/week1-LN-warmup.pdf)     
  * __Lab:__   [Lab 1](docs/week1-lab.pdf),  sol: see Blackboard
  * __Slides:__    see Blackboard    
  * __Videos:__    see Blackboard    
  * __Precheck:__  see Blackboard  
  * __Quiz:__      see Blackboard 
     
 ***
 
 
 
### Week 2: Asymptotic Notation and Summations

_Sept 6-10_

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
     
  * __Lecture notes:__ [LN-asymptoticNotation.pdf](docs/week2-LN-asymptoticNotation.pdf),  [LN-summations.pdf](docs/week2-LN-summations.pdf)
  * __Lab:__   [Lab2](docs/week2-lab.pdf), sol: see Blackboard 
  * __Slides:__ see Blackboard      
  * __Videos:__    see Blackboard     
  * __Precheck:__  see Blackboard
  * __Quiz:__ [quiz2-practice.pdf](docs/week2-quiz-practice.pdf),   quiz 2: see Blackboard
     
 ***
   
   
   
   
   
### Week 3: Mergesort and Recurrences

_Sept 13-17_

This week we continue with the topic of analysis and  introduce  the "recurrence" to express the running time of recursive algorithms. To motivate the first recurrence, we introduce a new sorting algorithm called Mergesort.  We express the running time of Mergesort   using a recurrence, which solves to O(n lg n).  Mergesort is the first algorithm we see in this class which beats the quadratic sorting algorithms from  previous lectures. 

__Objectives:__ By the end of this  week you should be able to: 

* Understand Mergesort: how it works, why it works, and its running time analysis using a recurrence
* Understand how to express the running time of recursive algorithms using recurrences
* Solve recurrences by repeated iteration
* Recognize broadly classes of recurrences ( logarithmic, linear, Θ(n lg n), exponential)

__Resources:__
     
  * __Lecture notes:__ [LN-recurrences.pdf](docs/week3-LN-recurrences.pdf)
  * __Lab:__   [Lab3](docs/week3-lab.pdf); sol: see Blackboard     
  * __Slides:__    see Blackboard    
  * __Videos:__    see Blackboard     
  * __Precheck:__  see Blackboard     
  * __Quiz:__ [quiz3-practice.pdf](docs/week3-quiz-practice.pdf) ; quiz 3: see Blackboard
     
 ***


### Week 4: Heapsort and Quicksort

_Sept 20-27_

So far we have discussed tools necessary for analyzing algorithms (asymptotic notation, summations and recurrences) and we have seen a couple of sorting algorithms at work. This week we introduce new sorting algorithms: Heapsort, Quicksort, and it's randomized version, Randomized-Quicksort. Heapsort is based on the heap, which is the standard implementation of a priority queue. Randomized-Quicksort is considered the most efficient general-purpose sorting algorithm in practice.


__Objectives:__ By the end of this  week you should be able to: 

* Understand the interface of a Priority Queue
* Understand how heaps are defined, the operations supported by a heap (Find-Min, DeleteMin, Insert, Heapify, Buildheap) and their Θ() bounds
* Understand Heapsort
* Understand Quicksort and its analysis
* Understand Randomized-Quicksort and its analyzis

__Resources:__
     
  * __Lecture notes:__ [LN-heapsort.pdf](docs/week4-LN-heapsort.pdf), [LN-quizksort.pdf](docs/week4-LN-quicksort.pdf)
  * __Lab:__   [Lab4](docs/week4-lab.pdf); sol: see Blackboard   
  * __Slides:__    see Blackboard   
  * __Videos:__    see Blackboard  
  * __Precheck:__  see Blackboard    
  * __Quiz:__      see Blackboard
     
 ***
  
  
### Week 5: Sorting lower bound. Faster sorting. Selection. 

_Sept 27-Oct 1_

We have seen several sorting algorithms so far, all of which have worst-case running time at least Ω(n lg n). The natural question to ask is: Can we do better than Θ(n lg n) in the worst-case? We introduce the concept of lower bound, and show that sorting lower bound in the comparison model of computation is Ω(n lg n). We describe a couple of different ways to sort which do not use the comparison model and under certain assumptions achieve linear time (bucket sort and counting sort)

We introduce a new problem, called the selection problem: Given a set S of n elements, {x_1, x_2, ..., x_n} and an integer k (1 ≤ k ≤ n), find the kth smallest element in S. We describe several ideas for solving this problem, culminating with an elegant and ingenious algorithm that runs in O(n) worst-case.

__Objectives:__ By the end of this  week you should be able to: 

* Understand the comparison-based sorting lower bound, when it applies and what assumptions it makes
* Understand BucketSort and CountingSort ,  their analysis and assumptions
* Understand the selection problem, and the algorithms for it (quick-select and smart-select)


__Resources:__
     
  * __Lecture notes:__ [LN-heapsort.pdf](docs/week4-LN-heapsort.pdf), [LN-quizksort.pdf](docs/week4-LN-quicksort.pdf)
  * __Lab:__   [Lab4](docs/week4-lab.pdf); sol: see Blackboard   
  * __Slides:__    see Blackboard   
  * __Videos:__    see Blackboard  
  * __Precheck:__  see Blackboard    
  * __Quiz:__      see Blackboard
     
     
 ***



### Week 6: 


__Objectives:__ By the end of this  week you should be able to: 

* 
__Resources:__
     

     
 ***
 
 
### Week 7: 


__Objectives:__ By the end of this  week you should be able to: 

* 
__Resources:__
     
 
     
 ***
 

### Week 8: 


__Objectives:__ By the end of this  week you should be able to: 

* 
__Resources:__
     
  
 ***
 
 
 
### Week 9: 


__Objectives:__ By the end of this  week you should be able to: 

* 
__Resources:__
     
  
     
 ***




### Week 10: 


__Objectives:__ By the end of this  week you should be able to: 

* 
__Resources:__
     
  
     
 ***



### Week 11: 


__Objectives:__ By the end of this  week you should be able to: 

* 
__Resources:__
     
 
     
 ***
 
 
 
### Week 12 & 13: 


__Objectives:__ By the end of this  week you should be able to: 

* 
__Resources:__
     
  
     
 ***
 
 
### Week 14: 


__Objectives:__ By the end of this  week you should be able to: 

* 
__Resources:__
     
  
     
 ***
 
 
 
### Week 15: 


__Objectives:__ By the end of this  week you should be able to: 

* 
__Resources:__
     
  
     
 ***
