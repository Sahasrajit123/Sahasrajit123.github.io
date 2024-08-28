---
title: "Research"
permalink: /research/
author_profile: true
use_math: true
title: "Research Experience"
excerpt: "Research Experience"
---

<!--with differentially private user queries and we study this problem epirically and theoretically. In a side project we also focus on the statisitical complexity of (Probably Approximately Correct) PAC learning of a set of items under regression
-->

Research projects: 

My research work at Stanford may be broadly classfied into two groups a) **social choice** and b) machine learing focussing on the selection/learning of multiple items.



<center> ## 1. **Machine learning:** </center>

In this work, we focus on prediction of multiple $k$ items in the context of recommendation systems.

- **Differential Privacy with Multiple Selection**

    * **Objective** We consider a setup where an user sends a differentially private query to the server and propose a ``multi-selection'' architecture where the server sends multiple items and user chooses the one that best fits it. While, the user feature is one-dimensional, we show that Laplace noise addition is an optimal noise addition mechanism for the user and its error scales inversely with the number of items $k$.

    * **Authors:** Ashish Goel<sup>*</sup>, Zhihao Jiang<sup>*</sup>, Aleksandra Korolova<sup>*</sup>, Kamesh Munagala<sup>*</sup> and Sahasrajit Sarmasarkar*
    * [Paper](https://arxiv.org/abs/2407.14641) submitted to [ITCS 2025](http://itcs-conf.org/).

- **Multi-Selection for Private Recommendation Systems**

    * **Objective** We propose a multi-selection model for a neural network-based movie recommendation system, trained on the MovieLens 25M dataset, where users submit differentially private queries to the server. Additionally, we introduce a local PCA model that allows users to select a single item from the set of recommended options. Our empirical results demonstrate that, under "reasonable" privacy guarantees, our architecture achieves a utility comparable to that of the non-private scenario.

    * **Authors** Sahasrajit Sarmasarkar, Zhihao Jiang, Ashish Goel, Aleksandra Korolova and Kamesh Munagala
    * Paper submitted to [WSDM 2025](https://www.wsdm-conference.org/2025/)

- **A Characterization of List Learnability for Agnostic and Realizable Regression**

    * **Objective** In this work, we study the problem of list PAC learning (for both agnostic and realizable regression) where the aim of a learner is to learn to predict a set of $k$ labels with the loss being measured with respect to the closest label. We identify two dimensions of the hypothesis class—referred to as the $k$ fat-shattering dimension and the $k$ OIG dimension—whose finiteness is both necessary and sufficient for agnostic and realizable regression, respectively. 

    * **Authors** Chirag Pabbaraju<sup>*</sup>, Sahasrajit Sarmasarkar*
    * Paper under preparation 

<center> ## 2. **Social choice** </center>

This area focuses on combining individual preferences to make collective decisions and measure social well-being. 

- **Metric Distortion under Probabilistic Voting**

    * **Objective** We extend the study of metric distortion in social choice, which evaluates the performance of voting rules, to the probabilistic voting framework that includes Plackett-Luce (PL). For example, in the PL model with candidate strength inversely proportional to the square of their metric distance, we show that Copeland's distortion is at most 2, whereas that of Random Dictator (RD) scales with the square root of the number of candidates. However in the classical model, where RD beats Copeland with a distortion of 3 versus 5. 

    * **Authors** Sahasrajit Sarmasarkar<sup>*</sup> and Mohak Goyal<sup>*</sup>
    * [Paper](https://arxiv.org/abs/2405.14223) under review at [Neurips 2024](https://neurips.cc/)

- **A Mechanism for Participatory Budgeting With Funding Constraints and Project Interactions**

    * **Objective** We investigate the challenge of participatory budgeting through menu-based preference elicitation, focusing on capturing project interactions, such as substitution and complementarity, from voters. We introduce an innovative preference elicitation approach that enables voters to express how their utilities from projects within specific 'groups' interact. In this context, we examine the property of strategy-proofness and present a fixed-parameter tractable (FPT) algorithm for maximizing social welfare.

    * **Authors** Mohak Goyal<sup>*</sup>, Sahasrajit Sarmasarkar* and Ashish Goel
    * [Paper](https://link.springer.com/chapter/10.1007/978-3-031-48974-7_19) presented at [WINE 2023](https://wine2023.shanghaitech.edu.cn/).

- **Low sample complexity participatory budgeting**

    * **Objective:** We study the problem of participatory budgeting where each voter votes for a preferred allocation of projects. We present a PB mechanism that attains a distortion of 1.66 when three votes are randomly sampled by the mechanism. This surpasses the distortion barrier of 2 achieved by the Randomized Dictator and Random Diarchy schemes, which select one and two voters at random from the set, respectively.

    * **Authors** Mohak Goyal<sup>*</sup>, Sukolsak Sakshuwong<sup>*</sup>, Sahasrajit Sarmasarkar* and Ashish Goel
    * [Paper](https://drops.dagstuhl.de/storage/00lipics/lipics-vol261-icalp2023/LIPIcs.ICALP.2023.70/LIPIcs.ICALP.2023.70.pdf) presented at [ICALP 2023](https://icalp2023.cs.upb.de/).






<!--

1. **Sequential Deliberation in Participatory Budgeting** <br/>
    *Advisor: [Prof. Ashish Goel](https://web.stanford.edu/~ashishg/), Department of Management Science and Engineering, Stanford* <br/>
    *Introduction*: We consider the problem of seqential deliberation in participatory budgeting where randomly sampled agents bargain in rounds with the outcome of the previous round being the diasgreement point for the current round.<br/> 
    * We propose a randomised Nash bargaining scheme which achieves a distortion ratio of 1.66. <br/>
    * We also show that schemes with a single randomly sampled agent (Randomised Dictator) and two sampled agents (Randomised Diarchy) cannot achieve a distortion ratio better than 2. <br/>
    * Paper submitted to [AAMAS, 2023](https://aamas2023.soton.ac.uk/)*


2. **Query Complexity of Heavy-Hitter distribution| Bachelor's Thesis** (Aug '19 - Jan '20) <br/>
  *Guide : [Prof. Nikhil Karamchandani](http://www.ee.iitb.ac.in/~nikhilk/), Department of Electrical Engineering, IIT Bombay* <br/>
  *Introduction*: We studied the problem of identifying the subset of elements in the support of an underlying distribution $\mathcal{P}$ whose probability value is larger than a given threshold $\gamma$, by actively querying an oracle to gain information about a sequence $X_1, X_2, \ldots$ of $i.i.d.$ samples drawn from $\mathcal{P}$ under two different query models $(a)$ each query is an index $i$ and the oracle return the value $X_i$ and $(b)$ each query is a pair $(i,j)$ and the oracle gives a binary answer confirming if $X_i = X_j$ or not.<br/>
  * We propose upper bounds on the query complexity of our algorithm and also derive "matching" lower bounds on any optimal algorithm under both the query models.<br/>
  * We also consider noisy versions of the two query models and propose upper bounds on algorithms to estimate the desired subset of elements.<br/>
  * We derive upper bounds on algorithms for an alternate version of this problem where we wish to identify the subset of support elements which is an "outlier" i.e, whose support probability lies above $k$ standard deviations of the mean and design lower bounds on any optimal algorithm under the first query model.<br/>
  * [Paper](https://arxiv.org/abs/2005.14425) presented at [ISIT, 2021](https://2021.ieee-isit.org/)


3. **Thoerems in redundancies in multi-tasking ** (Jan '20 - Ongoing) <br/>
   *Guide : [Prof. Harish Pillai](https://www.ee.iitb.ac.in/wiki/faculty/hp), Deaprtment of Electrical Engineering, IIT Bombay* <br/>
   *Introduction* : We study the problem of redundancies during distributed computation. We consider a problem of $n$ jobs(tasks) and $c$ servers with $k$ distinct jobs in each server with each job being present in $r$ servers. We attempt to create distributions to ensure minimum redundancies in jobs when a set of $x$ servers chosen uniformly at random return their jobs.
   * We prove that the expectation of the number of distinct jobs is same irrespective of the distribution chosen.<br/>
   * We design a sufficient criterion such that the variance of the number of distinct jobs for any $x$ would be the least amongst all distributions.<br/>
   * We also show that constructions using Balanced Incomplete Block Designs achieved the above requirement for certain values of $n$ and $k$.<br/>   


4. **Straggler mitigation under gradient coding| \[[Report](https://sahasrajit123.github.io/files/partial_gradient_coding_extended.pdf)\]** (Sep '20 - Ongoing) <br/>
   *Guide: [Prof. Lalitha Vadlamani](https://www.iiit.ac.in/people/faculty/lalitha.v), IIIT Hyderabad, [Prof. Nikhil Karamchandani](http://www.ee.iitb.ac.in/~nikhilk/), IIT Bombay* <br/>
   *Introduction* : This is a synchronous gradient coding problem where the master does not expect the sum of all the $k$-gradients but the sum of any $l=\alpha.k$ gradients would suffice. Each of the $n$ child servers is provided with a set of gradients to compute and transmit one or more linear combinations of them. We aim to design schemes which could tolerate upto $s$-stragglers with minimum number of gradients per worker.
   * Designed schemes attaining the lower bound on the number of gradient data subsets assigned to every worker but with high communication load per worker.<br/>
   * Proved that the above scheme is "optimal" in the number of gradients assigned to any worker under certain constraints on $n,l$ and $s$.<br/>
   * We also simulate such schemes using different delay model on machines and show empirically that such schemes may indeed converge faster than full recovery schemes and the ones which don't use any coding.<br/>
   * [Paper](https://arxiv.org/abs/2102.10163) presented at [ISIT, 2021](https://2021.ieee-isit.org/)
   

 
4. **On the early spreading rate of COVID-19 in India| \[[Report](https://www.researchgate.net/publication/340898213_On_the_early_spreading_rate_of_COVID-19_in_India)\]** (Mar '20 - Apr '20) <br/>
   *Guide: [Prof. D.Manjunath](https://www.ee.iitb.ac.in/wiki/faculty/dmanju), Department of Electrical Engineering, IIT Bombay* <br/>
  *Introduction*: We attempted to model the early spreading of CoVID-19  in India and other countries using subtle variations of graphical SIR(Susceptible Infected Recovered) models.
  * Studied various SIR models to approximately model the spread rate of CoVID-19 in India.<br/>
  * Three different models were simulated for four different countries to estimate the contact rates using the data available on the number of cases.<br/>
   


5. **Approximately Optimal Arms Identification of a MAB| \[[Slides](https://Sahasrajit123.github.io/files/Top_k_Arm_Selection.pdf)\]** (Aug '19 - Nov '19) <br/>
   *Guide : [Prof. Sharayu Moharir](https://www.ee.iitb.ac.in/web/people/faculty/home/sharayum), Department of Electrical Engineering, IIT Bombay* <br/>
   *Introduction*: This is a MAB (Multi Arm Bandit) setting problem where we wish to identify a set of top $m$ arms with $\epsilon$-error tolerance correctly with probability at least $(1-\delta)$. This algorithm proceeds in rounds with each round divided into 2 events- Sampling Strategy and Stoppping Criterion.
   * Modified the stopping criterion and the confidence intervals in a previous work on PAC optimal subsets.<br/>
   * Theoretically proved $2/3^{rd}$ factor improvement in the pull complexity with the above modifications.<br/>
    
-->




   <!---
   <ol> 
    <li> Each query is an index $i$ and the oracle return the value $X_i$. </li> 
    <li> Each query is a pair $(i,j)$ and the oracle gives a binary answer confirming if $X_i = X_j$ or not.</li> </ol> <br/>
     -->
  


<!---
My research interests broadly lie in **Applied Probability, Learning Theory, Optimization, Game Theory** and **Social Networks**. I am primarily interested in theoretical aspects of problems in these fields and I also like to apply these tools to solve real world problems.


Research Projects:
===
1.  **Strategic Interaction on Networks with Imperfect Substitutability | Master's Thesis** (June '18 - Present) <br/>
    *Guide : [Prof. Ankur Kulkarni](http://www.sc.iitb.ac.in/~ankur/), Systems & Control Department, IIT Bombay* <br/>
    *Introduction*: We study a public goods game on networks with imperfect substitutability, wherein each node is an agent and the action performed is the effort put in the game. The benefit function of each player is dependent on the sum of their own effort and a substitutability factor times the sum of effort of each of their neighbours. The cost is dependent on only one's own effort.
    * Proved that the Nash equilibria of a public goods game on a network are given by suitably scaled solutions to a Linear Complementarity Problem defined using the adjacency matrix of the underlying graph.<br/>
    * Characterized the effort maximizing solutions of public goods game using special structures on the graph which are generalizations of independent sets.<br/>
    * Derived absolute upper bounds for the aggregate effort of any equilibria when the underlying graphs are trees.<br/>
    
2.  **On independent Cliques and Linear Complementarity Problems | Master's Thesis** (June '18 - November '18) <br/>
    *Guide : [Prof. Ankur Kulkarni](http://www.sc.iitb.ac.in/~ankur/), Systems & Control Department, IIT Bombay* <br/>
    *Introduction*: Linear Complementarity Problem (LCP(M,q)) is an optimization problem defined as  "Find x such that x >= 0, y = Mx + q >= 0,  y^Tx =  0". We study the l<sub>1</sub> norm maximizing solutions of LCP(I + dA,-e), where A is the adjacency matrix of a graph, d belongs to the interval (0,\infty) and e is the vector of 1's.
    * Generalized the concept of independent sets to a union of independent cliques and defined solutions of the LCP(I + dA,-e) with support as union of independent cliques as Independent Clique Solutions (ICS).<br/>
    * Derived an algorithm which constructs an ICS of the LCP(I + dA,-e) for suitable d.<br/>
    * Proved that the maximum l<sub>1</sub> norm amongst all the LCP(I + dA,-e) solutions is achieved by an ICS.<br/>
    * For d >= 1, proved that  the maximum weighted l<sub>1</sub> norm is achieved at the characteristic vector of a maximum weighted independent set.<br/>
    * [Paper](https://arxiv.org/abs/1811.09798) submitted to **Mathematics of Operations Research** 
    
3.  **Estimation of edge resistances using MCMC** (July '17 - October '17) <br/>
    *Guide : [Prof. Vivek Borkar](https://www.ee.iitb.ac.in/web/faculty/homepage/borkar), EE Department, IIT Bombay* <br/>
    *Introduction*: The effective resistance of an edge is the resistance assuming all edges are of resistance 1 unit, which is an important metric in social networks and useful for graph sparsification. We provide a fast (O(nlog(n))) algorithm for estimating edge resistances of a graph.
    * Derived an Markov Chain Monte Carlo (MCMC) based algorithm in a Probably Approximately Correct(PAC) Learning framework to estimate effective edge resistances of a graph.<br/>
    * Provided the complexity analysis and achieved faster convergent rates than existing MCMC algorithms by using Aldous' and Wilson's Algorithm to generate uniform random spanning trees.<br/>
    * Illustrated using simulations that the estimates give the correct order (ranking) of resistances much faster than the time each estimate takes to converge to the true resistance value.<br/>
    \[[Report](https://kc1729.github.io/files/RnD_Report.pdf)\]

4. **Risk Aware Economic Dispatch | Summer Internship** (January '17 - April '17) <br/>
    *Guide : [Prof. Rahul Jain](http://www-bcf.usc.edu/~rahuljai/Welcome.html), EE Department, University of Southern California* <br/>
    *Introduction*: Economic dispatch solves the optimal output of electricity generation facilities, to meet the system load, at the lowest possible cost, subject to transmission and operational constraints. We consider the risk averse version of this problem and solve it.
    * Surveyed the literature of Stochastic Programming and algorithms to solve multistage stochastic programs.<br/>
    * Studied various type of Risk Measures applicable to Power Markets and reformulated the economic dispatch problem to make it solvable under the risk aware and stochastic regime.<br/>
    * Simplified the problem involving CVaR risk measure into a risk neutral stochastic program which can be solved using standard algorithms like Stochastic Decomposition.<br/>
    \[[Report](https://kc1729.github.io/files/report_ver1.pdf)\]

5.  **A Reinforcement Learning Algorithm for Restless Bandits** (January '17 - April '17) <br/>
    *Guide : [Prof. Vivek Borkar](https://www.ee.iitb.ac.in/web/faculty/homepage/borkar), EE Department, IIT Bombay* <br/>
    *Introduction*: The restless bandit problem is to find optimal policies which choose to keep each bandit active or passive at every time step. They use a heuristic called Whittle Index which gives a threshold based near optimal policy. However, computing the Whittle Index is intractable in general and we provide an algorithm to find it.
    * Proposed and analyzed a two timescale learning algorithm to learn the Whittle index for indexable restless bandits which uses the LSPE(Least Squares Policy Evaluation) and Gradient Descent schemes.<br/>
    * Used Linear Function Approximation and Approximate Dynamic Programming to learn the previously intractable Whittle Index Heuristic to solve the restless bandits problem.<br/>
    * Conducted simulations to test our algorithm in scheduling of web crawlers for ephemeral content.<br/>
    * [Paper](https://ieeexplore.ieee.org/abstract/document/8307959) published in Indian Control Conference 2018.<br/>
-->
