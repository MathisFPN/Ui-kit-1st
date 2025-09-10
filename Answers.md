# Answers

## Pour chaque élément de la liste ci-dessus, vous rédigez un paragraphe expliquant à quoi il sert.

Les targets dans une application, désignent les paramètres, noms et frameworks utilisés pour cette application. Dans un projet tu peux avoir plusieurs targets : par exemple l’app principale, un target pour les tests unitaires, etc.

Quand crée un projet iOS sur XCode il génère des fichiers de base AppDelegate / SceneDelegate (lancement, passage au premier plan, mise en arrière-plan, fermeture, etc), ViewController (un contrôleur d’exemple), Main.storyboard (interface par défaut) et le dossier Assets.xcassets. AppDelegate/SceneDelegate gèrent le lancement. ViewController et storyboard te donnent un point d’entrée pour afficher ta première UI. Ces fichiers sont des squelettes — tu les adaptes ou les remplaces selon ton architecture (Storyboard, SwiftUI, programmematic UI).

Le fichier Assets.xcassets centralise les ressources et je crois qu'il permet de stocker a différentes résolutionsq, etc 

Le storyboard est un éditeur d’interface qui regroupe les différentes scènes (UIViewController) et les transitions. 

Le simulateur permet d'émuler des iphones, mac, etc et de tester l'application directement depuis l'ordinateur

## EXO 2
A quoi sert le raccourci Cmd + R ?
Ce raccourci permet de lancer l'application sur l'émulateur 

A quoi sert le raccourci Cmd + Shift + O ?
Le raccourci Cmd + Shift + O sert à rechercher et ouvrir rapidement un fichier au sein du projet 

Trouver le raccourci pour indenter le code automatiquement
Le raccourci est Ctrl + I

Et celui pour commenter la selection.
Celui pour commenter : Cmd + /

deQueueReusableCell
Au lieu de créer chaque cellule individuellement et de les afficher de manière sélective, nous n'en créons qu'une poignée, suffisamment pour remplir l'écran, voire un peu plus. Lors du défilement, nous réutilisons les cellules hors écran, ce qui optimise considérablement la mémoire.

Expliquer ce qu’est un Segue et à quoi il sert.
Il définit une transition entre deux contrôleurs de vue dans le fichier storyboard de l'app. 

Auto-layout et contraintes 
Auto layout et les contraintes permetent de fixer un ensemble de règles qui vont définir comment les composants d'une maquette se comporteront entre eux et avec leurs éléments parents


C'est quoi un #selector 
un selector est un nom de méthode qui permet de définir une méthode cible qui sera executée en réponse d'un évenement.

Que rep .add ici ? 
.add est une case de UIBarButtonItem.SystemItem qui crée un bouton système affichant l’icône +


https://ios-nu-wine.vercel.app
