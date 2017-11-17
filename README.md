# streamFunctionV

Original OpenFOAM(R)'s streamFunction create result as a pointScalarField which
can't be post-processed with sample utility. This modification creates
additional field streamFunctionV. It is volScalarField made by point -> cell
interpolation of the streamFunction pointScalarField.

## Installation

Create a clone of the repository (or download [tar-ball](https://github.com/mrklein/streamFunctionV/archive/master.tar.gz)) and run wmake in the
folder with C file.

## Disclaimer

This offering is not approved or endorsed by OpenCFD Limited, producer and
distributor of the OpenFOAM software via www.openfoam.com, and owner of the
OPENFOAM(R)  and OpenCFD(R)  trade marks.

## Acknowledgement

OPENFOAM(R)  is a registered trade mark of OpenCFD Limited, producer and
distributor of the OpenFOAM software via www.openfoam.com.
