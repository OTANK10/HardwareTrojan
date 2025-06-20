Hardware Trojan Detection using Unsupervised Learning and Simulation-Based Side-Channel Features

* Overview
This project presents a groundbreaking methodology for detecting hardware Trojans in integrated circuits using machine learning techniques applied to simulation-based side-channel features. Our approach eliminates the dependency on golden reference models, addressing a critical limitation in real-world supply chain security scenarios.

*Key Achievements
90% detection accuracy without golden references
Detection of subtle Trojans affecting only 2-5% of circuit logic
Real-time monitoring potential with low resource overhead

*Features
Simulation-Based Detection: Extract behavioral features from Quartus Prime and ModelSim simulations
Multiple Feature Types: Toggle counts, timing patterns, and Hamming weight analysis
Unsupervised Learning: PCA-based dimensionality reduction with K-Means and DBSCAN clustering
Comprehensive Circuit Support: Counters, combinational logic, and complex pipeline structures
Automated Pipeline: Streamlined workflow from Verilog to detection results

*Detection Performance by Circuit Type
4-bit Counter: 93.5% accuracy
Combinational Multiplier: 60% accuracy
Adder Chain: 57% accuracy

*Prerequisites
Intel Quartus Prime (20.1.1 or later)
ModelSim-Altera (2020.1 or later)
Python 3.8+
Required Python packages:

bashpip install -r requirements.txt
