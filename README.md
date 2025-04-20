This repo provides nix.shell implementations for building and running opencl
applications.

Currently Implemented:
- AMD
- nvidia
- Intel

build with:
```
cmake .. -DOpenCL_LIBRARY=${OPENCL_LIBRARY} -DOpenCL_INCLUDE_DIR=${OPENCL_HEADERS}
```

NOTE: make sure that the opencl file is in the same folder as the executable
TODO: cmake move opencl file into binary folder
