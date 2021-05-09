# Particle Filter

Particle filter is a technique for implementing recursive Bayesian filter by Monte Carlo sampling. The idea is to represent the posterior density by a set of random particles with associated weights and then compute estimates based on these samples and weights.

### Project

In this project I have implemented a 2 dimensional particle filter in C++. The particle filter was given a map and some initial localization information (analogous to what a GPS would provide). At each time step the filter will also get observation and control data.
