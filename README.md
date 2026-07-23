# numerical-investigation
Investigating efficient methods of numerical computation

### Logarithms (see [logarithm.ipynb])
- Naive series approximation for Log(1 + x)
    - linear convergence
    - numerically stable
- Cleverer series approximation using Log((1+x)/(1-x))
    - Quadratic convergence
    - numerically stable
- Newton-Raphson method for Exp(t) - x
    - quadratic convergence
    - expensive in flops / iteration
    - potentially unstable
- Simpson rule integration for 1/t
    - Fixed flops


Achievable accuracy as a function of the number of floating point operations expended. 
![accuracy per flop](accuracy_per_flop.png)
