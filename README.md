Dynamic Epistemic Learning Course

Shuai Wang @ ILLC, UvA

In case of confusion:

The number of preconditon is named demand;
The number of postcondition is named active;

To use:

1) You need BuDDy.

2) Compile Smodels as described.

2) Go to the mas directory and type:

	make main
	
3) For precondition free action learning, type:

	./main 1 100 (for a domain of 100 propositions)
or

	./main 1 1000 (for a domain of 1000 propositions)

4) For conditional action learning, type:

	./main 2 100 (for a domain of 100 propositions)
or  

	./main 2 1000 (for a domain of 1000 propositions)

and for demand-oriented testings, type:

	./main 3 (the domain is hard-coded to 100)
