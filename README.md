# finetune-StyleGAN3-with-anime-face-datase

## Table des matières
1. **Installation**
2. **Téléchargement du modèle pré-entraîné**
3. **Génération d'images**
4. **Expérimentation avec le paramètre Truncation Psi**
5. **Génération de vidéos d'interpolation**
6. **Ajustement fin avec de nouvelles données**
7. **Génération d'images avec le modèle ajusté**

### 1. Installation
- **Cloner le dépôt StyleGAN3** et **installer les dépendances** nécessaires pour PyTorch.

### 2. Téléchargement du modèle pré-entraîné
- Créer un dossier `checkpoints` et télécharger un modèle pré-entraîné pour StyleGAN3.

### 3. Génération d'images
- Utiliser le modèle pour générer des images avec des seeds spécifiques, puis afficher les images avec `matplotlib`.

### 4. Expérimentation avec Truncation Psi
- Tester différents niveaux de **Truncation Psi** pour voir leur impact sur la diversité des images, et comparer les résultats avec un tableau d'images.

### 5. Génération de vidéos d'interpolation
- Installer des dépendances pour l'interpolation et créer une vidéo interpolée entre deux seeds.

### 6. Ajustement fin du modèle avec de nouvelles données
- **Prétraiter les images** en redimensionnant puis convertissant en format LMDB.
- **Ajuster le modèle** avec les nouvelles données via un nouvel entraînement.

### 7. Génération d'images avec le modèle ajusté
- Générer des images à partir du modèle ajusté pour visualiser les résultats après fine-tuning.

---

Consultez la [documentation officielle de StyleGAN3](https://github.com/NVlabs/stylegan3) pour plus de détails et d'options avancées.
