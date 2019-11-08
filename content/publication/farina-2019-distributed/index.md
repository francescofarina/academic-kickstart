+++
title = "A distributed asynchronous method of multipliers for constrained nonconvex optimization"
date = 2019-04-01
authors = ["Francesco Farina", "Andrea Garulli", "Antonio Giannitrapani", "Giuseppe Notarstefano"]
publication_types = ["2"]
abstract = "This paper presents a fully asynchronous and distributed approach for tackling optimization problems in which both the objective function and the constraints may be nonconvex. In the considered network setting each node is active upon triggering of a local timer and has access only to a portion of the objective function and to a subset of the constraints. In the proposed technique, based on the method of multipliers, each node performs, when it wakes up, either a descent step on a local augmented Lagrangian or an ascent step on the local multiplier vector. Nodes realize when to switch from the descent step to the ascent one through an asynchronous distributed logic-AND, which detects when all the nodes have reached a predefined tolerance in the minimization of the augmented Lagrangian. It is shown that the resulting distributed algorithm is equivalent to a block coordinate descent for the minimization of the global augmented Lagrangian. This allows one to extend the properties of the centralized method of multipliers to the considered distributed framework. Two application examples are presented to validate the proposed approach: a distributed source localization problem and the parameter estimation of a neural network."
featured = true
publication = "*Automatica*"
tags = ["journal"]
url_pdf = "http://www.sciencedirect.com/science/article/pii/S0005109819300469"
doi = "10.1016/j.automatica.2019.02.003"
+++

