MSc-Thesis
==========


**PDF here:**
https://github.com/mike-ghes/MSc-Thesis/blob/master/westernthesis.pdf?raw=true

###High-level thoughts:

  _Hybrid functions don't do anything._ In Symbolic Domains paper, you claimed that this saved us exponential terms. Hybrid functions leave the expression unsimplified. If we wanted an unsimplified expression, the input has n+m terms to begin with. The only gain is moving from n+m terms to n+m-1 terms. What's the point?
	
  _Where is the computer science?_ I feel like the average math undergrad could do a better job writing this thesis. I have two chapters on integration and I'm not really saying anything new on the subject. 
  
#### 1 Introduction
  - https://github.com/mike-ghes/MSc-Thesis/issues/2
  - Needs to be completely rewritten. File hasn't been touched in 4 months. Starting with the intro/conclusion wasn't very helpful.
  
#### 2 Hybrid Set Theory
  - Needs a bit more fluff to blend everything together in the intro.
  - **2.1 Hybrid Sets** https://github.com/mike-ghes/MSc-Thesis/issues/4
    - Need to work on transition.
    - Examples in 2.1.1 and 2.1.2 are a bit silly but I wanted to get something concrete in.
  - **2.2 Hybrid Relations** https://github.com/mike-ghes/MSc-Thesis/issues/5
    - Another silly example in 2.2.1, just wanted to show a relation. I should probably add concrete examples of what [<] looks like.
  - **2.3 Hybrid Functions** https://github.com/mike-ghes/MSc-Thesis/issues/6
    - I should get rid of explicit definition for join and just say "instead of join we used \oplus".
    - I've gotten rid of the whole "marked join". The definitions didn't work and *-reduce accomplishes what we wanted out of marked join.
    - Not sure on definition for refinement
  - **2.4 Pseudo-functions** https://github.com/mike-ghes/MSc-Thesis/issues/7
    - Still to-do. wasn't sure if I wanted to keep pseudo-functions.
	- 2.4.2 Convolution maybe should move to integration? Still very rough.	

#### 3 Symbolic Linear Algebra
  - https://github.com/mike-ghes/MSc-Thesis/issues/8
  - Need to do introduction.
  - **3.1 Oriented Intervals** https://github.com/mike-ghes/MSc-Thesis/issues/9
    - One of the few ideas that doesn't seem like crap to me.
	- Needs some more.
  - **3.2 Vector Algebra** https://github.com/mike-ghes/MSc-Thesis/issues/10
    - Need to switch over to *-reduction from marked join.
    - Figure out outer product which should lead into matrix multiplication
  - **3.3 Matrix Algebra**
    - Effectively unstarted.
	- Addition has already been done.
	- Multiplcation depends on vector outer product	

#### 4 Integration I
  - https://github.com/mike-ghes/MSc-Thesis/issues/11
  - Mostly happy with the chapter, aside from not really saying anything new.
  - Some of the pages break at weird spots.
  - Riemann integration on the chopping block (replace with Lebesgue)

#### 5 Integration II
  - Currently working in here.
  - Might just stop at Stokes on singular chains and leave integration on manifolds as a remark.
  
#### 6 Integration III
  - Possible replacement for Riemann section.

#### 7 Parallel Inclusion/Exclusion
  - ???
  
#### 8 Conclusions
  - Again, needs to be completely rewritten.
	
	
	
	
	
		
	
	