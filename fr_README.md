# Travaux Pratiques en Programmation Orientée Objet (C++)
Ce dépôt contient des travaux pratiques issus de cours axés sur le développement de compétences en concepts de programmation orientée objet (POO) utilisant C++. Chaque séance pratique explore les principes clés de programmation à travers des tâches et implémentations structurées.
## Contenu
### TP1 - Gestion d'Agenda
L'objectif était de concevoir un programme pour gérer un agenda. Cela impliquait :
- Créer des classes pour les entrées (`Entree`) avec un nom et un numéro de téléphone.
- Implémenter un tableau dynamique (`Tableau`) pour stocker et manipuler les entrées, supportant les opérations d'ajout, suppression et affichage.
- Développer une classe agenda (`Agenda`) qui utilisait le tableau et supportait des fonctionnalités comme la concaténation d'agendas, l'ajout, la suppression et l'affichage d'entrées.
### TP2 - Opérateurs d'Agenda
En s'appuyant sur le TP1, cette séance a introduit la surcharge d'opérateurs pour améliorer la classe `Agenda`. Les opérateurs implémentés comprenaient :
- `<<` pour afficher l'agenda.
- `+=` pour ajouter des entrées ou concaténer des agendas.
- `[]` pour trouver la première occurrence d'un nom.
- `-=` pour supprimer toutes les entrées correspondant à un nom.
- `==` pour comparer deux agendas.
- D'autres fonctionnalités avancées, comme tester la présence de noms dans un agenda ou filtrer les entrées par lettre de début.
### TP3 - Héritage
Cette séance a introduit l'héritage en étendant les classes de base pour créer des hiérarchies. Les tâches se concentraient sur :
- Abstraire les propriétés et comportements communs dans des classes parentes.
- Utiliser des classes dérivées pour implémenter des fonctionnalités spécifiques.
- Le polymorphisme pour gérer dynamiquement des objets à travers des références de classe de base.
### TP4 - Polymorphisme
En s'appuyant sur le TP3, ce pratique se concentrait sur :
- Utiliser des classes polymorphes pour gérer dynamiquement des types d'objets divers.
- Implémenter des classes abstraites et des fonctions virtuelles pour fournir une architecture flexible et évolutive.
- Améliorer la réutilisabilité et la maintenabilité du code grâce aux principes POO.
## Objectif
Ces travaux fournissent collectivement une base solide dans les concepts POO de C++, avec des applications qui simulent des scénarios du monde réel, incluant la gestion de données, la surcharge d'opérateurs, l'héritage et le polymorphisme. Le dépôt sert de référence et d'outil d'apprentissage pour les étudiants et professionnels intéressés par la maîtrise des techniques de programmation C++.
