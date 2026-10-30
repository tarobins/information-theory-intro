# Information Theory: Foundations, Inference & Modern Applications
### *From Shannon Entropy and Channel Capacity to Information Geometry, Machine Learning & Computational Biology*

Welcome to **Information Theory: Foundations, Inference & Modern Applications**! Designed in the pedagogical spirit of Richard McElreath's *Statistical Rethinking*, this course bridges mathematical fundamentals, physical mental models, and from-scratch numerical simulation.

---

## 🚗 Twin Companion Architecture

The curriculum is organized into **two synchronized 1-to-1 parallel tracks**:

* 📖 **[Conceptual Track (`conceptual/`)](conceptual/README.md)**: A pure reading edition focusing on mental models, step-by-step mathematical reasoning, and physical intuition (The 20 Questions Game, The Economy of Codewords, The Rubber Metric of Probability Space, The Minimum Bias Rule, and The Sensory Bottleneck).
* 🐍 **[Python Laboratory (`python/`)](python/README.md)**: A hands-on computational lab manual implementing every algorithm, simulation, and theorem from scratch using `numpy`, `scipy`, and `matplotlib`.

---

## 📚 Master 12-Chapter Syllabus (`00`–`11`)

| Ch | Conceptual Track | Python Lab | Part | Core Topics & Key Concepts |
| :--- | :--- | :--- | :--- | :--- |
| **00** | **[Ch 00](conceptual/00_START_HERE.ipynb)** | **[Ch 00 (Python)](python/00_START_HERE.ipynb)** | Part I | The Nature of Surprise, Counting States, The Communication Model, Course Architecture |
| **01** | **[Ch 01](conceptual/01_self_information_and_shannon_entropy.ipynb)** | **[Ch 01 (Python)](python/01_self_information_and_shannon_entropy.ipynb)** | Part I | Axioms of Information (Additivity, Monotonicity), Self-Information $I(x)=-\log_2 p(x)$, Shannon Entropy $H(X)$, Binary Entropy Curve, Perplexity as Equivalent Fair Die |
| **02** | **[Ch 02](conceptual/02_source_coding_kraft_and_huffman.ipynb)** | **[Ch 02 (Python)](python/02_source_coding_kraft_and_huffman.ipynb)** | Part I | Prefix-free Codes, The Kraft-McMillan Inequality, Source Coding Theorem, Huffman Coding Algorithm, Arithmetic Coding Concept |
| **03** | **[Ch 03](conceptual/03_relative_entropy_and_kl_divergence.ipynb)** | **[Ch 03 (Python)](python/03_relative_entropy_and_kl_divergence.ipynb)** | Part II | Kullback-Leibler (KL) Divergence $D_\text{KL}(P \parallel Q)$, Gibbs' Inequality, Excess Description Cost, Cross-Entropy Loss, Asymmetry of KL (Forward vs Reverse) |
| **04** | **[Ch 04](conceptual/04_mutual_information_and_venn_geometry.ipynb)** | **[Ch 04 (Python)](python/04_mutual_information_and_venn_geometry.ipynb)** | Part II | Joint Entropy $H(X, Y)$, Conditional Entropy $H(X \mid Y)$, Mutual Information $I(X; Y)$, Information Venn Diagrams, Data Processing Inequality |
| **05** | **[Ch 05](conceptual/05_channel_capacity_and_blahut_arimoto.ipynb)** | **[Ch 05 (Python)](python/05_channel_capacity_and_blahut_arimoto.ipynb)** | Part III | Discrete Memoryless Channel (DMC), Channel Capacity $C = \max_{p(x)} I(X; Y)$, Binary Symmetric Channel (BSC), Binary Erasure Channel (BEC), Blahut-Arimoto Algorithm |
| **06** | **[Ch 06](conceptual/06_differential_entropy_and_continuous_limits.ipynb)** | **[Ch 06 (Python)](python/06_differential_entropy_and_continuous_limits.ipynb)** | Part III | Differential Entropy $h(X) = -\int f(x)\log f(x) dx$, Coordinate Transformations & Jacobian Penalty, Negative Differential Entropy, The Maximum Entropy of Gaussians |
| **07** | **[Ch 07](conceptual/07_the_principle_of_maximum_entropy_maxent.ipynb)** | **[Ch 07 (Python)](python/07_the_principle_of_maximum_entropy_maxent.ipynb)** | Part IV | E.T. Jaynes' MaxEnt Principle, Lagrange Multipliers for Moment Constraints, The Brandeis Dice Problem, Gibbs-Boltzmann Distribution, Derivation of Exponential and Gaussian Priors |
| **08** | **[Ch 08](conceptual/08_fisher_information_and_information_geometry.ipynb)** | **[Ch 08 (Python)](python/08_fisher_information_and_information_geometry.ipynb)** | Part IV | Score Function, Fisher Information Matrix $\mathcal{I}(\theta)$, Cramér-Rao Lower Bound, Fisher Metric as the Hessian of KL Divergence, Natural Gradient Descent |
| **09** | **[Ch 09](conceptual/09_rate_distortion_and_information_bottleneck.ipynb)** | **[Ch 09 (Python)](python/09_rate_distortion_and_information_bottleneck.ipynb)** | Part V | Rate-Distortion Theory $R(D)$, Mutual Information Trade-off, The Information Bottleneck Principle (Tishby), $\beta$-VAE as Rate-Distortion Optimization |
| **10** | **[Ch 10](conceptual/10_active_learning_and_experimental_design.ipynb)** | **[Ch 10 (Python)](python/10_active_learning_and_experimental_design.ipynb)** | Part V | Expected Information Gain (EIG), Lindley's 1956 Bayesian Experimental Design, Mutual Information as Acquisition Function, Flaky Test Culprit Localization Case Study |
| **11** | **[Ch 11](conceptual/11_applied_genomics_and_neural_coding.ipynb)** | **[Ch 11 (Python)](python/11_applied_genomics_and_neural_coding.ipynb)** | Part V | Information in the Genome, Position Weight Matrices (PWMs), Sequence Logos & Relative Entropy (Schneider 1990), Barlow's Efficient Coding Hypothesis in Sensory Neurons |

---

## 🚀 Getting Started

1. Open JupyterLab at your local instance.
2. Navigate to `information_theory_intro/conceptual/00_START_HERE.ipynb` to begin reading.
3. Open `information_theory_intro/python/00_START_HERE.ipynb` to run the interactive simulations side-by-side!
