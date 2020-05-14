---
layout: template
title: capopt
---

# capopt: Capping Methods for the Automatic Configuration of Optimization Algorithms

Welcome to the capopt project website!<br>
[people](#people)|
[download](#download)|
[tutorial](#tutorial)|
[examples](#examples)|
[license](#license)|
[support](#support)


***

The main objective of *capopt* is to speed up the automatic configuration of optimization algorithms. It implements several capping mechanisms for optimization scenarios. These methods use the performance of previously seen executions to determine a performance envelope, which is used to evaluate how good a new configuration is during its execution. If a poorly performing configuration is identified, *capopt* stops the execution and returns a penalized result value.

The following paper describes *capopt* in detail and present an extensive experimental evaluation. You can also check its [supplementary page](suppcor) for further experimental details.

> **Capping Strategies for the Automatic Configuration of Optimization Algorithms**<br>
> Marcelo de Souza, Marcus Ritt, and Manuel López-Ibáñez<br>
> Submitted to Computers & Operations Research, 2020.<br>
> [preprint will be available soon | [supplementary page](suppcor)]

#### Bibtex
```
@article{DeSouzaEtAl2020,
   title   = {Capping Strategies for the Automatic Configuration of Optimization Algorithms},
   author  = {de Souza, Marcelo and Ritt, Marcus and L{\'o}pez-Ib{\'a}{\~n}ez, Manuel},
   journal = {Submitted to Computers \& Operations Research},
   year    = {2020}
}
```

Please, make sure to reference us if you use *capopt* in your research.

***

## People

**Maintainer:** [Marcelo de Souza][marcelo]{:target="_blank"}

**Collaborators:** [Marcus Ritt][marcus]{:target="_blank"} and [Manuel López-Ibáñez][manuel]{:target="_blank"}

**Contact:** marcelo.desouza [at] udesc.br

***

## Download

### Dependencies

***

## Tutorial

***

## Examples

***

## License

This software is Copyright (C) 2020 Marcelo de Souza.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program (see https://github.com/capopt/capopt). If not, see https://www.gnu.org/licenses.

IMPORTANT NOTE: Please be aware that the fact that this program is released as Free Software does not excuse you from scientific propriety, which obligates you to give appropriate credit! If you write a scientific paper describing research that made substantive use of this program, it is your obligation as a scientist to (a) mention the fashion in which this software was used in the Methods section; (b) mention the algorithm in the References section. The appropriate citation is:

+ Marcelo de Souza, Marcus Ritt, and Manuel López-Ibáñez. Capping Strategies for the Automatic Configuration of Optimization Algorithms. Submitted to Computers & Operations Research, 2020.

***

## Support

For any question or suggestion please contact [Marcelo de Souza][marcelo]{:target="_blank"} (marcelo.desouza [at] udesc.br).

***



[marcelo]: https://souzamarcelo.github.io
[marcus]: https://www.inf.ufrgs.br/~mrpritt
[manuel]: http://lopez-ibanez.eu
