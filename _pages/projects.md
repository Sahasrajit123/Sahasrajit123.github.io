---
title: "Undergraduate Projects"
permalink: /projects/
author_profile: true
use_math: true
title: "Undergrad Projects"
excerpt: "Projects"
---

My undergrad projects may be classified into a) **theoretical research** and b) **hardware design work**. 

<!-- * We propose upper bounds on the query complexity of our algorithm and also derive "matching" lower bounds on any optimal algorithm under both the query models.<br/>
  * We also consider noisy versions of the two query models and propose upper bounds on algorithms to estimate the desired subset of elements.<br/>
  * We derive upper bounds on algorithms for an alternate version of this problem where we wish to identify the subset of support elements which is an "outlier" i.e, whose support probability lies above $k$ standard deviations of the mean and design lower bounds on any optimal algorithm under the first query model.<br/> 
* We show that assignments based on balanced incomplete block designs ensure the variance of the number of distinct jobs would be the least amongst all distributions.<br/>
   * Furthermore, assignments based on repetition coding ensure the variance of the number of distinct jobs is the largest<br/> 
        We prove that the expectation of the number of distinct jobs is same irrespective of the assignment chosen.<br/>
    Introduction* : This is a synchronous gradient coding problem where the master does not expect the sum of all the $k$-gradients but the sum of any $l=\alpha.k$ gradients would suffice. Each of the $n$ child servers is provided with a set of gradients to compute and transmit one or more linear combinations of them. We aim to design schemes which could tolerate upto $s$-stragglers with minimum number of gradients per worker.
   * Designed schemes attaining the lower bound on the number of gradient data subsets assigned to every worker but with high communication load per worker.<br/>
   * Proved that the above scheme is "optimal" in the number of gradients assigned to any worker under certain constraints on $n,l$ and $s$.<br/>
   * We also simulate such schemes using different delay model on machines and show empirically that such schemes may indeed converge faster than full recovery schemes and the ones which don't use any coding.<br/>
   * [Paper](https://arxiv.org/abs/2102.10163) presented at [ISIT, 2021](https://2021.ieee-isit.org/) and [Extended version accepted at IEEE-TCOM](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=26).
    * Implemented a pipelined design for convolving a kernel with an image stored in a shared memory.<br/>
  * Parallelized the operation using multiple engines which can fetch the image through pipes and perform convolution to reduce computation time and utilize the entire memory bandwidth.<br/>
* Pipelined RISC processor implementation (Oct '18 - Nov '18)<br/>
  Employed hazard-mitigation, operand-forwarding techniques to design a six stage execution pipeline and synthesized on Altera Deo-Nano FPGA Board running at 50 MHz.<br/>
  * Superscaler processor implementation (Apr '19 - May '19)<br/>
  Designed an out of order execution engine consisting of two way fetch supported by specialised execution engines, reorder buffer, register renaming and reservation station to extract instruction level parallelism.<br/>
* Designed the harness of the whole car keeping into considerations the current and voltage rating of each input signal in each board.<br/>
  * Designed and tested the CAN (Controlled Area Network) node using CAN enabled micro-controller atmega-16M1 in embedded C using interrupts for sending and receiving messages.<br/>
  * Developed codes using interrupts in ECU (embedded C programming) for reading data from CAN bus, processing and sending control commands to BLDC (Brushless DC motors) on CAN bus.<br/> -->

  <!-- The goal in this project was to implement general purpose micro-processor designs with an instruction set architecture having 16 diverse instructions in VHDL.  -->

**Theoretical research projects**:

We focussed on problems related to **gradient coding, distributed computing** and some problems in **heavy-hitter estimation**. 

- **Query Complexity of Heavy-Hitter distribution** (Aug '19 - Jan '20) <br/>
  *Guide : [Prof. Nikhil Karamchandani](http://www.ee.iitb.ac.in/~nikhilk/), Department of Electrical Engineering, IIT Bombay* <br/>
  * **Objective**: We investigated the problem of identifying the subset of elements in the support of an underlying distribution $\mathcal{P}$ with probabilities exceeding a given threshold $\gamma$, using **two distinct query models** under a fixed confidence. In the first model, a query $t$ provides the realization of the random variable $X_t$. In the second model, a query $(i,j)$ reveals whether $X_i$ is equal to $X_j$. We provide **upper and lower bounds** under both the query models.
  * **Authors:** Sahasrajit Sarmasarkar, Kota Srinivas Reddy and Nikhil Karamchandani
  * [Paper](https://arxiv.org/abs/2005.14425) presented at [ISIT, 2021](https://2021.ieee-isit.org/)


- **Optimal Moments on Redundancies in Noisy Parallel Computing Setup**| [Paper](https://arxiv.org/abs/2402.12584) (Jan '20 - Jan '21) <br/>
   *Guide : [Prof. Harish Pillai](https://www.ee.iitb.ac.in/wiki/faculty/hp), Deaprtment of Electrical Engineering, IIT Bombay* <br/>
   * **Objective**: We consider a setup where the master assigns $n$ jobs(tasks) to $c$ servers with $k$ distinct jobs in each server with each job being present in exactly $r$ servers. The goal is to ensure that the master receives most of jobs when each server is equally likely to straggle and we show balanced incomplete block designs and repitition coding based assignments attain the least and the largest variance respectively. 
   * **Authors:** Sahasrajit Sarmasarkar and Harish Pillai
   


- **Straggler mitigation under gradient coding** (Sep '20 - Sep '21) <br/>
   *Guide: [Prof. Lalitha Vadlamani](https://www.iiit.ac.in/people/faculty/lalitha.v), IIIT Hyderabad, [Prof. Nikhil Karamchandani](http://www.ee.iitb.ac.in/~nikhilk/), IIT Bombay* <br/>
   * **Objective**: We consider the problem of **gradient descent** where the master does not compute the sum of gradients across all $n$ data points but sum of any $\alpha$ fraction of them suffices. We study this problem as a **distributed gradient coding** problem where each child server has access to some gradients and it sends their linear combination to the server and we showed the optimality of some of our schemes. Further, we show empirically that such schemes may indeed converge faster than typical baselines.
   * **Authors:** Sahasrajit Sarmasarkar, Lalitha Vadlamani and Sahasrajit Sarmasarkar
   * [Paper](https://arxiv.org/abs/2102.10163) presented at [ISIT, 2021](https://2021.ieee-isit.org/) and [Extended version accepted at IEEE-TCOM](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=26).
 

   <!-- 
 -->


**Digital System Design Work**:

<!--- 
1. **Iterative decoding algorithms on modern codes| \[[Report](https://Sahasrajit123.github.io/files/Godzilla.pdf)\]** (Jan '20- May '20)<br/>
   *Guide: [Prof. Manoj Gopalkrishnan](https://www.ee.iitb.ac.in/~manojg), [Prof. Nikhil Karamchandani](http://www.ee.iitb.ac.in/~nikhilk/), EE, IIT-B*<br/>
   *Introduction*: The goal in this project was to do an existing literature survey on modern codes specifically to do with LPDC (Low Density Parity Check) codes and turbo codes.
   * Studied the classical message passing algorithm on non-cyclic codes and the convergence in error probability of belief propagation algorithm on certain ensembles of LDPC codes under certain symmetric channels.<br/>
   * Read up on EXIT charts to get an information theoretic viewpoint of the decoding process and went through the convergence of the peeling decoder of LDPC codes under Binary erasure channel.<br/>
   * Studied turbo codes, their representations as factor graphs , the density evolution process during iterative decoding , stability condition, their corresponding EXIT charts and their weight distribution.<br/>
--->

- **Hardware Accelerator for Graphics Computation| \[[Report](https://Sahasrajit123.github.io/files/Report_accelerator.pdf)\]** (Oct '19 - Nov '19) <br/>
   *Guide: [Prof. Madhav Desai](https://www.ee.iitb.ac.in/web/people/faculty/home/madhav), EE, IIT-B* <br/>
   **Introduction**: The goal in this project was to build an efficient hardware accelerator which exploits parallelism and we implemented a **pipelined design** for convolving a kernel with an image stored in shared memory. **Parallelized** the operation using multiple engines which can fetch the image through pipes and perform **convolution** to reduce computation time and utilize the entire memory bandwidth.
  


  
- **Superscaler and Pipelined Processor Design| \[[Github repository](https://github.com/mohilp1998/superscalar_architecture)\]** (Oct '18 - May '19) <br/>
   *Guide: [Prof. Virendra Singh](https://www.ee.iitb.ac.in/~viren/), EE, IIT-B* <br/>
   **Introduction**: Designed a **pipelined RISC** processor that employed **hazard-mitigation, operand-forwarding** techniques and an execution superscaler engine consisting of two way fetch supported by **specialised execution engines, reorder buffer, register renaming and reservation station** to extract instruction level parallelism. 
   <!-- Verified the running of these designs on a simulator and further synthesized on **Altera Deo-Nano FPGA** Board running at 50 MHz. -->
  


- **[IIT Bombay Racing](https://iitbracing.org) (Electric Subsystem)** (Academic year '17-'19) <br/>
   Worked as a **junior design engineer** and a **design enginner** in a cross functional team of 60+ students from 7 engineering disciplines which designs and fabricates an electric race car for [Formula Student](https://www.imeche.org/events/formula-student) competition held annually at Silverstone, UK.<br/>
   **Tasks accomplished**: 
   * Lead the designed of the **harness** of the whole car taking into account the electric requirements of each part. Further, we designed and tested the **CAN (Controlled Area Network)** node using **CAN** enabled micro-controller **atmega-16M1** in embedded C using interrupts.<br/> 
   * Developed codes using interrupts in ECU (**embedded C programming**) for reading data from CAN bus and sending control commands to **BLDC** motors.<br/>
  
   
 
<!-- 6. **Stereo-Camera Calibration & Image Rectification on FPGA** (Summer '18) <br/>
   *Guide: [Prof. Sachin Patkar](https://www.ee.iitb.ac.in/web/people/faculty/home/patkar), EE, IIT-B* <br/>
   * Developed a dual OV7670 camera setup compatible with De0-Nano Board (Cyclone IV-E FPGA).<br/>
   * Used FTDI chip FT245RL for sending bytes captured by camera in default YUV format through serial port communication with PC by writing VHDL and Verilog codes.<br/>
   * Used OpenCV library on C++ for image construction from the received bytes on the serial port of PC.<br/>

   3.  **Carry Save Adder Network Optimisations| Summer Internship** (May '19 - July'19) <br/>
   *Texas Instruments, Bangalore* <br/>
   * Devised algorithms for connections of input and output pins of full adder cells so as to minimise the maximum delay of the whole network.<br/>
   * Worked on buffer insertion problem and used linear programming to insert buffers so that the whole network could be wave-pipelined.<br/>
   * Worked on cell-selection problem to meet a certain delay target of the whole network with the lowest cost.<br/>
   * Implemented all the above algorithms using actual delay data of cells as per 65nm node technology to incorporate slew and loading of cells and generalised the above two algorithms to any combinational network.<br/>
  
    
 -->

 

 
 

<!---
Technical projects:

1. **Approximately Optimal Arms Identification of a Multi-Armed Bandit** (Aug' 2019 - Nov' 2019) <br/>
   *Guide : [Prof. Sharayu Moharir](https://www.ee.iitb.ac.in/web/people/faculty/home/sharayum)* <br/>
    This is an exploration problem to identify a subset of m arms which perform better than the remaining n-m arms with at least $1-\delta$ confidence. We use a PAC framework which consists of two main events -- Sampling strategy and Stopping criteria. We studied variants of the Top-k arm selection problem in the multi-armed bandit setting with Bernoulli bandits. We suggested an alternative stopping criterion and proved improved bounds on sample complexity in the PAC framework. These theoretical results were verified by experiments on a suite of bandit instances. <br/>
  \[[Slides](https://kc1729.github.io/files/Top_k_Arm_Selection.pdf)\]
--->
<!---
I have outlined my non-research projects in this page. My research work can be found [here](https://kc1729.github.io/research/)

Technical Projects:
===
1.  **Deep Reinforcement Learning for Atari games |  Summer Internship** (May '16 - July '16) <br/>
    *Guide : [Prof. Paul Weng](https://weng.fr/index.html), [UM-SJTU Joint Institute](http://umji.sjtu.edu.cn/)* <br/>
    Reviewed the code of Google DeepMind for choosing optimal actions while playing Atari Games and ran experiments on  variants of its  Deep Q-Network (DQN) by incorporating ideas like  Double DQN and  Duelling network architectures.  Binarized the neural network estimating the Q-function to speed up learning and save on memory, leading to a  3-fold decrease in memory usage compared to original code.<br/>
    
2.  **Mathematics of Deep Learning** (Jan '18 - April '18) <br/>
    *Guide : [Prof. Vivek Borkar](https://www.ee.iitb.ac.in/web/faculty/homepage/borkar), EE Department, IIT Bombay* <br/>
    Surveyed the recent literature on the mathematics underlying regularization in deep neural networks and how stochastic gradient descent (SGD) performs variational inference. Reviewed theoretical analysis of Entropy-SGD which provably outperforms the classical SGD algorithm by converging to wider valleys.
    \[[Report](https://kc1729.github.io/files/EE763_140070014.pdf)\]
    
3.  **Risk Constrained Markov Decision Processes** (Jan '17 - April '17) <br/>
    *Guide : [Prof. Vivek Borkar](https://www.ee.iitb.ac.in/web/faculty/homepage/borkar), EE Department, IIT Bombay* <br/>
    Surveyed the literature on risk aware markov decision processes and corresponding reinforcement learning algorithms, namely risk-aware versions of value iteration, policy gradient and actor-critic algorithms.
    \[[Report](https://kc1729.github.io/files/EE736_140070014.pdf)\]
        
4.  **Johnson-Lindenstrauss Lemma and its Applications** (Jul '17 - November '17) <br/>
    *Guide : [Prof. Sharayu Moharir](https://sites.google.com/site/sharayumoharir/), EE Department, IIT Bombay* <br/>
    Studied and presented various probabilistic proofs and applications of Johnson-Lindenstrauss lemma which uses random projections to find low-distortion embeddings of points into a low-dimensional space.
    
5.  **RF Transmit Dongle for Communications Lab** (Jan '17 - April '17) <br/>
    *Guide : [Prof. Shalabh Gupta](https://www.ee.iitb.ac.in/wiki/faculty/shalabh), EE Department, IIT Bombay* <br/>
    Prototyped a low cost, portable transmit dongle compatible with GNURadio which transmits signals with sampling rate upto 3 MSamp/sec using AFE7070 modulator, Hitachi SRAM and a 0808 DAC circuit. Generated digital samples using custom-made GNURadio block, enabled data transmission to FPGA using UART and sent the signal to AFE7070 Modulator after digital to analog conversion.
    
6.  **Microprocessor Design - Pipelined Implementation** (July '16 - November '16) <br/>
    *Guide : [Prof. Virendra Singh](https://www.ee.iitb.ac.in/~viren/), EE Department, IIT Bombay* <br/>
    Designed and implemented a working microprocessor with 19 instructions using a Pipelined design architecture on the Deo Nano Board in VHDL. Used the NMRU (Not Most Frequently Used) scheme and implemented a fully associative cache so as to improve the performance.
    
7.  **8-PSK Costas Loop GNURadio Block** (July '16 - November '16) <br/>
    *Guide : [Prof. Shalabh Gupta](https://www.ee.iitb.ac.in/wiki/faculty/shalabh), EE Department, IIT Bombay* <br/>
    Designed a custom GNURadio block using Python which performs carrier frequency recovery from phase modulation signals for small frequency errors of the order 10−1 hertz and noise with amplitude around 2 % of the signal amplitude. Analysed the Gain margin and Phase margin for the custom block.
    
    
8.  **Pyraminx Utility Kit** (Jan '15 - April '16) <br/>
    *Guide : [Prof. Kavi Arya](https://https://www.it.iitb.ac.in/~kavi/), CSE Department, IIT Bombay* <br/>
    Implemented the BFS algorithm and AVL trees to derive the  optimal solutions of a Pyraminx, a tetrahedron Rubiks Cube style puzzle. Used Allegro, a C++ framework,  to design an interface to help solve pyraminx optimally, find cube algorithms and generate solve analysis. Designed an Android app implementing image processing techniques to read pyraminx configurations and send it to a Java server.
-->
