# Hi, I'm Yaomeng Li

**AI Applications · Numerical Algorithms · Scientific Computing**

I hold a **PhD in Geotechnical Engineering from Shandong University**. My work connects AI application development, numerical methods, and high-performance scientific computing.

I build practical AI applications and performance-oriented numerical software with Python, C++, and MATLAB, combining model deployment, parallel computing, and reproducible validation.

## What I work on

- **AI applications:** local speech recognition and text-to-speech, cloud-based LLM translation, desktop and web integration
- **Algorithm engineering:** numerical kernels, reference implementations, accuracy and performance comparisons
- **High-performance computing:** OpenMP, MPI, Intel MKL, large multidimensional data, and build tooling
- **AI for Science:** scientific modeling, parameter optimization, PDE solvers, and computational validation

## Featured projects

| Project | My work and engineering focus | Stack |
| --- | --- | --- |
| [AI Voice Translator](https://github.com/liyaomeng202114981-ops/ai-voice-translator) | Application development integrating local ASR/TTS with cloud-based LLM translation; CPU int8 / CUDA float16 ASR configuration, Electron service management, startup diagnostics, and meeting-record export | Python, JavaScript, React, Electron, faster-whisper, DeepSeek, Piper |
| [Peridigm for Windows](https://github.com/liyaomeng202114981-ops/peridigm-windows) | Windows/MSVC port and engineering integration of upstream Peridigm; Microsoft MPI compatibility, dependency/build tooling, portable terminal, validation scripts, and ParaView export | C++, MSVC, CMake, Microsoft MPI, Trilinos, ParaView |
| [3D Viscoelastic Overthrust Solver](https://github.com/liyaomeng202114981-ops/viscoelastic-3d-overthrust-cpp) | Three-dimensional viscoelastic wave simulation with B-spline spatial derivatives, OpenMP domain-block parallelism, and large-model input handling | C++20, OpenMP, Intel MKL, Armadillo, HDF5 |
| [B-Spline Viscoelastic Wave Simulation](https://github.com/liyaomeng202114981-ops/viscoelastic-wave-simulation-matlab) | B-spline numerical solver, Fourier pseudospectral reference implementation, controlled comparisons, and regression tests | MATLAB, numerical methods, benchmarking |

### Validation and contribution evidence

- **AI Voice Translator:** 21,000 extended text test cases across 210 language directions. This is test-set coverage, not a claim that all translations or end-to-end speech tests passed. ASR/TTS run locally; general translation uses a cloud API. See the [validation scope](https://github.com/liyaomeng202114981-ops/ai-voice-translator/blob/main/docs/TESTING.md) and [publication checks](https://github.com/liyaomeng202114981-ops/ai-voice-translator/blob/main/docs/CHECKS-20260906.md).
- **Peridigm for Windows:** the historical Windows CPU/MPI build passed 222/222 CTest entries. My contribution is the Windows port and surrounding engineering tools; the upstream solver and third-party components retain their original attribution. See [my contribution map](https://github.com/liyaomeng202114981-ops/peridigm-windows/blob/main/windows/docs/WINDOWS-WORK.md) and [dated validation records](https://github.com/liyaomeng202114981-ops/peridigm-windows/blob/main/windows/docs/VALIDATION-RECORD.md).
- **Numerical simulation projects:** repository examples and paper benchmarks can use different grids and configurations. Performance claims should be read with their corresponding experiment settings and reference baselines.

## Engineering strengths

- Translating research problems into mathematical models, working code, and testable experiments
- Building reference implementations and comparing numerical accuracy, runtime, and memory use
- Working with multidimensional data, memory-intensive workloads, and parallel computation
- Developing build scripts, regression checks, technical documentation, and deployment diagnostics
- Connecting scientific-computing experience with practical AI application development

## Technologies

**Languages:** Python, C++, MATLAB, JavaScript  
**AI and data:** PyTorch, NumPy, SciPy, OpenCV, Optuna, faster-whisper  
**Systems and HPC:** OpenMP, MPI, Intel MKL, Armadillo, HDF5, CPU/CUDA model deployment  
**Engineering:** Git, CMake, Linux, Windows, Node.js, React, Electron

## Current direction

I am expanding my work in model deployment, inference benchmarking, PyTorch profiling, and AI-assisted development. My current CUDA experience is in model-inference deployment; my published parallel numerical software uses OpenMP and MPI.

Open to opportunities in **AI application engineering, AI-assisted software development, AI for Science, scientific software, and numerical algorithm engineering**.
