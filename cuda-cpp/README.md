# CUDA C/C++ — NVIDIA DLI

Course: *Getting Started with Accelerated Computing in CUDA C/C++*.

My course files and study notes from NVIDIA DLI in 2024.
I received a certificate of competency on 10 September 2024.

[Certificate][certificate] · [All NVIDIA DLI courses](../README.md)

## Session 1: CUDA fundamentals

- Kernel launches and thread indices.
- Grid-stride loops and memory allocation.
- Error checks and numerical exercises.

Examples include vector addition and matrix multiplication.
The session also includes a heat conduction exercise.

[Session 1 files](Session%201/)

## Session 2: GPU memory

- Device properties and launch configuration.
- Unified Memory and page faults.
- Memory prefetch and SAXPY exercises.

[Session 2 files](Session%202/)

## Session 3: Streams and profiling

- Concurrent CUDA streams.
- Explicit device memory allocation.
- Overlap between data transfers and kernel execution.

The saved notebook uses Nsight Systems to compare execution profiles.
The final exercise covers an N-body simulator.

[Session 3 files](Session%203/) · [Profiling notebook][profiling]

## Recorded assessment result

The saved course output reports a pass for both N-body test cases.
These times come from the NVIDIA course environment.

| Bodies | Recorded runtime | Course limit |
| --- | --- | --- |
| 4,096 | 0.1220 s | 0.9 s |
| 65,536 | 0.2129 s | 1.3 s |

Both cases passed the correctness checks.
See the assessment output in the [profiling notebook][profiling].

## Use the files

The notebook commands use `nvcc` and `nsys` in the course environment.
Some paths refer to that original environment.
The N-body source expects `files.h` and `timer.h`.
Their contents are saved as `files.txt` and `timer.txt` in its folder.

## Credits and licence

NVIDIA provided the course exercises and instructional material.
This folder contains the saved exercises and my study notes.
It retains the original repository's [MIT licence](LICENSE).

[certificate]: ../certificates/accelerated-computing-cuda-cpp.pdf
[profiling]: Streaming%20and%20Visual%20Profiling.ipynb