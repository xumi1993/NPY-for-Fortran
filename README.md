# NPY for Fortran
This Fortran module allwos to save numerical Fortran arrays in Numpy's *.npy format. Currently supported are:
```fortran
1. integer(1), integer(2), integer(4), integer(8)
2. real(4), real(8)
3. complex(4), complex(8)
```
Saving an array is simply done by calling:
```fortran
call save_npy("filename.npy", array)
```

Reading *.npy files isn't currently supported.