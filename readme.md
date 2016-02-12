# Cours Github

Dans ce cours, nous allons aborder l'utilisation de git et github.

## Vocabulaire

__git__ : système de versionning.  
Permet par exemple d'apporter des modifications à un projet web, sans affecter le travail déjà effectué, et sans créer de dossier supplémentaire.

__github__ : Service web qui améliore git.  
Fonctions supplémentaires (et indispensables) apportées par github:
- dépot distant (sur internet), qui permet le travail à plusieurs
- la possibilité d'exposer son travail dans des dépôts publics
- la possibilité d'utiliser des dépôts privés (payant)
- la possiblité d'héberger un site web (php interdit) sur une branche 'gh-pages'

__dépôt // repository __ : dossier géré par git.

## Pas à Pas

### Prérequis : compte github et client graphique

- Rendez-vous sur la [page d'accueil](https://github.com) et inscrivez-vous.
- [Téléchargez le client](https://desktop.github.com) pour votre machine  
Soyons clairs : git et github s'utilisent au mieux en utilisant la ligne de commande.  
Mais le client graphique simplifie énormément la tâche, et nous suffira.

### Définir un dossier local comme _dépôt_

- Créez un dossier dans votre espace de travail habituel  
Appelons-le, par exemple 'testGit'.
- Dans le client, cliquer sur le '+', puis 'Add'
- Naviguez jusqu'à votre dossier.

C'est bon, votre dossier est géré par git.  
_maintenant, on fait des tests en salle de formation..._

### Définir un dépôt distant pour notre dépôt local

On peut synchroniser un dépôt local (défini précédemment), avec un dépôt sur github.  
Ainsi, on peut partager son travail avec la communauté.

Pour diposer de repos privés, il faut passer par [une formule payante](https://github.com/pricing), ou un concurrent, comme [bitbucket](https://bitbucket.org/).

#### Créer un dépot sur github

Sur votre page de profil github ( _http://github.com/monpseudo_ ) cliquez sur l'onglet '_Repositories_' puis sur le bouton '_New_'.

Remplissez le formulaire, __Sans cliquer__ sur 'Initialize this repository with a README'.  
Validez en cliquant sur '__Create repository__'.

Sur la page suivante, copiez l'url (exemple : _https://github.com/ejallier/test1.git_).

#### Synchroniser les dépôts

- Dans le client github, sélectionnez votre dépôt local, puis:   
. pour Mac :  
Menu '_Repository / Repository Settings_'  
. Pour PC :  
Menu '_Engrenage / Repository Settings_'

- Clic sur '_Remote_', puis collez l'url du dépôt distant.
