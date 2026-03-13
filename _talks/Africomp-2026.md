---
title: "`jaxmat`: Automated and Differentiable Constitutive Modeling in JAX"
collection: talks
type: "Talk"
venue: "Africomp - 7th African Conference on Computational Mechanics"
date: 2026-02-25
location: "Cape Town, South Africa"
authors: "**J. Bleyer**, Paul Bouteiller, Jack S. Hale, Andrey Latyshev, Corrado Maurini"
excerpt: ""
---
We present `jaxmat`, an open-source library for automated and differentiable constitutive modeling of materials, built entirely within the JAX ecosystem. The goal of `jaxmat` is to bridge the gap between traditional computational mechanics and modern machine learning frameworks, enabling researchers and engineers to define, calibrate, and accelerate material models with greater flexibility and efficiency.
At its core, `jaxmat` provides a modular and extensible framework for implementing constitutive behavior ranging from classical phenomenological models to fully data-driven formulations. Unlike conventional libraries based on pre-coded material laws, `jaxmat` emphasizes composability: users can construct complex constitutive responses by combining elementary, well-defined building blocks such as elastic potentials, yield functions, hardening rules, or viscous flow laws. Each component can be readily replaced or extended—by analytical expressions or neural network surrogates—without modifying the surrounding structure. This design naturally supports the development of hybrid physics–ML models.
Beyond flexibility, `jaxmat` achieves high computational efficiency through just-in-time compilation and automatic vectorization, enabling parallel evaluation of large ensembles of material points on modern hardware. Demonstrative applications highlight the use of `jaxmat` for parameter identification, uncertainty quantification, and physics-informed neural constitutive models, showcasing its versatility across data-driven and physics-based workflows.
Overall, `jaxmat` establishes a unified framework for automated, modular, and differentiable constitutive modeling, supporting both classical and machine learning–enhanced approaches. The library is open-source and designed to interoperate with existing finite element and scientific computing software, offering a practical and extensible tool for researchers in computational mechanics, materials science, and scientific machine learning.
