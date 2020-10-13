# Modification des ateliers 

Tâche 1 : Faire un fichier ejs de modification
    - Créer un fichier modify.ejs
    - Le fichier contient le header, footer et un formulaire contenant les informations de l'atelier
    - Le formulaire renvoie un post contenant les nouvelles informations sur /update-workshop

Tâche 2 : Modifier index.ejs
    - Rajouter un bouton "Modifier" pour chaque atelier
    - Chaque bouton renvoie une requête GET sur /workshop/:name avec name qui est le nom de Workshop

Tâche 3 : Modifier index.js
    - Modifier le GET sur /workshop/:name pour qu'il affiche modify.ejs
    - Enregistrer les modifications reçues par le POST sur /update-worshop dans le repository
