# Topological Approach to Clustering

In this repository I would like to show a beginner-friendly overview concern a branch of the topological data analysis. I have focused on introducing a concept called *persistent homology* and its applications in the clustering task.

The area of mathematics called algebraic topology, is basically studying topological objects using algebraic tools. A simplicial complex, one of the most basic structure in algebraic topology, can be simply connected with a cloud of points or even with a whole dataset. Tools based on the homological algebra, due to the *ripser* library, can be also simply connected with the way to measure connectedness of such dataset, or in other words, it might be used to decide if some points are close to each other or not. Homology theory, equipped with the time parameter, become quite nice instrument, that can be handled by any data scientist, once the clustering task is concerned.  

In this article, I have skipped mathematical details, proofs and so on, as my goal was building an intuition, how tools known from the algebraic topology can be used in the data science world (in this case, for the clustering challenge). Precisely, I have presented constructions for the below topics:

- simplexes and simplicial complexes
- 0-connectedness
- 1-connectedness and loops in topological sense
- 0-persistent homology, as the measure of being connected in 0-dimensional sense
- 1-persistent homology

Used libraries: ripser, persim, sklearn, matplotlib, numpy and random.


Below there are some screens with persistent homology diagrams:


![Img](https://github.com/Yelon-ml/Topological_Approach_to_Clustering/blob/master/screens/s1.PNG)

![Img](https://github.com/Yelon-ml/Topological_Approach_to_Clustering/blob/master/screens/s3.PNG)

![Img](https://github.com/Yelon-ml/Topological_Approach_to_Clustering/blob/master/screens/s2.PNG)

![Img](https://github.com/Yelon-ml/Topological_Approach_to_Clustering/blob/master/screens/s4.PNG)
