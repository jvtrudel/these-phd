# L'équation de Schrodinger dépendante du temps

Écrivons l'équation de mouvement quantique sous la forme proposée par Schrodinger:

$$i \hbar \frac{d}{dt}\Psi(t) = H(t) \Psi(t)$$

Dans cette formulation générique, $\Psi(t)$ est l'état du système au temps $t$ et $H(t)$ est l'Hamiltonien. La description précise des termes de l'hamiltonien et des variables dynamiques ne sera possible que lorsque nous aurons précisé à quel *système* nous nous intéressons.

Dans cette thèse, nous décrirons l'interaction entre photons et molécules. Il est donc possible de préciser l'hamiltonien et les variables génériques:

$$H(t, r, R, \nu)= H_m(t,r,R) + H_l(t,\nu) + H_{ml}(t,r,R)$$

Les variables $r$, $R$ et $\nu$ décrivent respectivement les degrés de libertés électroniques, nucléaires et les variables internes de photons.

## Formalisme abstrait

Nous adopterons une notation d'opérateur qui permet de réfléchir et de manipuler de manière abstraite les fonctions d'onde et les termes de l'Hamiltonien. Seul une maitrise de l'algèbre permet de manipuler l'équation de mouvement. La connaissance précise du système aura bien sûr un impact sur l'algèbre applicable (exemple, système multi-électronique ou mono-électronique, fermions ou boson, ...). Également, le calcul des éléments de matrice et la mise en place des algorithmes d'évolution de la fonction d'onde sera grandement dépendante de la représentation (système de coordonnées) choisie. D'autre part, cette formulation abstraite constitue un avantag puisqu'il permet de s'affranchir d'un système de coordonné et permet de décomposer le problème en sous-problèmes que l'on peu traité de manière hétérogènes en utilisant des représentations différentes.


## Hamiltonien moléculaire

Pour une molécule seule, nous avons l'Hamiltonien moléculaire:

$$ H_m = T_e + T_N + V_{ne} + V_{nn} + V_{ee} $$

où

  - $T_e$ est l'énergie cinétique des électrons
  - $T_N$ est l'énergie cinétique des noyaux (coordonnées relatives, modes de vibrations,...)
  - $V_{ne}$ est le terme d'attraction électron-noyaux
  - $V_{nn}$ est le terme de
  - $V_{ee}$ est le terme d'interraction électron-électron

### $H_2$ en représentation cartésienne

Considérant $H_2$, une molécule à 2 noyaux et 2 électrons en représentation cartésienne:

- $T_e=$
- $T_N$ est l'énergie cinétique des noyaux (coordonnées relatives, modes de vibrations,...)
- $V_{ne}$ est le terme d'attraction électron-noyaux
- $V_{nn}$ est le terme de
- $V_{ee}$ est le terme d'interraction électron-électron


## Formulation en seconde quantification

L'un des degrés de liberté qui est particulièrement difficile de décrire en coordonnée cartésienne est le spin de l'électron. Il est possible de le faire en introduisant une variable de spin et en prenant quelques précausion quant à la forme de la fonction d'onde.

Une seconde approche consiste à incorporer à directement l'algèbre des particules au sein même de l'équation de mouvement. Le formalisme dit de la seconde quantification permet de parvenir à ce résultat qui a l'avantage de rendre explicites les conatraintes induites par le spin.






Description en seconde quantitation ...



##



# Autres formes

## Opérateur d'évolution temporelle

# Bases et représentation
