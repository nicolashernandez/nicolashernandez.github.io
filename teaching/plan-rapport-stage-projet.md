# Quoi mettre dans un RAPPORT de stage ou de projet  ?

## Un plan "idéal"

Ci-dessous un plan "idéal" d'un rapport de "stage" sur une mission de développement (mi-technique, pas guide utilisateur à part dans les illustrations éventuelles de la réalisation).

Dans le rapport technique (i.e. davantage le cas pour les rapports de "projet"), il y a surtout les sections 1, 5, 6 et 7.1. 

```
1. Introduction (contexte, problématique, contribution, plan du rapport)
2. Présentation de l'environnement de travail (entreprise, équipe avec les profils techniques, projet, techniques/outils de dev) ; votre position dans l'organigramme de l'entreprise
3. Gestion de projet
  3.1. Planification (gantt explicité produit a posteriori accepté)
  3.2. Méthodologie de travail 
4. Etude de l'existant
  4.1. Solution actuellement en place : Description et limites
  4.2. Etat de l'art : présentation des (pistes de) solutions alternatives possibles   
5. Conception : Expliquer verbeusement et à l'aide de diagrammes opportuns ce que vous avez conçu. 
  * Les diagrammes principaux sont ceux de cas d'utilisation, d'interactions, d'activités, de séquences, d'états et de classes. 
  * Si une application était déjà en place, fournissez ce qui est nécessaire pour que l'on comprenne votre contribution (précisez ce qui était existant et ce qui correspond à votre production). 
6. Réalisation
  6.1. Choix technologique motivé
  6.2. Présentation de ce qui a été développé (potentiellement sur plusieurs sections) : idéalement autour de quelques cas canoniques avec des captures écrans et extraits de code ou algo choisis pour illustrer des aspects pertinents
7. Conclusion
  7.1. Bilan et perspectives sur l'application réalisée (l'état de votre avancement dans le projet au prorata de votre explication sur votre activité et difficulté rencontré : ce qui a été conçu, réalisé, ce qui pourrait être poursuivi, pistes éventuelles sur la manière de concevoir/réaliser la suite)
  7.2. Bilan personnel sur l'expérience humaine, méthodologique et technique 
```
## Retour sur quelques sections 


## Introduction 

* présenter le sujet et définir les concepts liés à votre domaine (nécessité que cela soit accessible pour un non-informaticien)
* voir la note sur les _glossaires_
* Les définitions doivent être simples dans l'introduction. Vous pouvez produire une définition plus conséquente dans la section où vous utiliserez effectivement la notion !

### Conception

[1] est une bonne référence pour la description des **diagrammes UML**.[1] https://laurent-audibert.developpez.com/Cours-UML/ 

Suivant votre façon de présenter certaines informations peuvent passer dans la partie "5. Conception" ou dans la partie "6. Réalisation". 

Vous n'êtes pas non plus obligés d'être exhaustifs. Vous pouvez dans l'analyse avoir une **description des fonctionnalités les plus importantes** et renvoyer le reste en annexe si vous les aviez produits pour votre cahier des charges. 

Sont aussi bienvenus les diagrammes de navigation dans les écrans (en expliquant les IHM), la présentation de l'arborescence des fichiers, schéma de base de données... A vous de voir si vous les placez en annexe ou ailleurs (un schéma bd peut être redondant avec un diagramme de classe, on peut donc l'omettre ou le mettre en annexe, mais si on n'a pas de diagramme de classes alors il vaut mieux le faire apparaître dans le rapport, l'arborescence de fichiers expliqué devrait se trouver dans le README).

### Glossaire
* Vous pouvez faire un glossaire mais le lecteur ne doit pas être obligé de le lire pour comprendre les termes que vous utilisez. En d'autres termes, il faut, au moins à la première occurrence d'un terme dans votre rapport, définir brièvement (par exemple entre parenthèses) ce que cela signifie. 


## Remarques diverses

* Votre rapport doit être **compréhensible** sans avoir à lire un cahier des charges, lire le glossaire, lire les annexes ! 
* Référencer dans le texte les **figures** et expliquer ce qu'il est important d'y regarder 
* Adopter une **numérotation des sections** en chiffres arabes (pas de lettres ni de chiffres romains et encore moins un mélange pour pouvoir savoir où on se trouve dans le document).
* Entre un titre d'une section/chapitre et celui d'une sous-section/chapitre, il devrait toujours y avoir une **annonce** présentant le contenu de la section.
* Un rapport de stage de DUT/LP doit tourner autour de **25-30 pages** de contenu (pas beaucoup plus et pas beaucoup moins). 
* Page de garde... mettre nom, maître de stage et tuteur
