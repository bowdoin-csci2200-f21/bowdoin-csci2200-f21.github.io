Week 1: Introduction and warmup (bubble sort, insertion sort, selection sort). Asymptotic analysis basics.
Sept 1-3

We start by reviewing two fundamental problems---searching and sorting---and going over a couple of simple algorithms. We also review the basics of algorithms analysis using big-oh notation, as well as best-cases and worst-cases. You are probably familiar with most of this content from Data Structures (if this content is new, you'll need to budget more time this first week to understand these new concepts).

Objectives: By the end of this week you should be able to:

Understand searching (linear search, binary search) and simple sorting (bubble sort, selection sort, insertion sort) and be able to compare them, analyze them and apply them to various inputs
Understand the basics of algorithm analysis, big-Oh notation best-case and worst-case analysis
Resources:

Lecture: LN-warmup.pdf
Slides and videos: see Blackboard
Precheck: see Blackboard
Lab: Lab 1 (for Lab1-sol see Blackboard)
Quiz: Quiz1 see Blackboard
Assignment: Assignment1 posted on Gradescope (due end of week 3, by Sunday 9/19)
Week 2: Asymptotic Notation and Summations
Sept 6-10

Joke: An infinite number of computer scientists walk into a bar. The first one orders a beer. The second one, half a beer. The third one, a quarter. The barman pours two beers. The computer scientists complain: Is that all you're giving us? The barman says: "Come on guys, you should know your limits! "

The goal of weeks 2, 3 is to give you the conceptual tools to analyze algorithms. This week (week 2) we start by introducing the concepts of "asymptotic" analysis and "order of growth". The order of growth is analyzed with O(), Ω() and Θ() notation. We'll give a formal definition of each one and discuss the differences between them and why big-oh is not sufficient.

When analyzing algorithms it is common to encounter the so-called "summations". In fact, you already encountered a summation when you tried to analyze Selection Sort or Insertion Sort! We introduce the two basic summations that come up most often in the analysis of algorithms: arithmetic and geometric summations.

This part of the class is heavy on discrete math like logarithms, exponents, limits and recursive functions, which most of you have not seen in a long time. Hang in there! The bright side is that there are formulas and rules for everything and it's just a matter of practice. Really. Give yourself time to practice and expect it will take time. I have included many exercises and examples which will help you through. It is really important that you budget plenty of time.

If you are not fond of analysis, I have some good news: once this module is over, you'll know enough to be able to analyze pretty much anything! The remaining of the semester will be focused on new algorithms. If you like analysis, I have some good news for you as well: In the next modules you'll see analysis tools at work on some pretty neat algorithms.

Objectives: By the end of this week you should be able to:

Understand the relevance of analysis in practice, as well as its assumptions and limitations
Understand the definitions of O(), Ω(), Θ()
Understand the rate of growth of common functions
Find the rate of growth of a function
Compare the order of growth of two arbitrary functions f(n), g(n)
Analyze basic algorithm running times using O(), Ω(), Θ()
Understand arithmetic and geometric summations and their Θ() bound
Recognize arithmetic and geometric summations in different forms and give Θ() bounds
Resources:

Lecture: LN-asymptoticNotation.pdf, LN-summations.pdf
Slides and videos: see Blackboard
Precheck: see Blackboard
Lab: Lab2 (for Lab2-sol see Blackboard)
Quiz: quiz2-practice.pdf, Quiz2: see Blackboard
Assignment: work on Assignment 1
Week 3: Mergesort and Recurrences
Sept 13-17

This week we continue with the topic of analysis and introduce the "recurrence" to express the running time of recursive algorithms. To motivate the first recurrence, we introduce a new sorting algorithm called Mergesort. We express the running time of Mergesort using a recurrence, which solves to O(n lg n). Mergesort is the first algorithm we see in this class which beats the quadratic sorting algorithms from previous lectures.

Objectives: By the end of this week you should be able to:

Understand Mergesort: how it works, why it works, and its running time analysis
Understand how to express the running time of recursive algorithms using recurrences
Solve recurrences by repeated iteration
Recognize broadly classes of recurrences ( logarithmic, linear, Θ(n lg n), exponential)
Resources:

Lecture: LN-recurrences.pdf
Slides and videos: see Blackboard
Precheck: see Blackboard
Lab: Lab3 (for Lab3-sol see Blackboard)
Quiz: quiz3-practice.pdf ; Quiz3: see Blackboard
Assignment:
Assignment 1 due end of this week (by Sunday 9/19)
Assignment 2 posted on Gradescope (due end of week 4, by Sunday 9/26)
Week 4: Heapsort and Quicksort
Sept 20-27

So far we have discussed tools necessary for analyzing algorithms (asymptotic notation, summations and recurrences) and we have seen a couple of sorting algorithms at work. This week we introduce new sorting algorithms: Heapsort, Quicksort, and it's randomized version, Randomized-Quicksort. Heapsort is based on the heap, which is the standard implementation of a priority queue. Randomized-Quicksort is considered the most efficient general-purpose sorting algorithm in practice.

Objectives: By the end of this week you should be able to:

Understand the interface of a Priority Queue
Understand how heaps are defined, the operations supported by a heap (Find-Min, DeleteMin, Insert, Heapify, Buildheap) and their Θ() bounds
Understand Heapsort
Understand Quicksort and its analysis
Understand Randomized-Quicksort and its analyzis
Resources:

Lecture notes: LN-heapsort.pdf, LN-quicksort.pdf
Slides and videos: see Blackboard
Precheck: see Blackboard
Lab: Lab4 (for Lab4-sol see Blackboard)
Quiz: Quiz4 see Blackboard
Assignment:
Assignment 2 due end of this week (due by Sunday 9/26)
Assignment 3 posted on Gradescopoe (due end of week 6 by Friday 10/8)
Week 5: Sorting lower bound. Faster sorting. Selection.
Sept 27-Oct 1

We have seen the most important sorting algorithms so far and all of them have worst-case running time at least Ω(n lg n). The natural question to ask is: Can we do better than Θ(n lg n) in the worst-case? We introduce the concept of lower bound, and show that sorting lower bound in the comparison model of computation is Ω(n lg n). We describe a couple of different ways to sort which do not use the comparison model and under certain assumptions achieve linear time (bucket sort and counting sort). This concludes the module on sorting.

This week we introduce a new problem: the selection problem. Given a set S of n elements, {x_1, x_2, ..., x_n} and an integer k (1 ≤ k ≤ n), find the kth smallest element in S. We describe several ideas for solving this problem, culminating with an elegant and ingenious algorithm that runs in O(n) worst-case.

Objectives: By the end of this week you should be able to:

Understand the comparison-based sorting lower bound, when it applies and what assumptions it makes
Understand BucketSort and CountingSort, their analysis and assumptions
Understand the selection problem, and the algorithms for it (quick-select and smart-select)
Resources:

Lecture notes: LN-linsort.pdf, LN-selection.pdf
Slides and videos: see Blackboard
Precheck: see Blackboard
Lab: Lab5; Lab5-sol see Blackboard
Quiz: Quiz5 see Blackboard
Assignment: Assignment 3 due end of next week (by Friday 10/8)
Week 6: Problems
Oct 4-8

At this point in the class (1) you have the tools to analyze algorithms and you appreciate the interplay between analysis and design (what we mean by this is that analyzing your ideas gives you further ideas for how to improve on your initial ideas!); and (2) you have seen some fundamental algorithms and building blocks---sorting, priority queues and selection. One of the goals of this class is to provide the conceptual tools for solving new problems on your own. This week we'll take a break from new content and work on problem solving.

This week there is no new content (no lecture notes, no videos and no precheck). The work for this week consists of a set of Jupyter notebooks which provide implementation and visualization of some of the algorithms discussed so far; use them to refresh your programming and to deeper understand the algorithms. And set of new problems to solve.

Objectives: This week's objective is algorithmic problem solving. By the end of this week,

Connect the algorithms discussed so far with their implementation.
You would have seen examples of new problems, which may seem like they have nothing to do with the content in the previous weeks; yet, the process of coming up with solutions to these problems on your own illustrates the very nature of algorithmic problem solving
You understand that algorithmic problem solving is both a science and an art
Hopefully, you would have had one "ahaa!" moment
Resources:

Lecture notes: python-mysterySort.ipynb, python-insertionSort.ipynb, python-mergeSort.ipynb, python-quickSort.ipynb
Slides and videos: see Blackboard
Precheck: see Blackboard
Lab: Lab6; Lab6-sol see Blackboard
Quiz: Quiz6 see Blackboard
Assignment:
Assignment 3 due end of this week (due by Friday 10/8)
Assignment 4 posted on Gradescopoe (due end of week 8 by Sunday 10/24)
Week 7: Divide-and-conquer
Oct 13-15 (note: fall break on 10/11, 10/12)

What do you do when you encounter a new problem and you don't know how to start? Coming up with solutions is both an art and a science, and although there are no recipes, there are some techniques that come up frequently. By now you have some practice, and you perhaps noticed that some of the problems have similar solutions. We'll spend the next three weeks looking at more problems, grouped by the technique used to solve them.

This week we introduce a technique called divide-and-conquer. In fact you already saw this technique at work in Mergesort. This week we give more examples of problems that can be solved via divide-and-conquer, including the famous Strassen's matrix multiplication algorithm.

Objectives: By the end of this week you should be able to:

Understand how D&C works in general
Understand the algorithms for integer multiplication and matrix multiplication
Be able to apply D&C to new problems
Resources:

Lecture notes: LN-divideAndConquer.pdf
Slides and videos: see Blackboard
Precheck: see Blackboard
Lab: Lab7; Lab7-sol see Blackboard
Quiz: Quiz7 see Blackboard
Assignment:
Assignment 4 due end of next week by Sunday 10/24)
Week 8: Dynamic Programming
Oct 18-22

