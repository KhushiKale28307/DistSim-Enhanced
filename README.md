# 🚀 DistSim – Distributed Systems Simulator

> An interactive 3D Distributed Systems Architecture Simulator for designing, visualizing, and testing modern distributed systems with real-time traffic simulation, chaos engineering, and hardware-aware performance modeling.

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![Three.js](https://img.shields.io/badge/Three.js-r128-black)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-CDN-blue)

---

# 📖 Overview

DistSim is a browser-based simulator that enables users to build distributed system architectures using drag-and-drop components such as:

- Load Balancers
- API Gateways
- Firewalls
- Kubernetes Pods
- Servers
- SQL Databases
- NoSQL Databases
- Redis Cache
- CDN
- Object Storage
- Message Queues

The simulator visualizes request routing, system performance, node failures, replication, cache behavior, and network traffic in a real-time 3D environment.

---

# ✨ Features

## 🖥 Interactive Architecture Builder

- Drag & Place Infrastructure Components
- Connect Nodes Visually
- Delete and Modify Components
- Save Architecture Designs
- Export Architecture as JSON

---

## 🌐 Real-Time Traffic Simulation

Supports multiple traffic types:

- READ
- WRITE
- SEARCH
- STATIC
- UPLOAD
- MALICIOUS

Visual packet animation demonstrates request flow through the architecture.

---

## ⚙ Hardware-Aware Simulation

Choose realistic infrastructure models including:

### NVIDIA

- H200
- H100
- A100
- RTX 4090
- L40S

### Apple

- M3 Ultra
- M3 Max
- M3 Pro
- M2 Ultra

### AWS

- EC2 Compute
- GPU Instances
- RDS
- ElastiCache
- ALB

### Google Cloud

- Compute Engine
- TPU
- GPU Instances

### Microsoft Azure

- HPC
- GPU Nodes

### Bare Metal

- AMD EPYC
- Intel Xeon
- Ampere Altra

Performance is automatically derived from:

- CPU Cores
- GPU TFLOPS
- Memory Bandwidth
- RAM
- Network Speed
- Disk Throughput

---

## 📊 Live Metrics Dashboard

Displays:

- Requests Per Second
- Processed Requests
- Failures
- p99 Latency
- Active Partitions
- Pipeline Health
- Architecture Cost
- SLA Success Rate
- Connection Count

---

## 🗄 Data Replication Simulator

Implements simplified eventual consistency.

Features include:

- Primary Database
- Replica Databases
- Replication Delay
- Replica Lag
- Stale Reads
- Cache Hits
- Cache Misses
- Replication Monitoring

---

## ⚡ Chaos Engineering

Inject failures into the system:

- Node Crash
- Network Partition
- Traffic Spike
- Cascading Failure
- DDoS Simulation

Observe:

- Failure propagation
- Replica synchronization
- Recovery behavior
- SLA degradation

---

## 🔍 Node Inspector

Inspect every node in real time.

View:

- CPU Load
- Queue Depth
- Errors
- Health Status
- Processed Requests

---

## 🎮 Interactive Controls

Keyboard Shortcuts:

| Key | Action |
|------|--------|
| S | Select Tool |
| C | Connect Tool |
| Delete | Delete Node |
| ESC | Cancel Current Action |
| Space | Pause/Resume Simulation |

---

# 🏗 Architecture Components

- Internet
- Load Balancer
- Firewall
- API Gateway
- Queue
- Server
- Kubernetes Pod
- SQL Database
- NoSQL Database
- Redis Cache
- CDN
- Storage

---

# 🛠 Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Three.js
- Tailwind CSS
- Google Fonts
- Canvas API

No backend is required.

Runs entirely inside the browser.

---

# 📁 Project Structure

```
DistSim/
│
├── index.html
├── README.md
│
├── CSS
│   └── Embedded Styles
│
├── JavaScript
│   ├── Simulation Engine
│   ├── Rendering Engine
│   ├── Traffic Generator
│   ├── Replication Engine
│   ├── Hardware Database
│   ├── Chaos Engine
│   ├── Metrics Dashboard
│   └── UI Controls
│
└── Assets
```

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/yourusername/distsim.git
```

## Open Project

Simply open:

```
index.html
```

in any modern browser.

No installation required.

---

# 🌍 Browser Support

- Google Chrome ✅
- Microsoft Edge ✅
- Firefox ✅
- Brave ✅

---

# 📈 Simulation Workflow

```
Internet
      │
      ▼
Load Balancer
      │
      ▼
API Gateway
      │
      ▼
Firewall
      │
      ▼
Servers / Kubernetes
      │
      ▼
Cache
      │
      ▼
Database
      │
      ▼
Storage
```

---

# 📊 Performance Metrics

The simulator tracks:

- Throughput
- Latency
- Queue Length
- Packet Loss
- Replica Consistency
- Cache Efficiency
- CPU Utilization
- Network Partitions
- Failure Rate
- Architecture Cost

---

# 🎯 Educational Objectives

DistSim helps students understand:

- Distributed Systems
- Load Balancing
- Eventual Consistency
- Database Replication
- Cache Coherency
- Kubernetes
- Cloud Infrastructure
- Chaos Engineering
- CAP Theorem
- Fault Tolerance

---

# 🔮 Future Improvements

- Raft Consensus Algorithm
- Paxos Consensus
- Docker Containers
- Kubernetes Cluster Autoscaling
- Prometheus Metrics
- Grafana Dashboard
- Multi-Region Deployment
- Service Mesh
- gRPC Simulation
- Kafka Topic Visualization
- Redis Cluster
- PostgreSQL Replication
- AI-based Auto Scaling
- Failure Prediction using Machine Learning

---

# 📸 Screenshots

Add screenshots of:

- Main Menu
- Architecture Builder
- Traffic Simulation
- Chaos Engineering
- Metrics Dashboard
- Node Inspector

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

# 📜 License

This project is released under the MIT License.

---

# 👨‍💻 Authors

Developed as an academic project on **Distributed Systems & Parallel Processing**.

Contributors:
- Team Members
1.Sanika
2.Ratnadeep
3.Siddharth
---

# ⭐ Acknowledgements

- Three.js
- Tailwind CSS
- Cloudflare CDN
- NVIDIA
- AWS
- Google Cloud
- Microsoft Azure

---

## 💡 Project Goal

To provide an interactive platform where students and developers can design distributed architectures, simulate real-world workloads, observe failures, and understand system behavior through visual experimentation.
