**🧠 BuildABrain: Synthetic Intelligence**
An exploratory project focused on the fundamentals of neural architecture, hardware-software co-design, and the compute infrastructure required for large-scale AI.

**🚀 Project Vision**
To bridge the gap between foundational neural networks and "Copilot-class" intelligence. This repository documents my journey from basic image classification to understanding the massive-scale distributed training required for NVIDIA Hopper (H100) clusters.

**🛠 Tech Stack (Current Implementation)**
*Framework:* Keras / TensorFlow (Sequential API)
*Model Type:* Multi-layer Perceptron (MLP) for Categorical Classification
*Hardware Acceleration:* NVIDIA T4 Tensor Core GPUs (via Google Colab)
*Dataset:* Fashion-MNIST (28x28 pixel grayscale images)

**📖 Key Concepts Explored**
*Data Transformation:* Implementing Flatten layers to convert multidimensional image data into 1D input tensors.
*Categorical Logic:* Mapping linear outputs (y = mx + b) to 10-neuron Dense layers for multi-class classification.
*Hardware Benchmarking:* Profiling model performance on NVIDIA consumer vs. enterprise-grade silicon.

**📈 Future Roadmap (Large-Scale LLM)**
As this project scales toward a code-specialized "Brain," I am researching:
*Optimization:* transitioning to DeepSpeed and FlashAttention-2 for memory efficiency.
*Distributed Training:* Understanding the cost-optimization of pre-training on 8-GPU H100/B200 nodes.
*Custom Kernels:* Exploring CUDA kernel optimization for transformer-based architectures.

**⚖️ License**
This project is licensed under the MIT License.
