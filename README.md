# NVIDIAGTC2026
As an AI integrator in Industrial automation, I am taking the opportunity of lifelong learning in Technology and Innovation. This project is created in purpose of NVIDIAGTC2026. The project is about GPU-accelerated HVAC anomaly detection using a PyTorch autoencoder. Detects faults and energy inefficiencies in real time on NVIDIA GPUs.

Project Overview:
Detect anomalies in HVAC energy usage using a GPU-accelerated autoencoder. Simulates building telemetry with common faults (coil fouling, damper stuck, sensor bias) and identifies inefficiencies automatically.

Why AI/ML:
The autoencoder learns normal HVAC patterns from multi-variable data and flags deviations using reconstruction error. Unsupervised learning detects subtle anomalies without labels, making it industrial-ready.

NVIDIA Involvement:
•	All training and inference run on CUDA-enabled GPUs via PyTorch for massive speedup on large datasets.
•	Demonstrates GPU-accelerated AI for real-time industrial monitoring, highlighting NVIDIA’s role in high-performance AI infrastructure.
•	Can scale to millions of telemetry points, showing the power of NVIDIA hardware in smart buildings, digital twins, and industrial automation.

Design Choices:
•	Synthetic dataset allows controlled fault injection and realistic scaling.
•	Feed-forward autoencoder is simple, interpretable, and effective.
•	Batch processing maximizes GPU throughput.
•	Visualization and energy waste estimation highlight practical business impact.

Potential Extensions:
•	Time-series LSTM autoencoder for sequential predictions
•	Root cause analysis with feature contributions
•	Integration with Omniverse digital twin simulations
•	Edge deployment on NVIDIA Jetson

Outcome:
A scalable, GPU-accelerated AI system for industrial HVAC anomaly detection demonstrates NVIDIA GPU impact and AI-powered energy efficiency.


