# Navy

Le Navy est un projet de milieu d'année, c'est jeu de bataille navale, avec un mode multijoueurs (Terminales),
Il se joue avec 4 bateaux et avec un systeme de positionnement.


## But du programme

Le but de ce projet est de devlopper un programme qui reconstitue le jeu de la bataille navale, avec un mode multi entre deux terminaux avec l'utilisation des signaux.

Le joueur demarre avec 4 bateaux de longueurs 2,3,4 et 5. faut les positionner grâce à un fichier text dont les exemples sont donnés dans le dossier log.


## Fonctions autorisées

```

	open, close, read, write, lseek, malloc, free, getpid, kill, signal,
	sigaction, sigemptyset, setcontext, getcontext, usleep, nanosleep, pause, getline, fopen,
	fclose
	
```

## Mise en route

Ces instructions vous permettront d'obtenir une copie du projet opérationnel sur votre machine locale à des fins de développement et de test.

### Pré-requis

De quoi avez-vous besoin pour installer le logiciel et comment l'installer ?

```

gcc
make

```

### Installation

Compilation du projet

```
make
```

Lancement du projet

Usage Joueur1 : $>./navy [pos.txt]

Usage Joueur2: $>./navy [PID Joueur1] [pos.txt]





