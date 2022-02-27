---
title: TP automatisation des processus
---

## Présentation

Ce TP est une formation d'introduction à l'utilisation de Bonita Community Edition en tant que BPMS. Il a pour objectif de vous permettre de vous familiariser avec les concepts du BPM et de l'automatisation des processus, et des fonctionnalités cœurs de Bonita.
Il comporte à la fois des informations théoriques et une partie mise en pratique avec des exercices permettant de créer une première application à l'aide de Bonita.

Le TP se compose :
* D'un ensemble de slides
* D'un ensemble d'exercices décrits sur ce site web
* Les [corrections des exercices](https://github.com/dcoille/cours-IUT2/releases/latest)

## Prérequis
1. [Téléchargez](https://fr.bonitasoft.com/telechargez) et installez la dernière version du Studio Bonita. Pour plus de détails référez vous à la [documentation officielle](https://documentation.bonitasoft.com/bonita/latest/bonita-studio-download-installation)
1. Vous pouvez également optionnellement télécharger les corrections et les slides au format PDF depuis la [section "release" du projet GitHub](https://github.com/dcoille/cours-IUT2/releases/latest)
1. Téléchargez [Fake SMTP](http://nilhcem.github.io/FakeSMTP/downloads/fakeSMTP-latest.zip). Cette application va être utilisée pour simuler un serveur de mail.
1. Il est recommandé d'utiliser Chrome ou Firefox lors du développement pour bénéficier de l'outillage de test de ces navigateurs. 
   Edge et Safari sont également supportés (IE11 n'est plus supporté). Afin de savoir quel navigateur est utilisé par défaut par le Studio, cliquez sur le bouton **Lancer** ![icone lancer](images/icon-run.png). L'application utilisateur Bonita devrait s'ouvrir avec le navigateur par défaut de votre système d'exploitation. Vous pouvez configurer le Studio Bonita pour qu'il utilise un navigateur autre que celui par défaut :
   - Dans le Studio cliquez sur le bouton **Préférences** ![icône préférences](images/preferences.png)
   - Dans la section **Web** cliquez sur **Navigateur**
   - Cliquez sur le bouton **Nouveau...**
   - Entrez un nom et utilisez le bouton **Parcourir...** pour sélectionner l'exécutable du navigateur web (e.g. *C:\Program Files (x86)\Google\Application\chrome.exe* pour Chrome sur Windows)
   - Cliquez sur le bouton **OK**
   - Dans la liste **External web browsers** sélectionnez le navigateur souhaité et cliquez sur le bouton **Appliquer**
   - Fermez la fenêtre des préférences

[Débuter les exercices](00-introduction.md)
