# Dynamic-Programming
dynamic programming, find the shortest path in state space to swing up an underactuated acrobot
This is a homework problem for ESE 650 2020 Spring at Upenn.
- the GOAL is to swing up an acrobot from selected initial state. Here an acrobot is 2nd-order-pendulum that can generate torque at the joint connecting two links.

- Use discretized state space that has discretization: 0.0785rad for theta and 0.1rad/s for omega
- use dynamic functions from paper: 'A Case Study in Approximate Linearization: The Acrobot Example'
- use approximate integretion function: 4-th order Runge-Kutta instead of odeint because the latter is too slow
- the process would take 5-10 minutes to run

