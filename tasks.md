# Modification des ateliers 

Tâche 1 : Faire un fichier ejs de modification
    - Créer un fichier modify.ejs
    - Le fichier contient le header, footer et un formulaire contenant les informations de l'atelier
    - Le formulaire renvoie un post contenant les nouvelles informations sur /update-workshop

Tâche 2 : Modifier index.ejs
    - Rajouter un bouton "Modifier" pour chaque atelier
    - Chaque bouton renvoie une requête GET sur /workshop/:name avec name qui est le nom de Workshop

Tâche 3 : Modifier index.js
    - Implémenter la fonction updateWorkshop dans inMemoryWorkshop.js
    - Modifier le GET sur /workshop/:name pour qu'il affiche modify.ejs
    - Enregistrer les modifications reçues par le POST sur /update-worshop dans le repository


# Suppression des ateliers

Tâche 1 : Modifier index.js
    - Rajouter un bouton supprimer pour chaque atelier
    - Chaque bouton renvoie une requête GET avec le nom de l'atelier à /remove-workshop

Tâche 2 : Implémenter la suppression
    - Coder removeWorkshopByName dans inMemoryWorkshop.js
    - Dans index.js dans le get sur /remove-workshop récupérer les informations de l'atelier et le supprimer avec removeWorkshopByName
    - Afficher les ateliers restants 