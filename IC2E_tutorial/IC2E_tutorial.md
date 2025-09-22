**Target audience**

Quite broad: data scientists, engineers, researchers and practitioners. We need to make it interesting for the cloud computing community.

Potential uses of synthetic data in cloud computing services:

- Data sharing, internal and external,  
- ~~Cloud migration: sensitivity of data adds a layer of complexity to migration,~~   
- Cloud enablement: run cloud services on synthetic data.  
- Data retention: being able to keep the data for longer than what the law allows with real sensitive data.

**Submitted Structure with some tweaks**

—--------------- Introductory talk, 45m \+ QA —----------------------------  
**1\. Introduction to Tabular Synthetic Data**

- Definition and Motivation  
- A spectrum of approaches: random, handcrafted, rule-based, and AI-generated  
- Real-world use cases mapped to each type (e.g., testing, simulation, knowledge

transfer)

- Mock data (generate with an LLM for example)  
- Simulation (like engine failure events)  
- Knowledge transfer?  
- Discussion of blurred boundaries between categories (e.g., LLM-based data generation  
  as both AI and “random”, use of rule-based synthetic data as training data for foundational models)  
- Pre-trained foundational model vs learning from scratch vs. rule-based (old style).  
  - Address scalability here.


**2\. Focus on AI-Generated Synthetic Data**

- High-level explanation of density estimation as a foundation  
- Taxonomy of deep generative models and how they approach synthetic data generation  
- Examples from recent literature and open-source implementations 

**3\. The TabularARGN Framework**

- Introduction to the TabularARGN model family  
- Capabilities: flat tables, sequential records, and multi-table setups  
- Integration of LLMs for modeling text columns in tabular datasets  
- A snippet on our SDK

QA  
—-----------—-----------—-----------—-----------—-----------—-----------—-----------—------------  
Maybe a short 5 minutes break here? Ask?  
—------------------------------------ 1 hour —------------------—-----------—-----------—------------  
**4\. Hands-On Part 1: Data Generation and Quality Assessment**

- Walkthrough of generating synthetic tabular data  
- Exploring key generation parameters  
- Using the Synthetic Data SDK’s built-in quality assurance reports to evaluate fidelity  
- Briefly introduce evaluation metrics  
- Synthetic data as a drop-in replacement (TSTR evaluation)  
- **~~Explainability enabler~~**~~: Using synthetic data for model interpretation in the absence of original data~~ 

—-----------—-----------—-----------—-----------—-----------—-----------—-----------—------------

Coffee break

—------------------------------------ 1 hour and a half —------------------—-----------—--------  
Finish previous session if needed.

**7\. ~~Advanced~~ ML Use Cases**

- **Upsampling and data augmentation**: Conditioning on minority groups or value combinations  
- **Extrapolation**: Generating plausible combinations never seen during training  
- **Imputation**: Using SD models for smart imputation across missing features  
- **Hands-On Part 4**: Guided mini-challenges for each technique (time permitting)

**5\. Privacy-Preserving Data Sharing**

- Why synthetic data matters for secure data collaboration (e.g., data clean rooms)  
  - Real world motivation: MIMIC dataset?, health-care dataset?  
- Overview of privacy protection mechanisms (data minimization, differential privacy, empirical leakage tests)  
- **Hands-On Part 2**: Exploring privacy metrics and safe data sharing workflows

**9\. Wrap-Up and Discussion**

- Recap of key takeaways  
- Open Q\&A  
- Pointers to further resources, documentation, and community tools

—-----------—-----------—-----------—-----------—-----------—-----------—-----------—------------

**~~6\. Machine Learning Use Cases~~**

- **~~Model portability~~**~~: Synthetic data as a drop-in replacement (TSTR evaluation)~~  
- **~~Explainability~~**~~: Using synthetic data for model interpretation in the absence of original data~~  
- **~~Hands-On Part 3~~**~~: TSTR analysis and SHAP-based model explanation~~

Extra if time permits:

**8\. Fairness and Responsible AI**

- Generating “fair” synthetic datasets (e.g., ensuring statistical parity)  
- Effects on downstream-model fairness  
- **Hands-On Part 5 (Optional)**: Generating and analyzing fairness-aware synthetic data

- 

**References**

[https://research.aimultiple.com/synthetic-data-use-cases/](https://research.aimultiple.com/synthetic-data-use-cases/)  
[https://www.youtube.com/watch?v=Qs-0zXeE9J4](https://www.youtube.com/watch?v=Qs-0zXeE9J4)  
