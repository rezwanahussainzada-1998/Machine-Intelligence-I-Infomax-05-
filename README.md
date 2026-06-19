# Machine-Intelligence-I-Infomax

Independent Component Analysis (ICA) via Infomax Algorithm

Key Features & Explorations

Infomax Optimization & Density Matching: Implemented the Infomax approach from scratch, using a logistic sigmoid function as the non-linear transfer function to closely match the cumulative distribution functions of the underlying acoustic sources.

Standard vs. Natural Gradient Ascent: Developed and contrasted two optimization techniques. The comparison demonstrates how the natural gradient accelerates convergence and maintains scale-invariance by adjusting the standard gradient step using the current weight space geometry.

Statistical and Density Analysis: Evaluated the performance through correlation matrices between the true and estimated sources. Plotted statistical signal distributions to confirm that while mixed signals exhibit smooth Gaussian profiles, the recovered signals perfectly capture the highly peaked, heavy-tailed non-Gaussian signatures of the original sound files.

Sheet05_most_principle_component.ipynb: The step-by-step Jupyter Notebook containing the full audio data preprocessing pipeline, explicit optimization updates, correlation metrics, and density visualization charts.
