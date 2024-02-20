### Utilizando visão computacional para classificar tumores cerebrais através de ressonância

## Base de Dados: https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset/data

## Metodologia:
Foi utilizado como base a modelo RestNet50V2, através de fine tuning e o recurso ImageDataGenerator do Keras, o modelo foi treinado em 5712 imagens de ressonâncias, sendo estas dividas em 4 classes ('Pituitary', 'NoTumor', 'Meningioma', 'Glioma').

## Resultados:
O modelo obteve uma excelente performance com uma taxa de acerto de mais de 99%

![image](https://github.com/EvandroSanches/BrainTumor_CNN/assets/102191806/86f09d96-d5d9-40e6-bbab-60efb2044f99)

Matriz de confusão

![image](https://github.com/EvandroSanches/BrainTumor_CNN/assets/102191806/43dbaf41-272b-47a8-a85f-a60c6ceb32c1)
