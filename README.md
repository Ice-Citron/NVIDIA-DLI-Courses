# NVIDIA DLI Courses

This repository contains the certificates from the NVIDIA Deep Learning Institute
(DLI) courses that I've completed in 2024, as well as the respective notes that
I've taken whilst doing these courses.

## Certificates

- [Transformer NLP certificate][nlp-cert] — 20 March 2024.
- [CUDA C/C++ certificate][cuda-cert] — 10 September 2024.

## Transformer NLP

Course: *Building Transformer-Based Natural Language Processing
Applications*.

I completed this course and received a certificate of competency.

The lab material covers:

- Transformer architecture and BERT tokenizers.
- BERT pre-training with NVIDIA NeMo.
- Text classification and named entity recognition.

The final assessment uses the Federalist Papers for authorship
attribution. The saved notebooks contain model configuration and
outputs from model training and inference.

[Lab notebooks](transformer-nlp/labs/) ·
[Assessment notebooks](transformer-nlp/assessment/) ·
[Course slides](transformer-nlp/slides/)

## Model parallelism

Course: *Model Parallelism: Building and Deploying Large Neural Networks*.

I attended this course but did not complete the assessment in time.

The saved lab notebooks cover hardware checks and SLURM job submission.
The slides explain methods for distributed model training.

[Lab notebooks](model-parallelism/Lab%201/) ·
[Course slides](model-parallelism/pptx_Resource_Slides/)

## CUDA C/C++

Course: *Getting Started with Accelerated Computing in CUDA C/C++*.

I received a certificate of competency on 10 September 2024.
The saved work covers CUDA kernels and GPU memory management.
It also includes concurrent streams and Nsight Systems profiles.
The N-body assessment output records a pass for both test sizes.

[CUDA exercises and notes](cuda-cpp/) ·
[Certificate][cuda-cert]

## Repository structure

```text
certificates/      Completion certificates for NLP and CUDA C/C++.
transformer-nlp/    NLP labs, assessment notebooks, and slides.
model-parallelism/  Environment lab notebooks and course slides.
cuda-cpp/          CUDA exercises, study notes, and saved outputs.
```

## Credits and licence

NVIDIA provided the course notebooks and lecture slides.
This repository contains my saved course work and assessment attempts.

The root contains an [Apache 2.0 licence](LICENSE).
The CUDA folder retains its [MIT licence](cuda-cpp/LICENSE).

[nlp-cert]: certificates/transformer-nlp.pdf
[cuda-cert]: certificates/accelerated-computing-cuda-cpp.pdf
