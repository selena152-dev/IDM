This project involves the development of a personnel registration system using x86 Assembly language, designed to handle multiple operations like adding, deleting, listing personnel, displaying the oldest and youngest person, and calculating the average age. It provides a menu-driven interface, where users can interact with the system through simple input prompts.

🏗 **Développement du Programme en Assembleur**

🔹 **Menu Principal & Navigation**
   - [x] Afficher un menu avec les 6 choix possibles.
   - [x] Lire et traiter l'entrée utilisateur pour choisir une option.
   - [x] Boucle pour revenir au menu après chaque action.

🔹 **1. Enregistrer du personnel**
   - [x] Demander à l’utilisateur de saisir un nom et un âge.
   - [x] Stocker ces informations en mémoire.
   - [x] Générer un numéro d’enregistrement unique.

🔹 **2. Lister les personnes enregistrées**
   - [x] Vérifier si des personnes sont enregistrées.
   - [x] Parcourir et afficher la liste avec leurs numéros, noms et âges.

🔹 **3. Supprimer une personne spécifique**
   - [x] Demander le numéro d’enregistrement à supprimer.
   - [x] Vérifier si la personne existe.
      - [x] Si oui : supprimer la personne et réorganiser la liste.
      - [x] Si non : afficher un message d’erreur.
   - [x] Afficher la liste mise à jour.

🔹 **4. Afficher la personne la plus âgée et la plus jeune**
   - [x] Parcourir la liste et identifier la personne la plus âgée et la plus jeune.
   - [x] Afficher leurs informations.

🔹 **5. Calculer et afficher l’âge moyen**
   - [ ] Parcourir la liste et calculer la moyenne des âges.
   - [ ] Afficher la moyenne avec la liste des âges.

🔹 **6. Quitter le programme**
   - [ ] Arrêter le programme proprement avec un message de sortie.

⚙ **Optimisation & Tests**
   - [ ] Tester chaque fonctionnalité séparément.
   - [ ] Vérifier la gestion des erreurs (ex. : entrée invalide, liste vide…).
   - [ ] Valider le respect des restrictions (instructions, registres autorisés…).
   - [ ] Ajouter des commentaires clairs dans le code.

📑 **Finalisation & Rendu**
   - [ ] Rédiger un document PDF expliquant le fonctionnement du programme :
      - [ ] Structure des données utilisées.
      - [ ] Explication du code et de chaque fonction.
      - [ ] Exemple d’exécution.
   - [ ] Vérifier que le fichier .asm est bien commenté.
   - [ ] Faire une dernière relecture avant la soumission.
