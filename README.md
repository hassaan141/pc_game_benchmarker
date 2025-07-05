# 🔧 GPU Performance Benchmarking Toolkit

This project benchmarks and visualizes the GPU temp and framerate performance of modern games across a custom-built PC with an RTX 2070, 16GB RAM, and i7-9700K CPU.

## 🖥️ Test Environment
- **GPU**: NVIDIA RTX 2070
- **CPU**: Intel i7-9700K
- **RAM**: 16GB DDR4
- **OS**: Windows 11 
- **Logging Tools**: MSI Afterburner + RivaTuner Statistics Server

## 🧪 Benchmarked Workloads
| Game/Test             | RTX | Notes |
|-----------------------|-----|-------|
| Unigine Heaven (Max)  | ❌  | Synthetic GPU stress test |
| CS2 (Benchmark map)   | ❌  | CPU-bound FPS benchmarking |
| Minecraft (RTX ON)    | ✅  | Path-traced lighting using RTX |

## 📈 Metrics Collected
- FPS (Framerate)
- GPU temperature (°C)
- GPU usage (%)
- GPU power draw (Watts)
- CPU usage (optional)

## 📊 Visualizations
Graphs generated using Python:
- `scripts/graph_temp_vs_framerate.py`

See the `graphs/` folder for side-by-side comparisons.

## 📜 Sample Graph
![GPU Temp vs FPS](graphs/heaven_fps_temp.png)

## ⚙️ Automation


## 🔮 Future Work
- Add DLSS comparison for supported games
- Compare to Linux runs
- - `scripts/automate_windows.py`: Automates Unigine Heaven with pyautogui
