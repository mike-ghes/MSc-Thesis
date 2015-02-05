MSc-Thesis
==========

###High-level thoughts:
  _Where is the computer science?_

  Hybrid functions don't give us any computational benefit at all. In Symbolic Domains paper, you claimed that this saved us exponential terms. Hybrid functions only leave the composition unsimplified. The only gain is moving from n+m terms to n+m-1 terms.
	
  We already have inner product of two vectors and matrix addition. I'm working on outer product which should easily extend into matrix multiplication.

  I have two chapters on integration and I'm not really saying anything new on the subject. Also a bit indecisive lately whether I want to go back to simplices for triangle meshes in 3D. Most integration treatments cover simplices but triangles/tets more used for computation.

  
### 1 Introduction https://github.com/mike-ghes/MSc-Thesis/issues/2

	Needs to be completely rewritten. File hasn't been touched in 4 months. Starting with the 
	intro/conclusion wasn't very helpful.

	
### 2 Hybrid Set Theory

  - Motivation for hybrid functions representing piece-wise functions.
	
  - Needs a bit more fluff to blend everything together
	
#### 2.1 Hybrid Sets https://github.com/mike-ghes/MSc-Thesis/issues/4
  
  - Need to work on transition.
	
  - Examples in 2.1.1 and 2.1.2 are a bit silly but I wanted to get something concrete in.
	
#### 2.2 Hybrid Relations https://github.com/mike-ghes/MSc-Thesis/issues/5
  
  - Another silly example in 2.2.1, just wanted to show a relation. Maybe a concrete usage?
	
#### 2.3 Hybrid Functions https://github.com/mike-ghes/MSc-Thesis/issues/6
  
  - Need to get rid of explicit definition for join and just say "instead of join we used \oplus".
  
  - I've gotten rid of the whole "marked join". The definitions don't work. *-reduce accomplishes what we wanted out of marked join.
	
  - Not sure on definition for refinement

#### 2.4 Pseudo-functions https://github.com/mike-ghes/MSc-Thesis/issues/7
		Still to-do. wasn't sure if I wanted to keep pseudo-functions.
		2.4.2 maybe should move to integration? Still very rough.
		
### 3 Symbolic Linear Algebra

  - Need to do introduction.
	3.1 INTERVALS
		One of the few ideas that doesn't seem like crap to me.
		Needs some more.
	3.2 VECTORS
		Need to switch over to *-reduction from marked join.
		Figure out outer product which should lead into matrix multiplication
	3.3 MATRIX
		Effectively unstarted.
		Addition has already been done.
		Multiplcation depends on vector outer product
		
4 Integration I
	Mostly happy with the chapter, aside from not really saying anything new.
	Riemann integration is definitely on the chopping block (replace with Lebesgue)
	
5 Integration II
	Currently working here.
	Might just stop at singular chains.
	
6 Integration III
	Possible replacement for Riemann section.
	
	
	
	
	
		
	
	