# Welcome !

**FAIR_Bioinfo** - [![DOI](https://zenodo.org/badge/164655551.svg)](https://zenodo.org/badge/latestdoi/164655551)

**Gitbook** - [![](https://img.shields.io/badge/Gitbook-FAIR_Bioinfo-blue.svg)](https://fair-bioinfo.gitbook.io/fair-bioinfo/) [![](https://img.shields.io/badge/Github-FAIR_Bioinfo_Gitbook-blue.svg)](https://github.com/thomasdenecker/FAIR_Bioinfo-Gitbook) 
[![DOI](https://zenodo.org/badge/197582632.svg)](https://zenodo.org/badge/latestdoi/197582632)

**Docker image** - [![](https://img.shields.io/badge/Docker-FAIR_Bioinfo-blue.svg)](https://hub.docker.com/r/tdenecker/fair_bioinfo) [![](https://images.microbadger.com/badges/image/tdenecker/fair_bioinfo.svg)](https://microbadger.com/images/tdenecker/fair_bioinfo) 

**Licence pour le code** - [![](https://img.shields.io/badge/LICENCE-CeCILL%202.1-brightgreen.svg)](https://github.com/thomasdenecker/FAIR_Bioinfo/blob/master/LICENCE)

**Licence pour le GitBook** - 
[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

**Bienvenue à FAIR_bioinfo**

FAIR_Bioinfo est une formation initialement pensée pour la communauté francophone. En effet, les ressources sont nombreuses concernant la reproductibilité en anglais mais un manque se faisait sentir en français. Vous trouverez tout le contenu du cours présenté dans les différentes sessions (slides en français). Nous proposons aussi la version retranscrite de ces cours au format gitbook en anglais : https://fair-bioinfo.gitbook.io/fair-bioinfo/

*FAIR_Bioinfo is a training course initially designed for the French-speaking community. Indeed, there are many resources concerning reproducibility in English but there was a lack in French. You will find all the course content presented in the different sessions (slides in French). We also offer the transcribed version of these courses in gitbook format in English: https://fair-bioinfo.gitbook.io/fair-bioinfo/*

**Informations pratiques**
- Quand ? : le dernier vendredi après midi de chaque mois (sauf juillet à définir), rdv 12h30
- Durée ? : 1h30 (questions incluses)
- Lieu ? : Salle de conférence A.Kalogeropoulos, b. 400, campus Orsay

**Objectifs**

L'objectif est de proposer et d'utiliser un panel d'outils permettant la réalisation d'un projet complet de bio-info en partant de rien et aboutissant à la création d'un conteneur (technologie Docker). Le partage, la valorisation et l'analyse dynamique des données seront inclus dans le panel.
FAIR correspond à l'acronyme anglais "Findable, Accessible, Interoperable, & Reusable", initialement défini pour les données mais que nous détournons ici pour leurs protocoles d'analyse.
Le projet support est une étude "d'expression différentielle de gènes" à partir de données RNAseq d'O.tauri.

**Pré-requis**

Quasi-rien ... Savoir taper sur un clavier ?

**Contact**

- Thomas DENECKER (<thomas.denecker@gmail.com>)
- Claire Toffano-Nioche (<claire.toffano-nioche@u-psud.fr>)

# Communications orales

## La mémoire du code

**Nouveaux outils pour la session**
- Git
- Github

**Programme :**
- Présentation du dépot local Git et du dépôt distant Github
- Mise en pratique par un exemple simple

**Date :** 26/11/2018

**Orateur :** Thomas Denecker

**Slides :** [Git/Github](https://thomasdenecker.github.io/Club-Bioinfo/docs/git-github.html)

**Wiki  :** [Git](https://github.com/thomasdenecker/FAIR_Bioinfo/wiki/Git), [Github](https://github.com/thomasdenecker/FAIR_Bioinfo/wiki/Github) et [Markdown](https://github.com/thomasdenecker/FAIR_Bioinfo/wiki/Markdown)

## Ce n'est pas de la magie

**Nouveaux outils pour la session**
- Terminal

**Programme :**
- Présentation du projet et de l'application finale
- Présentation des données
- Présentation du workflow de l'analyse
- Ouvrir un terminal (Mac Os, Ubuntu ou Windows)
- Initialisation du projet sur Git/Github
- Premier script shell : création de l'arborescence du projet
- Amélioration du script shell : récupération des données

**Date :** 25/01/2019

**Orateur :** Thomas Denecker

**Slides :** [Session 2](https://thomasdenecker.github.io/FAIR_Bioinfo/docs/session2.html)

## Installer et jouer avec les outils d'analyse

**Nouveaux outils pour la session**
- conda
- quelques outils d'analyse pour des données RNAseq

**Programme :**
- Présentation des outils du workflow (FastQC, Bowtie2, Samtools, HTseq-Count)
- Installation de FastQC à la main
- Présentation de conda
- Script pour l'installation de FastQC avec conda
- Amélioration du script d'installation : ajout des autres outils (travail à la maison)
- Amélioration du script d'analyse : workflow d'analyse à faire en boucle pour chaque échantillon (à faire tourner à la maison)

**Date :** 22/02/2019

**Orateur :** Thomas Denecker & Claire Toffano

**Slides :** [Session 3](https://thomasdenecker.github.io/FAIR_Bioinfo/docs/session3.html)

## Une virée en mer

**Nouveaux outils pour la session**
- Docker
- Cloud IFB

**Programme :**
- Présentation de docker
- Ecriture du dockerfile
- Utilisation du docker avec le script d'analyse
- Partager le docker : Docker Hub
- Pourquoi ? utilisation dans un cloud (ex. IFB)

**Date :** 29/03/2019

**Orateur :** Thomas Denecker

**Slides :** [Session 4](https://thomasdenecker.github.io/FAIR_Bioinfo/docs/session4.html)

## I've got the power !

**Programme :**

_La parallélisation_
   - Snakemake
   - Comparaison avec le script.sh

_Le cluster de calcul_

   - C'est quoi?
   - Cluster de l'IFB / I2BC
   - Singularity ↔ Docker
   - Exemple sur l'IFB et l'I2BC

**Date :** 26/04/2019

**Orateur :** Thomas Denecker

**Slides :** [Session 5](https://thomasdenecker.github.io/FAIR_Bioinfo/docs/session5.html)

## LoveR

**Programme :**

_Rappel R_

_Le package Shiny_
   - Import d'un fichier
   - Affichage d'un tableau
   - Connection tableau <-> graphique
   - Graphique R de base avec paramétrage


_Teasing de la puissance de R_
 - Exploration des données : dplyr  
 - Réalisation de graphiques : plotly, google chart, ggplot2
 - Lecture de fichiers spéciaux : fasta, fastq, excel
 - Croisement de jeux de données : upset R

**Date :** 24/05/2019

**Orateur :** Thomas Denecker

**Slides :** [Session 6](https://thomasdenecker.github.io/FAIR_Bioinfo/docs/session6.html)

## Notebooks

**Programme :**

_Markdown_

_Jupyter / Jupyterlab_
 - Docker Jupyter
 - Mise en ligne avec Binder

_Rmarkdown_

_Générer le notebook de l'application shiny_

**Date :** 21/06/2019

**Orateur :** Thomas Denecker

**Slides :** [Session 7](https://thomasdenecker.github.io/FAIR_Bioinfo/docs/session7.html)

**Example :** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/thomasdenecker/notebookJupyter/master)

## Achever un projet reproductible

**Programme :**

_Exposer son projet_
 - Une vitrine sur web : Github pages
 - Ajouter une licence
 - Versionner son projet : Release
 - Obtenir un DOI : Zenodo

_Et maintenant ?_
 - Encore plus loin dans la reproductibilité
 - Limites de notre solution

**Date :** 05/07/2019

**Orateur :** Thomas Denecker

**Slides :** [Session 8](https://thomasdenecker.github.io/FAIR_Bioinfo/docs/session8.html)
