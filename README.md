# Analyzing the Effect of Link Recommenders in Degree Inequality

📄 [**Download Paper (PDF)**](https://github.com/tripledoubleE/NetSci25/blob/main/Analyzing_the_Effect_of_Link_Recommenders_in_Degree_Inequality.pdf)  
📧 Contact: [e.e.erdem@uva.nl](mailto:e.e.erdem@uva.nl)

---

## 🔍 Overview

This project investigates how different **link recommendation algorithms** affect **degree inequality** in social networks, specifically focusing on the **fairness vs. performance trade-off**.

We evaluate:
- Structural similarity methods: *Common Neighbors, Adamic-Adar, Resource Allocation, Cosine, Jaccard, PageRank*
- Latent factor models: *DeepWalk, Node2vec, GCN, GAE, GVAE, GraphSAGE*

across two datasets:
- **Twitter** (directed, time-split)
- **Facebook (Amherst41)** (undirected, degree-preserving split)

---

## 📊 Key Findings

- Structural similarity methods **amplify popularity bias** and yield **lower fairness** (high Gini index).
- Graph-based latent factor models (e.g. **GAE, VGAE, GCN**) achieve **higher precision with improved fairness**.
- The trade-off is dataset-dependent, but **graph neural models consistently strike a better balance**.

---


## 📬 Contact

For questions or collaboration, feel free to reach out:  
📧 **e.e.erdem@uva.nl**
