# Prediction de la fonction non codante de l'ADN

![ADN](https://user-images.githubusercontent.com/93741954/182470078-c5747684-2e9e-4893-abc7-6ef74486665c.jpg)

### Introduction
L'ADN porte des instructions génétiques pour le développement, la fonction, la
croissance et la reproduction de tous les organismes connus. L'ADN est essentiellement le
langage de programmation de la vie ; informations stockées sous A, T, G et C. Il est logique
que nous puissions utiliser des séquences d'ADN pour faire des prédictions sur la fonction, la
classification et les niveaux de transcription d'un gène. Cependant, cela est extrêmement
difficile, car il existe de nombreuses caractéristiques inconnues et de nombreux algorithmes
bio-informatiques doivent être générés à la main.

Avec l'émergence de l'apprentissage automatique, et l'augmentation des ensembles de
données génétiques disponibles, il est possible d'appliquer l'apprentissage automatique aux
ensembles de données génétiques pour faire des prédictions complexes. Des modèles
d'apprentissage automatique et des réseaux de neurones profonds ont été utilisés pour prédire
la fonction non codante de l'ADN, identifier les protéines de liaison à l'ADN et même prédire
le niveau de transcription des gènes.

### About Dataset
Le jeu de données Molecular Biology (Splice-junction Gene Sequences) concerne les jonctions
d'épissage. Dans les gènes, il y a des régions qui sont enlevées pendant le processus de transcription de
l'ARN appelé introns et régions utilisées pour générer de l'ARNm appelés exons. Les jonctions entre
elles sont appelées jonctions d'épissage. La tâche consiste à déterminer si le milieu de la séquence est
une jonction d'épissage et quel est son type : les jonctions d'épissage sont de deux types :
- Exon-intron (EI) : représente la fin d'un exon et le début d'un intron
- Intron-exon (IE) : représente l'endroit où l'intron se termine et où commence l'exon suivant,
ou section codante.

Dans ce jeu de données, les échantillons sont des séquences d'une longueur de 60 paires de
bases et appartiennent à l'une des trois classes :

- « EI » (jonction exon-intron) qui contient la jonction exon-intron.
- « IE » (jonction Intron-Exon) qui contient la jonction intron-exon.
- "N" (Ni EI ni IE) qui ne contient aucune jonction d'épissage.

![INTRON_EXON](https://user-images.githubusercontent.com/93741954/182471050-6630546b-7c61-4c4e-9624-728c00ca8aad.png)
