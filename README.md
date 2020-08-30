# Solving Ordinary Differential Equations with Deep Learning

There have been many papers solving ODEs, PDEs, SDEs and BSDEs... So this project is just for fun: see whether it is possible and how hard to solve ODEs and others with deep learning, and if so, how good the results will be.

## First Case: 1-dim 1-order ODE.

I simply consider df(x)/dx = 1, f(0) = 0. I use a simple 3-layer NN to approximate the function to be find (f(x) = x).

The results seem to be good on the internal where x is sampled. But I don't know how good it is compared with some classical numerical methods.
