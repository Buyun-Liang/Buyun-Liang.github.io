---
permalink: /software/
title: "Software"
excerpt: 
author_profile: true
# redirect_from: 
#   - /about/
#   - /about.html
---

# PyGRANSO

![Example screenshot](./PyGRANSO_logo.png)

PyGRANSO: a Python numerical package using GRadient-based Algorithm for Non-Smooth Optimization.

Toward a user-friendly and scalable numerical package for nonsmooth, nonconvex, constrained optimization

Please check https://sun-umn.github.io/PyGRANSO-Documentation for detailed instructions (introduction, installation, settings, examples...).

## Brief Introduction

Optimization for nonconvex, nonsmooth, and constrained problems is an essential part of machine learning and deep learning, which is hard to reliably solve without optimization expertise, and also outpace what existing convex optimization software packages can handle. GRANSO is the first numerical optimization package that can handle these problems but exist some limitations such as lack of auto-differentiation and GPU acceleration that preclude the potential broad deployment by general users.

PyGRANSO is python numerical package revamped and translated from the original GRANSO package. In order to lower the barriers to general users and solve modern machine/deep learning problem, we introduced several main features including auto-differentiation, GPU acceleration, tensor input, scalable QP solver and improved core algorithms. PyGRANSO is available at the GitHub repository https://github.com/sun-umn/PyGRANSO under the MIT license, along with a documentation website https://sun-umn.github.io/PyGRANSO-Documentation. 