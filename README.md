# 基础库



https://github.com/pytorch/pytorch

87k

Tensors and Dynamic neural networks in Python with strong GPU acceleration



https://github.com/run-llama/llama\_index

39.1k

LlamaIndex is the leading framework for building LLM-powered agents over your data.

0. **LLM数据增强框架，轻松集成私有数据**
   LlamaIndex 是一个数据框架，提供300+集成工具，支持API、PDF、SQL等数据源接入，并通过索引和图结构优化数据，使LLMs更高效地查询和推理私有数据。

* **灵活可扩展，适用于不同开发者需求**
  提供简洁的高层API，5行代码即可实现数据检索，同时支持深度定制（数据连接器、索引、检索器等），并可无缝集成LangChain、Flask、Docker等应用框架。



https://github.com/langchain-ai/langchain

101k

🦜🔗 Build context-aware reasoning applications

0. **LangChain：构建智能推理应用的LLM开发框架**
   LangChain 提供开源库和第三方集成，支持模型交互（langchain-core）、检索增强生成（RAG）、智能代理（Agents）等核心组件，简化 LLM 应用开发。

* **LangGraph & LangSmith：从开发到生产的完整生态**
  LangGraph 让开发者构建多智能体应用，并支持可视化流程控制；LangSmith 提供应用监测和优化工具，确保 LLM 应用高效部署和持续改进。



https://github.com/ray-project/ray

Ray is an AI compute engine. Ray consists of a core distributed runtime and a set of AI Libraries for accelerating ML workloads.

* **统一的分布式计算引擎**
  Ray 是一个适用于 AI 和 Python 应用的统一框架，提供核心分布式运行时和一套加速 ML 工作负载的 AI 库，支持从单机开发环境扩展到集群，简化了 ML 计算的规模化操作。

* **轻松扩展，支持各种工作负载**
  Ray 可以无缝地将代码从本地计算机扩展到集群，并且具备通用性，能够高效处理各种类型的工作负载，适合需要大规模计算的 ML 应用。





https://github.com/fastapi/fastapi

81.1k



https://github.com/HKUDS/LightRAG

12k

"LightRAG: Simple and Fast Retrieval-Augmented Generation"

