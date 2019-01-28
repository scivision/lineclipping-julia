[![Build Status](https://travis-ci.com/scivision/lineclipping-julia.svg?branch=master)](https://travis-ci.com/scivision/lineclipping-julia)

# Line clipping in Julia

`lineClipping.jl` Cohen-Sutherland line clipping algorithm for Julia.
Input scalars, output intersection length, or `nothing` if no intersection.


```julia
cohensutherland(xmin, ymax, xmax, ymin, x1, y1, x2, y2)
```

### Python / Fortran

For Python or Fortran line clipping, see https://github.com/scivision/lineclipping-python-fortran
