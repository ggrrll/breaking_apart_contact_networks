### Code and data for the paper:

https://www.biorxiv.org/content/10.1101/2020.03.01.971630v1.abstract

### Repository structure

- the [measles\_data\_analysis](measles_data_analysis.ipynb) notebook contains the code for the data processing and visualization of the WHO measles data
- the [segregation_and_epidemics_sim](segregation_and_epidemics_sim.ipynb) notebook contains the code for the stochastic simulations of networks models and data analysis
- [datasets](./datasets) folder contains the datasets on measles to reproduce fig 1 of paper 
- [network_fig](./network_fig) folder contains the subplots for the figure showing an example network (fig 2 of paper)
- [sim_plots](./sim_plots) folder contains all main (sub)plots, related to the simulations and analysis of results
 
 
You can find here below a cartoon representing the **segregation algorithm**:

Given that 'social-status' variables *s*, *s1*, *s2* and *snew*, *node_1* decides that s/he is too 'far' from her/his neighbour *node_2* ![](https://latex.codecogs.com/gif.latex?\(|s_1&space;-&space;s_2&space;|&space;>&space;\tau\)) . S/he willing to rewire his edge, and picks at random *node_new*, which is now 'close enough' ![](https://latex.codecogs.com/gif.latex?\(|s_1&space;-&space;s_{new}&space;|&space;<&space;\tau\)), so s/he willing to stay.



![](pict_segre_algo.png) 


### Please cite as:


*Lazzari, Gianrocco, and Marcel Salathe. 
"Breaking Apart Contact Networks with Vaccination." 
BioRxiv (2020).*
 
 or
 
```
 @article{lazzari2020breaking,
  title={Breaking Apart Contact Networks with Vaccination},
  author={Lazzari, Gianrocco and Salathe, Marcel},
  journal={BioRxiv},
  year={2020},
  publisher={Cold Spring Harbor Laboratory}
}
```
