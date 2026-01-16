<div align="center">

# 🧬 Evolution Simulation

### *Artificial Life Through Neural Networks & Genetic Algorithms*

[![Unity](https://img.shields.io/badge/Unity-2021.3+-black?style=for-the-badge&logo=unity)](https://unity.com/)
[![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)](https://docs.microsoft.com/en-us/dotnet/csharp/)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

*Watch digital organisms evolve, adapt, and compete for survival in real-time*

[Getting Started](#-getting-started) • [Features](#-features) • [Results](#-evolution-results) • [Customization](#-customization)

</div>

---

## 🌟 Overview

A sophisticated Unity-based evolution simulator that brings artificial life to your screen. This project demonstrates how simple organisms can develop complex survival behaviors through the power of evolutionary algorithms and neural networks—no manual programming of behavior required.

**What makes this special:**
- Organisms learn to survive purely through evolution
- Neural networks emerge naturally through genetic selection
- Visual, real-time demonstration of natural selection
- Highly customizable evolution parameters

---

## ✨ Key Features

### 🤖 **Intelligent Agents**
- Sensor-driven organisms that perceive their environment
- Neural network-based decision making
- Adaptive behavior emerging from evolution

### 🧬 **Genetic Evolution**
- Genome-based heredity system
- Mutation and crossover mechanisms
- Fitness-based natural selection
- Multi-generational evolution tracking

### 📊 **Real-Time Visualization**
- Live population dynamics
- Generation-by-generation tracking
- Visual genome distribution analysis
- Performance metrics dashboard

### ⚙️ **Customizable Parameters**
- Adjustable mutation rates
- Configurable neural network architecture
- Flexible fitness criteria
- Variable population sizes

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| **Game Engine** | Unity 2021.3+ |
| **Programming Language** | C# |
| **AI Techniques** | Neural Networks, Genetic Algorithms |
| **Physics** | Unity Physics Engine |
| **Concepts** | Artificial Life, Evolutionary Computation |

---

## 🚀 Getting Started

### Prerequisites

```bash
✓ Unity Hub (Latest Version)
✓ Unity Editor 2021.3 or later
✓ Basic understanding of Unity interface (optional)
```

### Installation & Running

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ayushpremrocks/Evolution-Simulation.git
   cd Evolution-Simulation
   ```

2. **Open in Unity**
   - Launch Unity Hub
   - Click "Add" → Select the cloned project folder
   - Open the project

3. **Run the simulation**
   - Navigate to `Assets > Scenes > SampleScene.unity`
   - Press the ▶️ **Play** button
   - Watch evolution in action!

---

## 🧠 Core AI Concepts

### 🔬 Genetic Algorithms
Implements natural selection through:
- **Selection**: Fittest organisms reproduce more
- **Mutation**: Random genetic variations
- **Crossover**: Combining parent genomes
- **Elitism**: Preserving top performers

### 🧪 Neural Networks
Small but effective networks that:
- Process sensory inputs
- Make movement decisions
- Evolve through generations
- Emerge without manual training

### 📈 Fitness-Based Evolution
Survival criteria determine reproduction:
- Position-based fitness (e.g., "stay in top half")
- Performance tracking across generations
- Adaptive pressure shapes behavior

---

## 🔧 Customization Guide

Modify these files to experiment with evolution:

| File | Purpose | Key Parameters |
|------|---------|----------------|
| `Globals.cs` | Global settings | Population size, generation length |
| `NeuralNet.cs` | Network architecture | Layer sizes, activation functions |
| `NextGen.cs` | Evolution logic | Mutation rate, selection pressure |
| `Input_sensors.cs` | Sensing | Sensor types, range |
| `Output_sensors.cs` | Actions | Movement, behavior outputs |

### Example: Adjusting Mutation Rate
```csharp
// In NextGen.cs
public float mutationRate = 0.05f; // Try values between 0.01 - 0.2
```

---

## 📊 Evolution Results

### Experiment 1: Complex Genomes (20 genes × 6 bits)

#### Generation 0 - Random Distribution
<img src="https://github.com/user-attachments/assets/979fd483-b5dc-4d96-a85a-b6cd23036102" width="600" alt="Generation 0">

*Initial population with completely random genomes.*

---

#### Generation 100 - Selection Pressure
<img src="https://github.com/user-attachments/assets/6c534ea9-6bae-43e9-9e7a-cb80a7632380" width="600" alt="Generation 100">

*Clustering begins as successful patterns emerge.*

---

#### Generation 300 - Convergence
<img src="https://github.com/user-attachments/assets/a72ea656-b0f1-4114-8cec-069641f53aae" width="600" alt="Generation 300">

*Two dominant genome types emerged and stabilized.*

#### 🧬 Dominant Genomes Identified

After 300 generations, the population converged to two primary genetic patterns:

**Genome Type A:**
```
18F9F1DC0D6A280E291F48D00AF89A2A842D1FBA94D8ED66E4E10F746A40C0E1
67D90F8E922B60DE04507C548921678317E2C81A6B49969091B36955
```

**Genome Type B:**
```
6FA7DACB34B31D5D70D0A6ED8F41AEF3F57DB828E3D78B0C8DABEA5BC8A915C0
140714DA91D35208A358FFF0B7CE9424282F6460BCC98D153DA9CFCD
```

**Insight:** Longer genomes (120 bits) allowed for greater genetic diversity, resulting in multiple successful survival strategies coexisting.

---

### Experiment 2: Simple Genomes (6 genes)

#### Generation 0 - Starting Point
<img src="https://github.com/user-attachments/assets/2ab62e7f-0efa-4b7f-8303-c56a17264575" width="600" alt="Gen 0 Simple">

*Small genome experiment begins with random distribution.*

---

#### Generation 70 - Complete Homogeneity
<img src="https://github.com/user-attachments/assets/5f00ce41-f861-4afb-bad3-fbe9468e8aae" width="600" alt="Gen 70 Simple">

*Single optimal genome dominates entire population.*

#### 🧬 Final Dominant Genome
```
DB5BFEEBAE209C0D811FDE2225BC4BD5A92E
```

**Insight:** Shorter genomes (36 bits) led to faster convergence but less diversity. A single "perfect" solution quickly dominated due to limited genetic search space.

---

## 🎯 Key Takeaways

| Genome Complexity | Convergence Speed | Final Diversity | Use Case |
|------------------|-------------------|-----------------|----------|
| **Simple (6 genes)** | Fast (~70 gen) | Low (1 type) | Quick experiments |
| **Complex (20 genes)** | Slow (~300 gen) | High (2+ types) | Realistic evolution |

---

## 🗺️ Future Enhancements

- [ ] Multi-objective fitness functions
- [ ] Predator-prey ecosystems
- [ ] Sexual reproduction simulation
- [ ] Machine learning integration
- [ ] 3D environment support
- [ ] Real-time genome visualization
- [ ] Export evolution data to CSV

---

## 📚 References & Inspiration

- [Genetic Algorithms in Plain English](https://www.youtube.com/watch?v=9zfeTw-uFCw)
- [NEAT: NeuroEvolution of Augmenting Topologies](http://nn.cs.utexas.edu/downloads/papers/stanley.ec02.pdf)
- [The Bibites - Digital Life Simulation](https://www.youtube.com/c/TheBibitesDigitalLife)

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs via Issues
- Suggest new features
- Submit pull requests
- Share your evolution experiments

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

<div align="center">

**Ayush Prem**

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://ayushpremrocks.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayushpremrocks/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ayushpremrocks)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ayushprempersonal@gmail.com)

*Building the future, one simulation at a time* 🚀

</div>

---

<div align="center">

### ⭐ Star this repo if you found it interesting!

**Made with ❤️ and lots of evolution**

</div>
