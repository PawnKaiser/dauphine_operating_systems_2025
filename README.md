# Systèmes d'exploitation - L3 Informatique Dauphine (2023)

🇫🇷 Ce dépôt contient les ressources pédagogiques du cours de systèmes d'exploitation pour les étudiants en licence 3
informatique à l'université Paris-Dauphine, pour l'année 2025.

🇬🇧 This repository contains the teaching resources (in French) for the operating systems course for students in licence
3 in Computer Science at Université Paris-Dauphine, for the year 2025.

## Présentation

Ce cours est une introduction aux concepts des systèmes d'exploitation pour les étudiants en troisième année de
licence informatique. Il s'intéresse au fonctionnement des systèmes Unix, ceux-ci étant
très répandus et existant dans des versions _open source_. Le cours conjugue études théoriques, au travers de
cours magistraux, et travaux pratiques permettant d'illustrer la théorie.

## Organisation

* 15 heures de CM
* 15 heures de TP

## Prérequis

* Une précédente expérience avec un langage de programmation (C, C++, Java, etc.).
* Une expérience élémentaire avec l'utilisation d'un système d'exploitation (Unix de préférence).

## Objectifs du cours

1. Comprendre le rôle d'un système d'exploitation et de ses composants.

2. Être capable d'interagir avec un système d'exploitation de type Unix grâce à l'interpréteur de commandes.

3. Comprendre le lien entre développement applicatif et système d'exploitation.

4. Maîtriser les bases de la programmation système sous Unix en C.

5. Comprendre les mécanismes centraux d'un système d'exploitation (virtualisation, concurrence et persistence) et leurs
   implémentations.

## Évaluation

* [Projet informatique](./out/projet.pdf) (30 % de la note finale).
* [Examen terminal]() (70 % de la note finale).

## Ouvrages de référence

Ce cours est basé sur l'excellent **Operating Systems: Three Easy Pieces** de _Remzi H. Arpaci-Dusseau_ et _Andrea C.
Arpaci-Dusseau_. L'ouvrage est disponible librement sur [son site Internet](https://pages.cs.wisc.edu/~remzi/OSTEP/).

Il est nécessaire d'acquérir une maîtrise basique du langage de programmation C pour
ce cours. Des rappels du langage sont donnés dans le cours.

