# JOB_LISTING_APP

## Application de Recherche d'Emploi

Cette application permet aux utilisateurs de gérer les enregistrements de recherche d'emploi/stage, notamment des détails tels que le type d'annonce, le statut, la date, l'entreprise, le poste, et plus encore. L'application est développée en utilisant Python avec PySide6 pour l'interface utilisateur graphique (GUI) et SQLite pour la gestion de la base de données.

## Fichiers

- **job_record.py** : Définit la classe `JobRecord`, représentant un enregistrement de recherche d'emploi/stage.
- **database_manager.py** : Implémente la classe `DatabaseManager` pour l'interaction avec la base de données SQLite.
- **main.py** : Contient la logique principale de l'application, y compris l'interface utilisateur et les fonctionnalités.
- **real_ad_examples.txt** : Contient des exemples d'enregistrements de recherche d'emploi/stage dans un format similaire à un fichier CSV.

## Commentaires sur le Projet

- La structure du projet suit une approche modulaire, séparant les fonctionnalités en différents fichiers pour une meilleure organisation et lisibilité du code.
- La bibliothèque PySide6 est utilisée pour créer l'interface utilisateur graphique, offrant une interface propre et intuitive pour l'utilisateur.
- SQLite est utilisé pour la gestion de la base de données, permettant un stockage et une récupération efficaces des données d'enregistrement d'emploi.

## Difficultés Rencontrées

- **Gestion de la Base de Données** : Mettre en place les interactions avec la base de données et garantir une création adéquate de la base de données ont posé un défi. La classe `DatabaseManager` a dû être soigneusement conçue pour gérer les connexions, la création de table et l'insertion de données.

- **Conception de l'Interface Graphique (GUI)** : Concevoir la mise en page de l'interface graphique et l'intégrer avec la fonctionnalité de l'application a nécessité une réflexion approfondie pour garantir une expérience utilisateur fluide.

## Ce qui n'a pas pu être Réalisé et Pourquoi

- L'application couvre les exigences spécifiées, notamment l'ajout, la liste et le stockage des enregistrements de recherche d'emploi/stage. Cependant, des fonctionnalités supplémentaires, telles que la modification et la suppression des enregistrements, pourraient être envisagées pour des améliorations futures.

- En raison de contraintes de temps et de l'objectif de répondre aux exigences spécifiées, des fonctionnalités plus avancées telles que la visualisation des données ou l'exportation des enregistrements vers un fichier n'ont pas été implémentées dans cette version. Ce sont des améliorations potentielles pour les versions futures de l'application.

---
