# Lecture 0

Agent - entity that perceives its environment and acts upon that environment

State - a configuration of the agent and its environment

initial state- from where the agent begins

actions - choices that can be made in a state(funciton)
Actions(s) returns the set of actions that can be executed in state s

transition model - a description of what state results from performing any applicable action in any state
Results(s,a) returns the state resulting from performing action a in state s

state space - the set of all states reachable from the initial state by any sequence of actions

goal test - way to determine whether a given state is a goal state

path cost - numerical cost associated with a given path

## Search Problem

- intial state
- actions
- transition model
- goal path
- path cost function
