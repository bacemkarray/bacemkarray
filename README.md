 # Bacem Karray

Computer Engineering student at McMaster University building projects across GPU programming, machine learning systems, agentic workflows, retrieval systems, and applied computer vision.

This GitHub is my project portfolio: a record of the systems I build to learn deeply, test ideas, and turn technical concepts into working software.

---

## Featured Projects

### 1. [Ray Tracer](https://github.com/bacemkarray/ray-tracing)

A C++ path tracer with both CPU and CUDA renderers. The project implements recursive ray scattering, antialiasing, gamma correction, depth-of-field camera controls, and multiple material types including diffuse, metal, and dielectric surfaces.

**Why it matters:** This project connects graphics programming with GPU acceleration. The CUDA renderer parallelizes work across pixels, making it a practical comparison between a straightforward CPU renderer and a GPU implementation of the same rendering logic.

**Tech:** C++, CUDA, CURAND, Make, NVIDIA Nsight

---

### 2. [Transformer Playground](https://github.com/bacemkarray/transformer-playground)

A benchmark for parameter-efficient fine-tuning of a 7B language model on BBC XSum summarization. It compares LoRA and QLoRA across quality, training time, VRAM usage, and distributed training behavior.

**Why it matters:** This project explores how much task performance can be recovered while freezing almost all of a large model's parameters. It includes adapter-based fine-tuning, quantization, multi-GPU training, and ROUGE-L evaluation.

**Tech:** Python, PyTorch, Hugging Face, LoRA, QLoRA, Accelerate, ROUGE

---

### 3. [Agentic Hyperparameter Tuning](https://github.com/bacemkarray/agentic-hpt)

An autonomous hyperparameter tuning framework orchestrated with LangGraph. Parallel worker nodes tune individual neural-network hyperparameters while an LLM-powered coordinator analyzes results and decides whether to continue tuning or finalize training.

**Why it matters:** This project applies agentic control to a real ML workflow. It combines graph-based orchestration, experiment tracking, optimization, and LLM decision-making into a modular training pipeline.

**Tech:** Python, LangGraph, PyTorch, Optuna, MLflow, OpenAI API

---

### 4. [RAG From Scratch](https://github.com/bacemkarray/rag-from-scratch)

A minimal retrieval-augmented generation prototype built without high-level orchestration frameworks. It implements raw document parsing, chunking, embeddings, vector search, query rewriting, conversation memory, and response generation.

**Why it matters:** This project breaks RAG down to its core systems-level components. It gave me a clearer understanding of why frameworks like LangChain and LangGraph exist, and what architectural complexity they help manage.

**Tech:** Python, ChromaDB, sentence-transformers, OpenAI API, vector search

---

### 5. [ASL to English Translator](https://github.com/bacemkarray/asl-to-english-translator)

A real-time American Sign Language to English translation tool built during York University's CTRL+HACK+DEL hackathon. It uses computer vision and machine learning to detect ASL gestures and convert them into English text.

**Why it matters:** This project applies AI to accessibility-focused interaction. It combines real-time video processing, gesture recognition, and a simple user interface into a working hackathon prototype.

**Tech:** Python, OpenCV, MediaPipe, TensorFlow, Flask

---

# Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)  ![CMake](https://img.shields.io/badge/CMake-%23008FBA.svg?style=for-the-badge&logo=cmake&logoColor=white) ![nVIDIA](https://img.shields.io/badge/cuda-000000.svg?style=for-the-badge&logo=nVIDIA&logoColor=green) ![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white) ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![mlflow](https://img.shields.io/badge/mlflow-%23d9ead3.svg?style=for-the-badge&logo=numpy&logoColor=blue) ![Scipy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) 
