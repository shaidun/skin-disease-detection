# Experimental results recorded in the notebooks

The following values were present in saved notebook outputs. They are reported here as notebook-recorded results, not as a claim of clinical performance. Separate notebooks may use different runs, data splits, or configurations; do not compare them directly without checking those details.

| Experiment | Metric recorded | Value |
|---|---:|---:|
| ResNet50V2 hyperparameter-search notebook, final run | Test accuracy | 94.51% |
| ResNet50V2 hyperparameter-search notebook, final run | Validation accuracy | 94.51% |
| ResNet50V2 hyperparameter-search notebook, final run | Training accuracy | 98.12% |
| ResNet50V2 Gaussian Blur experiment | Test accuracy | 89.88% |
| ResNet50V2 Gaussian Blur experiment | Validation accuracy | 89.40% |
| MobileNetV2 experiment | Test accuracy | 78.80% |
| ResNet50V2 five-fold cross-validation notebook | Mean fold accuracy ± standard deviation | 86.32% ± 0.75 percentage points |
| ResNet50V2 five-fold cross-validation notebook | Mean macro F1 ± standard deviation | 86.22% ± 0.69 percentage points |

## Important interpretation notes

- The 94.51% value appears in the hyperparameter-search notebook output; validate the notebook's data split and evaluation procedure before presenting it as a final result.
- The Gaussian Blur and MobileNetV2 values come from different notebook runs and may not use identical settings.
- Cross-validation metrics summarise folds from the cross-validation notebook and are not interchangeable with a held-out test score.
- Some notebooks include training logs and paths from Google Colab. Paths must be adapted before re-running.
- The notebooks' output cells were cleared in the public copies; these summaries preserve the selected recorded metrics.
