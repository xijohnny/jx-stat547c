# November 20

Quick skim of Wang and Blei, get big ideas down. All proofs are in the appendix and are highly techincal/long...

# November 22

Bayesian asympotics is the asymptotic study of prior and posterior distributions, under frequentist reasoning (i.e., the true parameter
is a constant, or point mass). This begins with the weak consistency of Doob, which is related to Martingale convergence. Doob's 
consistency says roughly that if the model is identifiable, unless the parameter only belongs to sets of probability measure 0 under the prior. In other words,
for any prior \mu, the posterior is consistent for a true parameter $\theta$, $\mu$- almost surely. These are exceptionally weak conditions in the context of
the result, but the result itself is in turn also relatively weak. Indeed, one can imagine many priors that may not be supported at the true value,
particularly as the dimension grows. It is particularly troublesome in the non-parametric setting, where even well-designed priors may violate the assumptions above.

The classical Bernstein von-Mises theorem provides a stronger perspective, and is often cited as an early justification for Bayesian inference. Under much
stronger conditions, it can be shown that the posterior converges to a normal distribution centered at the true parameter in total variation (which implies
convergence in distribution, but not necessarily the other modes). The assumptions are not quite straight forward - they will be studied in great detail later on. 

# December 6th

Finishing up reading material for the intro section: Van der Vaart's asymptotic statistics and some of Scherevish. Get started on the details of Wang and Blei.

# December 7th

Finish reading Wang and Blei, including skimming the appendix. Don't think I will include any of the main proofs - they are far too long. 
