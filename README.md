# 🚀 Y24-Orbit-Simulation

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)](https://github.com/yourusername/Y24-Orbit-Simulation)
[![NASA Data](https://img.shields.io/badge/Data-NASA%20Ephemeris-red.svg)](https://ssd.jpl.nasa.gov/)

A sophisticated **three-body orbital simulation** that models the gravitational interactions between the Sun, Earth, and asteroid 2024YR4 using real NASA ephemeris data. This project demonstrates advanced orbital mechanics and numerical integration techniques.

## 🌟 Features

- **🔬 Three-Body Gravitational Simulation**: Complete N-body physics simulation
- **📊 Real NASA Data Integration**: Uses actual ephemeris data from JPL
- **🎯 Error Analysis**: Compares simulation results with real orbital data
- **📈 3D Visualization**: Interactive 3D plotting of orbital trajectories
- **⚙️ Parameter Tuning**: Adjustable masses, distances, and time steps
- **📋 RMSE Validation**: Root Mean Square Error calculation for accuracy assessment

## 🛠️ Technologies Used

- **Python 3.8+** - Core programming language
- **NumPy** - Numerical computations and array operations
- **Matplotlib** - 3D plotting and visualization
- **Pandas** - Data manipulation and analysis
- **Jupyter Notebook** - Interactive development environment

## 📦 Installation

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Y24-Orbit-Simulation.git
   cd Y24-Orbit-Simulation
   ```

2. **Install dependencies**
   ```bash
   pip install numpy matplotlib pandas jupyter
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Open the simulation**
   - Navigate to `src/Simulation.ipynb`
   - Run all cells to execute the simulation

## 🎮 Usage

### Basic Simulation

The main simulation runs a three-body gravitational simulation with:
- **Sun** (mass: 1.9885×10³⁰ kg)
- **Earth** (mass: 5.9722×10²⁴ kg)
- **Asteroid 2024YR4** (mass: 1×10¹⁴ kg)

### Parameter Experiments

The notebook includes several parameter studies:

1. **Asteroid Mass Variation** - Testing different asteroid masses
2. **Solar Mass Variation** - Exploring effects of changing Sun's mass
3. **Distance Multiplier** - Adjusting gravitational distance scaling

### Output Analysis

Each simulation provides:
- **3D trajectory plots** for all celestial bodies
- **RMSE calculations** comparing simulation vs. NASA data
- **Real-time error tracking** throughout the simulation

## 📊 Data Sources

The simulation uses real ephemeris data from NASA's Jet Propulsion Laboratory:

- **Sun ephemeris**: `data/sun.txt`
- **Earth ephemeris**: `data/earth.txt`
- **Asteroid 2024YR4 ephemeris**: `data/2024YR4.txt`
- **Additional Earth data**: `data/Earth_data.csv`

## 🔬 Physics Implementation

### Gravitational Force Calculation

The simulation implements Newton's law of universal gravitation:

```
F = G × (m₁ × m₂) / r²
```

Where:
- **G** = Gravitational constant (6.67430×10⁻²⁰ km³/kg·s²)
- **m₁, m₂** = Masses of interacting bodies
- **r** = Distance between bodies

### Numerical Integration

Uses **Euler integration** method with configurable time steps:
- Default time step: 24 hours (86400 seconds)
- Maximum simulation time: ~5 years
- Real-time position and velocity updates

## 📈 Results

### Accuracy Metrics

- **Baseline RMSE**: ~3.1 million km
- **Parameter sensitivity analysis** included
- **Real vs. simulated trajectory comparison**

### Visualization Features

- **Color-coded trajectories**:
  - 🟡 Gold: Sun
  - 🔵 Cyan: Earth
  - 🟣 Purple: Simulated Asteroid
  - 🔴 Red: Real Asteroid (NASA data)
- **3D interactive plots**
- **Error analysis graphs**

## 🧪 Experiments

### Mass Variation Studies

1. **Asteroid Mass**: 1×10¹⁴ kg → 4.5×10²⁷ kg
2. **Solar Mass**: 1.9885×10³⁰ kg → 2.5×10³⁰ kg / 1.3×10³⁰ kg

### Distance Scaling

- **Distance multiplier**: 1.0 → 1.1
- **Gravitational force scaling** effects

## 🤝 Contributing

We welcome contributions! Please feel free to:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

## 📝 License

This project is licensed under the Apache 2.0 License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

- **Project Link**: [https://github.com/Yousinator/Y24-Orbit-Simulation](https://github.com/Yousinator/Y24-Orbit-Simulation)
- **Issues**: [GitHub Issues](https://github.com/Yousinator/Y24-Orbit-Simulation/issues)

---

<div align="center">

**Made with ❤️ by Yousinator**

</div>
