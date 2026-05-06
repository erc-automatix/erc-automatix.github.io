---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

{% include base_path %}
{% include toc %}


## <i class="fa-brands fa-github"></i> [jaxmat](https://bleyerj.github.io/comet-fenicsx/)



<div class="image-text-container">
    <div class="text-column">
{{ "

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17611833.svg)](https://doi.org/10.5281/zenodo.17611833)

🚀 `jaxmat` is an open-source Python library for implementing material constitutive models in JAX."  | markdownify }}
    </div>
    <div class="image-column">
    <img src="https://erc-automatix.github.io/jaxmat/_images/jax_framework.png" alt="Image Description" class="centered-image" width=400>
    </div>
</div>

`jaxmat` accelerates the development of new material models by combining concise syntax, reusable building blocks, and automatic differentiation, eliminating the need to manually derive consistent tangent operators. It also provides a natural foundation for data-driven constitutive modeling.

- Bridges the gap between classical constitutive modelling and modern ML frameworks
- Automatic differentiation replaces hand-derived jacobians and tangent operators
- `jax.jit` and `jax.vmap` give GPU-accelerated, vectorised evaluation across thousands of material points with a single line of code
- Modular design: swap yield surfaces, hardening laws, or flow rules independently, or replace any component with a neural network
- Every parameter is differentiable, making material identification and inverse problems natural to formulate


## <i class="fa-brands fa-github"></i> [dolfinx_materials](https://github.com/bleyerj/dolfinx_materials)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13882184.svg)](https://doi.org/10.5281/zenodo.13882184)


`dolfinx_materials` is a Python add-on package to the `dolfinx` interface to the [FEniCSx project](https://fenicsproject.org/).
It enables the user to define **complex material constitutive behaviours** which are not expressible using classical [UFL](https://fenics.readthedocs.io/projects/ufl/en/latest/) operators.
