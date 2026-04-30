# Tafilalet Oasis: Deep Learning & Big Data for Land Monitoring
Ce projet est le résultat d'un travail de fin d'études de Master IA & Big Data. Il vise à surveiller l'évolution de l'oasis du Tafilalet (Maroc) en utilisant des techniques de Computer Vision et de Deep Learning pour lutter contre les enjeux climatiques.
## Résumé du Projet
L'oasis du Tafilalet est un écosystème fragile. Ce projet propose une approche double pour l'analyse environnementale :
1.  **Segmentation Sémantique (U-Net)** : Classification de l'occupation du sol pour identifier les zones de palmeraies, les zones urbaines et les sols nus, les habitations, les points d'eaué.
2.  **Prédiction Temporelle (ConvLSTM)** : Modélisation de l'évolution future du terrain basée sur des séries temporelles d'images satellites.
## Architecture des modèles
![Architecture UNet](./models/Architecture UNET.png)
![Architecture CONVLSTM](./models/Architecture CONVLSTM.png)
## Stack Technique
*   **Langage** : Python (Jupyter Notebooks)
*   **Deep Learning** : TensorFlow / Keras
*   **SIG (Système d'Information Géographique)** : QGIS pour le prétraitement des données spatiales.
*   **Modèles** :
    *   `U-Net` pour l'extraction de masques.
    *   `ConvLSTM` pour la prévision spatio-temporelle.
*   **Biliothèques** : fichier requirements.txt
## Équipe & Encadrement
Projet réalisé par une équipe de 5 étudiants sous la direction de 2 professeurs (Master IA & Big Data).
*   **Étudiants** : Paul Renardier , Mathis Ehkirch, Soma Kouyate, Darly Junior Nguema, Emmanuel Bibang.
*   **Superviseurs** : Badr-Eddine Benelmostafa, Sohaid Baroud.
