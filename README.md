# MDP REPRESENTATION

## AIM:
To represent a Markov Decision Process(MDP) problem in the following ways.

Text representation,
Graphical representation,
Python - Dictonary representation.

## PROBLEM STATEMENT:

### Problem Description
To develope a game application. The role of the agent is to promote if the level is cleared or depromote if the game is lost.

### State Space
{L1,L2,L3}->{0,1,2}
- L1-> Level 1
- L2-> Level 2
- L3-> Level 3

### Sample State
L1-> 0-> Level 1

### Action Space
{W,L}->{0,1}
- W-> Winning
- L-> Loosing

### Sample Action
W-> 0-> Winning

### Reward Function
```
R= {
    +1, if we come closer to winning
    +0, otherwise

```
### Graphical Representation
![image](https://github.com/srinivas-aids/mdp-representation/assets/93427183/f2de4644-ae1c-4d07-8a3e-8a02e298a734)


## PYTHON REPRESENTATION:
```py
T = {
    0 : {
        0 : [(1.0, 1, 1.0, True)],
        1 : [(1.0, 0, 0.0, False)]
    },
    1 : {
        0 : [(1.0, 2, 1.0, True)],
        1 : [(1.0, 0, 0.0, False)]
    },
    2 : {
        0 : [(1.0, 2, 1.0, True)],
        1 : [(1.0, 1, 0.0, False)]
    }
}

T
``````

## OUTPUT:
<img width="451" alt="image" src="https://github.com/srinivas-aids/mdp-representation/assets/93427183/7419c4a2-6fde-4f7b-898d-fbfb97c46a22">

## RESULT:
Thus the given Markov Decision Process(MDP) problem is represented in the following ways.

Text representation,
Graphical representation,
Python - Dictonary representation.
