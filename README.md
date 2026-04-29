# NUMA-Simulator
NUMA Simulator is an interactive web-based tool designed to help students and developers understand how NUMA (Non-Uniform Memory Access) systems work.

The simulator models multiple nodes, each with its own memory and processes. It generates memory access requests and classifies them as:
- Local Access (fast)
- Remote Access (slow)

The system then visualizes:
- Memory blocks per node
- Process allocation
- Real-time access behavior
- Performance statistics and latency
- Distribution charts using Chart.js

Features:
- Configurable number of nodes, processes, memory, and requests
- Real-time simulation with adjustable speed
- Step-by-step execution support
- Visual highlighting of memory accesses (green = local, red = remote)
- Live statistics (total accesses, latency, local vs remote)
- Graphical distribution of memory access patterns

Tech Stack:
- HTML (UI structure) :contentReference[oaicite:0]{index=0}
- CSS (modern dark UI design & animations) :contentReference[oaicite:1]{index=1}
- JavaScript (simulation logic & visualization) :contentReference[oaicite:2]{index=2}
- Chart.js (data visualization)

Purpose:
This project is useful for learning operating system concepts such as NUMA architecture, memory latency, and process scheduling behavior.

Future Improvements:
- Advanced scheduling algorithms
- Memory allocation strategies
- Real-world workload simulation
- Exportable performance reports
