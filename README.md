# dynamic-programming
Dynamic Programming notes and findings for in-house presentation

Links
-----
* [Dynamic Programming – From Novice to Advanced] (https://www.topcoder.com/community/data-science/data-science-tutorials/dynamic-programming-from-novice-to-advanced/)
* [Introduction to Dynamic Programming Applied to Economic] (http://www.fep.up.pt/docentes/joao/material/aea/notas_pbrito_2008.pdf)
* [Principle of Optimality - Dynamic Programming] (https://www.youtube.com/watch?v=_zE5z-KZGRw)

Knapsack
--------
* [Solving using the bottom up approach with detailed explanation and images] (http://www.es.ele.tue.nl/education/5MC10/Solutions/knapsack.pdf)
* [Comparing bottom up and top down approach (code in Java)] (https://github.com/mission-peace/interview/blob/master/src/com/interview/dynamic/Knapsack01.java)
* [Comparing bottom up and top down approach with solution picker diagrams (code in C)] (http://www.programminglogic.com/knapsack-problem-dynamic-programming-algorithm/)

Interesting Use Cases
---------------------
* https://www.youtube.com/watch?v=qadw0BRKeMk
* Distribution of effort problem (Operational Research):
  * https://www.oxbridgenotes.co.uk/revision_notes/operational-research-lse-operational-research-techniques/samples/further-dynamic-programming
  * http://www-home.math.uwo.ca/~heinicke/courses/236_03/dynprog_virusex_upd.htm
  * http://web.csulb.edu/~obenli/Research/IE-encyc/dynprog.html (good intro and usage of DP to solve inventory control problem aka Dynamic lot-size model)


Dynamic Programming vs ...
--------------------------
* [Divide and Conquer] (https://en.wikipedia.org/wiki/Divide_and_conquer_algorithms)
* [Memoization] (https://en.wikipedia.org/wiki/Memoization)
* [Recursion] (https://www.codechef.com/wiki/tutorial-dynamic-programming#Cold_War_between_Systematic_Recursion_and_Dynamic_programming)
* [Greedy] (https://en.wikipedia.org/wiki/Greedy_algorithm)


History
-------
[RICHARD BELLMAN ON THE BIRTH OF DYNAMIC PROGRAMMING] (http://smo.sogang.ac.kr/doc/dy_birth.pdf)

The essence of dynamic programming is Richard Bellman's Principle of Optimality. This principle, even without rigorously defining the terms, is intuitive:

"An optimal policy has the property that whatever the initial state and the initial decisions are, the remaining decisions must constitute an optimal policy with regard to the state resulting from the first decision."

This is a self-evident principle in the sense that a proof by contradiction is immediate. Rutherford Aris restates the principle in more colloquial terms:

"If you don't do the best with what you have happened to have got, you will never do the best with what you should have had."


Analogy
-------
How do you put together a jigsaw puzzle?  You find pieces that fit together and connect them.  What happens when you connect two big chunks of pieces together?  You get an even bigger chunk. Dynamic Programming is the same kind of thing.  You solve the easy small problems first (finding individual pieces that fit together), and then use the results to solve the larger problem (combining all the little pieces into the whole puzzle).
