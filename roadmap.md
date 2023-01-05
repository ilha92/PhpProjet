# Road map

On va créer un site internet qui permet au utilisateurs de s'authentifier et d'ajouter des posts.
 3 Pages:

 ## Page login

 - retrouver dans l'acceuil la barre des taches Profils se deconnecter

 - Un formulaire pour s'inscrire 

 - Script pour ajouter un user dans la base de données 

 - formulaire de connection (username, Password, email)

 - script pour verifier si l'utilisateur a donné un email, username et password valide ($emailValid,$PasswordValid, $usernameValid)

 - Stocker les infos (id, email, avatar, role) dans la base de donner users: session 

 - Mieux gerer les erreurs.(en faisant des var dump pour verifier)

 # Profil: 
 
 Les informations de l'utilisateur (avatar, username, email, couverture), un formulaire pour créer un post.
 
 - retrouver dans l'acceuil la barre des taches Profils se deconnecter

 - Afficher l'avatar de l'utilisateur, sinon afficher une image par défaut.

 - Un formulaire pour changer l'image de profil.

 - Un script (/routes/uploadAvatar.php), enregistre l'image, et met a jour l'utilisateur dans la base de données

 - Un formulaire pour ajouter des taches.

 - script pour ajouter un todo dans la base données.

 - Afficher tous les posts de l'utilisateur:

 - Un post c'est un titre, une image optionnelle, contenu.

 - Pouvoir changer sa photo de profils 

 - Pouvoir mettre une photo de profils en arriere plan dans la page profis 

 - Ajouter l'option pour valider un post

 - Ajouter l'option modifier nos post 

 - Ajouter l'option supprimer nos post



# Page Accueil

Afficher tous les posts de tout les utilisateurs ordonnés par date. (les plus récents d'abord).
 
 - créer une page d'accueil ou va retrouver les post des utilisateurs 
 
 - et publier nos post 

- retrouver dans l'acceuil la barre des taches Profils se deconnecter

- pouvoir retrouver nos likes dans une tache que je vais rajouter (bouton favoris)

- pouvoir commenter les post 