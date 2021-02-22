---
title: "Research"
permalink: /research/
author_profile: true
use_math: true
title: "Research Experience"
excerpt: "Research Experience"
---

Research projects: 



1. **Query Complexity of Heavy-Hitter distribution| Bachelor's Thesis** (Aug '19 - Jan '20) <br/>
  *Guide : [Prof. Nikhil Karamchandani](http://www.ee.iitb.ac.in/~nikhilk/), Department of Electrical Engineering, IIT Bombay* <br/>
  *Introduction*: We studied the problem of identifying the subset of elements in the support of an underlying distribution $\mathcal{P}$ whose probability value is larger than a given threshold $\gamma$, by actively querying an oracle to gain information about a sequence $X_1, X_2, \ldots$ of $i.i.d.$ samples drawn from $\mathcal{P}$ under two different query models $(a)$ each query is an index $i$ and the oracle return the value $X_i$ and $(b)$ each query is a pair $(i,j)$ and the oracle gives a binary answer confirming if $X_i = X_j$ or not.<br/>
  * We propose upper bounds on the query complexity of our algorithm and also derive "matching" lower bounds on any optimal algorithm under both the query models.<br/>
  * We also consider noisy versions of the two query models and propose upper bounds on algorithms to estimate the desired subset of elements.<br/>
  * We derive upper bounds on algorithms for an alternate version of this problem where we wish to identify the subset of support elements which is an "outlier" i.e, whose support probability lies above $k$ standard deviations of the mean and design lower bounds on any optimal algorithm under the first query model.<br/>
  * [Pre-print](https://arxiv.org/abs/2005.14425) posted on [arxiv](https://arxiv.org)


2. **Thoerems in redundancies in multi-tasking| R & D project| \[[Report](https://sahasrajit123.github.io/files/report_RnD.pdf)\]** (Jan '20 - Ongoing) <br/>
   *Guide : [Prof. Harish Pillai](https://www.ee.iitb.ac.in/wiki/faculty/hp), Deaprtment of Electrical Engineering, IIT Bombay* <br/>
   *Introduction* : We study the problem of redundancies during distributed computation. We consider a problem of $n$ jobs and $n$ servers with $k$ distinct jobs in each server with each job being present in $k$ servers. We attempt to create distributions to ensure minimum redundancies in jobs when a set of $x$ servers chosen uniformly at random return their jobs.
   * We prove that the expectation of the number of distinct jobs is same irrespective of the distribution chosen.<br/>
   * We design a sufficient criterion such that the variance of the number of distinct jobs for any $x$ would be the least amongst all distributions.<br/>
   * We also show that constructions using Balanced Incomplete Block Designs achieved the above requirement for certain values of $n$ and $k$.<br/>   


3. **Straggler mitigation under gradient coding| \[[Report](https://sahasrajit123.github.io/files/partial_gradient_coding_extended.pdf)\]** (Sep '20 - Ongoing) <br/>
   *Guide: [Prof. Lalitha Vadlamani](https://www.iiit.ac.in/people/faculty/lalitha.v), IIIT Hyderabad, [Prof. Nikhil Karamchandani](http://www.ee.iitb.ac.in/~nikhilk/), IIT Bombay*
   *Introduction* : This is a synchronous gradient coding problem where the master does not expect the sum of all the $k$-gradients but the sum of any $l=\alpha.k$ gradients would suffice. Each of the $n$ child servers is provided with a set of gradients to compute and transmit one or more linear combinations of them. We aim to design schemes which could tolerate upto $s$-stragglers with minimum number of gradients per worker.
   * Designed schemes attaining the lower bound on the number of gradient data subsets assigned to every worker but with high communication load per worker.<br/>
   * We also design cyclic schemes restricting to transmission of two linear combinations per worker with slightly higher number of gradients being computed by every worker.<br/>
   * Proved that the above scheme is "optimal" in the number of gradients assigned to any worker under certain constraints on $n,l$ and $s$.<br/>
   

 
4. **On the early spreading rate of COVID-19 in India| \[[Report](https://www.researchgate.net/publication/340898213_On_the_early_spreading_rate_of_COVID-19_in_India)\]** (Mar '20 - Apr '20) <br/>
   *Guide: [Prof. D.Manjunath](https://www.ee.iitb.ac.in/wiki/faculty/dmanju), Department of Electrical Engineering, IIT Bombay* <br/>
  *Introduction*: We attempted to model the early spreading of CoVID-19  in India and other countries using subtle variations of graphical SIR( Susceptible Infected Recovered) models.
  * Studied various SIR models to approximately model the spread rate of CoVID-19 in India.<br/>
  * Three different models were simulated for four different countries to estimate the contact rates using the data available on the number of cases.<br/>
   


5. **Approximately Optimal Arms Identification of a MAB| \[[Slides](https://Sahasrajit123.github.io/files/Top_k_Arm_Selection.pdf)\]** (Aug '19 - Nov '19) <br/>
   *Guide : [Prof. Sharayu Moharir](https://www.ee.iitb.ac.in/web/people/faculty/home/sharayum), Department of Electrical Engineering, IIT Bombay* <br/>
   *Introduction*: This is a MAB (Multi Arm Bandit) setting problem where we wish to identify a set of top $m$ arms with $\epsilon$-error tolerance correctly with probability at least $(1-\delta)$. This algorithm proceeds in rounds with each round divided into 2 events- Sampling Strategy and Stoppping Criterion.
   * Modified the stopping criterion and the confidence intervals in a previous work on PAC optimal subsets.<br/>
   * Theoretically proved $2/3^{rd}$ factor improvement in the pull complexity with the above modifications.<br/>
    





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
