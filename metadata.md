|                   Parameter                   |                 Value                |
|:---------------------------------------------:|:------------------------------------:|
|                Dimension ($N$)                |       50 (KP and TSP), 120 (BP)      |
|             Population Size ($M$)             |                  128                 |
| Number of neighbours ($k$) for $NS$ and $DNS$ |                  15                  |
|       Linear Weight coefficient ($\phi$)      |                 0.85                 |
|     Number of repetitions per solver ($R$)    |                   1                  |
|                  Generations                  |                 1000                 |
|                    Mutation                   |              Uniform One             |
|                   Crossover                   |                Uniform               |
|          Crossover and mutation rates         |               0.5, 0.8               |
|              Thresholds for $NS$              |                                      |
|               KP ($t_a$, $t_s$)               |           3 ($NS_{f,p,i}$)           |
|               TSP ($t_a$, $t_s$)              | 3 ($NS_{f,i}$), 1e-7, 1-e10 ($NS_p$) |
|               BP ($t_a$, $t_s$)               |                 1e-7                 |
|     Regions and number of samples for CVT     |           1,000 and 100,000          |