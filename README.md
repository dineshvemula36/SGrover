# SGrover  A Scalable 5,6-Qubit Grover's Quantum Search Algorithm
  Grover's quantum search algorithm is one of the well-known applications of quantum computing, enabling quantum computers to perform a database search (unsorted array) 
and quadratically outperform their classical counterparts in terms of time. Given the restricted access to database search for an oracle model (black-box), 
researchers have demonstrated various implementations of Grover's circuit for two to four qubits on various platforms. However, larger search spaces have not yet been
explored. This is because every time you want to exaplore a large search space you have to design a new circuit. All these circuits vary from each other.  
In this work, we find a common design pattern for ease of building an Oracle for a higher order of qubits.  Furthermore, the reusability of the proposed 
quantum circuits using subroutines is also illustrated by the opportunity for large-scale implementation of quantum algorithms in the future.


Here I put a few circuits that make it easier to tackle the this problem. The idea of formulating it in a way that is computable by a IBM quantum computer and is based on our work of 
Dr. Dinesh Reddy Vemula  et al. and the paper:  https://arxiv.org/abs/2205.00117

