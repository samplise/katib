# Instructions to Train XGBoost model via Katib 

## Install Kubernetes & Katib:

``` console
root@root#bash setup_katib_env.sh
```

## Create a XGBoost Experiment

``` console
root@root#kubectl apply -f katib-xgboost.yaml
```
