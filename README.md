# extremum_seeking
A collection of extremum seeking control implementations.  What's included:

 - Vanilla Extremum Seeking: basic ES peak-seeking scheme.  Algorithm minimizes a quadratic objective, includes low pass filtering of gradient estimate
 
  - Adaptive Probe Extremum Seeking: Vanilla ES with adaptive probe amplitude.  Probe amplitude is determined after passing gradient estimate through squared sigmoid function and low pass filtering.  This algorithm removes the neighborhood convergence of vanilla ES and allows the algorithm to converge to the true optimum asymptotically
