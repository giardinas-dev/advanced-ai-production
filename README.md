# advanced-ai-production
Advanced AI projects for real-world applications, including Reinforcement Learning, Generative AI, MLOps, and Explainable AI (XAI). The repository contains:

[Generative AI for Data Augmentation](https://colab.research.google.com/drive/1Ve0gqfVsMEjy7NrUyyXMwFvuN_7pkQT2)
 – Synthetic image generation for the OxfordPets dataset. The pipeline includes OCR-based caption reformulation, image generation conditioned on captions, caption validation, and image validation using pre-trained models to ensure that synthetic images match the original labels. The workflow emphasizes preprocessing, data augmentation, quality validation, and benchmarking the generated images for downstream tasks.

[Reinforcement Learning for Cybersecurity Simulation](https://colab.research.google.com/drive/1EjRXWi_mL-B0Ri3bvKQfJK1rO5NjhDx1)
 – Implementation of DDQN and SARSA to simulate random and maximal attacks on a system. The project evaluates algorithm performance with repetitive actions and null actions to analyze if the agent has learned meaningful policies. The focus is on training, performance benchmarking, error analysis, and visualization of learning outcomes.

[MLOps for Model Deployment and Monitoring](https://colab.research.google.com/drive/1IJaBor_KnEiL7hrCoV4Y3ULOBPtueHPV)
 – Automated pipelines using GitHub Actions for training and deploying a model published on Hugging Face. The project includes Grafana dashboards and a free endpoint for real-time monitoring of model usage, data collection, and pipeline automation.

[Explainable AI (XAI) on CIFAR-10](https://colab.research.google.com/drive/1eDB5pi7vayk05kba7dHJ9hOGhtRJXak0#scrollTo=RItqoR-h41g1)
 – Analysis of a black-box DenseNet model using XAI techniques such as LIME, SHAP, and Grad-CAM. Additionally, a glass-box substitute model (Decision Tree) is used to extract interpretable features and highlight which pixels influence class predictions. The workflow emphasizes preprocessing, feature extraction, visualization of decision-relevant pixels, benchmarking of interpretability methods, and detailed reporting.

All projects emphasize: data preprocessing and cleaning, performance evaluation across multiple benchmarks, visualization of results, validation pipelines, feature and error analysis, and comprehensive reporting of outcomes.

Technologies used: TensorFlow, PyTorch, Hugging Face, GitHub Actions, Grafana, pandas, numpy, matplotlib, seaborn, executed in Google Colab and local environments.

License: MIT License.
