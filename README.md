# computer-vision-projects

Ce projet explore plusieurs algorithmes de détection d'objets en utilisant des modèles comme **Faster-RCNN**, **SSD** et **YOLOv8**. 
L'objectif est d'effectuer la détection en temps réel, sur des images et vidéos, avec une comparaison des performances.


## Fonctionnalités principales 🚀
1. **Détection d'objets :**  
   - Images statiques  
   - Vidéos pré-enregistrées  
   - Détection en temps réel via Webcam  

2. **Modèles utilisés :**
   - Faster-RCNN (précision élevée)
   - SSD (rapidité équilibrée)
   - YOLOv8 (détection en temps réel)

3. **Visualisation :**
   - Visualisation des prédictions avec TensorBoard
   - Génération d'images et de vidéos annotées

4. **Analyse comparative des modèles :**
   - Rapidité (FPS)
   - Précision (mAP, Recall)
   - Simplicité d'implémentation

## Installation 🛠️

### 1. Cloner le dépôt :
```bash
git clone https://github.com/amouzougit/computer-vision-projects.git
cd computer-vision-projects

2. Installer les dépendances :
pip install -r requirements.txt

3. Lancer les tests :
Détection sur des images :
python detect_image.py --source images/ --model yolov8n.pt

Détection sur des vidéos :
python detect_video.py --source video.mp4 --model yolov8n.pt --save

Détection en temps réel (Webcam) :

python detect_webcam.py --model yolov8n.pt

## Résultats obtenus 📊

### Exemple de détection sur une image :
![Image Detection](images/image_detection.png)

### Comparaison des modèles (YOLOv8 vs SSD vs Faster-RCNN) :
| Modèle        | mAP50 (%) | Temps d'inférence (ms) | FPS  |
|---------------|-----------|------------------------|------|
| YOLOv8        | 85.6      | 10.3                  | 97   |
| SSD           | 78.2      | 16.5                  | 60   |
| Faster-RCNN   | 89.3      | 120.4                 | 8    |


### Visualisation avec TensorBoard 📈
Lancer TensorBoard pour voir les courbes d'entraînement :
```bash
tensorboard --logdir runs/detect
Ensuite, ouvrir http://localhost:6006 dans un navigateur.

- [YOLOv8 Documentation](https://docs.ultralytics.com/)
- [TensorFlow Hub](https://tfhub.dev/)


## Contribuer 🤝
Les contributions sont les bienvenues !  
Si vous avez des idées ou des corrections, n'hésitez pas à ouvrir une **issue** ou à faire un **pull request**.

## Contact 📧
**Amouzou Git**  
- LinkedIn : https://www.linkedin.com/in/amouzou
- Email : kevoamouzou@gmail.com


