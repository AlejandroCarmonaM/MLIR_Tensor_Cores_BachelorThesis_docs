# MLIR_Tensor_Cores_BachelorThesis_docs

My Bachelor's Thesis focused on utilizing Tensor Cores in NVIDIA GPUs within a device-agnostic
framework. Tensor Cores may achieve speed-ups in between 5x and 10x over the regular performance of the GPU. However, programs
must be written accordingly to exploit their potential. To do so, I had to develop an understanding of both CUDA and its vendor
libraries CuBLAS and CuDNN and the ways in which they used Tensor Cores. In order to achieve device-agnostic programming, I
dabbled into LLVM and MLIR to write agnostic operations that may be transformed into GPU-specific ones. These operations would
then make use of CuBLAS and CuDNN with different datatypes. Finally, I built equivalent PyTorch scripts to compare the framework’s
performance to the state of the art, with favourable results. It was graded with honors with a 10,0.
