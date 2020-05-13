---
layout: template
title: Supplementary page [capopt]
plugins:
  - jekyll-target-blank
---

Supplementary page to the paper:

# Capping Methods for the Automatic Configuration of Optimization Algorithms

[Marcelo de Souza][marcelo]{:target="_blank"}, [Marcus Ritt][marcus]{:target="_blank"} and [Manuel López-Ibáñez][manuel]{:target="_blank"}<br>
Computers & Operations Research, 2020

***

## Abstract

Automatic configuration techniques are widely and successfully used to find good parameter settings for parameterized algorithms. Configuration is costly, because it is necessary to evaluate many configurations on different instances. For decision problems, when the objective is to minimize the running time of the algorithm, many configurators implement capping methods to discard poor configurations early. Such methods are not directly applicable to optimization problems, when the objective is to optimize the cost of the best solution found, given a predefined running time limit. We propose new capping methods for the automatic configuration of optimization algorithms. They use the previous executions to determine a performance envelope, which is used to evaluate new executions and cap those that do not satisfy the envelope conditions. We integrate the capping methods into the irace configurator and evaluate them on different optimization scenarios. Our results show that the proposed methods can save from about 5% to 80% of the configuration effort, while finding configurations of the same quality. Based on the computational analysis, we identify two conservative methods, that save an average of about 20% of the configuration effort and never found significantly worse configurations than those obtained without capping on all tested problems. We also provide evidence that capping can help to better use the available budget in scenarios with a configuration time limit.

**Keywords:** automatic algorithm configuration; capping methods; optimization algorithms; parameter tuning

***

## Configuration Scenarios

TBD.


[marcelo]: https://souzamarcelo.github.io
[marcus]: https://www.inf.ufrgs.br/~mrpritt
[manuel]: http://lopez-ibanez.eu