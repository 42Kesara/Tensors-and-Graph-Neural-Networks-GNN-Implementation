📊 Tensors and Graph Neural Networks (GNNs) - Deep Dive into Graph-based Learning
Welcome to our project on Tensors and Graph Neural Networks (GNNs)! This repository contains our group assignment for the Tensors and Graphs course, where we explore the theory, implementation, and applications of tensors and GNNs in machine learning.

🚀 Project Overview
Tensors serve as the fundamental data structures for representing high-dimensional data in machine learning, while Graph Neural Networks (GNNs) allow us to learn from graph-structured data effectively. We apply GNNs to analyze relationships in the Cora dataset of scientific publications.

🔍 Key Features
Tensor Operations: Essential operations with tensors, using PyTorch and TensorFlow.
Graph Neural Network Implementation: Implementation of key GNN architectures such as Graph Convolutional Networks (GCNs) and Graph Attention Networks (GATs).
Cora Dataset Analysis: Node classification and link prediction tasks on the Cora dataset, utilizing GNNs for insightful analysis.

🛠️ Technologies
Libraries: PyTorch, TensorFlow
Data: Cora citation dataset with node-level and edge-level features
Core Models: GCN, GAT, GraphSAGE, GIN

📂 Repository Structure
plaintext
Copy code

📦 GNN-Project
├── 📁 data/         # Cora dataset and preprocessing scripts
├── 📁 models/       # GNN model architectures
├── 📁 results/      # EDA, results, and model outputs
├── 📄 README.md     # Project documentation
└── 📄 Report.pdf    # Detailed project report

📈 Methodology
Data Processing: Loading and exploring the Cora dataset.
Model Development: Implementing GNN architectures for node classification and link prediction.
Training & Evaluation: Training GNNs with tensor operations and analyzing their performance.

📊 Results
Our experiments show that:
GCNs perform well on node classification tasks.
GATs excel in adaptive weighting, improving performance on heterogeneous graphs.
For details, check out our full Report.

📊 Results Screenshot
![1](https://github.com/user-attachments/assets/3fe1274d-2977-4169-bd23-d965dfc07b77)
![2](https://github.com/user-attachments/assets/3bc31e4b-6b8e-4264-a759-0ee2878e324c)
![3](https://github.com/user-attachments/assets/58c76847-6f73-4168-8922-5560334ac223)
![5](https://github.com/user-attachments/assets/b33f7adc-bceb-451e-bcd9-ee0ad025163c)
![6](https://github.com/user-attachments/assets/8755b209-59dd-43c3-957e-7c2b12839c9b)


📅 Future Work
In future iterations, we plan to:
Implement dynamic graphs for real-time data updates.
Explore GNN scalability on larger datasets.
Apply GNNs to other domains such as molecular chemistry and social network analysis.

👥 Team
Kesara Lakpriya
G.M. Chathura Samarajeewa
Y.M. Weerathunga

📜 References
Deep Learning with PyTorch, by Stevens et al.
Graph Neural Networks: Foundations, Frontiers, and Applications, by Wu et al.
🌟 Contributing
Want to contribute? Fork the repository, submit issues, or open a pull request. We'd love to hear your thoughts and improvements!
