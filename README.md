# fmsdual

This is a library for computing derivatives of functions to machine precision.

If _J_ is a square matrix with _J<sub>i,i+1</sub>_ = 1 and zero elsewhere we have _J<sup>n</sup><sub>i,i+n</sub>_ = 1 and zero elsewhere.
If _f_ is sufficiently smooth we have 

>  _f(x + J)_ = &Sigma;<sub>_n_ &ge; 0</sub> _f_<sup>(_n_)</sup>(_x_) _J<sup>n</sup>_/_n_!

Where _f_<sup>(_n_)</sup>(_x_) is the _n_-th derivative of _f_ at _x_ and we write _x_ for _xI_ where _I_ is the identity matrix.
