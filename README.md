# Quality Diversity Methods for Instance Generation

$NS_{NN}$: Novelty Search with neural-network reduction proposed in GECCO '24. Traditional NS using a NN to search in an encoded 2D space (from 8D feature vectors)

$NS_{f,i,p}$: Traditional Novelty Search Algorithm with two archives using features, instance or performance based descriptors to compute the novelty score ($s$).

$DNS_{f,i,p}$: Archiveless NS with based on dominance using features, instance or performance based descriptors to compute the novelty score ($s$).
>Bahlous-Boldi, R., Faldor, M., Grillotti, L., Janmohamed, H., Coiffard, L., Spector, L., & Cully, A. (2025). Dominated Novelty Search: Rethinking Local Competition in Quality-Diversity. arXiv preprint arXiv:2502.00593.

$ME_{CVT}$: MapElites algorithm using the Centroidal Voronoi Tessellations. For this method, we only considered the *instance-based* descriptor.
>Vassiliades, V., Chatzilygeroudis, K., & Mouret, J. B. (2017). Using centroidal voronoi tessellations to scale up the multidimensional archive of phenotypic elites algorithm. IEEE Transactions on Evolutionary Computation, 22(4), 623-630.

All the experiments were run using [DIGNEApy](https://github.com/DIGNEA/DIGNEApy.git). Check [Metadata](./metadata.md) for the parameter setting of each method.

## Data Available at Mendeley Data 

Remember to cite the dataset if you use them.

- [Knapsack Instances](https://data.mendeley.com/preview/g3h2xcv8mf?a=91336b53-ee87-46a2-b654-4e68522ce3d9)
    > Marrero, Alejandro; Segredo, Eduardo; Leon, Coromoto; Hart, Emma (2025), “50-dimensional KP Instances from QD methods”, Mendeley Data, V2, doi: 10.17632/g3h2xcv8mf.2
- [Bin Packing Instances](https://data.mendeley.com/preview/znkgvnfddr?a=7f096813-dcb8-4e34-90a2-cc75763bc310)
  > Marrero, Alejandro; Segredo, Eduardo; Leon, Coromoto; Hart, Emma (2025), “BP Instances from QD methods”, Mendeley Data, V2, doi: 10.17632/znkgvnfddr.2

- [Travelling Salesman Problem Instances](https://data.mendeley.com/preview/czf5ttmjpg?a=07f1b786-aa62-4d03-905f-df0c8e00f6fe) 
    > Marrero, Alejandro; Segredo, Eduardo; Leon, Coromoto; Hart, Emma (2025), “TSP Instances from QD methods”, Mendeley Data, V2, doi: 10.17632/czf5ttmjpg.2

