# Awesome-File-Compression-Archive-Management
# Awesome-File-Compression-Archive-Management

# Awesome-Machine-Learning-Compression-Pruning



Top Machine Learning Compression Pruning (Opensource) 🌟 Star if you like it! 🌟



A curated list of top machine learning model compression, structured/unstructured neural network pruning, low-bit quantization (FP8/INT4/2-bit/1-bit), knowledge distillation, and compiler optimization tools—featuring commercial SaaS/Hosted platforms alongside their open-source equivalents.



---



## Table of Contents



- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source Equivalents & Tools](#open-source-equivalents--tools)

  - [Neural Network Pruning, Sparsity & Compression Toolkits](#neural-network-pruning-sparsity--compression-toolkits)

  - [Low-Bit Quantization & Mixed-Precision Engines](#low-bit-quantization--mixed-precision-engines)

  - [Ultra-Low-Bit (1-Bit / Ternary / Extreme Compression) & Bonsai Models](#ultra-low-bit-1-bit--ternary--extreme-compression--bonsai-models)

  - [Hardware-Aware Model Compilers & Edge Optimization Suites](#hardware-aware-model-compilers--edge-optimization-suites)

  - [Knowledge Distillation & Compression-Aware Training Frameworks](#knowledge-distillation--compression-aware-training-frameworks)

- [Contributing](#contributing)



---



## SaaS/Hosted Platforms



Commercial, cloud-hosted model optimization suites, proprietary compression compilers, and managed hardware-aware quantization platforms.



* **[Neural Magic (Red Hat AI / nm-vllm Enterprise)](https://neuralmagic.com)** - Commercial sparsity-aware inference and model compression platform delivering GPU-class LLM performance on commodity CPUs and GPUs.

* **[OctoML / OctoAI (NVIDIA)](https://nvidia.com)** - Cloud-based machine learning optimization and deployment service built on Apache TVM for automated model tuning and quantization.

* **[Deci AI (NVIDIA AutoNAC)](https://nvidia.com)** - Commercial neural architecture search and model compression platform optimizing deep learning models for latency and edge hardware constraints.

* **[Pruna AI](https://pruna.ai)** - Commercial and enterprise AI optimization engine combining quantization, pruning, caching, and compilation into automated compression workflows.

* **[Qualcomm AI Hub & Qualcomm AI Engine Direct](https://qualcomm.com)** - Cloud-hosted device farm and proprietary SDK for quantizing, compiling, and profiling models on Snapdragon NPUs/DSPs.

* **[Intel OpenVINO Cloud / Tiber Developer Cloud](https://intel.com)** - Managed cloud environment for compressing, quantizing (NNCF), and benchmarking neural networks on Intel CPUs, GPUs, and NPUs.

* **[NVIDIA TensorRT & NIM Cloud](https://nvidia.com)** - Proprietary high-performance deep learning inference optimizer and managed cloud microservice suite with FP8/INT4/INT8 calibration.

* **[CentML (NVIDIA)](https://nvidia.com)** - Commercial ML compiler and model optimization platform reducing memory footprint and inference latency across cloud GPUs.

* **[Edge Impulse](https://edgeimpulse.com)** - Cloud-hosted TinyML and embedded AI platform providing EON Compiler quantization and pruning for microcontrollers.



---



## Open-Source Equivalents & Tools



Free and open-source software (FOSS) neural pruning libraries, GPTQ/AWQ/GGUF quantizers, 1-bit/ternary LLM frameworks, model compilers, and distillation toolkits.



### Neural Network Pruning, Sparsity & Compression Toolkits



* **[Torch-Pruning (DepGraph)](https://github.com)** - General-purpose open-source structural pruning library for PyTorch supporting LLMs, Vision Transformers, Diffusion models, and CNNs via Dependency Graphs.

* **[LLM-Pruner](https://github.com)** - Structural pruning framework for Large Language Models preserving multi-task generalization with minimal post-training recovery.

* **[SparseGPT & Wanda](https://github.com)** - Groundbreaking open-source one-shot pruning algorithms capable of inducing 50%+ sparsity in massive LLMs without retraining.

* **[LLM Compressor (vLLM / Neural Magic)](https://github.com)** - Unified open-source library for applying quantization (FP8, INT8, INT4) and 2:4 semi-structured sparsity to Hugging Face models for vLLM.

* **[NVIDIA Model Optimizer (TensorRT ModelOpt)](https://github.com)** - Open-source library of post-training and training-in-the-loop quantization, sparsity, and speculative decoding techniques.

* **[DeepSpeed Compression (Microsoft)](https://github.com)** - Modular open-source library unifying weight quantization, activation quantization, layer reduction, and knowledge distillation.

* **[NNI (Neural Network Intelligence - Microsoft)](https://github.com)** - Open-source AutoML toolkit featuring comprehensive model pruning algorithms (L1/L2, Taylor, Movement, Slim) and quantization-aware training.

* **[torchao (PyTorch Architecture Optimization)](https://github.com)** - Official PyTorch-native open-source library for sparsity, 2:4 pruning, and low-bit quantization integrated with `torch.compile`.



### Low-Bit Quantization & Mixed-Precision Engines



* **[AutoAWQ](https://github.com)** - Open-source Activation-Aware Weight Quantization (AWQ) toolkit compressing LLMs to 4-bit with 3x speedup and minimal perplexity loss.

* **[GPTQModel](https://github.com)** - Production-grade open-source post-training quantization library supporting GPTQ, Marlin, Triton, and QQQ kernels.

* **[bitsandbytes](https://github.com)** - Accessible open-source CUDA library enabling 8-bit (`LLM.int8()`) and 4-bit (`NF4` / `FP4` QLoRA) model compression in PyTorch.

* **[llama.cpp (GGUF Quantization)](https://github.com)** - Foundational open-source C/C++ inference engine supporting 1.5-bit to 8-bit K-quants and importance-matrix (`imatrix`) quantization.

* **[ExLlamaV2 (EXL2)](https://github.com)** - Open-source inference engine introducing variable-bitrate EXL2 quantization (2.5-bit to 8-bit) for optimal VRAM packing.

* **[HQQ (Half-Quadratic Quantization)](https://github.com)** - Fast, calibration-free open-source quantizer supporting 8-bit, 4-bit, 3-bit, 2-bit, and 1-bit weights.

* **[QuIP# & AQLM](https://github.com)** - State-of-the-art extreme compression open-source frameworks enabling accurate 2-bit LLM quantization via lattice and additive codebooks.



### Ultra-Low-Bit (1-Bit / Ternary / Extreme Compression) & Bonsai Models



* **[Bonsai-demo (PrismML-Eng)](https://github.com)** - Open-source demonstration and tooling for compact, ultra-compressed Bonsai language models engineered for high-efficiency inference.

* **[BitNet.cpp (Microsoft)](https://github.com)** - Official open-source inference framework for 1-bit and ternary (`BitNet b1.58`) LLMs delivering fast, lossless CPU execution with dramatic energy savings.

* **[OneBit / FBI-LLM](https://github.com)** - Open-source 1-bit parameter representation frameworks compressing LLM linear layers to binary sign matrices.

* **[Pruna (Open-Source Core)](https://github.com)** - Open-source Python optimization framework wrapping quantization, pruning, compilation, and caching algorithms into a unified `smash` API.



### Hardware-Aware Model Compilers & Edge Optimization Suites



* **[Apache TVM](https://github.com)** - Open-source end-to-end machine learning compiler stack optimizing and compressing models for CPUs, GPUs, and specialized accelerators.

* **[OpenVINO & NNCF (Intel)](https://github.com)** - Open-source Neural Network Compression Framework providing post-training quantization, QAT, and structured pruning for edge and server hardware.

* **[Arm NN & ExecuTorch (Meta)](https://github.com)** - Open-source edge AI runtimes supporting Arm KleidiAI, XNNPACK, and 4-bit/8-bit quantized execution on mobile CPUs and NPUs.

* **[ONNX Runtime & Olive (Microsoft)](https://github.com)** - Open-source hardware-aware model optimization tool automating quantization, graph fusion, and transformer compression for ONNX models.

* **[TensorRT-LLM (NVIDIA Open-Source Library)](https://github.com)** - Open-source C++/CUDA library supporting FP8, INT4-AWQ, W4A16, and SmoothQuant model compression.

* **[AI Model Efficiency Toolkit (AIMET - Qualcomm)](https://github.com)** - Open-source library developed by Qualcomm Innovation Center providing advanced quantization (AdaRound, CLE) and spatial SVD/channel pruning.



### Knowledge Distillation & Compression-Aware Training Frameworks



* **[DistilKit (Arcee AI)](https://github.com)** - Open-source toolkit for distilling large teacher LLMs into compact student models using logit-based and hidden-state distillation.

* **[Minitron (NVIDIA) / LLM-Shearing](https://github.com)** - Open-source structured pruning + continued pre-training recipes for shrinking frontier LLMs into smaller, dense architectures.

* **[MergeKit](https://github.com)** - Open-source toolkit for model merging, passthrough layer pruning, and parameter-space compression without GPU retraining.

* **[TextBrewer](https://github.com)** - Flexible open-source PyTorch knowledge distillation toolkit designed specifically for compressing NLP and Transformer models.



---



## Contributing



Contributions are welcome! Feel free to open a Pull Request to add more open-source neural pruning libraries, quantization engines, 1-bit LLM toolkits, or hardware model compilers.



1. Fork the repository.

2. Add your project under the appropriate category with a concise description.
