# pikaia
Modern Fortran Edition of the Pikaia Genetic Algorithm 

Overview
------

This is an refactoring of the PIKAIA unconstrained optimization code from the [High Altitude Observatory](http://www.hao.ucar.edu/modeling/pikaia/pikaia.php).  The original code is public domain and was written by Paul Charbonneau & Barry Knapp.  The new code differs from the old code in the following respects:
 * The original fixed-form source (FORTRAN 77) was converted to free-form source.
 * The code is now object-oriented Fortran 2003/2008.  All user interaction is now through the ```pikaia_class```.
 * All real variables are now double precision.
 * The random number generator was replaced with calls to the intrinsic Fortran ```random_number``` function.
 * There are various new options (e.g., a convergence window with a tolerance can be specified as a stopping condition, and the user can specify a subroutine for reporting iterations).
 * Mapping the variables to be between 0 and 1 now occurs internally, rather than requiring the user to do it.

Examples
------

Coming soon...

See also
------
 * PIKAIA description page: http://www.hao.ucar.edu/modeling/pikaia/pikaia.php
 * Original source code: http://download.hao.ucar.edu/archive/pikaia/

