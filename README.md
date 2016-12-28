# Vector Addition using CUDA
Developed a CUDA C prgram to perform vector addition on NVIDIA Jetson TX1 GPU embedded board.

In this program, GPU kernel code runs with 4 thread blocks each with 256 threads for performing addition on vector of length 1024.

With this code, 1024 threads will run parallely on GPU to perform the vector addition in comparison to a "for" loop that runs from 0 to 1023 sequentially in CPU to perform vector addition.


