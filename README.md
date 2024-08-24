# Conversion_d_un_jeu_de_donnee_a_un_fichier_Numpy
Projet de Conversion d'Images en Fichier NumPy Compressé
Ce projet permet de charger des images depuis un répertoire spécifié, de les convertir en tableaux NumPy, puis de les sauvegarder dans un fichier .npz compressé.

Auteur
Nom: OSHASHA Fiston
Fonctionnalités
Chargement d'images depuis un dossier spécifique
Conversion des images en tableaux NumPy
Sauvegarde des tableaux NumPy dans un fichier .npz compressé
Gestion des erreurs lors du chargement d'images non valides
Prérequis
Python 3.x
Bibliothèques : numpy, opencv-python
Pour installer les bibliothèques nécessaires, vous pouvez utiliser pip :

bash
Copier le code
pip install numpy opencv-python
Utilisation
Clonez ce dépôt sur votre machine locale.
Modifiez les variables images_dir et output_dir dans le script Python pour spécifier le chemin de votre répertoire d'images et le répertoire de sortie.
Exécutez le script pour générer un fichier .npz contenant les images et leurs noms.
bash
Copier le code
python script.py
Structure du Projet
plaintext
Copier le code
.
├── script.py           # Le script principal pour convertir et sauvegarder les images
└── README.md           # Ce fichier README
Exemple
Voici un exemple d'utilisation du script :

python
Copier le code
# Spécifiez le chemin vers le dossier contenant les images
images_dir = '/votre/chemin/vers/dossier/images'

# Spécifiez le répertoire de sortie où le fichier NumPy sera sauvegardé
output_dir = '/votre/chemin/vers/dossier/output'

# Exécutez le script pour sauvegarder les images
python script.py
Licence
Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.
