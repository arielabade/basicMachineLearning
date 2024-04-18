# AI Harvard CS50 FreeCodeCamp

## Search: how to make solutions with AI?

- **Terminology**

_Agent_: entity that perceives its environment and acts upon it.

_State_: configuration between agente and enviroment.

_Initial state_: where the agent begins?

_Actions_: the set of actions that occurs through state. Actions are functions valid in certain states. The function may be representated by **F(a)**

_Transition model_: a function tthat returns the result statte at performing an acttionn. The function may be representated by **F(a,s).**

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
  - Put it on repeat:
      - If the frontier is empty, no solution.
      - Remove a node from the frontier.
      - If node containns goal state, return the solution.
      - Expand the node, considering possible actions that drives you to the goal state.
    

## Knowlodge

How to make AI understand and represent information w

## Uncertainty

How computers can deal with uncertain events?

## Optimization

What is the best way to solve tthe problem?

## Learning

How to gather iinnfoormation and transform it into leraning?

## Neural Netwoorks

How we can reproduce brainn thiking?

## Language

How to reproduce natural language?

Source: https://www.youtube.com/watch?v=5NgNicANyqM&t=21053s
