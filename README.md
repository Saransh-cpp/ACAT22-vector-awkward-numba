# Compiling Awkward Lorentz Vectors with Numba

[![Talk](https://img.shields.io/badge/ACAT22-poster-blue?logo=github&logoColor=white&color=blue)](https://indi.to/zTs5b)

Due to the massive nature of HEP data, performance has always been a factor in its analysis and processing.
Languages like C++ would be fast enough but are often challenging to grasp for beginners, and can be difficult
to iterate quickly in an interactive environment . On the other hand, the ease of writing code and extensive
library ecosystem make Python an enticing choice for data analysis. Increasing interoperability between
Python and C++, as well as the introduction of libraries such as Numba, had been accelerating Python’s
traction in the HEP community.

Vector is a Python library for 2D, 3D, and Lorentz vectors, especially arrays of vectors, designed to solve
common physics problems in a NumPy-like way. Vector currently supports pure Python Object, NumPy,
Awkward, and Numba-based (Numba-Object, Numba-Awkward) backends.

We are introducing the library, with a focus on the Numba-based Awkward Lorentz vectors to perform operations
on HEP data without compromising on the speed and the ease of writing code. Awkward is one of the
core libraries of the Scikit-HEP ecosystem that allows data analysis with jagged arrays. Numba, on the other
hand, allows Python codebases to harness the power of Just-In-Time compilation, enabling the Python code
to be compiled before executing.

The library seamlessly integrates with the existing Scikit-HEP libraries, especially with Awkward. Our talk
will start with an introduction to this library, with the main agenda of compiling Awkward Lorentz vectors
with Numba. Furthermore, Vector is still under active development and preparing for a 1.0 release; hence, we
will also take in user feedback while discussing the overall development roadmap.

## References

All the links are available here - https://iris-hep.org/projects/vector.html

## Significance

The Vector library is relatively new and has not been independently presented at any HEP-focused conference.
Additionally, its interoperability with the Scikit-HEP ecosystem makes it a crucial part of most HEP analyses.
Furthermore, the seamless Numba and Awkward support allows it to integrate with any existing HEP pipeline,
making the pipeline faster, simpler, and more effective.

## Stuck somewhere? Reach out!

- If something is not working the way it should, or if you want to request a new feature, create a [new issue](https://github.com/scikit-hep/vector/issues) on GitHub.
- To discuss something related to vector, use the [discussions](https://github.com/scikit-hep/vector/discussions/) tab on GitHub or vector’s gitter ([Scikit-HEP/vector](https://gitter.im/Scikit-HEP/vector)) chat room.
- Have a look at vector's [changelog](https://vector.readthedocs.io/en/latest/#changes-in-vector-s-api) to stay up-to-date!

## Cite vector

If you use `vector` in your work, please cite it using the following metadata -

```bib
@software{Schreiner_vector,
author = {Schreiner, Henry and Pivarski, Jim and Chopra, Saransh},
doi = {10.5281/zenodo.5942082},
license = {BSD-3-Clause},
title = {{vector}},
url = {https://github.com/scikit-hep/vector}
}
```
