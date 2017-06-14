This program was written as an introduction to parallel computing and uses CUDA to calculate the Fibonacci sequence on a GPU.
To compile:

nvcc fib_cuda.cu -o fib_cuda

To run:

./fib_cuda x

where x is the desired numbers of the sequnce you wish to calculate.


Note: this program uses unsigned long integers, which overflow after the 93rd number in the sequence.
