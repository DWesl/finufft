.. _ackn:

Acknowledgments
===============

FINUFFT was initiated by Jeremy Magland and Alex Barnett at the
Center for Computational Mathematics, Flatiron Institute.
The main developer and maintainer is:

* Alex Barnett

Major code contributions by:

* Jeremy Magland - multithreaded spreader, benchmark vs other codes
* Ludvig af Klinteberg - SIMD vectorization/acceleration of spreader, julia wrapper
* Yu-Hsuan ("Melody") Shih - 2d1many, 2d2many vectorized interface, GPU version
* Andrea Malleo - guru interface prototype and tests
* Libin Lu - guru Fortran, python, MATLAB/octave, julia interfaces
  
Other significant code contributions by:

* Joakim Andén - catching bugs, Matlab/FFTW issues, performance tests, python
* Leslie Greengard and June-Yub Lee - CMCL Fortran test drivers
* Dan Foreman-Mackey - early python wrappers
* David Stein - python wrappers
* Vineet Bansal - pypy packaging
  
Testing, bug reports, helpful discussions:

* Hannah Lawrence - user testing and finding bugs
* Marina Spivak - Fortran testing
* Hugo Strand - python bugs
* Amit Moscovich - Mac OSX build
* Dylan Simon - sphinx help
* Zydrunas Gimbutas - explanation that NFFT uses Kaiser-Bessel backwards
* Charlie Epstein - help with analysis of kernel Fourier transform sums
* Christian Muller - optimization (CMA-ES) for early kernel design
* Andras Pataki - complex number speed in C++
* Timo Heister - pass/fail numdiff testing ideas
* Vladimir Rokhlin - piecewise polynomial approximation on complex boxes

We are also indebted to the authors of other NUFFT codes
such as NFFT3, CMCL NUFFT, MIRT, BART, etc, upon whose interfaces, code,
and algorithms we have built.
