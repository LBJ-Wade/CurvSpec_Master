# CurvSpec
Routines to compute power spectra of curved-sky (Healpix) maps based on the MASTER algorithm.

It makes use of the SLATEC routine rc3jj.f to compute the 3j-Wigner symbols, so you need to compile with f2py -c mll.f90 rc3jj.f -m mll and then import the master module.