This week we introduce the technique called dynamic programming and see it at work on three problems: board game, rod, and knapsak.

Objectives: By the end of this week you should be able to:

Understand the basic principles of dynamic programming
Understand the three examples discussed in the lecture notes (including correctness and analysis)
Move towards applying DP to new problems
Resources:

Lecture notes: LN-dynprog.pdf, LN-rod.pdf, LN-knapsack.pdf
Slides and videos: see Blackboard
Precheck: see Blackboard
Lab: Lab8; Lab8-sol see Blackboard
Quiz: Quiz8 see Blackboard
Assignment:
Assignment 4 due end of this week
Assignment 5 posted on Gradescopoe (due end of week 10)
Week 9: Greedy algorithms
Oct 25-29

This week we introduce the greedy technique via the activity selection problem.

Objectives: By the end of this week you should be able to:

Understand how the greedy technique works in general and contrast it with DP
Understand the greedy solution for the example discussed in the lecture notes (activity selection), including the correctness proof
Move towards applying the greedy technique to new problems
Resources:

Lecture notes: LN-greedy.pdf
Slides and videos: see Blackboard
Precheck: see Blackboard
Lab: Lab9; Lab9-sol see Blackboard
Quiz: Quiz9 see Blackboard
Assignment:
Assignment 5 due end of next week
Week 10:
Nov 1-5