The structure of this code is based on [nano-graphrag](https://github.com/gusye1234/nano-graphrag).



https://github.com/neuml/txtai

10.4k

💡 All-in-one open-source embeddings database for semantic search, LLM orchestration and language model workflows

0. **txtai：开源嵌入式数据库，赋能语义搜索与LLM工作流**
   txtai 结合向量索引、图数据库和关系数据库，支持跨文本、图像、音频和视频的嵌入式搜索，广泛应用于 RAG、自动化代理和多模态工作流。

* **智能管道与自主代理，简化 LLM 编排**
  提供强大的 LLM 驱动管道，支持问答、摘要、翻译、标注等任务，并通过 Python、YAML 或 API 轻松构建端到端的 AI 解决方案，可本地运行或容器化扩展。



# 大模型

## 推理开发框架

https://github.com/huggingface/transformers

140k

🤗 Transformers: State-of-the-art Machine Learning for Pytorch, TensorFlow, and JAX.

0. **多模态预训练模型与简易集成**
   🤗 Transformers 提供数千个预训练模型，支持文本、图像和音频等多种任务，包括文本分类、信息提取、图像分类、物体检测和语音识别等。用户可以轻松下载并使用这些模型，进行微调并在模型中心分享，同时支持 PyTorch、TensorFlow 和 JAX 的无缝集成，提供统一的API接口。

* **高性能与低成本优势**
  Transformers 提供高效的自然语言理解与生成、计算机视觉和音频处理能力，具有低门槛，适合教育工作者和从业人员使用。它减少了计算成本和碳排放，支持不同框架之间的转换，并允许用户根据需求定制模型，快速进行实验。



https://github.com/vllm-project/vllm

38.5k

50. **高吞吐量与高效内存管理**：

    * vLLM通过高效的注意力键值内存管理（PagedAttention）、连续批处理、快速模型执行（CUDA/HIP图）和多种量化技术（如GPTQ、AWQ、INT4等）提升推理性能。

    * 支持CUDA优化内核和先进的推理技术（如FlashAttention、FlashInfer、推测解码）。

51. **灵活易用与广泛支持**：

    * 无缝集成Hugging Face模型，支持分布式推理（张量并行和管道并行）、流输出，并兼容OpenAI API。

    * 支持NVIDIA、AMD、Intel、TPU等多种硬件平台，且支持多种流行的开源模型，如Transformer LLMs、Mixture-of-Expert LLMs和多模态LLMs。



https://github.com/ggml-org/llama.cpp

74.8k

LLM inference in C/C++

0. **高性能LLM推理与硬件优化**
   llama.cpp 提供无依赖的 C/C++ 实现，支持 Apple Silicon（通过 ARM NEON、Accelerate 和 Metal 框架优化），并在 x86 架构上支持 AVX、AVX2、AVX512 和 AMX。同时，支持 1.5-bit 到 8-bit 的整数量化，提升推理速度并减少内存使用。

* **GPU加速与多平台支持**
  通过自定义 CUDA 内核支持 NVIDIA GPU，并通过 HIP 和 MUSA 支持 AMD 和 Moore Threads MTT GPU。提供 Vulkan 和 SYCL 后端支持，实现 CPU+GPU 混合推理，加速超出 VRAM 容量的模型。



https://github.com/microsoft/onnxruntime

15.7k

ONNX Runtime: cross-platform, high performance ML inferencing and training accelerator

0. **跨平台推理加速**
   ONNX Runtime 提供跨平台的机器学习推理加速，支持来自深度学习框架（如 PyTorch、TensorFlow/Keras）以及经典机器学习库（如 scikit-learn、LightGBM、XGBoost）的模型。通过利用硬件加速器和图优化，提供最佳性能，帮助提升客户体验并降低成本。

* **训练加速与多节点支持**
  ONNX Runtime 还支持加速模型训练，特别是对使用 PyTorch 的变压器模型，通过简单的代码修改，能在多节点 NVIDIA GPU 上显著缩短训练时间。



https://github.com/microsoft/onnxruntime-genai

0.62k

Generative AI extensions for onnxruntime







## 训练&调优



https://github.com/deepspeedai/DeepSpeed

36.8k

•核心优势：一个开源的框架，帮助快速训练和部署LLM模型，优化大规模语言模型的开发流程。

应用场景：适用于大规模语言模型的快速开发与迭代，尤其是需要高效计算资源的企业环境。

60. **深度学习训练与推理优化**：

    * DeepSpeed通过创新的并行技术（如ZeRO、3D-Parallelism、DeepSpeed-MoE等）优化了大规模深度学习训练，并且通过高效的推理内核、通信优化和异构内存技术，大幅提升了推理性能，实现了更低延迟、更高吞吐量和成本减少。

61. **压缩与科学创新**：

    * 提供易用的模型压缩技术，如ZeroQuant和XTC，帮助压缩模型，提升推理速度和减少模型体积。

    * DeepSpeed4Science计划旨在利用AI技术解决科学领域中的重大挑战，推动科研领域的创新。



https://github.com/hiyouga/LLaMA-Factory

41.1k

0. **一站式高效LLM/VLM微调，支持100+模型**
   提供零代码CLI和Web UI，轻松微调100+大模型（如LLaMA、Mistral、Gemma、ChatGLM等），支持多模态训练、奖励建模、强化学习等多种微调方法，满足多场景需求。

* **强大优化工具与高效推理**
  集成LoRA、QLoRA等高效调优方案，并支持FlashAttention-2、RoPE scaling等前沿优化技术，同时兼容LlamaBoard、Wandb等实验监控工具，提供OpenAI风格API与Gradio UI，确保高效部署与推理。



https://github.com/unslothai/unsloth

30.7k

Finetune Llama 3.3, DeepSeek-R1 & Reasoning LLMs 2x faster with 70% less memory! 🦥

* **高效的模型微调与低内存占用**：

  * 使用OpenAI的Triton语言编写内核，无近似方法，确保训练准确度不丢失。

  * 支持4bit和16bit的QLoRA/LoRA微调，通过bitsandbytes实现大幅度减少内存占用，同时提高训练速度。

* **广泛硬件支持与快速训练**：

  * 支持NVIDIA GPU（从CUDA 7.0起）以及Linux和Windows（通过WSL）系统。

  * 不需硬件更换，训练速度比传统方法提高5倍，使用Unsloth Pro则可提升至30倍。

该项目是用于微调和优化大型语言模型（LLM）的 Python 工具库。它通过动态量化和显存优化技术，提高了模型微调速度，同时将显存占用降低 70%-80%，并支持多种硬件配置、LLM、超长上下文任务等功能。除此之外，还提供了可直接在线体验的 Jupyter Notebook 示例，降低了大模型微调的门槛。





https://github.com/Kiln-AI/Kiln

2.7k

The easiest tool for fine-tuning LLM models, synthetic data generation, and collaborating on datasets.

* **零代码微调与自动部署**：支持Llama、GPT4o和Mixtral等模型的零代码微调，并提供自动化的无服务器部署，极大简化了模型优化和上线的流程。

* **团队协作与数据管理**：基于Git的版本控制系统和直观的UI设计，便于团队协作，支持QA、PM和领域专家在结构化数据（如示例、提示、评分、反馈等）上的高效合作。



## LLM平台

https://github.com/ollama/ollama

128k

Get up and running with Llama 3.3, DeepSeek-R1, Phi-4, Gemma 2, and other large language models.



Ollama 是一个轻量级、可扩展的框架，旨在帮助用户在本地机器上构建和运行大型语言模型（LLM）。它提供了一个简单的 API，用于创建、运行和管理模型，并附带了一个预构建模型库，方便在各种应用中使用。

**简化的模型管理：** Ollama 提供了直观的命令行工具，用户可以轻松地创建、启动、停止和管理模型。例如，使用 `ollama show llama3.2` 查看模型信息，使用 `ollama list` 列出计算机上的模型，使用 `ollama ps` 查看当前正在运行的模型，使用 `ollama stop llama3.2` 停止指定的模型。&#x20;

**多平台支持：** Ollama 支持多种硬件架构，包括 Apple Silicon（通过 ARM NEON、Accelerate 和 Metal 框架优化）、x86 架构（支持 AVX、AVX2、AVX512 和 AMX）以及 NVIDIA GPU（通过自定义 CUDA 内核）。此外，还支持 Vulkan 和 SYCL 后端，以及 CPU+GPU 混合推理，以部分加速超出 VRAM 容量的模型。&#x20;



https://github.com/janhq/jan

27.6k

Jan is an open source alternative to ChatGPT that runs 100% offline on your computer

* Jan 是一个开源的 ChatGPT 替代品，完全离线运行在您的设备上。其目标是让普通用户轻松下载并运行大型语言模型（LLM），以实现对 AI 的完全控制和隐私保护。

* Jan 由 Cortex 提供支持，Cortex 是一个可嵌入的本地 AI 引擎，能够在任何硬件上运行。从个人电脑到多 GPU 集群，Jan 和 Cortex 支持多种架构，包括 NVIDIA GPU、Apple M 系列、Apple Intel、Linux Debian 和 Windows x64 等。



https://github.com/mudler/LocalAI

30.5k

🤖 The free, Open Source alternative to OpenAI, Claude and others. Self-hosted and local-first. Drop-in replacement for OpenAI, running on consumer-grade hardware. No GPU required. Runs gguf, transformers, diffusers and many more models architectures. Features: Generate Text, Audio, Video, Images, Voice Cloning, Distributed, P2P inference

1. **LocalAI** 是一个免费的开源替代方案，旨在提供与 OpenAI 兼容的本地 AI 推理，支持文本、音频、视频、图像、语音克隆等生成。它无需 GPU，支持在消费者级硬件上运行多种模型架构（如 llama.cpp、transformers、vllm 等），并可以作为 OpenAI 的替代品进行部署。

2. 主要功能包括文本生成、音频转文本、文本转音频、图像生成、嵌入生成、P2P 推理、语音活动检测、以及集成 WebUI，且能够直接从 Huggingface 下载模型，提供 OpenAI 相似的工具 API。



https://github.com/InternLM/lmdeploy

5.6k

LMDeploy is a toolkit for compressing, deploying, and serving LLMs.



https://github.com/xorbitsai/inference

6.4k

Replace OpenAI GPT with another LLM in your app by changing a single line of code. Xinference gives you the freedom to use any LLM you need. With Xinference, you're empowered to run inference with any open-source language models, speech recognition models, and multimodal models, whether in the cloud, on-premises, or even on your laptop.



https://github.com/songquanpeng/one-api

22.6k

LLM API management & key redistribution system, unifying multiple providers under a single API.&#x20;



https://github.com/lmstudio-ai

Discover, download, and run local LLMs



## 模型量化



https://github.com/microsoft/onnxruntime-genai/

Generative AI extensions for onnxruntime

* **高效执行生成式AI模型**
  该API为ONNX模型提供生成式AI循环，包括预处理、推理、logits处理、搜索和采样、KV缓存管理等功能，使用户可以在设备上高效运行LLM。支持一键调用`generate()`方法或逐步生成每个token，并可以在循环中动态调整生成参数。

* **支持多种生成策略和自定义评分**
  该库支持贪婪搜索、束搜索（Beam Search）以及TopP和TopK采样，帮助生成token序列，并内置处理逻辑，如重复惩罚。同时，用户可以轻松添加自定义评分，进一步优化生成效果。



https://github.com/microsoft/Olive

Olive: Simplify ML Model Finetuning, Conversion, Quantization, and Optimization for CPUs, GPUs and NPUs.

* **简化AI模型优化与转换**
  Olive是一款AI模型优化工具包，旨在简化针对不同硬件（如CPU、GPU、NPU）进行的模型微调、转换、量化和优化过程。通过自动选择最适合的优化技术，Olive可以输出高效的ONNX模型，确保在云端或边缘设备上进行推理时优化准确性和延迟。

* **易于使用且支持多种优化技术**
  Olive提供超过40种内置的优化组件，涵盖了模型压缩、优化、微调和编译等领先技术。通过简便的CLI和优化工作流，用户可以轻松执行常见的模型优化任务，支持与Hugging Face和Azure AI的无缝集成，内置缓存机制提高生产效率。



## 强化学习





## LLM





## VLM(多模态)

* CLIP

* DALL·E

* **多模态学习**：研究如何处理和融合来自不同模态（如文本、图像、语音等）的数据，以提升模型的表现。



## 周边

### 评估

https://github.com/THUDM/AgentBench

2.4k

A Comprehensive Benchmark to Evaluate LLMs as Agents (ICLR'24)

* **首个多环境LLM智能体评估基准**：AgentBench是首个针对LLM作为智能体在多环境下的综合评估基准，涵盖8种不同环境，全面测试LLM在多样化场景中的自主操作能力。

* **新增五大测试领域**：包括操作系统（OS）、数据库（DB）、知识图谱（KG）、数字卡牌游戏（DCG）和横向思维谜题（LTP），扩展了LLM在复杂任务中的表现评估范围。



https://github.com/CLUEbenchmark/SuperCLUE

3.1k

SuperCLUE: 中文通用大模型综合性基准 | A Benchmark for Foundation Models in Chinese



### 监控

https://github.com/helicone/helicone

3.2k

https://www.helicone.ai/

🧊 Open source LLM observability platform. One line of code to monitor, evaluate, and experiment. YC W23 🍓

**目标**：专注于LLM（大语言模型）应用的**监控、评估和实验**，是一个开源的**LLM观察性平台**。

主要用于**LLM应用的性能优化和监控**，帮助开发者快速发现问题并优化提示词、请求处理和模型响应质量。适合于**实验与生产中的实时监控**，并帮助开发者快速迭代和评估模型的效果。

* **一站式LLM开发与监控平台**：Helicone提供开源的一体化LLM开发平台，仅需一行代码即可集成OpenAI、Anthropic、LangChain等主流工具，支持请求日志记录、性能监控（如成本、延迟、质量）以及调试功能，帮助开发者快速优化LLM应用。

* **高效实验与评估能力**：内置Playground和Prompt管理功能，支持快速测试、迭代和版本控制提示词，同时提供自动化评估工具（如LastMile、Ragas）和微调合作伙伴（如OpenPipe、Autonomi），助力开发者提升模型表现并满足企业级安全合规需求（如SOC 2、GDPR）。



https://github.com/wandb/wandb

9.5k

The AI developer platform. Use Weights & Biases to train and fine-tune models, and manage models from experimentation to production.

**目标**：全面支持**机器学习和深度学习模型的训练、微调、监控和管理**。它提供了一个从实验到生产的**全流程管理工具**，尤其适用于训练和微调LLM模型。

* 适用于**整个机器学习生命周期**的管理，包括从模型训练、微调、实验跟踪、到部署和监控等全过程。

* 重点在于**训练与实验管理**，并且支持多种**模型调优和优化**的流程。它还适用于大规模的机器学习模型管理和团队协作。



* **全流程机器学习与LLM应用管理**：Weights & Biases（W\&B）提供从模型训练、微调到生产部署的全流程管理工具，支持跟踪、可视化和调试机器学习管道及LLM应用，帮助开发者更快构建和优化模型。

* **灵活部署选项**：W\&B支持多种部署方式，包括在私有云上通过Terraform脚本快速部署、在W\&B的单租户基础设施上托管（Dedicated Cloud），以及本地或裸金属服务器上的自托管（On-Prem/Bare Metal），满足不同环境下的生产需求。

### 云原生

https://github.com/kubeflow/kubeflow

14.7k

Machine Learning Toolkit for Kubernetes





# Agent



https://github.com/geekan/MetaGPT

46.6k

* **MetaGPT多代理框架与自动化软件公司功能**
  MetaGPT是一个多代理框架，通过将不同角色分配给GPT模型，形成一个协作性的软件公司。它可以根据一个简单的输入生成用户故事、需求分析、API、文档等，涵盖整个软件开发过程，并结合精心设计的标准操作程序（SOP）。MetaGPT的目标是自我进化，实现自我训练、微调、优化及自动更新。

* **开发路线图与功能实现**
  MetaGPT的短期目标是支持中型项目的完全自动化实现（约2000行代码），并完成多个功能的版本更新。它支持多种策略（如ReAct、CoT、Reflection等）和不同角色的工作，如数据分析师、机构研究员等，并且提供知识搜索、数据EDA、文档管理等功能。MetaGPT还支持多语言、多编程语言，并与不同的API（如SERPER、Selenium、Playwright）兼容。

- **多代理框架与软件公司内部协作**
  MetaGPT采用多代理框架，将产品经理、架构师、项目经理和工程师等角色转化为AI代理，模拟软件公司内部的协作流程。用户只需提供一行需求，MetaGPT即可自动生成用户故事、竞争分析、需求、数据结构、API等内容。

- **核心理念与标准化流程**
  MetaGPT的核心理念是“代码 = SOP(团队)”，即通过标准化操作流程（SOP）来指导和优化AI代理团队的工作。该框架将SOP的精细化管理应用于AI团队，帮助实现自动化的软件开发过程。



https://github.com/OpenBMB/IoA

0.66k

An open-source framework for collaborative AI agents, enabling diverse, distributed agents to team up and tackle complex tasks through internet-like connectivity.

* **开放式协作框架与异构代理整合**
  Internet of Agents（IoA）是一个开源框架，旨在通过模拟互联网的连接方式，使不同的AI代理能够协作解决复杂任务。它允许来自不同环境的代理（如AutoGPT和Open Interpreter）团队合作，利用各自的独特技能，共同解决单一代理无法处理的问题。

* **自适应任务执行与可扩展性**
  IoA支持代理自主组建团队，并能根据任务需求动态调整，支持异步任务执行，提升整体效率。它还具有自适应的对话流管理，确保代理之间的沟通灵活有序，同时框架具备高度的可扩展性，方便添加新代理或处理不同类型的任务。



https://github.com/raidendotai/cofounder

6.2k

ai-generated apps , full stack + generative UI

* **全栈生成式Web应用开发平台**
  Cofounder是一个开源平台，旨在简化全栈生成式Web应用的开发。它提供了一整套工具，用于构建后端系统、数据库和有状态的Web应用。平台的生成式用户界面（UI）与应用架构深度集成，配备AI引导的设计工具和模块化设计系统。

* **早期Alpha版本，尚不稳定**
  Cofounder目前处于早期Alpha版本，适合测试和探索。平台不稳定，可能会经历频繁的变更，直到正式发布1.0版本。使用时需要注意平台的高Token消耗，需合理规划使用。


## MultiAgent

https://github.com/camel-ai/camel
🐫 CAMEL: Finding the Scaling Law of Agents. The first and the best multi-agent framework. https://www.camel-ai.org





## 记忆



https://github.com/mem0ai/mem0

24.7k

The Memory layer for AI Agents

* **智能记忆层与个性化交互**
  Mem0为AI助手和代理提供多层记忆功能，包括用户、会话和AI代理的记忆保持，能够根据用户的偏好进行适应性调整，持续改进互动体验。它支持个性化的客户支持、AI助手和自主系统，提升交互的智能化和流畅度。

* **开发者友好与广泛应用场景**
  Mem0提供简易的API集成，保证跨平台的一致性，并且作为托管服务使得集成更加便捷。其适用于多个领域，包括AI助手、客户支持、医疗健康和游戏等，通过个性化推荐和上下文感知，增强用户体验。

https://github.com/modelscope/MemoryScope

0.39k

* **强大灵活的长期记忆管理**
  MemoryScope为LLM聊天机器人提供了长期记忆能力，能够记住用户的基本信息、习惯和偏好。通过向量数据库（默认使用ElasticSearch）存储记忆片段，系统通过多个工作单元（如信息过滤、观察提取、洞察更新）来管理和优化长期记忆，实现记忆检索和整合等功能，确保用户体验逐渐增加的“理解感”。

* **高效低延迟和层次化记忆结构**
  MemoryScope的前端操作（记忆检索）响应时间低至500ms，与后台操作（如记忆整合、反思）分离处理，确保快速响应。记忆存储在层次化结构中，确保内存一致性并过滤虚构内容，同时具备时间感知能力，能够在涉及时间引用时准确检索相关信息。



## 自动化工具



https://github.com/ComposioHQ/composio

14.6k

Production Ready Toolset for AI Agents

Composio equip's your AI agents & LLMs with 100+ high-quality integrations via function calling

* **多种工具集成与高效的AI代理支持**
  Composio为AI代理提供了生产就绪的工具集，支持250多种工具，涵盖软件工具（如GitHub、Notion、Slack等）、操作系统功能（如文件操作、代码分析工具等）以及搜索功能（如Google、Exa等）。平台支持多种框架（如OpenAI、Groq、Claude、Langchain等），并通过优化设计提升了工具调用的准确性，最多可提高40%。

* **灵活的架构与认证管理**
  Composio提供了可白标的后端集成解决方案，支持定制工具和扩展功能，具有灵活的架构设计。它还支持多种认证协议（如OAuth、API密钥、Basic JWT），简化了身份验证和授权过程，使得与不同系统和服务的集成更加高效。



### browser

https://github.com/browser-use/browser-use

https://browser-use.com/

29.9k

Make websites accessible for AI agents

* **智能浏览器自动化与多标签管理**
  Browser-use通过结合视觉理解和HTML结构提取，为AI代理提供强大的浏览器自动化功能。它支持自动处理多个浏览器标签，以便进行复杂的工作流和并行处理，确保AI能够高效地与网站互动。同时，通过提取点击元素的XPath，AI代理能够重复执行相同的操作，保证自动化的一致性和可靠性。

* **灵活的自定义操作与自我修复能力**
  用户可以为AI代理添加自定义操作，如保存文件、数据库操作、通知或处理人类输入。平台还具备智能错误处理和自动恢复机制，确保在执行过程中出现问题时能够快速恢复。此外，Browser-use支持所有LangChain LLMs，包括GPT-4、Claude 3和Llama 2，使其兼容性和扩展性更强。



https://github.com/microsoft/OmniParser/

14.2k

A simple screen parsing tool towards pure vision based GUI agent

* **智能屏幕解析，提升GPT-4V交互能力**
  OmniParser是一款专注于纯视觉GUI代理的屏幕解析工具，能够将用户界面截图解析为结构化、易于理解的元素。这大幅提升了GPT-4V在用户界面上的操作准确性，使其能够精准识别并执行界面中的交互操作。

* **无依赖于代码的视觉交互方案**
  作为一种纯视觉解析方法，OmniParser无需依赖底层代码或DOM结构，即可解析UI界面，为AI代理提供更通用的适配能力。该工具能够帮助AI更自然地理解和操作各种软件界面，实现更高效的自动化控制。



### PC\&mobile

https://github.com/X-PLUG/MobileAgent

3.4k

Mobile-Agent: The Powerful Mobile Device Operation Assistant Family



https://github.com/TencentQQGYLab/AppAgent

5.5k

AppAgent: Multimodal Agents as Smartphone Users, an LLM-based multimodal agent framework designed to operate smartphone apps.

* **智能操作手机应用**
  AppAgent 是基于 LLM 的多模态智能代理框架，旨在通过简化的操作空间模拟人类交互（如点击、滑动）来操作手机应用。该框架无需访问系统后台，能广泛适用于各种手机应用。

* **自我学习与任务执行**
  该代理通过自主探索或观察人类演示学习如何导航和使用新应用，构建知识库，以此执行跨应用的复杂任务。





## AI Search搜索

https://github.com/meilisearch/meilisearch

49.3k

A lightning-fast search engine API bringing AI-powered hybrid search to your sites and applications.

* **高效搜索与个性化体验**
  Meilisearch提供混合搜索，结合语义搜索和全文搜索，能够提供更相关的结果，支持搜索时显示结果、拼写容错、过滤与多重排序、同义词支持等功能，极大提升用户体验。其还具备地理位置搜索和多语言支持（包括中文、日文等），并允许个性化的多租户管理。

* **易于集成与高度定制化**
  Meilisearch支持快速部署和维护，提供RESTful API以及与LangChain等AI框架的无缝集成，支持多种插件和SDK，便于与现有技术栈对接。其灵活性让用户能够通过API密钥管理数据权限并进行高度自定义，适应不同需求。



https://github.com/qdrant/qdrant

22k

Qdrant - High-performance, massive-scale Vector Database and Vector Search Engine for the next generation of AI.&#x20;

* **高性能向量数据库与搜索引擎**
  Qdrant是一个基于Rust开发的高性能向量数据库和相似度搜索引擎，支持大规模部署。其主要功能包括向量存储、检索和管理，能够处理复杂的过滤条件，支持JSON负载和多种数据类型的查询，适用于神经网络匹配、语义搜索等应用。

* **分布式部署与资源优化**
  Qdrant支持分布式部署，包括通过分片扩展存储空间和复制提升吞吐量，同时提供零停机滚动更新和动态扩展功能。内建向量量化技术能有效降低内存使用，并通过SIMD硬件加速和异步I/O优化性能，确保高效的搜索和数据持久化。



https://github.com/developersdigest/llm-answer-engine

4.8k

Build a Perplexity-Inspired Answer Engine Using Next.js, Groq, Llama-3, Langchain, OpenAI, Upstash, Brave & Serper



https://github.com/InternLM/MindSearch

6k

🔍 An LLM-based Multi-agent Framework of Web Search Engine (like Perplexity.ai Pro and SearchGPT)





# WebUI



## all-in-one

https://github.com/Mintplex-Labs/anything-llm

38k

The all-in-one Desktop & Docker AI application with built-in RAG, AI agents, No-code agent builder, and more.

* 一站式文档与AI代理应用：

  * AnythingLLM使您能够轻松将文档转化为语言模型可使用的上下文，支持多种商业和开源的大规模语言模型及向量数据库。它提供了一个无需复杂设置即可本地或远程运行的私有聊天平台，支持多格式文档，并通过工作区实现文档的清晰管理。

* 高度定制化与扩展性：

  * 该应用允许用户无需编写代码即可创建自定义AI代理，并支持多用户管理和权限设置（Docker版）。此外，还提供了多功能聊天界面、对多模态数据的支持以及完整的开发者API，方便进行个性化集成和扩展。

* **全功能AI应用，支持多种文档和LLM模型**
  AnythingLLM是一款全栈AI应用，允许用户使用商用或开源LLM和VectorDB解决方案，构建私有的ChatGPT。用户可以上传各种文档类型（如PDF、TXT、DOCX等），并通过工作区来管理文档，确保每个工作区的上下文独立且整洁。支持自定义AI代理、无代码代理构建器、多用户管理和权限控制，适用于本地和云端部署。

* **简便的用户界面和强大的开发者支持**
  AnythingLLM提供简洁的聊天UI，具备拖放功能，并可以清晰显示引用来源。还支持多模态功能，包含浏览网页的AI代理等高级特性。此外，提供开发者API，便于进行自定义集成。同时，Docker版本支持多用户和嵌入式聊天窗口功能，适合大规模部署和多用户协作。





https://github.com/open-webui/open-webui

76.6k

User-friendly AI Interface (Supports Ollama, OpenAI API, ...)

* **离线自托管AI平台**：Open WebUI是一个功能丰富、用户友好的自托管AI平台，支持完全离线运行，集成Ollama和OpenAI兼容API，内置RAG推理引擎，提供Docker/Kubernetes一键部署，适用于多种LLM运行环境。

* **多功能集成与扩展性**：支持多设备响应式设计、PWA移动端体验、Markdown/LaTeX渲染、语音/视频通话、本地RAG文档交互、网页搜索与浏览、图像生成、多模型并行对话等功能，并具备RBAC权限管理和多语言支持，通过插件框架（Pipelines）可扩展自定义逻辑，满足多样化AI应用需求。

这是一个功能强大、用户友好的自托管 AI 平台，支持完全离线运行。它集成了多种大型语言模型运行器，如 Ollama 和 OpenAI 兼容的 API，支持网页搜索、本地 RAG 集成、权限管理、适配移动端、Markdown 和 LaTeX 等功能。







https://github.com/lobehub/lobe-chat

55.8k

🤯 Lobe Chat - an open-source, modern-design AI chat framework. Supports Multi AI Providers( OpenAI / Claude 3 / Gemini / Ollama / Qwen / DeepSeek), Knowledge Base (file upload / knowledge management / RAG ), Multi-Modals (Vision/TTS/Plugins/Artifacts). One-click FREE deployment of your private ChatGPT/ Claude application.

* **多功能开源AI聊天框架**：Lobe Chat 是一个现代化设计的开源AI聊天框架，支持多AI提供商（如OpenAI、Claude 3、Gemini、Ollama等），具备知识库管理、多模态交互（视觉、语音、插件、图像生成）、链式思维（CoT）可视化和分支对话等高级功能，提供一键免费部署私有ChatGPT/Claude应用的能力。

* **灵活部署与扩展性**：支持本地和远程数据库（如PostgreSQL），提供多用户管理（next-auth/Clerk）和插件系统（函数调用），兼容本地大语言模型（如Ollama），并支持TTS/STT语音对话、视觉识别、文本生成图像等功能，满足多样化场景需求，同时确保数据隐私和安全。







https://github.com/YaoApp/yao

7.2k

✨ Yao is an all-in-one application engine that enables developers to create web apps, REST APIs, business applications, and more, with AI as a development partner.

* **AI驱动的全栈开发引擎**：Yao是一个集成了AI开发伙伴的应用引擎，支持通过AI生成代码、可视化界面或手动编写代码来创建Web应用、REST API和业务应用。其设计的DSL（领域特定语言）易于读写，支持AI与开发者无缝协作，显著提升开发效率，AI可完成80%-90%的工作，开发者只需专注于剩余部分。

* **一体化与多场景支持**：Yao提供全栈开发解决方案，无需额外依赖包或工具链，内置V8引擎支持TypeScript，提供丰富的API和扩展能力。同时，Yao支持多种编程方式（AI生成、可视化、手动编码），并具备Serverless和边缘设备（如IoT）支持，适用于多样化应用场景。



https://github.com/arc53/DocsGPT

15.3k

Chatbot for documentation, that allows you to chat with your data. Privately deployable, provides AI knowledge sharing and integrates knowledge into your AI workflow

* **多格式支持与智能集成**
  DocsGPT是一款开源的生成AI工具，支持多种文档格式（如PDF、DOCX、CSV、EPUB等）和数据源（如URLs、Reddit、GitHub等），能够从各种来源快速检索并提供可靠的答案。该工具集成了API、工具和其他服务，允许用户在AI工作流中进行高效的知识共享和检索，同时避免信息偏差（hallucinations）。支持与多种大型LLM（如OpenAI、Google、Anthropic等）和本地模型（如Ollama、llama\_cpp）集成。

* **私有部署与企业级安全性**
  DocsGPT提供灵活的部署选项，适用于本地和私有云部署，支持Kubernetes以实现企业级的安全性和可扩展性。用户可以生成API密钥来简化设置过程，同时通过预构建的集成（如HTML/React聊天小部件、Discord/Telegram机器人等）快速实现功能扩展。这使得DocsGPT非常适合企业级用户进行文档管理和知识共享。



https://github.com/1Panel-dev/MaxKB

13.6k

💬 Ready-to-use & flexible RAG Chatbot, supporting mainstream large language models (LLMs) such as DeepSeek-R1, Llama 3.3, Qwen2, OpenAI, and more.

* **智能Q\&A与灵活的工作流引擎**
  MaxKB是基于大语言模型（LLM）和检索增强生成（RAG）技术的聊天机器人，适用于智能客服、企业知识库、学术研究和教育等场景。它支持直接上传文档或自动抓取在线文档，并具备自动文本拆分、向量化和RAG功能，有效减少模型的偏差，提高智能问答交互体验。此外，MaxKB配备强大的工作流引擎和功能库，可满足复杂业务场景的需求。

* **无缝集成与模型无关性**
  MaxKB支持与各种大型模型（包括私有模型如DeepSeek、Llama、Qwen等和公有模型如OpenAI、Claude、Gemini等）无缝集成。它可以快速实现零编码集成，轻松将智能问答功能添加到第三方业务系统中，提升用户满意度和系统效率。



https://github.com/khoj-ai/khoj

26.3k

Your AI second brain. Self-hostable. Get answers from the web or your docs. Build custom agents, schedule automations, do deep research. Turn any online or local LLM into your personal, autonomous AI (gpt, claude, gemini, llama, qwen, mistral). Get started - free.

* **多平台支持与个性化AI代理**
  Khoj是一款可自托管的个人AI应用，支持与本地或在线LLM（如Llama3、Qwen、Gemini、GPT、Claude、Mistral等）进行交互，并从网络或本地文档（如PDF、Word、Markdown、Notion文件等）中获取答案。用户可以创建具有定制知识、人格、聊天模型和工具的AI代理来执行不同角色，自动化重复性研究任务，并通过语义搜索快速找到相关文档。它还支持在浏览器、Obsidian、Emacs、桌面、手机或Whatsapp等平台上访问。

* **开源、自托管与云端选择**
  Khoj是一个开源且可自托管的应用，用户可以将其运行在本地计算机上，或选择使用云端应用。它提供强大的自动化功能，如生成个人化的新闻简报和智能通知，并支持语音输出和图像生成，增强了用户的研究和信息获取能力。



## 工作流(**Workflow**)

https://github.com/langgenius/dify

69.6k

Dify is an open-source LLM app development platform. Dify's intuitive interface combines AI workflow, RAG pipeline, agent capabilities, model management, observability features and more, letting you quickly go from prototype to production.

* **强大的AI工作流与多模型支持**
  Dify是一款开源的LLM应用开发平台，提供直观的可视化界面，用户可以快速构建和测试AI工作流。它支持与数百种商用和开源LLM（如GPT、Mistral、Llama3等）无缝集成，覆盖各种推理提供商和自托管解决方案。平台还具有强大的RAG管道功能，支持从文档提取、检索到自动化的文本处理，简化了AI应用的开发流程。

* **智能代理与后端服务**
  Dify提供强大的代理功能，用户可以根据LLM功能调用或ReAct模型定义代理，并为其添加内置或自定义工具（如Google搜索、DALL·E、WolframAlpha等）。平台还包含LLMOps功能，帮助用户监控应用日志和性能，并基于生产数据不断优化提示、数据集和模型。所有功能都配有API，方便与现有业务系统集成。

#####

https://github.com/labring/FastGPT

21.4k

FastGPT is a knowledge-based platform built on the LLMs, offers a comprehensive suite of out-of-the-box capabilities such as data processing, RAG retrieval, and visual AI workflow orchestration, letting you easily develop and deploy complex question-answering systems without the need for extensive setup or configuration.

* **简化的工作流编排与知识库管理**
  FastGPT提供了开箱即用的数据处理、RAG检索和知识库功能，支持多种文件格式（如PDF、DOCX、CSV等）的导入，并能混合使用多个数据库。平台通过可视化的Flow工作流编排工具，简化了复杂的问答系统开发，支持对数据进行版本管理、修改跟踪以及向量模型配置。此外，还提供URL读取、大规模CSV导入等功能，方便快速构建和部署知识库系统。

* **易于集成与调试功能**
  FastGPT支持通过OpenAPI接口进行自定义集成，允许执行知识库的增删改查操作。它还具备强大的调试功能，包括搜索测试、反馈编辑、以及显示完整的对话上下文，帮助开发者有效跟踪和调试应用。平台还支持无登录共享、Iframe嵌入和可定制聊天窗口嵌入，提升了应用的灵活性和用户体验。



https://github.com/n8n-io/n8nn

Fair-code workflow automation platform with native AI capabilities. Combine visual building with custom code, self-host or cloud, 400+ integrations.





https://github.com/FlowiseAI/Flowise

35.3k

Drag & drop UI to build your customized LLM flow



https://github.com/langflow-ai/langflow

48.7k

Langflow is a low-code app builder for RAG and multi-agent AI applications. It’s Python-based and agnostic to any model, API, or database.

* **低代码构建与灵活性**
  Langflow是一个Python基础的低代码应用构建平台，适用于RAG（检索增强生成）和多代理AI应用，支持多种模型、API、数据源和数据库。它提供可视化IDE，用户可以通过拖拽构建和测试工作流，实时迭代和控制工作流过程。

* **企业级安全与可扩展性**
  Langflow提供免费云服务，允许用户快速启动并实现无缝集成，支持通过LangSmith、LangFuse或LangWatch进行可观测性管理。它具备企业级安全性和可扩展性，同时支持将应用发布为API或导出为Python应用，并支持Python编写定制化工作流。





https://github.com/activepieces/activepieces

11.6

Your friendliest open source AI automation tool ✨ Workflow automation tool 200+ integration / Enterprise automation tool / Zapier Alternative

* **易于使用且灵活的自动化工具**
  Activepieces是一款开源、全功能的自动化工具，旨在为技术和非技术用户提供直观的操作界面。平台提供200多个集成功能，支持无代码构建工作流，同时通过TypeScript编写的可扩展“pieces”模块，提供了最佳的开发者体验，支持热重载和完全自定义。内置AI模块和SDK使用户可以轻松创建AI代理，满足企业自动化和AI需求。

* **安全性与企业级功能**
  Activepieces支持自托管和网络隔离，确保数据安全和隐私。它适合企业使用，提供完全的定制功能，从品牌化到权限控制，并支持包括聊天界面和表单界面在内的人类输入触发器。平台还具备高级功能，如工作流中的循环、分支、自动重试等，帮助用户构建高效、可控的自动化流程。



### **AI 代理开发框架**

https://github.com/JoshuaC215/agent-service-toolkit

2.3k

Full toolkit for running an AI agent service built with LangGraph, FastAPI and Streamlit

* **完整的AI代理服务工具包**
  该工具包包括一个基于LangGraph框架的可定制代理、一个使用FastAPI提供服务的API、一个Streamlit应用程序提供聊天界面，并通过Pydantic构建数据结构和设置。它支持流式和非流式端点，并提供多代理支持、内容审查和反馈机制，旨在帮助用户快速启动LangGraph项目。

* **易于部署和扩展**
  该项目支持Docker，提供Dockerfiles和docker compose文件，便于开发和部署。设计上采用异步处理（async/await）以高效处理并发请求，同时包含完整的单元和集成测试，确保服务的可靠性和可扩展性。

该项目能够帮助开发者用 Python 快速搭建和运行基于 LangGraph 框架的 AI 代理服务。它结合 FastAPI、Streamlit 和 Pydantic 等技术栈，提供了用户界面、自定义 Agent、流式传输等功能，并集成了内容审核（LlamaGuard）和用户反馈机制（LangSmith），极大地简化了 AI Agent 应用的开发和优化过程。





## 其他

https://github.com/oobabooga/text-generation-webui

42.6k



# RAG

## RAG实现

https://github.com/microsoft/graphrag

22.6k

A modular graph-based Retrieval-Augmented Generation (RAG) system

* **基于图的模块化检索增强生成（RAG）系统**
  GraphRAG 项目是一个数据管道和转换套件，旨在通过利用 LLM 的强大能力，从非结构化文本中提取有意义的结构化数据。

* **增强 LLM 推理能力**
  GraphRAG 旨在提升 LLM 在处理私有数据时的推理能力，可通过该系统增强对特定数据集的理解与分析。



https://github.com/gusye1234/nano-graphrag

2.4k

A simple, easy-to-hack GraphRAG implementation



https://github.com/infiniflow/ragflow

37.8k

RAGFlow is an open-source RAG (Retrieval-Augmented Generation) engine based on deep document understanding.

* **深度文档理解的RAG引擎**
  RAGFlow 是一个开源的基于深度文档理解的RAG（检索增强生成）引擎，提供智能的文档分块与知识提取能力，支持多种格式的数据，减少信息偏差并提供有据可查的引用。

* **自动化和兼容多数据源的RAG工作流**
  具备模板化分块、支持异构数据源（如Word、图片、Excel等），自动化简化RAG工作流，支持可配置的LLM与嵌入模型，并提供直观的API以便与企业系统无缝集成。



https://github.com/OpenSPG/KAG

5.5k

KAG is a logical form-guided reasoning and retrieval framework based on OpenSPG engine and LLMs.

* **逻辑推理与检索框架**
  KAG 是基于 OpenSPG 引擎和大型语言模型（LLM）的逻辑推理与问答框架，专为构建专业领域知识库中的逻辑推理和事实问答解决方案。它通过知识和块的相互索引、语义推理和混合推理方式，克服了传统 RAG 向量相似性计算模型的模糊性及 GraphRAG 的噪声问题，支持多跳推理和复杂的事实问答。

* **知识表示与混合推理**
  KAG 结合了非结构化数据（如新闻、事件、日志）和结构化数据（如交易、统计数据）以及领域专家经验，采用布局分析、知识提取和语义对齐等技术，构建统一的业务知识图谱。通过混合推理与逻辑形式指导，KAG 支持四种不同的求解过程：检索、知识图谱推理、语言推理和数值计算，增强了领域知识的推理能力。



## 整体方案

https://github.com/QuivrHQ/quivr

37.3k

Opiniated RAG for integrating GenAI in your apps 🧠 Focus on your product rather than the RAG. Easy integration in existing products with customisation! Any LLM: GPT4, Groq, Llama. Any Vectorstore: PGVector, Faiss. Any Files. Anyway you want.

* **灵活的RAG与多样化支持**：提供快速、高效的定制化RAG，支持多种文件格式（PDF、TXT、Markdown等）和多种LLM（如OpenAI、Anthropic等），并允许用户添加自定义解析器。

* **强大集成功能与定制化**：支持与Megaparse集成，能方便地将文件导入并利用RAG进行智能处理；同时，用户可以自定义RAG、添加互联网搜索和工具，增强个性化使用体验。



https://github.com/netease-youdao/QAnything

12.5k

Question and Answer based on Anything.

* **多格式支持与高效离线问答**
  QAnything是一个本地知识库问答系统，支持多种文件格式（如PDF、Word、PPT、XLS、Markdown、图片等），并可离线安装使用。它能快速、准确地回答基于本地存储文件的任何问题，支持中英文问答，并能处理大量数据，提供高效的检索和回答服务。

* **简易安装与硬件友好**
  QAnything无需复杂配置，支持一键安装与部署，适用于Windows、Mac和Linux等多平台，默认运行在纯CPU环境下，无需外部依赖。它提供多种模式，如文件聊天模式、检索模式及自定义Bot模式，方便用户根据需求灵活使用。

https://github.com/deepset-ai/haystack

AI orchestration framework to build customizable, production-ready LLM applications. Connect components (models, vector DBs, file converters) to pipelines or agents that can interact with your data. With advanced retrieval methods, it's best suited for building RAG, question answering, semantic search or conversational agent chatbots.

* **简介**：Haystack是一个开源的问答系统，专注于构建**端到端的搜索引擎**和**问答应用**。它支持多种数据源，如PDF、Word文档、CSV文件等，适合构建企业级的知识库问答系统。

* **特点**：

  * 支持**多种数据源**的输入（如文档、数据库等）。

  * 支持**分布式部署**和**可扩展性**。

  * 可以与**Transformer模型**集成，提升问答的准确度和智能化。

###



https://github.com/Cinnamon/kotaemon

21.2k

An open-source RAG-based tool for chatting with your documents.

* **用户友好的RAG体验与强大自定义能力**：

  * 提供简洁直观的UI，支持多种LLM（如OpenAI、Azure等）与本地LLM，适用于文档问答（QA）。

  * 开发者可通过提供的框架构建自定义RAG管道，且UI和功能高度可定制，支持Gradio主题和自定义元素。

* **高级功能与多模式支持**：

  * 支持混合RAG管道（全文本和向量检索），确保高质量的文档检索，支持复杂的推理方法（如问题分解、ReAct等）。

  * 提供文献引用、文档预览、复杂推理支持，并能处理多模态文档（包括表格、图形等）。



https://github.com/deepset-ai/haystack

19.3k

AI orchestration framework to build customizable, production-ready LLM applications. Connect components (models, vector DBs, file converters) to pipelines or agents that can interact with your data. With advanced retrieval methods, it's best suited for building RAG, question answering, semantic search or conversational agent chatbots.

* **灵活的AI管道与高度可定制性**：

  * 提供一个多组件的AI编排框架，支持各种LLM应用，如RAG、问答、语义搜索和对话代理。

  * 支持多种技术和模型（OpenAI、Cohere、Hugging Face等），可以根据需求自由选择和替换组件。

* **全面集成与扩展性**：

  * 集成数据库访问、文件转换、训练和推理等多种功能，支持扩展和自定义组件，便于创建符合特定需求的端到端NLP应用。

  * 支持海量文档处理，能够进行复杂决策和问题解决，帮助企业构建可扩展的智能系统。





## 专项

https://github.com/vanna-ai/vanna

13.3k

🤖 Chat with your SQL database 📊. Accurate Text-to-SQL Generation via LLMs using RAG 🔄.

52. **高效的SQL生成与自我学习**：

    * 通过训练RAG模型与数据，Vanna能够将自然语言问题转换为SQL查询，支持复杂数据集，准确度高。

    * 支持自动训练和用户反馈机制，随着时间推移，生成结果不断优化，提高未来查询的准确性。

53. **兼容性与隐私保障**：

    * 支持与任何SQL数据库连接，并确保数据隐私，数据库内容不会发送到LLM或向量数据库，SQL执行发生在本地环境。

    * 可以通过多种前端（如Jupyter、Slackbot、Streamlit等）进行交互，灵活适应不同使用场景。





https://github.com/pathwaycom/llm-app

12.7k

Ready-to-run cloud templates for RAG, AI pipelines, and enterprise search with live data. 🐳Docker-friendly.⚡Always in sync with Sharepoint, Google Drive, S3, Kafka, PostgreSQL, real-time data APIs, and more.

56. **即插即用的AI管道与模板**：

    * 提供可快速部署的RAG和AI企业搜索应用模板，支持大规模高准确度的应用，兼容多种数据源（如Google Drive、Sharepoint、S3、Kafka、PostgreSQL等）。

    * 模板支持本地测试和云端部署（GCP、AWS、Azure等），无需额外基础设施配置。

57. **实时数据同步与智能搜索功能**：

    * 自动与数据源同步，实时处理新增、删除、更新的数据，并具备内存中的数据索引功能，支持向量搜索、混合搜索和全文搜索，提供快速精准的检索体验。



## 文本提取

https://github.com/quivrhq/megaparse

5.5k

File Parser optimised for LLM Ingestion with no loss 🧠 Parse PDFs, Docx, PPTx in a format that is ideal for LLMs.

60. **多功能文档解析与高兼容性**：

    * 支持多种文件类型（如文本、PDF、PPTX、Word、Excel等），提供强大且高效的文档解析能力，确保在处理各种文档时不丢失信息。

61. **高效且开源**：

    * 以速度和效率为核心设计，确保快速解析；同时，作为开源工具，免费提供给用户使用，提供更多自定义和扩展的可能性。





https://github.com/pathwaycom/pathway

13.6k

Python ETL framework for stream processing, real-time analytics, LLM pipelines, and RAG.

56. **强大的流处理与实时分析能力**：

    * 提供一个易于使用的Python API，支持批处理和流处理，能高效处理实时数据流，且具备分布式计算能力，适用于开发和生产环境。

    * 支持多种数据源连接（如Kafka、GDrive、PostgreSQL等）并具有自定义连接器功能，保证数据流的稳定性和一致性。

57. **高效的LLM集成与可扩展性**：

    * 内置LLM扩展，提供多种工具集成（如LLamaIndex、LangChain等），支持快速构建RAG应用，并包含实时向量索引功能。

    * 基于Rust引擎进行增量计算，突破Python的多线程和分布式计算限制，实现高性能计算和可扩展性。



## 向量库

https://github.com/facebookresearch/faiss

33.1k

A library for efficient similarity search and clustering of dense vectors.

52. **高效的相似度搜索与向量聚类**：

    * 提供多种相似度搜索算法，支持大规模向量数据集（包括不完全适配内存的数据集），并支持多种距离度量（如L2距离、点积、余弦相似度等）。

    * 支持基于压缩向量和索引结构（如HNSW、NSG）优化搜索效率，能够处理海量数据并保证快速检索。

53. **GPU加速与可扩展性**：

    * 提供GPU加速实现，支持将GPU作为CPU索引的替代，显著提高大规模数据集的搜索速度，支持单机和多GPU使用。

    * 兼容Python/numpy接口，开发者可以方便地将Faiss集成到机器学习和数据处理管道中。



https://github.com/milvus-io/milvus

32.5k

Milvus is a high-performance, cloud-native vector database built for scalable vector ANN search

* **高性能、可扩展的向量数据库**：

  * 支持水平扩展，采用分布式架构，能够高效处理海量向量数据和实时流数据更新，适用于AI应用（如文本、图像、多模态数据搜索）。

  * 提供多种向量索引类型（如HNSW、IVF、SCANN等）并实现GPU加速，优化查询性能，支持大规模数据集和高并发查询。

* **灵活的多租户与安全控制**：

  * 支持多租户管理和冷热数据存储策略，能够根据访问频率优化存储成本并保证高效查询性能。

  * 提供细粒度的访问控制和数据安全保障（如用户身份验证、TLS加密、RBAC权限管理），确保数据在企业级应用中的安全性和隐私保护。



https://github.com/weaviate/weaviate

21.4k

Weaviate is an open-source vector database that stores both objects and vectors, allowing for the combination of vector search with structured filtering with the fault tolerance and scalability of a cloud-native database.

58. **高性能与灵活性**：

    * Weaviate是一个云原生的开源向量数据库，支持快速的近邻搜索（如10-NN）和结构化过滤，能够处理海量数据并提供毫秒级查询响应。

    * 提供灵活的向量化选择：支持在数据导入时进行向量化，也可以上传预先向量化的数据，支持多种模块与自定义模型集成，便于调优和扩展。

59. **生产就绪与多功能支持**：

    * Weaviate内建分布式架构，具备高可扩展性和高容错性，适合从快速原型开发到生产环境的无缝过渡。

    * 除了向量搜索外，还支持推荐、总结、神经搜索等功能，适用于软件工程师、数据工程师和数据科学家的多种应用场景。



https://github.com/lancedb/lancedb

5.6k

Developer-friendly, serverless vector database for AI applications. Easily add long-term memory to your LLM apps!

56. **无服务器、生产级向量搜索**：

    * LanceDB是一个开源、无服务器的向量数据库，支持高效的向量相似性搜索、全文搜索和SQL查询，且无需管理服务器。

    * 支持存储和查询向量、元数据以及多模态数据（如文本、图像、视频、点云等），并提供自动版本管理。

57. **兼容生态系统与GPU支持**：

    * 原生支持Python和JavaScript/Typescript，并与LangChain、LlamaIndex、Apache-Arrow等生态系统集成，支持GPU加速的向量索引构建。

    * LanceDB使用Rust编写，并基于Lance格式优化，特别适用于机器学习工作负载。



https://github.com/chroma-core/chroma

17.9k

the AI-native open-source embedding database

The fastest way to build Python or JavaScript LLM apps with memory!

* **简化的开发体验与全面功能**：

  * 提供简单易用的API，支持查询、过滤、密度估算等功能，适用于开发、测试和生产环境。

  * 完全类型化、经过全面测试和文档化，确保开发者的顺利使用和高效开发。

* **开源与生态系统集成**：

  * 开源且基于Apache 2.0许可，支持与LangChain、LlamaIndex等流行工具和框架的集成，提升应用扩展性。

  * 适用于Python和JavaScript，能快速构建具有记忆功能的LLM应用。



# 客户端

## 渲染

https://github.com/markdown-it/markdown-it

18.9k

Markdown parser, done right. 100% CommonMark support, extensions, syntax plugins & high speed

Markdown解析器，能够将Markdown文转换为HTML格式，在网页显示





https://github.com/highlightjs/highlight.js

24.1k

JavaScript syntax highlighter with language auto-detection and zero dependencies.

代码高亮工具，提供了丰富的语言高亮支持，使编程示例和代码片段在网页看起来美观、易读



https://github.com/KaTeX/KaTeX

18.7k

Fast math typesetting for the web.

KaTeX 是一个快速的、基于 JavaScript 的数学公式和文字排版库，用于在网页上渲染 LaTeX 公式。它能够解析 LaTeX 语法并将其转换为美观的数学符号和公式，支持多种浏览器，且渲染速度快。



## 文档处理

https://www.nuget.org/packages/OfficeConverter/

Convert Microsoft Office document to PDF (Office 2007 - 2016)

office文档处理工具，可以将office的系列文档（如word,excel,ppt）转化为pdf，以供文件读取和转存



https://github.com/PDFium/PDFium

0.41k

PDFium 是一个开源的 PDF 渲染库，提供了丰富的 API，支持 PDF 文档的渲染、操作和生成。



https://github.com/KevM/tikaondotnet

0.20k

Use the Java Tika text extraction library on the .NET platform

Tika是一个在.NET 平台上用来检测和提取多种文档中的元数据和结构化文本内容的接口库



https://github.com/apache/tika

2.8k

The Apache Tika toolkit detects and extracts metadata and text from over a thousand different file types (such as PPT, XLS, and PDF).

统一接口，文档解析，多格式支持。能检测并提取超过上百种不同文件类型的元数据和文本（如 PPT、XLS 和 PDF）。所有这些文件类型都可以通过单一接口进行解析。



https://github.com/opendatalab/MinerU

26.5k

开源高质量数据提取工具，将PDF转换成Markdown和JSON格式。



https://github.com/Byaidu/PDFMathTranslate

https://pdf2zh.com/

PDF scientific paper translation with preserved formats - 基于 AI 完整保留排版的 PDF 文档全文双语翻译





## 图像处理

https://github.com/PaddlePaddle/PaddleOCR

46.6k

Awesome multilingual OCR toolkits based on PaddlePaddle (practical ultra lightweight OCR system, support 80+ languages recognition, provide data annotation and synthesis tools, support training and deployment among server, mobile, embedded and IoT devices)

文本检测、文本识别、文本图像矫正等多功能。支持高性能推理、服务化和端侧部署等多种部署方式。



https://opencv.org/

轻量高效跨平台跨语言计算机视觉库，包含超过2500个算法。用于图片预处理/缩略图/人脸识别/特征提取/向量比对





## 音频处理

https://github.com/xiangyuecn/Recorder

5k

音频处理工具，用于在网页录制音频、格式转换、音频可视化、实时语音识别等

📖Recorder用于html5录音：html5 js 录音 mp3 wav ogg webm amr g711a g711u 格式，支持pc和Android、iOS部分浏览器、Hybrid App（提供Android iOS App源码）、微信，提供ASR语音识别转文字 H5版语音通话聊天示例 DTMF编码解码



# 安全

https://github.com/Election-Tech-Initiative/electionguard

0.82k

ElectionGuard is a set of open source software components that can be used to create and publish end to end verifiable elections as well create a publishable artifact for ballot comparison audits.

* **端到端可验证选举**
  ElectionGuard 是一个开源软件开发工具包（SDK），旨在提高选举的安全性、透明性和可访问性。它通过同态加密确保选票在任何电子系统中都能保持加密、安全和保密，并支持选举结果的发布和票据比对审计。

* **选民透明度与安全性**
  ElectionGuard 使选民能够确认自己的选票是否正确计数，并允许将结果公开发布或提供给第三方机构进行安全验证，确保选举过程的透明度和安全性。



https://github.com/stacklok/codegate/
0.53k

CodeGate: Security, Workspaces and Muxing for AI Applications, coding assistants, and agentic frameworks.


https://github.com/tencent/AI-Infra-Guard
0.83k

AI infrastructure security assessment tool designed to discover and detect potential security risks in AI systems.




# 标准

OPENAI

Triton

https://github.com/PennyroyalTea/gibberlink

Two conversational AI agents switching from English to sound-level protocol after confirming they are both AI agents

ANP
https://github.com/agent-network-protocol/AgentNetworkProtocol
AgentNetworkProtocol(ANP) is an open source protocol for agent communication. Our vision is to define how agents connect with each other, building an open, secure, and efficient collaboration network for billions of intelligent agents.

MCP
https://spec.modelcontextprotocol.io/specification/


Agora (牛津大学元协议)
Agora源于牛津大学团队论文（2024年10月提交）
属于前沿探索

agents.json
受robots.txt/sitemap.xml启发


LMOS（Language Model Operating System）
Eclipse开源项目

AITP（Agent Interaction & Transaction Protocol）
AITP由NEAR基金会发起
在2025年2月公布RFC征求意见并开放aitp.dev站点供文档和讨论




# 数据生成

https://github.com/snorkel-team/snorkel

5.8k

注：好久不更新了，应该是被LLM替代了

A system for quickly generating training data with weak supervision

* **Snorkel项目与弱监督学习**
  Snorkel项目最初于2015年在斯坦福大学启动，目标是通过数学和系统化的结构，简化和自动化训练数据的创建与管理，从而解决机器学习中的数据瓶颈。它为用户提供了一个框架，帮助用户以程序化的方式标注、构建和管理训练数据。通过与Google、Intel、斯坦福医学院等世界领先组织的合作，Snorkel项目发展迅速，并为弱监督建模、数据增强、多任务学习等领域贡献了大量创新。

* **Snorkel Flow：端到端机器学习平台**
  Snorkel Flow是为了支持更广泛的愿景而开发的端到端机器学习平台，结合了Snorkel项目中的理念，并加入了新的弱监督建模、数据增强、多任务学习等技术。Snorkel Flow通过集成不同的技术，提高了机器学习开发和部署的速度、灵活性和实用性，帮助团队更加高效地构建、训练、监控和分析AI应用。























# 论文&博客

https://github.com/Xnhyacinth/Awesome-LLM-Long-Context-Modeling

📰 Must-read papers and blogs on LLM based Long Context Modeling 🔥



https://github.com/dailydotdev/daily

https://daily.dev/

daily.dev is a professional network for developers to learn, collaborate, and grow together 👩🏽‍💻 👨‍💻



https://github.com/Shubhamsaboo/awesome-llm-apps

Collection of awesome LLM apps with AI Agents and RAG using OpenAI, Anthropic, Gemini and opensource models.



https://github.com/NirDiamant/RAG\_Techniques

This repository showcases various advanced techniques for Retrieval-Augmented Generation (RAG) systems. RAG systems combine information retrieval with generative models to provide accurate and contextually rich responses.



https://github.com/e2b-dev/awesome-ai-agents

A list of AI autonomous agents





# 其他

https://coolify.io/

https://github.com/coollabsio/coolify

An open-source & self-hostable Heroku / Netlify / Vercel alternative.



https://github.com/2noise/ChatTTS

A generative speech model for daily dialogue.





https://github.com/RockChinQ/LangBot

原生即时通信机器人平台

😎丰富生态、🧩支持扩展、🦄多模态 - 大模型原生即时通信机器人平台 | 适配 QQ / 微信（企业微信、个人微信）/ 飞书 / 钉钉 / Discord / Telegram 等消息平台 | 支持 OpenAI GPT、ChatGPT、DeepSeek、Dify、Claude、Gemini、Ollama、LM Studio、SiliconFlow、Qwen、Moonshot、ChatGLM 等 LLM 的机器人 / Agent | LLM-based instant messaging bots platform, supports Discord, Telegram, WeChat, Lark, DingTalk, QQ, OpenAI ChatGPT, DeepSeek



https://github.com/huggingface/lerobot

🤗 LeRobot: Making AI for Robotics more accessible with end-to-end learning



https://github.com/stepfun-ai/Step-Audio





https://uizard.io/

Turn product ideas into concepts instantly with GenAI





## Learn LLM From Scratch

https://github.com/jingyaogong/minimind

11.3k

Train a 26M-parameter GPT from scratch in just 2h!



## 浏览器/Web browsing

* pyppeteer

* playwright

* selenium



## 工具-Gym

https://github.com/ServiceNow/BrowserGym

BrowserGym, a Gym environment for web task automation



https://github.com/getsentry/sentry

https://sentry.io/welcome/

Developer-first error tracking and performance monitoring







## 工具-Search



web searches using providers like `SearXNG`, `Google PSE`, `Brave Search`, `serpstack`, `serper`, `Serply`, `DuckDuckGo`, `TavilySearch`, `SearchApi` and `Bing`



https://github.com/opsdisk/yagooglesearch



https://brave.com/search/api/



* https://serper.dev/: Serper.dev 是一个免费的 Google 搜索 API，它提供快速的搜索结果和准确的排名。它还允许用户搜索图像和视频

* google1(The World's Fastest and Cheapest Google Search API): https://www.serper.dev



* https://serpapi.com/



* google2: https://programmablesearchengine.google.com/

* Visit https://console.cloud.google.com/apis/credentials to get key.



* DuckDuckGo是专注隐私、反追踪以及避免信息过滤的搜索引擎，使用多方来源优化搜索结果，并加强内容的关联度。



* https://www.microsoft.com/en-us/bing/apis/bing-web-search-api

* bing: https://portal.azure.com/



* google0: https://www.searchapi.io/

* Brave Search API(注重隐私保护、提供公正搜索结果的搜索引擎): https://brave.com/search/api/





## VSCode插件

https://github.com/RooVetGit/Roo-Code.git

Roo Code (prev. Roo Cline) is an AI-powered autonomous coding agent that lives in your editor.

* **多功能AI编程助手**
  Roo Code 是一款集成在代码编辑器中的 AI 编程助手，能够执行多种开发任务，包括根据自然语言生成代码、调试和重构代码、编写文档、自动化重复任务等。它还支持与终端命令、浏览器交互，并能与任何 OpenAI 兼容的 API 或自定义模型集成。

* **定制化与智能模式**
  Roo Code 提供多个专业模式，如 Code Mode（通用编码）、Architect Mode（架构规划）、Debug Mode（问题诊断）等，帮助开发者在不同任务中获得专门化支持。同时，借助 Model Context Protocol（MCP），用户可以创建自定义工具和模式，满足特定需求，如安全审计、性能优化等。

* **与Cline的区别**

  &#x20;作为Cline的分叉版本，Roo Code在功能上进行了显著扩展，提供了多种工作模式，如Code模式、Architect模式和Ask模式，满足不同开发需求。此外，Roo Code支持自定义模式，允许用户根据特定任务创建个性化的工作流程。





https://github.com/cline/cline

Autonomous coding agent right in your IDE, capable of creating/editing files, executing commands, using the browser, and more with your permission every step of the way.

* **AI助手与自动化开发功能**
  Cline 是一款集成在 IDE 中的智能编程助手，能够在用户授权的情况下，执行复杂的开发任务，如创建/编辑文件、执行命令、使用浏览器等。它支持通过终端命令、自动调试、网页交互等方式，帮助开发者高效解决问题、修复 Bug，并能通过 Model Context Protocol (MCP) 扩展自身功能。

* **可定制与扩展性**
  Cline 支持多种 API 和模型（如 OpenRouter、OpenAI、Anthropic 等），并能够根据开发者的需求添加自定义工具，如集成 Jira、AWS EC2 管理等。同时，Cline 还提供任务快照和恢复功能，便于开发者在多个任务版本间切换，保障开发过程中的灵活性与安全性。





## ChatBot

https://github.com/CherryHQ/cherry-studio

🍒 Cherry Studio is a desktop client that supports for multiple LLM providers. Support deepseek-r1



https://github.com/Bin-Huang/chatbox

User-friendly Desktop Client App for AI Models/LLMs (GPT, Claude, Gemini, Ollama...)



## 知识库工具obsidian

https://github.com/siyuan-note/siyuan

A privacy-first, self-hosted, fully open source personal knowledge management software, written in typescript and golang.



https://github.com/khoj-ai/khoj

Your AI second brain. Self-hostable. Get answers from the web or your docs. Build custom agents, schedule automations, do deep research. Turn any online or local LLM into your personal, autonomous AI (gpt, claude, gemini, llama, qwen, mistral). Get started - free.









## 模型

https://github.com/stepfun-ai/Step-Audio

集语音理解与生成控制一体化的产品级开源实时语音对话系统（130B）



## 知识库

https://github.com/microsoft/generative-ai-for-beginners

https://github.com/dair-ai/Prompt-Engineering-Guide



### image-annotation

https://github.com/HumanSignal/awesome-data-labeling

https://github.com/HumanSignal/label-studio

https://github.com/wkentaro/labelme