L'ouvrage de référence recommandé pour le langage C est
[**Effective C** par _Robert C. Seacord_](https://nostarch.com/Effective_C).

Le classique **The C Programming Language, 2nd Edition** par _Brian W. Kernighan_ et
_Dennis M. Ritchie_ vaut toujours le détour même s'il ne tient pas compte des développements
les plus récents du langage.

Pour une vue d'ensemble relativement courte des éléments clés du langage C (45 pages), on pourra se
référer au document [Essential C](http://cslibrary.stanford.edu/101/EssentialC.pdf) mis gracieusement à disposition
par [Stanford CS Education Library](http://cslibrary.stanford.edu).

## Programme

|  Date | Type   | Titre                                                                                                                             | Chapitres                                                                                                                                                                                                                                                                                             |
|------:|:-------|:----------------------------------------------------------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  3/02 | CM     | [Ch 1 - Introduction](./out/slides/1_introduction.pdf)                                                                            | [Introduction](https://pages.cs.wisc.edu/~remzi/OSTEP/intro.pdf)                                                                                                                                                                                                                                      |
| 13/02 | TP     | [TP 1 - Utilisation du shell](./out/tps/1_shell.pdf)                                                                              |                                                                                                                                                                                                                                                                                                       |
| 16/02 | CM     | [Ch 2 - Virtualisation (CPU) : les processus](./out/slides/2_processus.pdf)                                                       | [Processes](https://pages.cs.wisc.edu/~remzi/OSTEP/cpu-intro.pdf) • [Process API](https://pages.cs.wisc.edu/~remzi/OSTEP/cpu-api.pdf)                                                                                                                                                                 |
|  6/03 | TP     | [TP 2 - Processus](./out/tps/2_processus.pdf) • [Correction](./out/tps/2_processus_correction.pdf)                                |                                                                                                                                                                                                                                                                                                       |
|  8/03 | CM     | [Ch 3 - Virtualisation (CPU) : ordonnancement](./out/slides/3_ordonnancement.pdf)                                                 | [Limited Direct Execution](https://pages.cs.wisc.edu/~remzi/OSTEP/cpu-mechanisms.pdf) • [CPU Scheduling](https://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched.pdf) • [Multi-level Feedback](https://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched-mlfq.pdf)                                                    |
|  9/03 | TP     | [TP 2 - Processus (suite)](./out/tps/2_processus.pdf) • [Correction](./out/tps/2_processus_correction.pdf)                        |                                                                                                                                                                                                                                                                                                       |
| 20/03 | CM     | [Ch 4 - Virtualisation (mémoire) : segmentation](./out/slides/4_segmentation.pdf)                                                 | [Address Spaces](https://pages.cs.wisc.edu/~remzi/OSTEP/vm-intro.pdf) • [Memory API](https://pages.cs.wisc.edu/~remzi/OSTEP/vm-api.pdf) • [Address Translation](https://pages.cs.wisc.edu/~remzi/OSTEP/vm-mechanism.pdf) • [Segmentation](https://pages.cs.wisc.edu/~remzi/OSTEP/vm-segmentation.pdf) |
| 22/03 | TP     | [TP 3 - Ordonnancement](./out/tps/3_ordonnancement.pdf)                                                                           |                                                                                                                                                                                                                                                                                                       |
|  3/04 | CM     | [Ch 5 - Virtualisation (mémoire) : pagination](./out/slides/5_pagination.pdf)                                                     | [Paging](https://pages.cs.wisc.edu/~remzi/OSTEP/vm-paging.pdf) • [Faster Translations (TLBs)](https://pages.cs.wisc.edu/~remzi/OSTEP/vm-tlbs.pdf) • [Smaller Tables](https://pages.cs.wisc.edu/~remzi/OSTEP/vm-smalltables.pdf)                                                                       |
|  5/04 | TP     | [TP 4 - Mémoire](./out/tps/4_memoire.pdf) • [Correction](./out/tps/4_memoire_correction.pdf)                                      |                                                                                                                                                                                                                                                                                                       |
| 19/04 | CM     | [Ch 6 - Concurrence : threads et verrous](./out/slides/6_threads.pdf)                                                             | [Concurrency](https://pages.cs.wisc.edu/~remzi/OSTEP/threads-intro.pdf) • [Thread API](https://pages.cs.wisc.edu/~remzi/OSTEP/threads-api.pdf) • [Locks](https://pages.cs.wisc.edu/~remzi/OSTEP/threads-locks.pdf)                                                                                    |
| 20/04 | TP     | [Projet](./out/projet.pdf)                                                                                                        |                                                                                                                                                                                                                                                                                                       |
| 10/05 | CM     | [Ch 7 - Concurrence : condition variables et sémaphores](./out/slides/7_semaphores.pdf)                                           | [Condition Variables](https://pages.cs.wisc.edu/~remzi/OSTEP/threads-cv.pdf) • [Semaphores](https://pages.cs.wisc.edu/~remzi/OSTEP/threads-sema.pdf) • [Common Concurrency Problems](https://pages.cs.wisc.edu/~remzi/OSTEP/threads-bugs.pdf)                                                         |
| 11/05 | TP     | [TP 5 - Threads et verrous](./out/tps/5_threads.pdf) • [Correction](./out/tps/5_threads_correction.pdf)                           |                                                                                                                                                                                                                                                                                                       |
| 24/05 | CM     | [Ch 8 - Persistence : périphériques d'entrées-sorties](./out/slides/8_peripheriques.pdf)                                          | [I/O Devices](https://pages.cs.wisc.edu/~remzi/OSTEP/file-devices.pdf) • [Hard Disk Drives](https://pages.cs.wisc.edu/~remzi/OSTEP/file-disks.pdf)                                                                                                                                                    |
| 25/05 | TP     | [TP 6 - Sémaphores](./out/tps/6_semaphores.pdf) • [Correction](https://greenteapress.com/wp/semaphores/)                          |                                                                                                                                                                                                                                                                                                       |
|  7/06 | CM     | [Ch 9 - Persistence : implémentation des systèmes de fichiers](./out/slides/9_systemes_fichiers.pdf)                              | [Files and Directories](https://pages.cs.wisc.edu/~remzi/OSTEP/file-intro.pdf) • [File System Implementation](https://pages.cs.wisc.edu/~remzi/OSTEP/file-implementation.pdf)                                                                                                                         |
|  7/06 | CM     | [Ch 10 - Persistence : cohérence du système de fichiers et journalisation](./out/slides/10_journalisation.pdf)                    | [FSCK and Journaling](https://pages.cs.wisc.edu/~remzi/OSTEP/file-journaling.pdf)                                                                                                                                                                                                                     |
|  8/06 | TP     | [TP 7 - Interface du système de fichiers](./out/tps/7_systemes_de_fichiers.pdf)                                                   |                                                                                                                                                                                                                                                                                                       |
| 21/06 | Examen | [Examen](./out/examens/examen_2023.pdf) • [Correction](./out/examens/examen_2023_correction.pdf)                                  |                                                                                                                                                                                                                                                                                                       |
| 22/06 | CM/TP  | [Ch 11 - Une introduction à Docker et aux conteneurs](./out/slides/11_conteneurs.pdf)                                             |                                                                                                                                                                                                                                                                                                       |
| 29/08 | Examen | [Examen rattrapage](./out/examens/examen_2023_rattrapage.pdf) • [Correction](./out/examens/examen_2023_rattrapage_correction.pdf) |                                                                                                                                                                                                                                                                                                       |

## Génération des diapositives et documents

Les diapositives sont générées à partir de fichiers en Markdown grâce à [Marp](https://marp.app/). Les autres documents
sont en Markdown également et le rendu est réalisé avec [Quarto](https://quarto.org/).

Sur le dépot, les commits modifiant les fichiers source déclenchent un workflow GitHub qui régénère les diapositives et
les documents et les stocke dans le dossier [out/](./out).

## Remerciements

Ce cours n'aurait pu voir le jour sans l'aide fantastique Thibaud Martinez et 
de [Remzi H. Arpaci-Dusseau](https://pages.cs.wisc.edu/~remzi/) et [Andrea C.
Arpaci-Dusseau](https://pages.cs.wisc.edu/~dusseau/) qui ont gracieusement fourni de nombreuses ressources
pédagogiques pour construire ce cours.
Je tiens également à remercier [Youjip Won](https://oslab.kaist.ac.kr/professor-youjip-won/)
et [Mathias Payer](https://nebelwelt.net/) pour avoir mis à disposition des diapositives que j'ai pu adapter et dont
j'ai pu m'inspirer pour créer le cours. Enfin, les exercices proposés par
[Johan Montelius](https://people.kth.se/~johanmon/ose.html) ont été une aide précieuse pour concevoir des séances de
travaux pratiques.
