# Lapack 3.4.2 shared libraries

The Lapack 3.4.2 source code, with the makefiles modified to allow shared library compilation and installation to a specific prefix, as per the instructions at http://theoryno3.blogspot.com/2010/12/compiling-lapack-as-shared-library-in.html.

This is used to create a manylinux1 Docker image based on CentOS 5.11, with a version of Lapack that includes the Lapacke C interface.
