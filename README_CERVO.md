# ReadMe CERVO

## Etapes:
1. Cloner le répertoire en local 
    Utiliser: ```git clone https://github.com/Coohrentiin/cnngeometric_pytorch.git```
    **OU** dans gitHub desktop: 
    - Faire dérouler l'onglet "Current repository"
    - Cliquer sur add et selectionner dans vos répository ou utiliser le chemin d'acces plus haut
2. Ouvrir Anaconda
3. Se placer dans le répertoire cnngeometric_pytorch (utiliser ```cd <chemin d'acces>```)
4. Creer un environement conda: ```conda env create -f environment.yml```
5. Lancer l'environnement: ```conda activate cnngeometric```
6. Entrainer le modèle, lancer la commande : ```python train.py  --geometric-model affine```