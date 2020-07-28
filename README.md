# tensorflow-cpu-prebuild
Tensorflow Prebuilds with CPU Optimizations for Linux


Version        | Python | CPU Flags                                             | Comment                   | Link
-------------- | ------ | ----------------------------------------------------- | ------------------------- | ----------------------
Tensorflow 2.2 | 3.8    | fma, avx, avx2, avx512f, avx512pf, avx512cd, avx512er | build with MKL Support    | [Download](https://www.dropbox.com/s/04fiee43ng0xwdc/tensorflow-2.2.0-cp38-cp38-linux_x86_64.whl?dl=1)
Tensorflow 2.2 | 3.8    | fma, avx, avx2, ssse3, cx16, sse4.1, sse4.2, popcnt   | Works on AMD Epyc 7702P, (build with MKL Support) | [Download](https://www.dropbox.com/s/qgpzh9wg7yck3sz/tensorflow-2.2.0-cp38-cp38-linux_x86_64.whl?dl=1)
Tensorflow 2.3 | 3.8    | fma, avx, avx2, ssse3, cx16, sse4.1, sse4.2, popcnt   | Works on AMD Epyc 7702P, (build with MKL Support) | [Download](https://www.dropbox.com/s/2tulz0bxbn4emcn/tensorflow-2.3.0-cp38-cp38-linux_x86_64.whl?dl=1)
