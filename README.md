# Libft

## Description

Le projet **Libft** est la première grande étape à l'école 42. Il consiste à recréer une bibliothèque standard en C, semblable à la célèbre `libc`. L'objectif principal est de se familiariser avec des fonctions de manipulation de chaînes, de mémoire, et d'autres opérations de base en C. Ce projet pose les fondations de la programmation en C, et prépare à la maîtrise des concepts nécessaires pour les projets futurs.

## Objectifs

- Comprendre le fonctionnement interne des fonctions de la bibliothèque standard C.
- Développer des compétences en gestion de la mémoire (allocation, libération).
- Travailler avec des structures de données de base.
- Respecter des règles de programmation strictes (norme de l'école 42).

## Fonctions à implémenter

Parmi les fonctions à implémenter, on retrouve :

1. **Manipulation de chaînes de caractères :**
   - `ft_strlen`
   - `ft_strcpy`
   - `ft_strdup`
   - `ft_strcat`
   - etc.

2. **Manipulation de la mémoire :**
   - `ft_memset`
   - `ft_bzero`
   - `ft_memcpy`
   - etc.

3. **Gestion des nombres :**
   - `ft_atoi`
   - `ft_itoa`

4. **Fonctions supplémentaires (partie bonus) :**
   - Fonctions de manipulation de listes chaînées (`ft_lstnew`, `ft_lstdelone`, etc.).

## Structure du projet

La structure du projet est organisée de manière à respecter les standards de développement de l'école 42. Voici un exemple de structure typique :

libft/
│
├── includes/          # Contient les fichiers header (.h)
│   └── libft.h
├── srcs/              # Contient les fichiers source (.c)
│   ├── ft_strlen.c
│   ├── ft_strcpy.c
│   ├── ft_memset.c
│   └── ...            # Autres fichiers source
├── Makefile           # Fichier permettant de compiler la bibliothèque
└── README.md          # Ce fichier



## Compilation

Pour compiler la bibliothèque, utilisez la commande suivante dans le terminal :

- make

Cette commande génère un fichier libft.a que vous pourrez utiliser dans d'autres projets.

- make clean : Supprime les fichiers objets.
- make fclean : Supprime les fichiers objets et la bibliothèque compilée (libft.a).
- make re : Reconstruit la bibliothèque à partir de zéro.

## Utilisation

Une fois la bibliothèque compilée, elle peut être utilisée dans n'importe quel projet en ajoutant libft.a et le fichier libft.h dans les fichiers sources.

## Contributeurs

Projet développé dans le cadre de l'école 42 par MakO0.

## Licence

Ce projet est sous licence MIT. Vous pouvez le modifier et le redistribuer librement.