# StorageSystemsSimulations.jl

```@meta
CurrentModule = StorageSystemsSimulations
```

## Overview

`StorageSystemsSimulations.jl` is a
[`PowerSimulations.jl`](https://sienna-platform.github.io/PowerSimulations.jl/stable/)
extension to support formulations and models related to energy storage.

Operational Storage Models can have multiple combinations of different restrictions.
To manage these variations, `StorageSystemsSimulations.jl` relies on the
[`PowerSimulations.DeviceModel`](@extref) attributes feature. Formulations can have varying
implementations for different attributes defined in [`PowerSimulations.DeviceModel`](@extref).

## About Sienna

`StorageSystemsSimulations.jl` is part of the National Laboratory of the Rockies (formerly known as NREL)'s
[Sienna ecosystem](https://sienna-platform.github.io/Sienna/), an open source framework for
power system modeling, simulation, and optimization. The Sienna ecosystem can be
[found on GitHub](https://github.com/Sienna-Platform/Sienna). It contains three applications:

  - [Sienna\Data](https://sienna-platform.github.io/Sienna/pages/applications/sienna_data.html) enables
    efficient data input, analysis, and transformation
  - [Sienna\Ops](https://sienna-platform.github.io/Sienna/pages/applications/sienna_ops.html) enables
    system scheduling simulations by formulating and solving optimization problems
  - [Sienna\Dyn](https://sienna-platform.github.io/Sienna/pages/applications/sienna_dyn.html) enables
    system transient analysis including small signal stability and full system dynamic
    simulations

Each application uses multiple packages in the [`Julia`](http://www.julialang.org)
programming language. `StorageSystemsSimulations.jl` is part of Sienna\Ops.

## How to use this documentation

  - **Tutorials** — walk-throughs to help you *learn* storage modeling workflows
  - **How to...** — task guides for configuring storage device models
  - **Explanation** — background on storage formulations and attributes
  - **Reference** — API and formulation details for quick look-up

`StorageSystemsSimulations.jl` follows the [Diátaxis](https://diataxis.fr/) documentation framework.

## Installation and Quick Links

  - [Sienna installation page](https://sienna-platform.github.io/Sienna/SiennaDocs/docs/build/how-to/install/):
    Instructions to install `StorageSystemsSimulations.jl` and other Sienna\Ops packages
  - [Central Sienna documentation](https://sienna-platform.github.io/Sienna/SiennaDocs/docs/build/index.html):
    Cross-linked documentation website for the core user-facing Sienna packages
