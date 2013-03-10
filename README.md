Docs for parallel repos:

[Intergrid](http://denis-bz.github.com/docs/intergrid.html):
interpolate in an N-d box grid, uniform or non-uniform.
This is just a wrapper for scipy.ndimage.map_coordinates and numpy.interp.
It's fast: ~ 1M interpolations / sec in 4d.

[Barypol](http://denis-bz.github.com/docs/barypol.html):
interpolate in an N-d box grid, using d + 1 corners of a simplex
(triangle, tetrahedron ...) around each query point.  
From Munos and Moore,
"Variable Resolution Discretization in Optimal Control",
1999, 24p; see the pictures and example on pp. 4-5.

[Nelder-Mead](http://denis-bz.github.com/docs/Nelder-Mead-py.html):
function minimization in Python NumPy, with restarts, verbose,
correct convergence test.

Comments are welcome, testcases most welcome.

