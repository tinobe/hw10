# Homework 10
### The Diffusion equation


Consider the diffusion equation
<p align="center">
<img src="stuffy_stuff/f1.png" width="100">
</p>
where *D* is a positive constant.

The explicit forward time centered space (FTCS)
method is
<p align="center">
<img src="stuffy_stuff/f2.png" width="300">
</p>

The von Neumann stability analysis predicts stability for
<p align="center">
<img src="stuffy_stuff/f3.png" width="100">
</p>

Implement this explicit method and compare the numerical results to the analytic solution. The analytic solution is available as column 3 in every output file. Experiment with different *dt* (or equivalent with different *D*). how is the numerical solution affected once the stability criterion is violated?
