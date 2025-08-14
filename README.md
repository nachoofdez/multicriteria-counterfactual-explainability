# Multicriteria Model-Agnostic Counterfactual Explainability

This repository contains the research work from my Master's Thesis on a novel multi-criteria framework for Counterfactual Explainability (CE) in machine learning. The project addresses the growing need for interpretable AI by generating realistic, actionable, and diverse counterfactuals, providing insights into how to change a model's output with minimal and feasible modifications.

## Introduction
Counterfactual Explainability aims to answer the question: *"What minimal changes to an input would change the model's prediction to a desired outcome?"*  
This thesis proposes a **multi-criteria optimization** framework that:
- Is **model-agnostic** and works with black-box models.
- Accounts for the **varying importance** of input variables.
- Generates **realistic and actionable** counterfactuals.
- Balances objectives such as validity, proximity, simplicity, actionability, diversity, and data manifold closeness.

The framework uses the **NSGA-III genetic algorithm** to optimize multiple objectives simultaneously, handling both categorical and continuous variables.

## Applications
The methodology was tested in:
- **Healthcare:** Predicting heart failure events and identifying minimal actionable changes in patient profiles.
- **Finance:** Determining modifications in financial applications to change loan approval outcomes.

## Contents
- **TFM_Final.pdf** — Full Master’s Thesis *"Multicriteria Model-Agnostic Counterfactual Explainability"* detailing methodology, theoretical background, and experiments.  
- **Note:** Due to ongoing journal submissions and confidentiality, the source code is **not** included.
