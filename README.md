# Projet OrnithoScope
En partenariat avec le CNRS, l'ENSEEIHT et l'OMP </br>


# Commandes courantes
## Générer les ancres 
```
python3 gen_anchors.py
```
## MobileNetV1
### Entraînement 
```
python3 train.py -c config.json   
```
### Evaluation 
```
python3 evaluate.py -c config.json  
```
### Predictions
```
python3 predict.py -w ../MobileNet_bestLoss.h5 -i birds_data/testset/img/bird/task_20210705-07_balacet 
```
## MobileNetV2
### Entraînement 
```
python3 train.py -c config2.json   
```
### Evaluation 
```
python3 evaluate.py -c config.json  
```
### Predictions
```
python3 predict.py -w ../MobileNet_bestLoss.h5 -i birds_data/testset/img/bird/task_20210705-07_balacet 
```