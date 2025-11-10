# Dhruv Patel  
**Email:** dhp005@ucsd.edu  
**Section:** B15  
**Mentor:** Prof. Yu-Xiang Wang  

---

**Q1. What is the most interesting topic covered in your domain this quarter?**  
The most interesting topic covered in my domain this quarter has been *Private Evolution* — specifically, how differential privacy can be integrated into generative and learning processes to produce synthetic data that still maintains statistical utility. I found it fascinating how small, controlled amounts of noise can protect individual-level information while still enabling useful model outputs. Understanding the theoretical trade-offs between privacy loss (ε) and data fidelity gave me a much deeper appreciation for the balance between ethical data sharing and model performance. This topic directly connects privacy theory with practical data science applications, which makes it both conceptually rich and highly relevant to modern AI systems.

---

**Q2. Describe a potential investigation you’d like to pursue for your Quarter 2 Project.**  
For the next quarter, I would like to investigate how generating differentially private synthetic data affects downstream analyses — particularly how the quality and usability of the generated dataset change as the privacy budget varies. My idea is to take a real clinical dataset (such as SUPPORT2) and produce multiple synthetic versions using various privacy mechanisms like the Laplace mechanism, Gaussian noise addition, and DP-GANs. I want to evaluate how these techniques influence correlation structure, predictive accuracy, and overall data utility. The goal would be to quantify the privacy-utility trade-off in measurable terms and provide guidelines for selecting an optimal privacy level for real-world healthcare applications.

---

**Q3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
In our current project, we primarily focused on baseline differential privacy mechanisms and basic noise addition to generate synthetic clinical data. If I could revise our approach, I would propose reproducing an existing research paper on private data generation to validate its claims and compare our outcomes directly. This would make our analysis more grounded and benchmark-driven. Additionally, instead of relying heavily on handcrafted parameters, I’d introduce Gradient-based Differentially Private Stochastic Processes (Gradient-DSP) with adaptive clipping to ensure better model convergence under tight privacy constraints. This modification could lead to more stable synthetic data distributions and closer alignment with the true data patterns.



**Q4. What other techniques would you be interested in using in your project?**  
In future iterations, I’d like to experiment with a combination of *privacy-preserving machine learning* and *causal inference* methods. For instance, using Differentially Private Stochastic Gradient Descent (DP-SGD) for model training while integrating causal discovery algorithms like PC or GES could help uncover relationships that persist even under noisy data conditions. I’m also interested in exploring *Bayesian methods* for uncertainty quantification in private data synthesis, which could provide confidence intervals around generated statistics. Finally, leveraging modern generative approaches such as diffusion models or variational autoencoders (VAEs) under differential privacy constraints might open up new ways to produce high-fidelity synthetic datasets that are both secure and analytically useful.
