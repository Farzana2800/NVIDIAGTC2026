# NVIDIAGTC2026
As an AI integrator in Industrial automation, I am taking the opportunity of lifelong learning in Technology and Innovation. This project is created in purpose of NVIDIAGTC2026. The project is about GPU-accelerated HVAC anomaly detection using a PyTorch autoencoder. Detects faults and energy inefficiencies in real time on NVIDIA GPUs.

Project Overview:
This project aims to detect anomalies used throughout in Building Automation in HVAC energy usage through a GPU-accelerated autoencoder model. It simulates large-scale building telemetry data and injects common HVAC faults such as coil fouling, stuck dampers, airflow restrictions, and sensor bias. The model automatically identifies operational inefficiencies by learning normal system behavior and flagging deviations.

Why AI/ML:
The autoencoder learns normal HVAC operational patterns from multi-variable telemetry data and identifies abnormalities using reconstruction error. Because the approach is unsupervised, it does not require labeled fault data. This makes the solution highly practical and industrial-ready, where labeled anomaly datasets are often unavailable. The model can detect subtle performance degradation that traditional rule-based systems may miss.

NVIDIA Involvement:
• All model training and inference run on CUDA-enabled NVIDIA GPUs using PyTorch.
• Demonstrates GPU acceleration for large-scale industrial telemetry processing.
• Benchmarks CPU vs GPU performance to highlight NVIDIA’s computational advantage.

Design Choices:
• Synthetic dataset enables controlled fault injection and realistic large-scale simulation.
• Feed-forward autoencoder architecture balances simplicity, interpretability, and performance.
• Standardized preprocessing ensures stable neural network training.
• Large batch sizes maximize GPU throughput.
• Visualization of reconstruction error clearly highlights anomaly thresholds.
• Energy deviation patterns simulate real HVAC inefficiencies for practical relevance.

Potential Extensions:
• Time-series LSTM or Transformer-based autoencoder for sequential modeling
• Root cause analysis using feature-level contribution scoring
• Integration with NVIDIA Omniverse for digital twin simulation
• Edge deployment on NVIDIA Jetson devices for on-site monitoring

Outcome:
This project presents a scalable, GPU-accelerated AI system for industrial HVAC anomaly detection. It demonstrates how NVIDIA GPU technology enables high-performance, real-time AI monitoring for energy efficiency and predictive maintenance in industrial automation environments.
