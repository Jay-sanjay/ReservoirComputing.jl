# Training Algorithms

## Linear Models

```@docs
    StandardRidge
    LinearModel
```

## Gaussian Regression

Currently, v0.9 is unavailable.

## Support Vector Regression

Support Vector Regression is possible using a direct call to [LIBSVM](https://github.com/JuliaML/LIBSVM.jl) regression methods. Instead of a wrapper, please refer to the use of `LIBSVM.AbstractSVR` in the original library.
