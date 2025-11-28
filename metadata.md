# Parameters used in the experiments

Common shared parameters:

- Population size: 128
- Offspring size. 128
- K: 15
- Generations: 1000
- Mutation: uniform_one_mutation
- Crossover: uniform_crossover
- Crossover rate: 0.5
- Mutation rate: 0.8
- $\phi$ (for NS): 0.85
- Seed: 42
- Repetitions (solvers in evolution): 1

## Knapsack
* $DNS_f$, $DNS_p$ and $DNS_i$
* $NS_f$, $NS_p$ and $NS_i$:
    - Threshold archive and solution set: 3
* $NS_{nn}$
    - Threshold archive: 0.5
    - Threshold solution set: 0.5
* $NS_{pca}$:
    - Threshold archive: 3
    - Threshold solution set: 3

* MapElites with CVT archive:
    - Regions: 1000
    - Number of samples: 100_000
   
## Travelling Salesman Problem

- Dimension 50 
* $DNS_f$, $DNS_p$ and $DNS_i$

* $NS_f$ and $NS_i$:
    - Threshold archive and solution set: 3
* $NS_p$:
    - Threshold archive and solution set: 1e-7, 1e-10

* MapElites with CVT archive:
    - Regions: 1000
    - Number of samples: 100_000


## Bin Packing

- Dimension 120 with max capacity of 150

* $DNS_f$, $DNS_p$ and $DNS_i$

* $NS_f$, $NS_p$ and $NS_i$:
    - Threshold archive and solution set: 1e-7
* MapElites with CVT archive:
    - Regions: 1000
    - Number of samples: 100_000