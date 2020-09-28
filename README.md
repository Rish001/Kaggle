# Kaggle

This repo  hosts my ipython notebooks of Kaggle competition: 
## Hash Code Archive
(https://www.kaggle.com/c/hashcode-drone-delivery/data?select=hashcode_delivery_instructions.pdf)

## Problem statement

In this competition, you are given a hypothetical fleet of drones, a list of customer orders, and availability of the individual products in warehouses. Can you schedule the drone operations so that the orders are completed as soon as possible?

## My solution

I modelled the problem as one of **assignment problem** in which **warehouses** serve as **sources** & **Delivery location** as **destinations**
No. of warehouses in the order of 1000
No. of drones in the order of 100
No. of orders in the order of 10000

### Optimisation objective:
Minimise total path cost of drones

## Algorithm Used:
Minimum cost flow algorithm in networks

## problem size
1. No. of warehouses in the order of 1000
2. No. of drones in the order of 100
3. No. of orders in the order of 10000
