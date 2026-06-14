This run saves train and test metrics for all non-Bayesian model families across classification, future burden, best intervention, parameter recovery, and optionally drug zero/few-shot analyses.
Classification files include macro/weighted F1, precision, recall, accuracy, balanced accuracy, plus per-class reports for every model.
Regression files include train_R2/RMSE/MAE and test_R2/RMSE/MAE for every model.
Drug files include zero-shot and few-shot train/test burden metrics and best-drug accuracy metrics.
PINN rows require PyTorch; if unavailable they are marked not_available. Oracle rows use true hidden parameters and are diagnostic upper bounds.