This week we'll wrap up the module on algorithmic techniques ---divide and conquer, dynamic programming, and greedy---by seeing a couple more examples of these techniques at work.

Objectives: By the end of this week you should be able to:

Reflect on the problems we've looked at and compare on how the general technique was instantiated for that specific problem.
At this point the problems we've seen should feel familiar, and the goal is be to be able to come up with the algorithms on your own.
Resources:

Lecture notes: LN-lcs.pdf, LN-techniques-review.pdf
Slides and videos: see Blackboard
Precheck: see Blackboard
Lab: Lab10
Quiz: Quiz10 see Blackboard
Assignment:
Assignment 5 due end of this week
Assignment 6 posted on Gradescopoe (due end of week 12)
Week 11: Graphs: Basics, BFS and DFS
Nov 8-12

We've reached the last module this semester, graphs. Once you learn about graphs, you start to see their applications everywhere around! This week we start with basic terminology and the traversals, breadth-first and depth-first. These simple algorithms are the stepping stone to many other problems.

Objectives: By the end of this week you should be able to:

Compare and contrast the adjacency list and adjacency matrix representation of a graph
Compare and contrast different types of graph: sparse, complete, dense, trees
Understand basic graph problems: path, connectivity, connected components, reachability
Understand breadth-first and depth-first traversals, their complexity, and their properties
Resources:

