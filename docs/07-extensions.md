---
title: Exercice 7 - Ajout de filtre d'acteur
---

## Objectif

L'objectif de cet exercice est d'ajouter un filtre d'acteur pour le validateur.

## Instructions résumées

Dupliquer le diagramme de processus de l'exercice précédent pour créer une version *3.0.0*.

Configurer un filtre d'acteur de type **Manager de l'initiateur du processus** sur la lane *Validateur*.

## Instructions pas à pas

1. Dupliquer le diagramme de processus de l'exercice précédent pour créer une version *3.0.0*

1. Sélectionner la lane *Validateur*

1. Configurer un filtre d'acteur de type **Manager de l'initiateur du processus** sur la lane *Validateur* :
   - Sélectionner la lane *Validateur*
   - Naviguer dans l'onglet **Général / Acteurs**
   - Sélectionner l'acteur *Employee actor* à partir du menu déroulant
   - Cliquer sur le bouton **Définir...** associé au filtre
   - Sélectionner un filtre de type **Manager de l'initiateur du processus**
   - Cliquer sur **Suivant**
   - Nommer le filtre *managerInitiateur*
   - Cliquer sur **Terminer**

1. Exécuter le processus avec les deux acteurs :
   - Lancer le processus à partir du Studio (l'utilisateur Walter Bates sera utilisé)
   - Soumettre le formulaire de *Saisie demande congés*. Si les acteurs sont correctement configurés, la tâche *Valider demande de congés* ne devrait pas être proposée
   - Se déconnecter du portail en naviguant sur le nom d'utilisateur dans le coin supérieur droit puis **Déconnexion**
   - Se connecter avec l'utilisateur *helen.kelly* et le mot de passe *bpm*
   - Si le filtre d'acteur s'est bien exécuté, la tâche *Valider demande de congés* devrait être disponible dans la liste des tâches à faire

[Exercice suivant : finaliser l'application](08-applications.md)
