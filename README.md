# Parallel_stencil

N 100000
R 3
BLOCK_SIZE 1024

execute time singlethread stencil

![singlethread stencil](/singlethread.jpg)

execute time multithread stencil

![singlethread stencil](/multithread.jpg)

execute time miltithread stencil with per-block shared memory

![singlethread stencil](/multithread_perblock.jpg)
