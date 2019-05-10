# MATLAB Mex wrapper for PESQ (Perceptual Evaluation of Speech Quality)

I modified some lines of code to solve linker errors when using MEX compiler.

It maybe useful if you encountered similar errors.

## Usage

1. using MATLAB run `compile_test.m` if you want to compile the source code.
    
2. after compiling, adding './bin' into MATLAB path.

```matlab
addpath('./bin/');
```

3. using `pesq_mex.m` function to compute PESQ. (there are examples in `compile_test.m` file.)

## About Python Wrapper for PESQ score
if you like using python to compute PESQ score, you may interested in this implementation: 

https://github.com/ludlows/python-pesq
