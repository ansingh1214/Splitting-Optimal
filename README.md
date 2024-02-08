Repository for the work **Splitting probabilities are optimal controllers of rare events** in which we showcase the generative utility of the splitting probability. 

Specifically, we derive an effective Doob force for the generalized bridge problem in which the system starting in a metastable state $A$ is conditioned to transfer to the product state $B$ within some finite time $t_f$. The derived force takes the form:
$$\lambda^*(\mathbf{r},t) = \frac{2k_{\mathrm{B}} T \nabla_{\mathbf{r}} q_B^{ss}(\mathbf{r})}{ q_B^{ss}(\mathbf{r}) + p_B(e^{\mu_2(t_f-t)} -1)}$$
where $q_B^{ss}$ is the splitting probability, $\mu_2 = k_{AB} + k_{BA}$ is the second eigenvalue of the Fokker-Planck generator related to the reactive states for bistable systems, $p_B$ is the probability of the product state.

The force can be used to obtain a reactive ensemble with a probability close to unity, and the ensemble shows the exact statistics as that of the original reactive trajectory ensemble. This is shown in the animation of the transient probability density $\rho$ and cumulative density $\Phi$ for a system in a 1D double well for times $t\in[0,t_f]$:

![viz1](https://github.com/ansingh1214/Splitting-Optimal/blob/main/jupyter_data/1D_DW_rho.gif)

## ##

Generality of the result is showcased in an interacting model system of 2D DNA-labelled colloids in which the committor is obtained from training an NN ansatz using the variational form of the Backward Kolmogorov equation. An animation of the driven reactive trajectory along with the forces is shown below, illustrating how the gradients of the committor encode forces that capture the natural fluctuations of the system during a reaction:
![viz1](https://github.com/ansingh1214/Splitting-Optimal/blob/main/jupyter_data/1.gif)

## ##
