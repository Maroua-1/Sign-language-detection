# Reconnaissance de la langue des signes avec CNN

Système de reconnaissance automatique de la langue des signes en temps réel utilisant les réseaux de neurones convolutifs (CNN).

**Présenté par :** Imane Hamraoui & Maroua Lhassouani  
**Encadré par :** Pr. MOUMOUN Lahcen  
**Année :** 2026

## Description

Ce projet permet de reconnaître en temps réel :
- Chiffres de 0 à 9
- Lettres de A à M
- 5 actions spéciales

Le système utilise une webcam pour capturer les gestes et un modèle CNN pour les classifier.

## Technologies utilisées

- Python 3.8+
- TensorFlow/Keras
- OpenCV
- NumPy
- Tkinter

## Installation

1. Cloner le dépôt :
```bash
git clone https://github.com/Maroua-1/Sign-language-detection.git
cd Sign-language-detection
```

2. Installer les dépendances :
```bash
pip install -r requirements_updated.txt
```

## Utilisation

Lancer l'application :
```bash
python app_interface_complete.py
```

## Structure du projet

```
Sign-language-detection/
├── data_set_capture.py          # Capture des images
├── training_model_updated.py    # Entraînement du modèle
├── app_interface_complete.py    # Application principale
├── model-bw.h5                  # Modèle entraîné
├── model-bw.json                # Architecture du modèle
└── requirements_updated.txt     # Dépendances
```

## Dataset

Le dataset contient environ 2500-3000 images :
- 28 classes (10 chiffres + 13 lettres + 5 actions)
- Images 64x64 pixels en niveaux de gris
- 60 à 113 images par classe

⚠️ **Le dataset n'est pas inclus dans ce dépôt GitHub (trop volumineux).**

📥 **Télécharger le dataset :**  
[Cliquez ici pour télécharger le dataset complet sur OneDrive](c:\Users\marwa_litxmy9\OneDrive\DataSet)

Après téléchargement, décompressez le dossier `DataSet/` à la racine du projet.

## Auteurs

- Imane Hamraoui
- Maroua Lhassouani

Encadré par : Pr. MOUMOUN Lahcen



