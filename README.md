# Caffe

This revision of Caffe allows users to do the linear algebra with Eigen.
For all the details of Caffe like documentation, installation instructions, etc., please refer to the [original project site](http://caffe.berkeleyvision.org).

# Build with Eigen
```
$ git checkout eigen
$ cp Makefile.config.example Makefile.config
# Uncomment USE_EIGEN := 1 in Makefile.config
$ make all
```
Enabling `USE_EIGEN` will set `CPU_ONLY` to 1 and omit `BLAS` settings.
