# BcdiCore.jl Documentation

## About

Bragg Coherent Diffraction Imaging (BCDI) Core implements some of the core functionality used for future projects BcdiAtomic.jl (an atomic scale BCDI solver), BcdiMeso.jl (a mesoscale BCDI Solver), BcdiMulti.jl (a multiscale BCDI solver), and BcdiTrad.jl (a BCDI solver using projection algorithms). BcdiCore.jl implements the loss functions and derivatives of loss functions used in these packages.

While this package is marked as BCDI specific, the methods are more general and can be used in many phase retrieval problems. In the future, this package may be incorporated into a more general phase retrieval core package.

Currently, this entire package must be run with access to GPUs. This may change in the future (especially if Issues requesting it are opened), but for our research group, using GPUs is a necessity.

## Installation

Currently, BcdiCore.jl is not registered in the Julia general registry. BcdiCore.jl can be installed by running in the REPL package manager (```]```):

```add git@github.com:byu-cig/BcdiCore.jl.git```

