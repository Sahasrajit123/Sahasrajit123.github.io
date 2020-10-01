---
title: "Projects"
permalink: /projects/
author_profile: true
use_math: true
title: "Projects"
excerpt: "Projects"
---

Technical Projects:
1. **Iterative decoding algorithms on modern codes** (Jan '20- May '20)<br/>
   *Guide: [Prof. Manoj Gopalkrishnan](https://www.ee.iitb.ac.in/~manojg), [Prof. Nikhil Karamchandani](http://www.ee.iitb.ac.in/~nikhilk/) Department of Electrical Engineering, IIT Bombay*
   *Introduction*: The goal in this project was to do an existing literature survey on modern codes specifically to do with LPDC (Low Density Parity Check) codes and turbo codes.
   * Studied the classical message passing algorithm on non-cyclic codes and the convergence in error probability of belief propagation algorithm on certain ensembles of LDPC codes under certain symmetric channels.<br/>
   * Read up on EXIT charts to get an information theoretic viewpoint of the decoding process and went through the convergence of the peeling decoder of LDPC codes under Binary erasure channel.<br/>
   * Studied turbo codes, their representations as factor graphs , the density evolution process during iterative decoding , stability condition, their corresponding EXIT charts and their weight distribution.<br/>
   

2. **On the early spreading rate of COVID-19 in India| \[[Report](https://www.researchgate.net/publication/340898213_On_the_early_spreading_rate_of_COVID-19_in_India)\]** (Mar '20 - Apr '20) <br/>
   *Guide: [Prof. D.Manjunath](https://www.ee.iitb.ac.in/wiki/faculty/dmanju), Department of Electrical Engineering, IIT Bombay* <br/>
  *Introduction*: We attempted to model the early spreading of CoVID-19  in India and other countries using subtle variations of graphical SIR( Susceptible Infected Recovered) models.
  * Studied various SIR models to approximately model the spread rate of CoVID-19 in India.<br/>
  * Three different models were simulated for four different countries to estimate the contact rates using the data available on the number of cases.<br/>
   <!-\[[Report](https://www.researchgate.net/publication/340898213_On_the_early_spreading_rate_of_COVID-19_in_India)\]>  
  
3. **Hardware Accelerator for Graphics Computation| \[[Report](https://Sahasrajit123.github.io/files/Report_accelerator.pdf)\]** (Oct '19 - Nov '19) <br/>
   *Guide: [Prof. Madhav Desai](https://www.ee.iitb.ac.in/web/people/faculty/home/madhav), Department of Electrical Engineering, IIT Bombay* <br/>
   *Introduction*: The goal in this project was to build an efficient hardware accelerator which exploits parallelism.
  * Implemented a pipelined design for convolving a kernel with an image stored in a shared memory.<br/>
  * Parallelized the operation using multiple engines which can fetch the image through pipes and perform convolution to reduce computation time and utilize the entire memory bandwidth.<br/>
  
4. **Superscaler and Pipelined Processor Design** (Oct '18 - May '19) <br/>
   *Guide: [Prof. Virendra Singh](https://www.ee.iitb.ac.in/~viren/), Department of Electrical Engineering, IIT Bombay* <br/>
   *Introduction*: The goal in this project was to implement general purpose micro-processor designs with an instruction set architecture having 16 diverse instructions in VHDL.
  * Pipelined RISC processor implementation (Oct '18 - Nov '18)<br/>
  Employed hazard-mitigation, operand-forwarding techniques to design a six stage execution pipeline and synthesized on Altera Deo-Nano FPGA Board running at 50 MHz.<br/>
  * Superscaler processor implementation (Apr '19 - May '19)<br/>
  Designed an out of order execution engine consisting of two way fetch supported by specialised execution engines, reorder buffer, register renaming and reservation station to extract instruction level parallelism.<br/>  

     
    
   
 

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
