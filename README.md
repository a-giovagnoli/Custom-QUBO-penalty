# Custom QUBO penalties

Quadratic Unconstrained Binary Optimization (QUBO) problems are combinatorial optimization problems which are classically NP hard but which seem to be solvable through the use of Quantum Computers. 

This is a PDF where I sum up an idea that I had to convert into a QUBO penalty a custom constraint given in the form of a truth table.
Once the constraint has been converted into a penalty it can then be summed (subtracted) to the original objective function that we want to minimize (maximize).

I´m not sure if this is a well known or standard practice to convert custom constraints into penalties, but I thought it was worth formalizing it and sharing it.
