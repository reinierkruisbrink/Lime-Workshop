# Lime-Workshop

This workshop is intended to guide participants through the usage of LIME with a simple ML model that predicts energy ratings for buildings in New York City. [LIME](https://christophm.github.io/interpretable-ml-book/lime.html) stands for **Local Interpretable Model-agnostic Explanations**. LIME focuses on training local surrogate models to explain individual predictions. Local surrogate models are interpretable models that are used to explain individual predictions of black box machine learning models. Surrogate models are trained to approximate the predictions of the underlying black box model. Instead of training a global surrogate model, LIME focuses on training local surrogate models. LIME is model-agnostic, meaning that it can be applied to any machine learning model. The technique attempts to understand the model by perturbing the input of data samples and understanding how the predictions change.
    
The data used in this workshop can be found at https://www.kaggle.com/datasets/mikhailma/energy-efficiency-of-buildings-in-new-york

This workshop was given at the Baise AI Symposium on the 24th of May 2023
