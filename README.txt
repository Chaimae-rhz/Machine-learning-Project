README - 🤖🎵💉 Projet Intelligence Artificielle : Classification Spotify & Diabète

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python) 
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-yellow?logo=scikit-learn)


📌 Objectif du projet

   Ce projet applique des techniques de Machine Learning pour résoudre deux problèmes de classification :

      1. Prédire la popularité des chansons Spotify.

      2. Détecter le risque de diabète à partir de données médicales.

🔹 Contenu du dossier "AI_Project_Spotify_Diabetes"

    --> Dossier Diabetes:
       - diabetes.csv : Données du dataset Diabète.
       - Diabetes.ipynb : Notebook Jupyter pour la prédiction du diabète.
       - logistic_model_Diabète.pkl : Modèle de classification pour Diabète.
       - scaler_Diabète.pkl : StandardScaler utilisé pour le dataset Diabète.
    
    --> Dossier Spotify:
       - data.csv : Données du dataset Spotify.
       - Song_Popularity.ipynb : Notebook Jupyter pour la prédiction de la popularité des chansons Spotify.
       - logistic_model.pkl : Modèle de classification pour Spotify (fichier sauvegardé).
       - scaler.pkl : StandardScaler utilisé pour la normalisation du dataset Spotify.

⚙️ Installation des dépendances

     1. Assurez-vous d’avoir Python 3.x installé.

     2. Ouvrez un terminal dans le dossier du projet.

     Exécutez la commande :

         pip install -r requirements.txt
 

--> Cela installera automatiquement toutes les bibliothèques nécessaires : 
                                  pandas, scikit-learn, matplotlib, seaborn.

🧪 Comment exécuter le projet ?

1. Ouvrir le dossier avec Jupyter Notebook ou Google Colab.
2. Exécuter :
   - `Song_Popularity.ipynb` pour analyser le dataset Spotify et faire une prédiction.
   - `Diabetes.ipynb` pour analyser le dataset Diabète et faire une prédiction.
3. Ne rien déplacer : tous les fichiers `.pkl`, `.ipynb` et `.csv` doivent rester dans le même dossier pour éviter les erreurs.


📂 Fichiers complémentaires

- Presentation_AI_Projet_PDF.pdf : Version PDF de la présentation
- Rapport_AI_Module.pdf : Rapport du projet (PDF)

💡 Notes utiles:
-Utilisez la fonction `preprocess_new_song()` (déjà incluse) pour automatiser le prétraitement des nouvelles entrées.
-Dépendances : pandas, numpy, seaborn, scikit-learn, matplotlib.
