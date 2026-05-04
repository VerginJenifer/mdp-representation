# MDP REPRESENTATION

## AIM:
To model the food delivery process as a Markov Decision Process (MDP) and analyze the states, actions, and rewards involved in completing the delivery efficiently.

## PROBLEM STATEMENT:

### Problem Description
An agent (delivery person) is assigned to deliver food from a restaurant to a customer. The goal is to complete the delivery quickly while minimizing delays and effort. The agent chooses actions such as picking up food, moving, or delivering based on the current state.

### State Space
The state space represents all possible stages of the delivery process:

D0 → Order Not Picked
D1 → Food Picked
D2 → Delivered (Goal State)

### Sample State
"Food is picked and the agent is on the way to the customer" (D2)

### Action Space
The possible actions available to the agent:

->Pick Up Food
->Start Delivery
->Continue Moving
->Deliver Food

### Sample Action
"Continue Moving"

### Reward Function
The reward function guides the agent:
+10 → Successfully picking up food
+20 → Delivering food to customer (goal achieved)
-2 → Delay in movement
-5 → Wrong action or unnecessary delay

### Graphical Representation
<img width="611" height="197" alt="image" src="https://github.com/user-attachments/assets/4df3c03f-7e1d-46c1-898f-4d98c13f8ac4" />



## PYTHON REPRESENTATION:


## OUTPUT:
Write your Python output here

## RESULT:
Write your output here

