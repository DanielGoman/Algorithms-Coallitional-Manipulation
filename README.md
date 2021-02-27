# Algorithms-Coallitional-Manipulation

A work by Lior Danino and Daniel Goman

A project in the course of Social Choice

This project features the algorithms suggested by M. Zuckerman, A.D. Procaccia and J.S. Rosenchein in a paper they published in 2008.

Link to the paper: https://www.sciencedirect.com/science/article/pii/S0004370208001963

The paper discusses the topic of Constructive Coallitional Weighted/Unweighted Manipulation problem (CCWM/CCUM respectively)

The paper features 3 algorithms that under some assumptions, correctly find if there's a coallitional manipulation in the Borda, Maximin and Plurality with Runoff voting rules.

The novelty of their work is presenting algorithms of polynomial time complexity in the size of the input to solve the problem of CCWM/CCUM, which is considered NP-Hard for a variety of prominent voting rules.

In our work we implement the 3 algorithms described in the paper:

    Algorithm 1, which is guaranteed to find a manipulation (when there is one) in the Maximin rule when given two copies of the set of manipulators.
  
    Algorithm 2, which is guaranteed to find a manipulation (when there is one) in the Borda rule when given an extra manipulator with maximal weight.
  
    Algorithm 3, which is guaranteed to find a manipulation (when there is one) in the Plurality with Runoff rule when given an extra manipulator with maximal weight.
  
To show our implementation is valid, we ran those algorithms on demo input which consists of cases where there is and is no manipulation.
