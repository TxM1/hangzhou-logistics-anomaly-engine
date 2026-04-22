#  Hangzhou Smart-Logistics Anomaly Engine (2026)

### **Executive Summary**
In the high-density delivery environment of 2026 Hangzhou, manual oversight of logistics bottlenecks is impossible. This project implements a **Real-time Anomaly Detection Pipeline** designed to identify delivery latency spikes in key districts (Xihu, Binjiang, etc.) using statistical ML.

### **Tech Stack**
* **Language:** Python 3.10+
* **Libraries:** Pandas (Data Engineering), NumPy (Mathematical Modeling), Matplotlib (Visualization)
* **Deployment:** Google Colab / GitHub Integrated Workflow

### **The Engine Logic**
The system monitors a high-velocity stream of delivery timestamps and applies a **Z-Score Anomaly Detection** model. By calculating the standard deviation of delivery times per district, it automatically flags outliers ($Z > 2.5$) that indicate traffic congestion or warehouse failures.

### **Business Value**
* **Proactive Mitigation:** Identifies "Black Swan" delivery delays before customer SLAs are breached.
* **Data-Driven Decisions:** Provides logistics managers with a clear heatmap of district performance.
