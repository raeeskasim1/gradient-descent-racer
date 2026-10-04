# Gradient Descent Racer

Follow a ball downhill on a loss curve. A learning rate can make it settle, wobble, or escape.



## Try it

Change the learning rate, run the descent, then reset and compare with rate 1.20. Use One step to inspect each update.

## How it works

This implements gradient descent on a one-dimensional quadratic. The derivative is exact. A rate below 1 converges for this loss; rate 1 oscillates and rates above 1 diverge unless already at the minimum. The display stops extreme divergence and clips loss values above the chart range. This is optimization, not neural-network training.
