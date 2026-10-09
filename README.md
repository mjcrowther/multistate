# multistate

> **`multistate` is no longer developed.** Its successor is [`pendragon`](https://reddooranalytics.se/software/pendragon/), from Red Door Analytics, for multi-state and competing-risks models in R and Stata. `pendragon` is a complete rewrite with a new syntax, not a new version of `multistate`. This repository is an archive: version 4.5.2 is the final version, and can still be installed as described below.

`multistate` provides a general framework for flexible parametric modelling of arbitrary multi-state survival models.


## Installation

The latest stable version of `multistate` can be installed with:

```{stata}
ssc install multistate
```

To install directly from this GitHub repository, use:

```{stata}
net install multistate, from("https://raw.githubusercontent.com/mjcrowther/multistate/main/")
```


Below are publications which have contributed to the development of the `multistate` package.

> Weibull CE, Lambert PC, Eloranta S, Andersson TML, Dickman PW, Crowther MJ. A multi-state model incorporating estimation of excess hazards and multiple time scales. *Statistics in Medicine* 2021;40(9)2139-2154.

> Hill M, Lambert PC, Crowther MJ. Relaxing the assumption of constant transition rates in a multi-state model in hospital epidemiology. *BMC Medical Research Methodology* 2021;21:16.

> Crowther MJ. merlin - a unified framework for data analysis and methods development in Stata. *Stata Journal* 2020;20(4):763-784. (Pre-print: https://arxiv.org/abs/1806.01615).

> Crowther MJ, Lambert PC. Parametric multi-state survival models: flexible modelling allowing transition-specific distributions with application to estimating clinically useful measures of effect differences. *Statistics in Medicine* 2017;36(29):4719-4742.

> Crowther MJ, Lambert PC. Simulating biologically plausible complex survival data. *Statistics in Medicine* 2013;32(23):4118-4134.
