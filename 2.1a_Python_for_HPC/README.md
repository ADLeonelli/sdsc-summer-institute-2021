## 2.1a. Python for HPC
Andrea Zonca, Senior Computational Scientist, SDSC

In this session we will introduce four key technologies in the Python ecosystem that provide significant benefits for scientific applications run in supercomputing environments. Previous Python experience is recommended but not required.

1.  First we will learn how to speed up Python code compiling it on-the-fly with numba 
2.  Then we will introduce the threads, processes and the Global Interpreter lock and we will leverage first numba then dask to use all available cores on a machine
3.  Finally we will distribute computations across multiple nodes launching dask workers on a separate Expanse job.