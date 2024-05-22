# Description du projet
Ce projet inclut un espace de gestion des utilisateurs avec des fonctionnalités d'inscription, de connexion et de déconnexion. Les mesures de sécurité incluent la prévention des doublons et l'utilisation de captcha pour protéger contre les bots.
espace de gestion des admin 
# Fonctionnalités
## Formulaire d'inscription : Le formulaire d'inscription ne demandera qu'un nom, un email et un mot de passe.
## Prévention des doublons : L'inscription empêchera l'entrée de données dupliquées dans la base de données, donc un email déjà présent dans la base de données ne pourra pas être enregistré à nouveau.
## Captcha sur la page de connexion : Le captcha sera sur la page de connexion, ce qui empêchera les bots essayant d'utiliser des mots de passe divulgués.
## Vérification du captcha : Si l'utilisateur ne parvient pas à compléter le captcha correctement, l'utilisateur ne sera pas connecté même si le mot de passe est correct.
# Session utilisateur :
Si l'utilisateur s'est connecté avec succès, il recevra une session contenant son identifiant et sera redirigé vers la page d'accueil.
La session empêchera l'utilisateur d'accéder aux pages de connexion et d'inscription.
Si l'utilisateur se déconnecte, sa session sera supprimée, l'empêchant ainsi d'accéder à la page d'accueil.
Si l'utilisateur ne s'est pas connecté, il ne recevra pas de session et ne pourra pas accéder à la page d'accueil.
# Utilisation
Accédez à la page d'inscription pour créer un nouveau compte.
Connectez-vous avec les informations d'identification enregistrées.
Utilisez l'application selon vos besoins.
Déconnectez-vous lorsque vous avez terminé.
# Interfaqces
![image](https://github.com/Ourrsanae/BTP1/assets/143679582/4f5445f4-cb59-44a2-975f-abc3fb19e034)
![image](https://github.com/Ourrsanae/BTP1/assets/143679582/b3e1b682-a121-4d08-b4cb-0a44141b2dac)
![image](https://github.com/Ourrsanae/BTP1/assets/143679582/026cc4fc-4f59-44d0-8983-9cb05b9d6ded)
![image](https://github.com/Ourrsanae/BTP1/assets/143679582/e2ab837e-2972-4b9c-8b05-fda9d630f468)
![image](https://github.com/Ourrsanae/BTP1/assets/143679582/004e6241-495f-4a8a-a76b-a599dc7b42f3)



