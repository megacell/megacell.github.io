## Research projects

### Block simplex least squares: method comparison (2013-Current)

Details forthcoming.

### Bayesian inference for traffic assignment (2014-Current)

Details forthcoming.

### Cellpath: data fusion for static route flow estimation (2013-2015)

Cathy Wu, Jerome Thai, Steven Yadlowsky, Alexei Pozdnoukhov, Alexandre M. Bayen. _Cellpath: fusion of cellular and traffic sensor data for route flow estimation via convex optimization._ 21st International Symposium on Transportation and Traffic Theory, 2015.

*Abstract:*
A new convex optimization framework is developed for the route flow estimation problem from the fusion of vehicle count and cellular network data. The issue of highly underdetermined link flow based methods in transportation networks is investigated, then solved using the proposed concept of _cellpaths_ for cellular network data. With this data-driven approach, our proposed approach is versatile: it is compatible with other data sources, and it is model agnostic and thus compatible with user equilibrium, system-optimum, Stackelberg concepts, and other models. Using a dimensionality reduction scheme, we design a projected gradient algorithm suitable for the proposed route flow estimation problem. The algorithm solves a block isotonic regression problem in the projection step in linear time. The accuracy, computational efficiency, and versatility of the proposed approach are validated on the I-210 corridor near Los Angeles, where we achieve 90% route flow accuracy with 1033 traffic sensors and 1000 cellular towers covering a large network of highways and arterials with more than 20,000 links. In contrast to long-term land use planning applications, we demonstrate the first system to our knowledge that can produce route-level flow estimates suitable for short time horizon prediction and control applications in traffic management. Our system is open source and available for validation and extension.

The following are the repositories for the system and experiments:
* [Block simplex constrained least squares solver](https://github.com/megacell/block-simplex-least-squares)
* [Highway experiments](https://github.com/megacell/traffic-estimation-wardrop)
* [Full-scale experiment: data generation](https://github.com/ion599/phi)
* [Full-scale experiment: optimization and analysis](https://github.com/ion599/optimization) -- to be merged with other repositories
* [Full-scale experiment: cell placement and route similarity](https://github.com/megacell/synthetic-traffic/tree/master/networks)

Forthcoming are full instructions to reproduce our results.
