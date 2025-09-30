# 📡 Accountable AI Development in B5G Systems

This repository contains the code, data, and metric computation framework introduced in the thesis chapter *"Accountable AI Development in B5G Systems"*. The work focuses on quantifying and enforcing explainability, fairness, and transparency in AI models deployed within next-generation (5G and B5G) intelligent networking systems. This includes experiments on encrypted network traffic classification, a critical use case where AI models must infer traffic categories without inspecting payload content. The project simulates realistic attack scenarios where adversaries attempt to manipulate or evade the model’s decision-making, highlighting the importance of accountability and explainability in high-stakes security settings.

## 🔍 Features

- 📊 **Explainability Metrics**: Implementation of custom post-hoc explainability metrics (e.g., fidelity, comprehensibility, contrastiveness) based on SHAP, LIME, and TreeSHAP.
- 🧠 **Model-Agnostic Framework**: Compatible with both classical ML models (e.g., SVM, Random Forest) and deep learning models used in wireless systems (e.g., MLP, LSTM).
- 🛰️ **Use Case Integration**: Supports simulations for Encrypted Network Traffic Analysis.
- 🔄 **Closed-Loop Feedback**: Prototype for integrating external stakeholder feedback into AI system updates.
- 📉 **Visualization Tools**: Jupyter notebooks for visualizing explanations and metric trends across time and use cases.

## 📌 Citation
```
@article{senevirathna2025enhancing,
  title={Enhancing Accountability, Resilience, and Privacy of Intelligent Networks With XAI},
  author={Senevirathna, Thulitha and Sandeepa, Chamara and Siniarski, Bartlomiej and Nguyen, Manh-Dung and Marchal, Samuel and Boerger, Michell and Liyanage, Madhusanka and Wang, Shen},
  journal={IEEE Open Journal of the Communications Society},
  year={2025},
  publisher={IEEE}
}
```
If you use this repository, please cite the thesis or related publications accordingly.

---

Feel free to open issues or contribute improvements!
