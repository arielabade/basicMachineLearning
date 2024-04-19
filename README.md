# AI Harvard CS50 FreeCodeCamp

## Search: how to make solutions with AI?

- **Terminology**

_Agent_: entity that perceives its environment and acts upon it.

_State_: configuration between agente and enviroment.

_Initial state_: where the agent begins?

_Actions_: the set of actions that occurs through state. Actions are functions valid in certain states. The function may be represented by **F(a)**

_Transition model_: a function that returns the result state at performing an acttionn. The function may be representated by **F(a,s).**

State space: the set of all possible states.

Goal state: determine if a goal state is a goal state. The final solution.

Path cost: numerical coost assciated with a given path. Whats the computational cost of the solution?

Solution: the solution that drives the initial state for the goal state.

Optimal solution: the solution with the lowest cost.

Node (a data structure that keep informations of):
  - A state.
  - A parent (the node that generated that node)
  - An action (action applied to parent to get node)
  - A path cost (the cost from the initial state to node)

- **Problem Approach**

  Frontier approach: how to go to the initial state to goal state?

  - Start with a frontier that contains the initial state.
  - Star with an empty explored set.
  - Put it on repeat:
      - If the frontier is empty, no solution.
      - Remove a node from the frontier.
      - If the  node contains a goal state, returns the solution.
      - Add the node to the explored sett.
      - Expand the node, considering possible actions that drive you to the goal state, adding result nodes to the frontier if they are not in the frontier yet.

    OBS: this avoids going back and forth between nodes.

- **How to keep the solution process to initial state to goal state**    


-**Depth-first search:** explores the path as deep as possible. It is implemented with a **stack** (pile up the solution in a stack data structure, with the last in first out using the frontier solution logic.)

-**Breadth-first search:** starts at a selected node and explores all of its neighbors. It's implemented with a **queue** first-in first-out datatype. 


- **Kinds Of Algorithms**

- **Uninformed search:** search strategy that uses no problem-specific knowledge.
  
-  **Informed search:** search strategy that uses problem-specific knowledge to find better solutions.

-**Variations**

-**Greedy best-first search:** search algorithms that expand the node that is close to the goal, based on a heuristic function (what is the shortest distance between the initial state and the goal?)  **H(n)**

-**A- STAR search:** search algorithms that expand the node with the cost value of node G(n) and the estimated cost to reach goal H(n). Reaching the total cost of **G(n) + H(n)**.
OBS: A- STAR search is optimal if H(n) never overestimates the cost and H(n) is a consistent heuristic function.

-**Algorithms**

- **Adversarial Algorithm (Minimax):** How to create an adversarial AI model to play tic-tac-toe?
    - Max(X) aims to maximize the score.
    - Min(O) aims to minimize the score.
    obs: giving data to the IA it is possible to train a model that plays tic-tac-toe.

**Requirements for tic-tac-toe AI**:

     - S0: initial state.
     
     - Players(s): returns which player to move in state _s_.

     - Actions(s): returns legal moves in state _s_.
     
     - Results(s,a): return state after action a taken in state _s_. -> transition function, takes a state as input and makes an action.
     
     - Terminal(s): checks if state _s_ is _a_ terminal state.
     
     - Utility(s):  final numerical value for terminal state _s_.

What happens after defining the requirements?

      1) 

- **Alpha-Beta Pruning:**
- **Evaluation FUnction:**

## Knowlodge

How to make AI understand and represent information w

## Uncertainty

How computers can deal with uncertain events?

## Optimization

What is the best way to solve tthe problem?

## Learning

How to gather information and transform it into learning?

## Neural Netwoorks

How we can reproduce brainn thiking?

## Language

How to reproduce natural language?

Source: https://www.youtube.com/watch?v=5NgNicANyqM&t=21053s

## Possible projects

- Tic Tac TOE (1:24h)
- 
