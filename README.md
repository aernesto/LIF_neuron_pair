# Broad goals
Simulate a pair of LIF neurons that encode a time-varying signal with [NEURON + Python](https://neuron.yale.edu/neuron/static/docs/neuronpython/firststeps.html).

We follow closely section 4.3.3 from "[Neural Engineering](https://mitpress.mit.edu/books/neural-engineering)"
by C. Eliasmith and C. H. Anderson.

# Quote from book
The caption of figure 4.7 reflects well our goal:
> An example of linear filtering. The input signal, 
> <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;x(t)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;x(t)" title="x(t)" /></a>,
> is fed into the somas of a pair of on-off neurons which encode the signal into 'on' and 'off' spikes. To get an estimate, 
> <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;\hat{x}(t)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\inline&space;\hat{x}(t)" title="\hat{x}(t)" /></a>, of that signal, we can linearly filter those spike trains by effectively placing the filter at the time of occurrence of each spike and summing the result. When the on and off neurons are symmetrical, their respective filters will be 'mirror images', as shown in the figure. 
