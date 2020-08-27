
<img src="img/int.png" width=150 height=125 align="right">


# AI Interpretability in Healthcare Scenarios

The use of Machine Learning algorithms has become ubiquitous. It's no suprise that the use of such algorithms in the medical domain is emerging as well. But unlike many domains, in medicine, predictions cannot be acted upon on merely blind faith, as the consequences may be catastrophic.

The need for a better understanding of models' behavior is clear. However, not many go the extra mille to interpt their model perdiction in a way that will also be clear to the domain experts (i.c the medical staff).

In this work, we incorporate existing tools for interpretability of machine learning models such as LIME algorithm (Ribeiro, Singh and Guestrin, 2016) and SHAP (Lundberg and Lee, 2017) together with MMD-critic (Kim, Khanna and Koyejo, 2016) to gain a better understading of the model. These "hybrids" are then evaluated to detemine which provaids better explanations.

Learn more [Here](https://bareini.github.io/AI-Interpretability/)

## Getting Started

1. **Select a model and Datase** - The notebook examines a pre-trained model saved in a pickle format.
The specific model used here was trained over XXXX dataset (Limited access). You may gain access dataset and train your own model, but you can also select different dataset and train another model. Just make sure to make the required changes (see code documentation).

2. **Utilize the interpretability evaluation section** - after loading you model you can now utilize the interpretability evaluation section. You can select samples with different strategies and try different explanations.
