
*Under development* - supposed to be `rksvd`, R package for sparse coding via k-SVD
======

Installation
------------

### Dependencies

* RcppEigen
* gcc >= 4.6 (C++)

-----

A highly optimized, parallel implementation of the Batch-OMP version of the KSVD learning algorithm. It implements the algorithm in the paper. The computation is done in highly optimized C++ code with OpenMP implementations for multicore archetectures.

["Efficient Implementation of the K-SVD Algorithm and the Batch-OMP Method"](http://www.cs.technion.ac.il/users/wwwb/cgi-bin/tr-get.cgi/2008/CS/CS-2008-08.pdf), by Ron Rubinstein, Michael Zibulevsky and Michael Elad, 2009.
