# Optimization_Analyzer
## What is the motivation behind this project?

This project is created for the purposes of my engineering thesis.
It's both the integral part of said thesis as well as a tool used in order to conduct experiments relevant to the thesis.

## What is this exactly?

It's a simple tool that's meant to show and analyze low-level code produced by compilers of different programing languages.
It can be used to directly compare not only the resulting code, but also statistics like execution time, memory usage etc.
Programs in the same language can be compared this way for two versions of a compiler as long as the path to them is provided.
Two programs in different languages can also be compared.

## Current state of the project

This is to serve as general tracking of progress.
Features/tasks listed here can change and break into sub-tasks later on.
Project scope can also change.

- [x] Git setup and initial project structure(can be changed later)
- [] Simple algorithm implenentation in all supported languages(exact algorithm - TBD)
    - [] C++
    - [] Java
    - [] Python
- [] Compilation module
- [] Runtime statistics collecting
- [] Runtime statistics reporting(with custom formating?)
- [] Saving/loading statistics for comparisons
- [] Comparing two programs based on statistics
- [] Low-level code extraction
    - [] C++
    - [] Java
    - [] Python
- [] UI
    - [] Dual text editor view
    - [] Program | Low-level view
    - [] Runtime performance view (?)
