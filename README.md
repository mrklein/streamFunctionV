# streamFunctionV

Original OpenFOAM's streamFunction create result as a pointScalarField which
can't be post-processed with sample utility. This modification of the creates
additional resulting field streamFunctionV. It is volScalarField made by point
-> cell interpolation of the streamFunction pointScalarField.

## Installation

Create a clone of the repository (or download [tar-ball](https://bitbucket.org/mrklein/streamfunctionv/get/master.tar.gz)) and run wmake in the
folder with C file.
