# Library

A repository containing my personal functions library.

## `visualization.py`

Some useful functions used for visualization purposes.

* `plot_decision_boundary()`:
  Plots decision boundaries of model predicting on X in comparison to y.
  - Input:
    - model (`torch.nn.Module`): our model.
    - X (`torch.Tensor`): The data on which we predict.
    - Y (`torch.Tensor`): The true labels.
  - Ouput:
    - None
