# Discrete Math Reviewing #
## Chapter 9 Relations ##
### 9.1 Relations and Their Properties ###

- Let A and B be sets. A binary relation from A to B is a subset of AXB
- We denote that as A **R** B.
- Three properties of relations -reflexive,symmetric(antisymmetric-for every not a=b,R(a,b)=>not R(b,a),asymmetric-exist ),transitive.

### 9.2 n-ary Relations and Their Applications ###
- A n-ary relation can be used on a database and stuff.

### 9.3 Representing Relations ###
- Representing relations using matrices.(0,1)
- Representing relations using Digraphs.(Directed Graph)

### 9.4 Closures of Relations###
- Closure is the new relation includes all relations and add as fewer arches as possible.
- Transitive closures:
- When R<sup>n</sup> don't change anymore ,we get a transitive closure.
- Warshall Algorithm: According the column add every row to the ones with '1'.

### 9.5 Equivalence Relations###
- A relation on a set A is called an equivalence relation if it is reflexive,symmetric and transitive.
- Equivalence classes are the elements that have a relations between each one of them.Each equivalence would have a representative of its kind.
-A partition is that the equivalence relations separate the set into pieces.

### 9.6 Partial Ordering###


## Chapter 7 Discrete Probabilities ##
### 7.2 Probability theory ###
- Conditional Probability  **p(E|F)=p(E&F)/p(F)**. The probability of E given F,so F is the condition.
- Independence- The events E and F are independent if and only if p(E&F)=p(E)p(F)
- Bernoulli	Trials and the Binomial Distribution. The probability of exactly k successes in n independent Bernoulli trails, with probability of success p and probability of failure q=1-p is C(n,k)p<sup>k</sup>q<sup>n-k</sup>.
- Random variables-Birthday Problem

### Bayes' Theorem ###
-p(F|E)=p(E|F)p(F)/(p(E|F)p(F)+p(E|!F)p(!F))
-Suppose that one person in 100,000 has a particular  disease. There is a test for the disease that gives a positive result 99% of the time when given to someone with the disease. When given to someone without the disease, 99.5% of the time it gives a negative result.There **99% is p(E|F) and 1-99.5% is p(E|!F)**
- The Bayesian Span Filter Problem: r(x,y,..,z)=p(x)p(y)...p(z)/(p(x)p(y)..p(z)+q(x)q(y)...q(z)).
