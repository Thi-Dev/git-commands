# Commandes git
# Les premières commandes de base sur git 

## Liste des commandes git

## git init 
- permet d'initialiser un repertoire

## git add .
- permet d'ajouter ou de modifier  des fichiers dans le stagging

## git commit 
- permet d'enregistrer une modification en local
- le message est important 

## git push 
- permet de pousser les modifications en ligne 

## git status 
- permet de lister les modifications éffectués/ à traiter
- permet de verifier le statut du repertoire.

## git log
- permet de lister les modifications en local 

## git branch feature/nom de la branche
- permet de creer une branche 

## git checkout -b feature/ nom de la branche
- permet de passer d'une branche a une autre 
- permet de se déplacer d'une branche a une autre
- avec l'option checkout -b permet de creer et de changer directement sur la branche

## git pull
- permet de récuperer les modifications à distance.

## git rebase 
- se mettre sur la branche 
- permet de telecharger les modifications dans la branche parente pour mettre sur la branche feature.
- Les modifications de la branche mère sont placées en dessous des modifications de la branche courante.
- Les modifications de la branche courante sont placées au dessus des modifications de la branche mère.

## git reset --force
- permet de supprimer un commit 
- permet de revenir a un commit définit par son identifiant + ( Numéro du commit )
- attention a utiliser avec precaution 

## git diff + Numero + Numero
- permet de comparer deux commit 