Lecture notes: LN-graphBasics.pdf, LN-bfsdfs.pdf
Slides and videos: see Blackboard
Precheck: see Blackboard
Lab: [Lab11]; Lab11-sol see Blackboard
Quiz: Quiz11 see Blackboard
Assignment:
Assignment 6 due end of next week
Week 12 : Application of BFS and DFS. Topological order. Shortest paths basics.
Nov 15-19

This week we introduce the problem of a computing topological order on a directed acyclic graph (DAG). Then we look at how topological order can be used to solve various other problems on DAGs, including a simple algorithm for computing shortest paths on a DAG.

Objectives: By the end of this week you should be able to:

Understand the applications of graph traversal to basic problems on directed and undirected graphs
Understand the concept of topological order
Understand the algorithms for computing topological order
Use topological order for dynamic programming on DAGs
Resources:

Lecture notes: LN-topsort.pdf
Slides and videos: see Blackboard
Precheck: see Blackboard
Lab: [Lab12]; Lab12-sol see Blackboard
Quiz: Quiz12 see Blackboard
Assignment:
Assignment 6 due end of this week
Assignment 7 posted on Gradescopoe (due end of week 15)
Week 13 : Shortest paths on DAGs.
Nov 22 (note: Thanksgiving break 11/23-26)

Objectives:

Understand the properties of shortest paths and how SP can be computed on a DAG
Resources:

Lecture notes: (none this week)
Slides and videos: (none this week)
Precheck: (none this week)
Lab: [Lab13]; Lab13-sol see Blackboard
Quiz: (none this week)
Week 14: Shortest paths.
Nov 29-Dec 3

This week we discuss computing shortest paths in graphs, and see some of the nicest algorithms in Computer's Science: Dijkstra's algorithm and Bellman-Ford's algorithm. While describing them we try to understand some common principles that guided their design. Bellman-Ford's algorithm uses dynamic programming and Dijkstra's algorithm is a greedy algorithm. These are new applications of the problem solving techniques we discussed in the previous weeks!

Objectives: By the end of this week you should be able to:

Understand the algorithms for computing shortest paths explained in the notes: how they work, why they work, and their complexity
Resources:

Lecture notes: LN-shpaths.pdf
Slides and videos: see Blackboard
Precheck: see Blackboard
Lab: [Lab14]; Lab14-sol see Blackboard
Quiz: Quiz14 see Blackboard
Assignment:
Assignment 7 due last day of classes
Week 15: Minimum spanning tree. Final review.
Dec 6-10

This final week we'll introduce another fundamental problem on graphs, the Minimum Spanning Tree (MST). We'll see a couple of properties of MSTs which will get us intuition for how to compute an MST efficiently. We'll glance at two well-known algorithms, Prim's and Kruskal's, which are both greedy algorithms much in the spirit of Dijkstra. Their correctness follows from a neat result called The Cut Theorem.

This last week we'll also do a quick review and work on some extra fun problems!

Objectives: By the end of this week you should be able to:

Understand the concept of MST (minimum spaninng tree) in a graph, and be able to answer basic questions about it sproperties
Know the general idea of Kruskal's and Prim's algorithms, and the Cut Theorem which captures their correctness
Resources:

Lecture notes: LN-mst.pdf, LN-mst-summary.pdf, LN-review.pdf,
Slides and videos: see Blackboard
Precheck: see Blackboard
Lab: [Lab15]; Lab15-sol see Blackboard
Quiz: Quiz15 see Blackboard
Assignment:
Assignment 7 due end of this week
