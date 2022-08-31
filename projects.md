+++
title = "Projects"
rss = "My personal projects"
image = "/assets/icon.png"
+++

# Projects

Here you can find my projects developed for the different M.Sc. courses and also for my personal experience during my spare time.

## Quadratic Disjoint Simplices

Source: [Github](https://github.com/matteodefra/Quadratic_disjoint_simplices)

![Quadratic](/assets/project_pics/quadratic.png)

Computational Mathematics and Optimization course. I first developed a theoretical analysis of the ADAGRAD algorithm with its convergence properties, then based on these I implemented a solver from scratch to find the minimum of a quadratic objective function subject to disjoint simplices constraint.

The picture above show exactly a simple 3D illustration of what we mean: a paraboloid function "cut" by different hyperplanes, depending on the variables involved in the simplex.

---

## Parallel Boruvka

Source: [GitHub](https://github.com/matteodefra/Parallel_Boruvka)

![Boruvka](/assets/project_pics/boruvka.png)

Parallel and Distributed System course. A parallel implementation of the ”Boruvka algorithm”, for finding the Minimum Spanning Tree of a given graph. I studied topics from the original paper, and I exploited also an ad hoc data structure to deal with this kind of problem, known as ”Disjoint Sets”. I exploited the C++ language and its basic functionalities

---

## ISPR assignments

Source: [GitHub](https://github.com/matteodefra/ISPR_assignments)

![ISPR](/assets/project_pics/ispr.png)

Assignments for the course "Intelligent Systems for Pattern Recognition". The picture resumes the 4 different topics treated in the assignments:
- Analysis of a time series, study of stationarity/nonstationarity and fitting of an ARMA model;
- Implementation of a Bayesian Network from scratch with relative Conditional Probability Tables and implementation of ancestral sampling over it;
- Implementation of a shallow and deep autoencoder with layerwise pretraining and optional finetuning. On the trained autoencoder, latent space interpolation and gradient ascent manifold assumption were tested;
- Review of the paper "Trust Region Policy Optimization" in the context of Reinforcement Learning, prepared a small presentation to capture the key aspects of it.
Everything was implemented in Python language through the use of notebooks

---

## GoEmotions

Source: [GitHub](https://github.com/matteodefra/GoEmotions)

![BERT](/assets/project_pics/bert.jpeg)

Exploited different BERT based models for a sentiment analysis task over the GoEmotions dataset.

---

## CSRAE

Source: [GitHub](https://github.com/matteodefra/csrae)

![CSRAE](/assets/project_pics/csrae.png)

Implementation of a Cauchy-Schwarz Regularized Autoencoder. Following the paper from [arxiv](https://arxiv.org/pdf/2101.02149.pdf), I implemented a variational autoencoder based on the Cauchy-Schwarz divergence, exploiting the PyTorch library. The more versatility of the divergence allows for the use of more complex priors like a gaussian mixture models against the normal gaussian used.

---

## SmartPark

Source: [Github](https://github.com/matteodefra/SmartPark)

![Smartpark](/assets/project_pics/smartpark.png)

I developed an intelligent Smart park for bycicles using the different IoT protocol stack. The aim was to synchronize locks intelligently through the use of sensors located above the parking spots. The sensors were programmed using the C language, exploiting the connection at the IPv6 layer, having two different purpose: locking and logging. The server was implemented in Python, receiving data from the CoAP sensors (locking) and MQTT sensors (logging).

---

### Stay tuned for incoming projects!